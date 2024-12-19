<script>
	import SocialButton from '$components/SocialButton.svelte';
</script>

<div
	class="grid grid-cols-1 bg-red-400 text-lg font-thin text-gray-600 md:grid-cols-2"
	id="avenues"
>
	<div
		class="order-1 bg-cover bg-center grayscale"
		style="background-image: url('/images/linkedin.jpg')"
	></div>
	<div class="order-2 flex flex-col gap-6 px-16 py-32 text-white">
		<h1 class="text-xl font-bold tracking-widest">PROFESSIONAL PROFILE</h1>
		<div class="w-1/4 border-b-2 border-white"></div>

		<p>
			Active networking and professional profile building has not been a strong preference for me. I
			prefer to build than to post. However, my LinkedIn profile is a good summary of previous work
			history and experience. It shows a range of projects and experience, and is a good summary of
			what I have done. It also includes the specific skills and technologies I have used in a
			commercial sense.
		</p>

		<p>
			For more direct or portable information, you can view my resume in PDF format in the link
			below.
		</p>

		<div class="flex gap-4">
			<SocialButton variant="red" url="https://mattburgess.medium.com/">
				<i class="fa-brands fa-linkedin"></i> Linkedin Profile
			</SocialButton>

			<SocialButton variant="red" url="/resume-matt-burgess.pdf">
				<i class="fa-solid fa-file-arrow-down"></i> View PDF Resume
			</SocialButton>
		</div>
	</div>
	<div
		class="order-3 bg-cover bg-center grayscale md:order-4"
		style="background-image: url('/images/github.jpg')"
	></div>
	<div class="order-4 flex flex-col gap-6 bg-white px-16 py-32 text-gray-600 md:order-3">
		<h1 class="text-xl font-bold tracking-widest">GITHUB PROFILE</h1>
		<div class="w-1/4 border-b-2 border-gray-800"></div>

		<p>
			Profile includes a collection of repositories and projects. Many of these are proof of concept
			or tech tests, or investigatinos of new libraries or languages. There are projects in
			JavaScript, Golang, Rust, and Elixir, covering many years of active development.
		</p>
		<div>
			<SocialButton variant="white" url="https://github.com/smallbatch-apps">
				<i class="fa-brands fa-github"></i> Github
			</SocialButton>
		</div>
	</div>

	<div
		class="order-5 bg-cover bg-center grayscale"
		style="background-image: url('/images/medium.jpg')"
	></div>
	<div class="order-6 flex flex-col gap-6 px-16 py-32 text-white">
		<h1 class="text-xl font-bold tracking-widest">TECHNICAL WRITING</h1>
		<div class="w-1/4 border-b-2 border-white"></div>

		<p>
			I have been writing on Medium since 2016, and have published nearly 70 articles on a range of
			topics, including web development, blockchain technology, and software engineering. There is a
			focus on more opinionated best-practices and JavaScript development. This is primarily because
			of the impact of JavaScript in web, especially to a less experienced audience. However, I have
			additionally written on database normalisation and design, and similiarly "backend" oriented
			topics.
		</p>
		<!-- <p>In addition to Medium I now publish articles on this website.</p> -->
		<div class="flex gap-4">
			<SocialButton variant="red" url="https://mattburgess.medium.com/">
				<i class="fa-brands fa-medium"></i> Medium Profile
			</SocialButton>

			<!-- <SocialButton variant="red" url="/articles">
				<i class="fa-solid fa-typewriter"></i> Article listing
			</SocialButton> -->
		</div>
	</div>
</div>
