<script>
  import Tweet from './Tweet.svelte';

  export let tweets = [];
</script>

{#each tweets as tweet}
  <Tweet tweet={tweet} />
{/each}
