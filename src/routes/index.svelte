<script>
    import { getContext } from 'svelte'
	
	const clickHandler = getContext('test')
</script>

<a href="/foo">Go to route: Foo</a><br/><br/><br/>

<button on:click={clickHandler}>Click me to test getContext</button>