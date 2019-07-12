<script>
  export let name;
  import Greeting from "./Greeting.svelte";
  import IfLogic from "./IfLogic.svelte";
  import EachList from "./EachList.svelte";
  import EventDemo from "./EventDemo.svelte";
</script>

<style>
  h1 {
    color: purple;
  }
</style>

<h1>Hello {name}!</h1>
<Greeting first_name="Guillaume" last_name="Bouffard" />
<IfLogic />
<EachList />
<EventDemo />
