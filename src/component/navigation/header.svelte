<script lang="ts">
	
	let menuItems = ['Bonsais', 'Evergreen', 'Climbing', 'More'];
</script>

<nav class="w-full rounded-full bg-white shadow">
	<div class="mx-auto flex h-16 w-3xl items-center justify-between pr-5">
		<!-- Logo -->
		<a href="/" class="flex items-center space-x-1">
			<img src="/logo/new-baba-nursary.png" alt="Plant Life Logo" class="h-15 w-auto" />
			<span class="text-xl font-bold">
				<span class="text-[#9ca067]">Plant</span> Life
			</span>
		</a>

		<!-- Menu -->
		<ul class="hidden items-center space-x-8 md:flex">
			{#each menuItems as item}
				<li>
					<a href="/" class="font-medium text-gray-800 hover:text-[#9ca067]">{item}</a>
				</li>
			{/each}
		</ul>

		<!-- Icons -->
		<div class="flex items-center space-x-4 text-gray-700">
			<button aria-label="Search" class="hover:text-[#9ca067]">
				<svg
					xmlns="http://www.w3.org/2000/svg"
					class="h-5 w-5"
					fill="none"
					viewBox="0 0 24 24"
					stroke="currentColor"
				>
					<path
						stroke-linecap="round"
						stroke-linejoin="round"
						stroke-width="2"
						d="M21 21l-4.35-4.35M11 19a8 8 0 1 1 0-16 8 8 0 0 1 0 16z"
					/>
				</svg>
			</button>

			<button aria-label="Account" class="hover:text-[#9ca067]">
				<svg
					xmlns="http://www.w3.org/2000/svg"
					class="h-5 w-5"
					fill="none"
					viewBox="0 0 24 24"
					stroke="currentColor"
				>
					<path
						stroke-linecap="round"
						stroke-linejoin="round"
						stroke-width="2"
						d="M5.121 17.804A10 10 0 1 1 18.879 17.804M15 11a3 3 0 1 1-6 0 3 3 0 0 1 6 0z"
					/>
				</svg>
			</button>

			<!-- Cart with green dot -->
			<div class="relative">
				<button aria-label="Cart" class="hover:text-[#9ca067]">
					<svg
						xmlns="http://www.w3.org/2000/svg"
						class="h-5 w-5"
						fill="none"
						viewBox="0 0 24 24"
						stroke="currentColor"
					>
						<path
							stroke-linecap="round"
							stroke-linejoin="round"
							stroke-width="2"
							d="M3 3h2l.4 2M7 13h10l4-8H5.4M7 13l-1.35 5.4a1 1 0 0 0 .98 1.2h11.74a1 1 0 0 0 .98-1.2L17 13M7 13H3m4 0a4 4 0 1 0 8 0"
						/>
					</svg>
					
				</button>
				<span class="absolute -top-1 -right-1 h-2.5 w-2.5 rounded-full bg-green-500"></span>
			</div>
		</div>
	</div>
</nav>
