<script lang="ts">
	import Header from './navigation/header.svelte';
</script>

<section
	class="relative flex h-screen w-full items-center justify-center bg-cover bg-center bg-no-repeat text-center"
	style="background-image: url('/landing-homepage-image.jpg');"
>
	<!-- Dark overlay -->
	<div class="absolute inset-0 bg-black/40"></div>

	<!-- Content -->
	<div class="relative z-10 px-4">
		<Header />
		<!-- Icon -->
		<div class="mb-4 flex justify-center">
			<!-- Example plant icon (Tailwind Heroicons or custom SVG) -->
			<svg
				xmlns="http://www.w3.org/2000/svg"
				class="h-12 w-12 text-white"
				fill="currentColor"
				viewBox="0 0 24 24"
			>
				<path
					d="M12 2C9.243 2 7 4.243 7 7v4.5A5.5 5.5 0 0 0 12.5 17H14v2a2 2 0 0 1-4 0h-2a4 4 0 0 0 8 0v-4a3 3 0 0 0-3-3H9V7a3 3 0 0 1 6 0h2a5 5 0 0 0-5-5z"
				/>
			</svg>
		</div>

		<!-- Heading -->
		<h1 class="mb-4 text-4xl font-bold text-white md:text-6xl">
			Get Up To <span class="text-green-400">50% Off</span>
		</h1>

		<!-- Subheading -->
		<p class="mb-4 inline-block rounded-full bg-green-500 px-6 py-2 text-white">
			New Stock Available, All This Season!
		</p>

		<!-- Button -->
		<a href="#shop" class="rounded bg-black px-6 py-2 text-white transition hover:bg-green-600">
			Shop Now
		</a>
	</div>
</section>
