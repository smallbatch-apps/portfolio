<script>
	import Header from '$components/Header.svelte';
	import SocialButton from '$components/SocialButton.svelte';
</script>

<div class="flex flex-col items-center gap-20 bg-red-400 py-40" id="about">
	<Header dark={true}>THE <span class="text-amber-200">SHORT</span> AND SWEET VERSION</Header>

	<div
		class="mb:px-0 container mx-auto px-10 text-center text-xl font-light leading-loose text-white"
	>
		I am an experienced Australian developer who currently lives in Bangkok, Thailand. Although I
		have been working in the field for more than 25 years I keep my skills constantly honed for the
		changing market and an always a current and active learner. My primary focuses are on web
		applications and blockchain development, but I am also an experienced technical manager and team
		lead.
	</div>

	<div class="flex justify-center gap-4">
		<SocialButton
			url="https://www.linkedin.com/in/matthew-burgess-9a7a6095/"
			variant="amber"
			size="icon"
		>
			<i class="fa-brands fa-linkedin fa-fw text-2xl"></i>
		</SocialButton>
		<SocialButton url="https://github.com/smallbatch-apps" variant="amber" size="icon">
			<i class="fa-brands fa-github fa-fw text-2xl"></i>
		</SocialButton>
		<SocialButton url="https://mattburgess.medium.com/" variant="amber" size="icon">
			<i class="fa-brands fa-medium fa-fw text-2xl"></i>
		</SocialButton>
		<SocialButton url="https://www.facebook.com/matt.burgess.33/" variant="amber" size="icon">
			<i class="fa-brands fa-facebook fa-fw text-2xl"></i>
		</SocialButton>
		<SocialButton url="mailto:matt@myclient.info" variant="amber" size="icon">
			<i class="fa-solid fa-envelope fa-fw text-2xl"></i>
		</SocialButton>

		<SocialButton url="tel:+66615945948" variant="amber" size="icon">
			<i class="fa-solid fa-phone fa-fw text-2xl"></i>
		</SocialButton>
	</div>
</div>
