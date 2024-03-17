<script>
	import logo from '$lib/logo.svg';
	import FontButton from './FontButton.svelte';
</script>

<div class="flex space-between px-10 py-5 bg-white">
	<div class="flex flex-1 gap-10 items-center">
		<object title="logo" data={logo}> </object>
		<input class="text-xl focus:outline-none focus:border-b border-black" value="Title" />
	</div>
	<div class="flex justify-center items-center flex-1 gap-3">
		<div class="rounded-lg border border-black h-full flex items-center px-3 gap-2">
			<button class="font text-xl">{'<'}</button>
			<input class="w-5 text-center focus:outline-none focus:border-b border-black" type="number" value={12} />
			<button class="font text-xl">{'>'}</button>
		</div>
		<FontButton><div class="font-bold">B</div></FontButton>
		<FontButton><div class="italic">I</div></FontButton>
		<FontButton><div class="underline">U</div></FontButton>
		<FontButton><div class="border-black border-b-4 px-2"><div>A</div></div></FontButton>
	</div>
	<div class="flex-1 flex justify-end">
		<button class="bg-gray-light rounded-lg px-5">Login</button>
	</div>
</div>
