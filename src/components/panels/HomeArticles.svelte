<script>
	import Panel from '$components/Panel.svelte';
	import Header from '$components/Header.svelte';
</script>

<div id="articles" class="py-32">
	<Panel>
		<Header><span class="text-amber-200">LATEST</span> ARTICLES</Header>

		<div class="mx-auto mt-32 flex flex w-full flex-col gap-10 md:w-2/3 md:flex-row">
			<a
				href="https://mattburgess.medium.com/why-would-i-use-react-hook-form-8ae7b905953e"
				target="_blank"
				class="flex flex-1 cursor-pointer flex-col gap-4 border border-transparent p-4 hover:border-gray-300"
			>
				<img
					src="/images/articles/article-react-hook-form.jpg"
					class="border border-2 border-red-400"
					alt="React Hook Form"
				/>
				<div>
					<h2 class="text-2xl font-semibold text-red-400">Why would I use React Hook Form?</h2>
					<div class="flex items-center justify-between gap-2 text-gray-500">
						<span class="text-sm text-gray-500">10 min read</span>
						<span class="text-sm text-gray-500">Dec 19, 2024</span>
					</div>
				</div>
				<p>
					Forms are some of the more complicated things we do in the web, and we don&apos;t always
					do them well. React Hook Form can be a way to tame this complexity, so let&apos;s go
					through it.
				</p>
			</a>
			<a
				href="https://mattburgess.medium.com/what-language-should-you-learn-f5fbaf36baad"
				target="_blank"
				class="flex flex-1 cursor-pointer flex-col gap-4 border border-transparent p-4 hover:border-gray-300"
			>
				<img
					src="/images/articles/article-choose.jpg"
					class="border border-2 border-red-400"
					alt="What language should you learn?"
				/>
				<div>
					<h2 class="text-2xl font-semibold text-red-400">What Language Should You Learn?</h2>

					<div class="flex items-center justify-between gap-2 text-gray-500">
						<span class="text-sm text-gray-500">10 min read</span>
						<span class="text-sm text-gray-500">Dec 8, 2024</span>
					</div>
				</div>
				<p>
					Most of us have stopped at various times and thought that it&apos;s time we learned a new
					language. But if you&apos;re anything like me you&apos;ve got analysis paralysis. So
					let&apos;s go through some of the options.
				</p>
			</a>
			<a
				href="https://mattburgess.medium.com/select-star-from-database-350b85ef9657"
				target="_blank"
				class="flex flex-1 cursor-pointer flex-col gap-4 border border-transparent p-4 hover:border-gray-300"
			>
				<img
					src="/images/articles/article-databases.jpg"
					class="border border-2 border-red-400"
					alt="Select Star from Database"
				/>
				<div>
					<h2 class="text-2xl font-semibold text-red-400">Select Star from Database</h2>

					<div class="flex items-center justify-between gap-2 text-gray-500">
						<span class="text-sm text-gray-500">25 min read</span>
						<span class="text-sm text-gray-500">Nov 23, 2024</span>
					</div>
				</div>
				<p>
					It&apos;s come to my attention that a lot of people have a limited understanding of the
					variety and diversity of database solutions that exist. Let&apos;s change that now.
				</p>
			</a>
		</div>

		<div class="mt-20 text-center text-xl font-semibold tracking-widest">
			View <a
				class="text-amber-600 underline decoration-dashed underline-offset-4 hover:text-amber-700"
				href="https://mattburgess.medium.com/">Medium Profile</a
			> for more articles
		</div>
	</Panel>
</div>
