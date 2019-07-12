<script>
  let isTrue = false;
  const toggle = () => {
    isTrue = !isTrue;
  };
</script>

<style>
  .true {
    background: lightgreen;
    color: darkgreen;
  }
  .false {
    background: red;
    color: darkred;
  }
</style>

{#if isTrue}
  <button class="true" on:click={toggle}>TRUE</button>
{:else}
  <button class="false" on:click={toggle}>FALSE</button>
{/if}
