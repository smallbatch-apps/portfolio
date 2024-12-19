<script>
	import { cn } from '$lib/utils';
	export let url;

	export let variant = 'red';
	export let size = 'medium';
	export let target = '_blank';

	const variantClasses = cn('inline-flex items-center gap-2 font-normal', {
		'border-white text-white hover:bg-red-300': variant === 'red',
		'border-gray-600 text-gray-600 hover:bg-gray-50': variant === 'white',
		'border-amber-200 text-amber-200 hover:bg-red-300': variant === 'amber',
		'px-8 py-3 text-lg font-semibold  border-2': size === 'medium',
		'px-2 py-1  border': size === 'small',
		'p-1  border': size === 'icon'
	});
</script>

<a href={url} {target} class={variantClasses}><slot /></a>
