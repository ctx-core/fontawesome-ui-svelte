<script>
import Icon from './Icon.svelte'
export let node = null
</script>
<Icon bind:node viewBox="0 0 512 512" width="512" height="512" {...$$props}><path d="M256 8C119 8 8 119 8 256s111 248 248 248 248-111 248-248S393 8 256 8zm0 448c-110.5 0-200-89.5-200-200S145.5 56 256 56s200 89.5 200 200-89.5 200-200 200z"></path></Icon>
