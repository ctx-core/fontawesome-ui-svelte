<script lang="ts">
import { Icon } from '@ctx-core/svg-ui-svelte'
import { unpick } from 'ctx-core/object'
export let node = null
let node__
$: node__, node = node__
let props
$: props = unpick($$props, 'class')
</script>

<Icon bind:node="{node__}" class="fa-icon {$$props.class||''}" {...props}><slot></slot></Icon>
