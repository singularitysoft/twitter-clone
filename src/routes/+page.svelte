<script>
  
  import TweetList from '../components/TweetList.svelte';

  let tweets = [
    { text: 'First tweet' },
    { text: 'Second tweet' },
    { text: 'Third tweet' },
  ];
</script>

<div class="container">
  <h1>Twitter clone</h1>
  <TweetList tweets={tweets} />
</div>

<style>
  @import '../../app.css';
</style>