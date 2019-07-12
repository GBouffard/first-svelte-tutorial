<script>
  import Greeting from "./Greeting.svelte";
  export let name;
</script>

<style>
  h1 {
    color: green;
  }
</style>

<h1>Hello {name}!</h1>
<Greeting first_name="Guillaume" last_name="Bouffard" />
