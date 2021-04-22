<script>
    import { getContext } from 'svelte'
</script>

<a href="/foo">Go to route: Foo</a><br/><br/><br/>

<button on:click={getContext('test')}>Click me to test getContext</button>