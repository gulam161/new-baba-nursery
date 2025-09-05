<script lang="ts">
	import TopCategories from './top-categories.svelte';
</script>

<section
	class="relative flex h-screen w-full items-center justify-center bg-cover bg-center bg-no-repeat text-center"
	style="background-image: url('/landing-homepage-image.jpg');"
>
	<!-- Dark overlay -->
	<div class="absolute inset-0 bg-black/60"></div>

	<!-- Content -->
	<div class="gap relative z-10 flex flex-col items-center justify-center">
		<img src="/products/eco-green-leaf-web-business.png" alt="leaf" class="h-30 w-auto grayscale" />

		<!-- Heading -->
		<h1 class="mb-8 text-4xl font-bold text-white md:text-6xl">
			Get Up To <span
				class="bg-gradient-to-t from-[#9ca067] to-[#cdcd8a] bg-clip-text text-transparent"
			>
				50% Off
			</span>
		</h1>

		<!-- Subheading -->
		<p
			class="mb-5 inline-block rounded-full bg-gradient-to-r from-[#9ca067] to-[#b1b175] px-6 py-2 text-white"
		>
			New Stock Available, All This Season!
		</p>

		<a
			href="#shop"
			class="rounded-full bg-black from-[#b1b175] to-[#9ca067] px-6 py-2 text-white transition hover:bg-gradient-to-r"
		>
			Shop Now
		</a>
	</div>
</section>

<!-- offer -->
<div
	class="flex h-20 items-center justify-center gap-6 bg-gradient-to-r from-[#9ca067] to-[#b1b175] px-6 py-2"
>
	<p class="text-lg font-normal tracking-wider text-white capitalize">
		save up to 45% off on first order...!
	</p>
	<a href="#shop" class="rounded-full bg-black px-6 py-2 text-white transition"> Buy Now </a>
</div>

<!-- About Nursery Plant -->
<section class="flex flex-col items-center justify-evenly bg-white px-6 py-12 md:flex-row md:py-20">
	<!-- Left Content -->
	<div class="max-w-md text-left md:text-center">
		<div class="mx-auto w-fit rounded-full bg-[#f7f7f7]">
			<img src="/products/eco-green-leaf-web-business.png" alt="Leaf Icon" class="h-16 w-auto" />
		</div>
		<h2 class="text-2xl font-semibold text-gray-800">About Nursery Plant</h2>
		<p class="mt-4 text-sm leading-relaxed text-gray-600">
			Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut
			labore et dolore magna aliqua.
		</p>
		<button
			class="mt-6 rounded-full bg-gradient-to-r from-[#9ca067] to-[#b1b175] px-6 py-2 text-white"
		>
			Explore us
		</button>
	</div>

	<!-- Right Images -->
	<div class="relative flex max-w-md items-center justify-start">
		<div class="relative rounded-full bg-[#f7f7f7]">
			<img
				src="/products/White-pot-leaf.png"
				alt="White-pot-leaf"
				class="relative z-20 w-48 md:w-64"
			/>
			<img
				src="/products/leafy-frame-ecology-square.png"
				alt="top-view-succulent"
				class="absolute top-11 right-3 z-10 w-40 rotate-45 md:w-60"
			/>
		</div>
		<div class="absolute top-6 left-52 z-20 w-48 rounded-full bg-stone-500/10 p-2.5 shadow md:w-18">
			<img
				src="/products/top-view-succulent-echeveria-agavoides.png"
				alt="White-pot-leaf"
				class="w-48 md:w-20"
			/>
		</div>
		<img
			src="/products/Hawthorn.png"
			alt="Small Plant 2"
			class="absolute bottom-0 left-58 w-20 rounded-full bg-stone-500/10 md:w-32"
		/>
	</div>
</section>

<!-- Top Categories -->
<TopCategories />
