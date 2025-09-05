<script lang="ts">
	interface Category {
		title: string;
		image: string;
	}

	const categories: Category[] = [
		{ title: 'Biennial', image: '/products/vegatable.png' },
		{ title: 'Evergreen', image: '/products/vegatable.png' },
		{ title: 'Climbing', image: '/products/vegatable.png' }
	];
</script>

<section class="flex w-full flex-col items-center justify-center bg-[#f2f2f2] p-4">
	<h2 class="text-2xl font-semibold text-gray-800">Top Categories</h2>
	<img src="/products/eco-green-leaf-web-business.png" alt="Leaf Icon" class="h-10 w-auto" />

	<div class="mx-auto grid max-w-5xl grid-cols-1 gap-8 sm:grid-cols-2 md:grid-cols-3">
		{#each categories as category}
			<div
				class="flex flex-col items-center rounded-lg border-[20px] p-6 [--frame:url('/products/leafy-frame-ecology-square.png')] [border-image-repeat:round] [border-image-slice:100] [border-image-source:var(--frame)]"
			>
				<img src={category.image} alt={category.title} class="mb-4 h-24 w-24 object-contain" />
				<h3 class="font-medium text-gray-700">{category.title}</h3>
			</div>
		{/each}
	</div>
</section>
