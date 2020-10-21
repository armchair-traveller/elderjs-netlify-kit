<script>
  export let templateHtml, settings;
</script>

<style>
</style>

<svelte:head>
  <link rel="stylesheet" href="/global.css" />
</svelte:head>
<div class="container">
  {@html templateHtml}
</div>
