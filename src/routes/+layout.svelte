<script lang="ts">
	import '../app.postcss';
	import { stack } from 'styled-system/patterns';
</script>

<main class={stack({ gap: '4' })}>
	<slot />
</main>
