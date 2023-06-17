<script lang="ts">
	const features = [
		{
			title: 'Upload & Organize',
			icon: 'upload',
			description:
				'Upload in bulk, organize content in categories, add custom filters & upload extras.'
		},
		{
			title: 'Stream On-Demand',
			icon: 'record',
			description: 'Showcase your content in a beautiful on-demand video catalog.'
		},
		{
			title: 'Stream live',
			icon: 'stream',
			description: 'Schedule events in advance & build excitement with a countdown overlay.'
		},
		{
			title: 'Monetization',
			icon: 'monetization',
			description: 'Offer subscriptions or one-time purchases. Accept credit cards & PayPal.'
		},
		{
			title: 'Analytics',
			icon: 'stream',
			description: 'Know what your audience likes & how your content is performing.'
		},
		{
			title: 'For all devices',
			icon: 'device',
			description: 'Get organized on all devices'
		}
	]
</script>

<section class="py-20 text-white bg-black">
	<div class="max-w-screen-xl mx-auto">
		<div class="flex items-center space-x-24">
			<div class="flex flex-col w-1/2">
				<div class="flex flex-col space-y-4">
					<h1 class="text-5xl font-bold font-heading">PT Bali Inter Pangan</h1>
					<p>
						Ini Company C Vivi Yah Teman Teman Dan Kidsss
					</p>
				</div>
				<div class="flex mt-12 space-x-3">
					<!---button class="w-1/3 primary">Start Free Trial</button>-->
					<button class="w-1/2 outline">Product</button>
				</div>
			</div>
			<div class="relative w-1/2">
				<img src="/images/top.jpeg" class="w-full h-full" alt="Hero" />
				<img src="/images/hero-image-mobile.png" class="absolute -bottom-4 -left-3" alt="Hero" />
			</div>
		</div>
		<div class="flex justify-between mt-32 space-x-24">
					<p>
						Pasta
					</p>
			
					<p>
						Essence
					</p>
			
					<p>
						Liquid Colour
					</p>
		</div>
	</div>
</section>

<section class="py-20">
	<div class="max-w-screen-lg mx-auto">
		<div class="flex flex-col justify-center text-center">
			<div class="flex flex-col space-y-3">
				<h2 class="text-4xl font-bold font-heading">Daftar Produk</h2>
				<p>You take care of the video quality and we take care of everything else</p>
			</div>
			<div class="flex justify-center mt-12 space-x-8">
				<button class="w-1/6 primary">Start Free Trial</button>
				<button class="w-1/6 outline-dark">Login</button>
			</div>
		</div>
		<div class="grid grid-cols-3 gap-12 mt-20">
			{#each features as feature}
				<div
					class="flex flex-col p-4 space-y-3 hover:shadow-xl transition duration-300 cursor-pointer"
				>
					<div class="flex space-x-3">
						<img
							src={`/icons/${feature.icon}.svg`}
							class="transform transition duration-300 hover:rotate-12"
							alt={feature.title}
						/>
						<h5 class="font-bold font-heading">{feature.title}</h5>
					</div>
					<p>{feature.description}</p>
				</div>
			{/each}
		</div>
	</div>
</section>

<section class="py-20 text-white bg-black">
	<div class="flex flex-col max-w-screen-xl mx-auto space-y-32">
		<div class="flex flex-col justify-center">
			<h2 class="text-4xl font-bold text-center font-heading">Deskripsi Produk</h2>
		</div>

		<div class="flex space-x-24">
			<div class="flex flex-col justify-center w-1/2 space-y-6">
				<h5 class="text-3xl font-semibold">Pasta</h5>
				<p>
					Ini Pasta Sangat Enak Banget Rasannya Nyummy.
				</p>
				<div class="flex space-x-3 cursor-pointer group">
					<p class="transition font-heading group-hover:font-bold">Get started</p>
					<img
						src="/icons/arrow.svg"
						class="transition transform group-hover:translate-x-1"
						alt="Arrow Icon"
					/>
				</div>
			</div>
			<div class="relative w-1/2">
				<img src="/images/Pasta.jpeg" alt="Monetize your way" class="w-full h-full" />
				<!---<div
					class="absolute flex flex-col py-8 space-y-3 text-black bg-white px-9 rounded-3xl -top-4 -left-6"
				>
					<div
						class="flex w-full px-3 py-4 space-x-16 font-semibold transition duration-300 transform bg-gray-100 font-heading rounded-xl hover:bg-blue-100 hover:text-primary hover:translate-x-1 hover:-translate-y-1 hover:shadow-xl"
					>
						<p>Donate</p>
						<p>45$</p>
					</div>
					<div
						class="flex w-full px-3 py-4 space-x-16 font-semibold transition duration-300 transform bg-gray-100 font-heading rounded-xl hover:bg-blue-100 hover:text-primary hover:translate-x-1 hover:-translate-y-1 hover:shadow-xl"
					>
						<p>Donate</p>
						<p>45$</p>
					</div>
					<div
						class="flex w-full px-3 py-4 space-x-16 font-semibold transition duration-300 transform bg-gray-100 font-heading rounded-xl hover:bg-blue-100 hover:text-primary hover:translate-x-1 hover:-translate-y-1 hover:shadow-xl"
					>
						<p>Donate</p>
						<p>45$</p> 
					</div>
				</div> -->
			</div>
		</div>

		<div class="flex space-x-24">
			<div class="relative flex w-1/2">
				<img src="/images/Essence.jpg" class="w-full h-full" alt="Optimized for growth" />
				<div class="absolute px-4 py-3 bg-white -top-4 -right-4 rounded-2xl">
					<div class="relative">
						<img src="/icons/email-black.svg" alt="Email Icon" class="w-8 h-6" />
						<span
							class="absolute text-xs rounded-full -top-2 -right-2 bg-primary px-[6px] py-[1px] font-heading font-bold"
							>1</span
						>
					</div> 	
				</div>
			</div>
			<div class="flex flex-col justify-center w-1/2 space-y-6">
				<h5 class="text-3xl font-semibold">Essence</h5>
				<p>
					Ini Baunnya Sangat Memberi Aroma Yang Sedap
				</p>
				<div class="flex space-x-3 cursor-pointer group">
					<p class="transition font-heading group-hover:font-bold">Get started</p>
					<img
						src="/icons/arrow.svg"
						class="transition transform group-hover:translate-x-1"
						alt="Arrow Icon"
					/>
				</div>
			</div>
		</div>
		<div class="flex space-x-24">
			<div class="flex flex-col justify-center w-1/2 space-y-6">
				<h5 class="text-3xl font-semibold">Liquid Coloring</h5>
				<p>
					Ini Warnannya Sangat Berwarna Warna Membuat Harimu Berwarna
				</p>
				<div class="flex space-x-3 cursor-pointer group">
					<p class="transition font-heading group-hover:font-bold">Get started</p>
					<img
						src="/icons/arrow.svg"
						class="transition transform group-hover:translate-x-1"
						alt="Arrow Icon"
					/>
				</div>
			</div>
			<div class="relative w-1/2">
				<img src="/images/Pasta.jpeg" alt="Monetize your way" class="w-full h-full" />
				
	</div>
</section>

<section class="pt-20 pb-40 text-white bg-black">
	<div class="flex flex-col max-w-screen-lg mx-auto">
		<div class="flex flex-col space-y-3 text-center">
			<h2 class="text-4xl font-bold font-heading">Ayo Bergabung Dengan Kami Bla Bla</h2>
			<p>Kami Adalah Perusahaan Jujur Dan Berkarisma.</p>
		</div>
		<div class="flex justify-center space-x-8 mt-14">
			<button class="w-1/5 secondary">Get started</button>
			<button class="w-1/5 outline">Login</button>
		</div>
		<div class="relative mt-20">
			<img src="/images/top.jpeg" alt="Business Desktop" class="w-full h-full" />
			<img
				src="/images/9.jpg" 
				alt="Business Mobile"
				class="absolute -bottom-12 -left-3 w-[250px] h-[300px]"
				
			/>
		</div>
	</div>
</section>

<section class="pt-20 pb-32">
	<div class="flex flex-col justify-center space-y-3 text-center">
		<h2 class="text-4xl font-bold font-heading">PT Bali Inter Pangan ^-^</h2>
		<p>At the end of the day have fun with celebrities</p>
	</div>

	<div class="flex  flex-col overflow-hidden mt-24 space-y-6">
		<div class="flex space-x-8">
			<img src="/images/1.jpg" alt="Showcase 1" class="w-[250px] h-[300px]" />
			<img src="/images/2.jpg" alt="Showcase 2" class="w-[250px] h-[300px]" />
			<img src="/images/3.jpg" alt="Showcase 3" class="w-[250px] h-[300px]" />
			<img src="/images/4.jpg" alt="Showcase 4" class="w-[250px] h-[300px]" />
			<img src="/images/10.webp" alt="Showcase 4" class="w-[250px] h-[300px]" />
			<img src="/images/11.webp" alt="Showcase 4" class="w-[300px] h-[300px]" />
		</div>
		<div class="flex space-x-8 -translate-x-72">
			<img src="/images/5.jpg" alt="Showcase 5" class="w-[250px] h-[300px]" />
			<img src="/images/6.jpg" alt="Showcase 6" class="w-[250px] h-[300px]" />
			<img src="/images/7.jpg" alt="Showcase 7" class="w-[250px] h-[300px]" />
			<img src="/images/8.jpg" alt="Showcase 8" class="w-[250px] h-[300px]" />
			<img src="/images/9.jpg" alt="Showcase 9" class="w-[250px] h-[300px]" />
			<img src="/images/12.jpg" alt="Showcase 9" class="w-[250px] h-[300px]" />
			<img src="/images/13.jpg" alt="Showcase 9" class="w-[250px] h-[300px]" />
		</div>
	</div>
</section>
