<script lang="ts">
 
  import FileList from './lib/FileList.svelte';
  import StatusBar from './lib/StatusBar.svelte';
</script>

<main>
 <FileList />
  <StatusBar />
</main>

<style>
  :root {
    font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen,
      Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
  }

  main {
    text-align: center;
    padding: 1em;
    margin: 0 auto;
  }


</style>
