<script lang="ts">
	import welcome from '$lib/svelte-welcome.png?enhanced';
</script>

<div>
	<enhanced:img src="../lib/svelte-welcome.png" alt="An alt text" />
	<enhanced:img src={welcome} alt="An alt text" />
</div>