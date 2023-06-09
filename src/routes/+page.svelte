<div class="flex justify-center m-5">
	<div class="p-5 rounded-3xl bg-slate-100 card">
		<article class="prose lg:prose-xl">
			<h1>Lorem Ipsum</h1>
			<p>
				For years parents have espoused the health benefits of eating garlic bread with cheese to
				their children, with the food earning such an iconic status in our culture that kids will
				often dress up as warm, cheesy loaf for Halloween.
			</p>
			<p>
				But a recent study shows that the celebrated appetizer may be linked to a series of rabies
				cases springing up around the country.
			</p>
		</article>
		<div />
	</div>
</div>

<style lang="scss">
	.card {
		transition: transform 0.5s ease-in-out, box-shadow 0.5s ease-in-out;
		transform: scale(1);
		box-shadow: 0 1px 3px 0 rgba(0, 0, 0, 0.1), 0 1px 2px 0 rgba(0, 0, 0, 0.06);
		&:hover {
			transform: scale(1.1);
			box-shadow: 0 10px 15px -3px rgba(0, 0, 0, 0.1), 0 20px 10px -1px rgba(0, 0, 0, 0.05);
			// filter: contrast(150%); /* added this line */
		}
	}
</style>
