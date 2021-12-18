<script lang="ts">
import { unpick } from '@ctx-core/object'
import { Icon } from '@ctx-core/svg-ui-svelte'
export let node = null
let node__
$: node__, node = node__
let props
$: props = unpick($$props, 'class')
</script>

<Icon bind:node="{node__}" class="fa-icon {$$props.class||''}" {...props}><slot></slot></Icon>
