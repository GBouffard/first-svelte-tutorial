<script>
  import Greeting from "./Greeting.svelte";
  import IfLogic from "./IfLogic.svelte";
  export let name;
</script>

<style>
  h1 {
    color: purple;
  }
</style>

<h1>Hello {name}!</h1>
<Greeting first_name="Guillaume" last_name="Bouffard" />
<IfLogic />
