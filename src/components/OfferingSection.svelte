<script>
	export let heading;
</script>

<div
	class="flex flex-1 flex-col items-center gap-6 px-10 text-center text-lg font-thin text-gray-600 md:px-0"
>
	<div
		class="flex size-40 items-center justify-center rounded-full border border-2 border-red-400 text-red-400"
	>
		<slot name="icon" />
	</div>

	<h2 class="text-2xl font-bold">{heading}</h2>
	<div class="w-1/3 border-b-2 border-red-400"></div>

	<slot />
</div>
