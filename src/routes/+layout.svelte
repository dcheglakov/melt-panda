<script lang="ts">
	import '../app.postcss';
	import { container } from 'styled-system/patterns';
</script>

<main class={container()}>
	<slot />
</main>
