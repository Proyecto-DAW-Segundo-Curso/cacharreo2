<script>
  import Header from "./lib/Header.svelte";
  import Contador from "./lib/Contador.svelte";
  import ModoVisual from "./lib/ModoVisual.svelte";
  import LineAdicional from "./lib/LineaAdicional.svelte";
  import Boton from "./lib/boton.svelte";
  import Darkmode from "./lib/Darkmode.svelte";
 
 



  let colores = ["blue", "red", "green", "orange"];
</script>

{#each colores as color, i}
  {#if i % 2 == 0}
    <Header {color} titulo={color} tam="3" />
  {:else}
    <Header {color} titulo={color} tam="2" />
  {/if}

{/each}

<Header titulo="Header1" />
<Header titulo="Otro" color="blue" />

<Contador />
<ModoVisual />
<Boton />

<Darkmode/>

<LineAdicional />

<style>
</style>
