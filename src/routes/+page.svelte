<!-- YOU CAN DELETE EVERYTHING IN THIS PAGE -->

<div class="container h-full mx-auto flex justify-center items-center">
	<div class="space-y-5">
		<h1>Let's get cracking bones!</h1>
		<p>Start by exploring:</p>
		<ul>
			<li>
				<code>/src/routes/+layout.svelte</code> - barebones layout, the CSS import order is critical!
			</li>
			<li>
				<code>/src/app.postcss</code> - minimal css to make the page full screen, may not be relevant
				for your project
			</li>
			<li><code>/src/routes/+page.svelte</code> - this page, you can replace the contents</li>
		</ul>

		<section class="services space-y-1 p-4">
			<div>Something 1</div>
			<div>Something 2</div>
			<div>Something 3</div>
			<div>Something 4</div>
			<div>Something 5</div>
		</section>
	</div>
</div>

<style lang="postcss">
	section > div {
		@apply variant-ringed-primary rounded-md px-2 py-1 text-sm;
	}
</style>
