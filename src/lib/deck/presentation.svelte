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
	<Code id="code" lines>
		{`
      const hello = () => {
        console.log("ciao");
      }
    `}
	</Code>
	<Notes>Testing notes</Notes>
</Slide>
