<script lang="ts">
	import ProductList from '$lib/components/productList.svelte';
	import Button from '$lib/components/ui/button/button.svelte';
</script>

<div
	class="bg-cover h-screen bg-center flex flex-col justify-center items-center gap-3 text-white bg-black"
	id="bg-back"
>
	<h1 class="font-bold text-5xl">Long-term thinking</h1>
	<span class="text-2xl w-[50%] text-center"
		>We're committed to responsible, sustainable, and ethical manufacturing. Our small-scale
		approach allows us to focus on quality and reduce our impact. We're doing our best to delay the
		inevitable heat-death of the universe.</span
	>
	<Button class="w-48 h-16 bg-white hover:bg-gray-100 text-black font-bold text-base"
		>Visit our store</Button
	>
</div>

<ProductList />
