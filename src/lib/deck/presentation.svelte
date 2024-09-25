<script lang="ts">
	import Code from './code.svelte';
	import Notes from './notes.svelte';
	import Slide from './slide.svelte';
</script>

<Slide animate>
	<p>First</p>
</Slide>

<Slide animate>
	<p>First</p>
	<p>Slide!</p>
</Slide>

<Slide animate>
	<p>First</p>
	<p>Slide!</p>
	<p>With <a href="https://github.com" target="_blank">links</a>!</p>
</Slide>

<Slide animate>
	<Code id="code" lines="|2">
		{`
		const myFunction = (message: string) => {
			console.log(message);
		}
		`}
	</Code>
</Slide>

<Slide animate>
	<Code id="code" lines="|3">
		{`
		const myFunction = (message: string) => {
			console.log(message);
			console.log("done!");
		}
		`}
	</Code>
</Slide>