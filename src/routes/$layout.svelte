<script>
    import { setContext } from 'svelte'

    setContext( 'test', () =>
    {
        alert( 'Hello world!')
    })
</script>

<slot></slot>