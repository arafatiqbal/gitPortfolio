<script lang="ts">
	import Darkmode from './Darkmode.svelte';
</script>

<!-- svelte-ignore a11y-no-noninteractive-tabindex -->
<!-- svelte-ignore a11y-label-has-associated-control -->
<!-- svelte-ignore a11y-no-noninteractive-tabindex -->
<div class="navbar bg-base-200">
	<div class="navbar-start">
		<div class="dropdown tooltip tooltip-right" data-tip="Menu">
			<label tabindex="0" class="btn btn-ghost btn-circle">
				<svg
					xmlns="http://www.w3.org/2000/svg"
					class="h-5 w-5"
					fill="none"
					viewBox="0 0 24 24"
					stroke="currentColor"
					><path
						stroke-linecap="round"
						stroke-linejoin="round"
						stroke-width="2"
						d="M4 6h16M4 12h16M4 18h7"
					/></svg
				>
			</label>
			<ul
				tabindex="0"
				class="menu menu-sm dropdown-content mt-3 z-[1] p-2 shadow bg-base-100 rounded-box w-52"
			>
				<li><a href="/">Home</a></li>
				<li><a href="/">Contact</a></li>
			</ul>
		</div>
	</div>
	<div class="navbar-center tooltip tooltip-bottom" data-tip="Home">
		<a href="/" class="btn btn-ghost normal-case text-xl">gitPortfolio</a>
	</div>
	<div class="navbar-end">
		<Darkmode />
	</div>
</div>
