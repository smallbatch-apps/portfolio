<script>
	import Panel from '$components/Panel.svelte';
</script>

<Panel className="relative">
	<div class="relative z-20 mx-auto w-2/3 py-60" id="hero">
		<div class="inline-flex flex-col">
			<div class="inline-flex">
				<div class="flex w-full justify-between text-5xl font-black">
					<div>MATT</div>
					<div>
						<a
							href="https://github.com/mattburgess"
							class="text-gray-600 hover:text-gray-500"
							aria-label="GitHub"
						>
							<i class="fa-brands fa-github-alt"></i>
						</a>
					</div>
				</div>
			</div>
			<div class="text-6xl font-black text-red-400">BURGESS</div>
			<div class="text-center text-3xl text-base font-extralight tracking-widest text-gray-500">
				WEB DEVELOPER
			</div>
		</div>
	</div>
	<img
		src="/images/matt-hero2.jpg"
		class="absolute bottom-0 right-0 z-10 h-full scale-x-[-1]"
		alt="Matt Burgess: Blockchain and Web Developer"
	/>
</Panel>
