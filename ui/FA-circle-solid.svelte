<script>
import Icon from './Icon.svelte'
export let node = null
</script>
<Icon bind:node viewBox="0 0 512 512" width="512" height="512" {...$$props}><path d="M256 8C119 8 8 119 8 256s111 248 248 248 248-111 248-248S393 8 256 8z"></path></Icon>
