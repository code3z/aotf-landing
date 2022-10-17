<script>
	import TeamMember from '../../src/components/team-member.svelte';
</script>

<svelte:head>
	<script id="luma-checkout" src="https://embed.lu.ma/checkout-button.js">
	</script>
</svelte:head>

<h1 class="text-7xl text-white font-bold leading-relaxed mb-6">
	Teenage Founder <br /> <span class="underlined">Coffee Hour</span>
</h1>
<p>
	We run weekly events to support young people starting startups, in partnership with the <a
		class="link"
		href="https://1517fund.com">1517 Fund</a
	>. Join us!
</p>
<h1 class="mt-12 text-2xl font-bold">Events</h1>
<a
	href="https://lu.ma/event/evt-UFPBxwAGYdRdLrS"
	data-luma-action="checkout"
	data-luma-event-id="evt-UFPBxwAGYdRdLrS"
>
	<div class="mt-6 shadow-xl border-2 border-white/ 60-md p-6 my-6 max-w-2xl rounded-2xl">
		<p class="font-bold mb-4 text-white">Weekly Dropin</p>
		<p>
			We'll discuss startups, fundraising, hiring, and other challenges of founding a startup, and
			just have a fun time with other teens and mentors.
		</p>
	</div>
</a>
<a
	href="https://lu.ma/aotf"
	class="hover:-translate-y-0.5 transition-all duration-300 block text-white/80 hover:text-white"
>
	<svg
		class="icon mx-2"
		fill="none"
		stroke="currentColor"
		viewBox="0 0 24 24"
		xmlns="http://www.w3.org/2000/svg"
		><path
			stroke-linecap="round"
			stroke-linejoin="round"
			stroke-width="2"
			d="M10 6H6a2 2 0 00-2 2v10a2 2 0 002 2h10a2 2 0 002-2v-4M14 4h6m0 0v6m0-6L10 14"
		/></svg
	><span>View more events on lu.ma</span></a
>

<h1 class="mt-12 text-2xl font-bold">Team</h1>
<ul>
	<li>Jai Relan</li>
	<li>Ian Cheshire</li>
	<li>Nancy Zuo</li>
	<TeamMember />
</ul>
