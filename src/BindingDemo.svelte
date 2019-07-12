<script>
  let name = "Boubou";
</script>

<style>
  input {
    font-style: italic;
    margin-top: 20px;
  }
  h3 {
    color: green;
  }
</style>

<input bind:value={name} />
<h3>Yo {name}</h3>
