<script>
	import Panel from '$components/Panel.svelte';
	import Header from '$components/Header.svelte';
	import ArticleItem from '$components/ArticleItem.svelte';
</script>

<div id="articles" class="py-32">
	<Panel>
		<Header><span class="text-amber-200">LATEST</span> ARTICLES</Header>

		<div class="mx-auto mt-32 grid w-full grid-cols-3 flex-col gap-10 md:w-2/3 md:flex-row">
			<ArticleItem
				url="https://medium.com/@mattburgess/javascript-shinies-map-set-and-symbol-11bc4f0d2fbf"
				title="Javascript Shinies: Map, Set and Symbol"
				description="It&apos;s come to my attention recently that Map, Set and set in particular are often seen as just Array and Object with… fancy. Let&apos;s dig more into them and see why they&apos;re more than that."
				image="article-map.jpg"
				readTime="9 min read"
				publishDate="Apr 9, 2025"
			/>
			<ArticleItem
				url="https://medium.com/@mattburgess/frontend-security-the-front-fell-off-045091079104"
				title="Frontend Security: The Front Fell Off"
				description="As frontend developers we often thing of security as a somebody-else problem. It&apos;s true that the bigger issues are tackled in the backend, but as frontend developer there are specific concerns that we need to be aware of."
				image="article-frontend-security.jpg"
				readTime="14 min read"
				publishDate="Mar 18, 2025"
			/>
			<ArticleItem
				url="https://mattburgess.medium.com/the-problem-with-nextjs-e44fd4c99d20"
				title="The Problem With NextJS"
				description="I&apos;ve been working with NextJS for a few years now, and the more I&apos;ve used it,
					and in more contexts, the clearer it has become that NextJS has a major issue."
				image="article-nextjs.jpg"
				readTime="10 min read"
				publishDate="Feb 10, 2025"
			/>
			<ArticleItem
				url="https://medium.com/@mattburgess/react-hook-form-vs-react-19-1e28009e6557"
				title="Why I Use Tailwind"
				description="And why you should too. Tailwind has quickly become the dominant way to style UIs. But
					with success comes the inevitable backlash. Tailwind seems to be getting some pushback
					lately, so I thought I&apos;d tackle it directly."
				image="article-tailwind.jpg"
				readTime="14 min read"
				publishDate="Feb 6, 2025"
			/>
			<ArticleItem
				url="https://medium.com/@mattburgess/react-hook-form-vs-react-19-1e28009e6557"
				title="In Defence of Agile"
				description="Developers don&apos;t much like “process”, and Agile has become a bit of an industry punching bag. Here&apos;s why memes shouldn&apos;t be your guide to good software practise."
				image="article-agile.jpg"
				readTime="11 min read"
				publishDate="31 Jan, 2025"
			/>
			<ArticleItem
				url="https://medium.com/@mattburgess/react-hook-form-vs-react-19-1e28009e6557"
				title="React Hook Form vs React 19"
				description="Well this is awkward. Just as I was finishing and publishing a video on why to use React
					Hook Form instead of React, React 19 comes out with a massive revamp of form handling.
					Let&apos;s break it down."
				image="article-rhfvsr19.jpg"
				readTime="9 min read"
				publishDate="Jan 2, 2025"
			/>
			<!-- <ArticleItem
				url="https://mattburgess.medium.com/why-would-i-use-react-hook-form-8ae7b905953e"
				title="Why would I use React Hook Form?"
				description="Forms are some of the more complicated things we do in the web, and we don&apos;t always do them well. React Hook Form can be a way to tame this complexity, so let&apos;s go through it."
				image="article-react-hook-form.jpg"
				readTime="10 min read"
				publishDate="Dec 19, 2024"
			/>
			<ArticleItem
				url="https://mattburgess.medium.com/what-language-should-you-learn-f5fbaf36baad"
				title="What language should you learn?"
				description="Most of us have stopped at various times and thought that it&apos;s time we learned a new language. But if you&apos;re anything like me you&apos;ve got analysis paralysis. So let&apos;s go through some of the options."
				image="article-choose.jpg"
				readTime="10 min read"
				publishDate="Dec 8, 2024"
			/>
			<ArticleItem
				url="https://mattburgess.medium.com/select-star-from-database-350b85ef9657"
				title="Select Star from Database"
				description="It&apos;s come to my attention that a lot of people have a limited understanding of the variety and diversity of database solutions that exist. Let&apos;s change that now."
				image="article-databases.jpg"
				readTime="25 min read"
				publishDate="Nov 23, 2024"
			/> -->
		</div>

		<div class="mt-20 text-center text-xl font-semibold tracking-widest">
			View <a
				class="text-amber-600 underline decoration-dashed underline-offset-4 hover:text-amber-700"
				href="https://mattburgess.medium.com/">Medium Profile</a
			> for more articles
		</div>
	</Panel>
</div>
