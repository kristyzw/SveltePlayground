<script>
  let name = 'Max';
  let age = 1;

  function incrementAge() {
    age += 1;
  }
</script>

<style>
  h1 {
    color: purple;
  }
</style>

<h1>Hello {name}, my age is {age}!</h1>
<button on:click={incrementAge}>Change Age</button>
