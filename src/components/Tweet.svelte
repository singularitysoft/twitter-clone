<script>
  export let tweet;
</script>

<div class="tweet">
  <p>{tweet.text}</p>
</div>

<style>
  .tweet {
    padding: 16px;
    border: 1px solid #ddd;
    border-radius: 4px;
    margin-bottom: 16px;
    background-color: #f3e5f5;
    box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
    color: #7b68ee;
  }
</style>
