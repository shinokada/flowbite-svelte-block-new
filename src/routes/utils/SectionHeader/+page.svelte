<script lang="ts">
	import { Breadcrumb } from 'flowbite-svelte';
</script>

<section class="pt-3 md:pt-5">
	<div class="px-4 mx-auto max-w-8xl">
		<div
			class="grid pb-6 border-b border-gray-200 md:pb-10 lg:gap-8 lg:grid-cols-3 dark:border-gray-800"
		>
			<div class="col-span-2 mb-2 lg:mb-0">
				<slot />
				<h1
					class="inline-block mb-2 text-3xl font-extrabold tracking-tight text-gray-900 dark:text-white"
				>
					<slot name="h1" />
				</h1>
				<p class="text-lg text-gray-500 xl:mr-64 lg:mb-0 dark:text-gray-400">
					<slot name="paragraph" />
				</p>
			</div>
		</div>
	</div>
</section>
