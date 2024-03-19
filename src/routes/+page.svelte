<script>
	import { onMount } from 'svelte';
	import Header from './Header.svelte';
</script>

<div class="flex flex-col">
	<Header />
	<div class="bg-gray flex-grow h-full pt-10 flex justify-center">
		<div class="w-[50%]">
			<div class="w-full bg-white aspect-[8.5/11]">
				<div class="p-10"></div> 
				<!-- figure out how to insert bold/italic/underlined text as the cursor moves -->
			</div>
		</div>
	</div>
</div>
