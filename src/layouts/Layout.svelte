<!-- Layout is for any layout components like Header+Nav, Footer, or a container. 
  Similar to layout in Gatsby, present on all pages -->
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
