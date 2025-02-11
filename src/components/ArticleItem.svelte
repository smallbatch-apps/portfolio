<script>
	// import { cn } from '$lib/utils';
	export let url;
	export let title;
	export let description;
	export let image;
	export let readTime;
	export let publishDate;
</script>

<a
	href={url}
	target="_blank"
	class="flex flex-1 cursor-pointer flex-col gap-4 border border-transparent p-4 hover:border-gray-300"
>
	<img src={`/images/articles/${image}`} class="border border-2 border-red-400" alt={title} />
	<div>
		<h2 class="text-2xl font-semibold text-red-400">{title}</h2>

		<div class="flex items-center justify-between gap-2 text-gray-500">
			<span class="text-sm text-gray-500">{readTime}</span>
			<span class="text-sm text-gray-500">{publishDate}</span>
		</div>
	</div>
	<p>{description}</p>
</a>
