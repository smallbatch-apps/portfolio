<script>
	export let dark = false;
</script>

<div class="flex flex-col items-center gap-2">
	<div
		class="text-2xl font-semibold tracking-widest"
		class:text-white={dark}
		class:text-gray-900={!dark}
	>
		<slot />
	</div>
	<div>
		<div class="relative flex items-center justify-center text-gray-200">
			<div class="flex -translate-y-[4px] gap-1.5">
				<i class="fa-solid fa-period"></i>
				<i class="fa-solid fa-period"></i>
				<i class="fa-solid fa-period"></i>
				<i class="fa-solid fa-period"></i>
				<i class="fa-solid fa-period"></i>
				<i class="fa-solid fa-period"></i>
				<i class="fa-solid fa-period"></i>
				<i class="fa-solid fa-period"></i>
			</div>
			<i class="fa-sharp fa-thin fa-chevron-down mx-8 text-4xl text-gray-500"></i>
			<div class="flex -translate-y-[4px] gap-1.5">
				<i class="fa-solid fa-period"></i>
				<i class="fa-solid fa-period"></i>
				<i class="fa-solid fa-period"></i>
				<i class="fa-solid fa-period"></i>
				<i class="fa-solid fa-period"></i>
				<i class="fa-solid fa-period"></i>
				<i class="fa-solid fa-period"></i>
				<i class="fa-solid fa-period"></i>
			</div>
		</div>
	</div>
</div>
