<script>
	import { cn } from '$lib/utils';
	export let variant = 'frontend';

	const classes = cn(
		'rounded-full px-2 py-1 text-xs font-semibold uppercase tracking-widest text-white',
		{
			'bg-red-400': variant === 'frontend',
			'bg-blue-400': variant === 'backend',
			'bg-green-400': variant === 'blockchain'
		}
	);
</script>

<span class={classes}>
	<slot />
</span>
