<script>
	import Heading from '$lib/components/Heading.svelte';
	import Button from '$lib/components/Button.svelte';
	import events from '$lib/events/';
	console.log(events);
</script>

<svelte:head>
	<title>Events</title>
</svelte:head>

<Heading>Events Events Events</Heading>

<section class="flex flex-col md:px-20 md:py-16 bg-white overflow-auto">
	<iframe
		title="1RG Public Calendar"
		src="https://lu.ma/embed/calendar/cal-wYZCgwOcJN8kiNH/events"
		width="100%"
		height="500"
		frameborder="0"
		style="border: 1px solid #bfcbda88; border-radius: 4px;"
		allowfullscreen="false"
		aria-hidden="false"
		tabindex="0"
	/>
</section>
