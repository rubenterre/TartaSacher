<script>
  import Detalles from "./components/Detalles.svelte";
  import Descripcion from "./components/Descripcion.svelte";
  import Video from "./components/Video.svelte";
  import AporteNutricional from "./components/Aporte_nutricional.svelte";
  import Rating from "./components/Rating.svelte";
</script>

<section>
  <div class="cabecera">
    <div class="cabecera__video">
      <Video />
    </div>
    <div class="cabecera__detalle">
      <Rating />
      <Detalles />
      <AporteNutricional />
    </div>
  </div>
  <Descripcion />
</section>

<style>
  .cabecera {
    display: grid;
    grid-template-columns: 1fr 1fr;
    background-color: var(--cor-principal);
    margin-top: 30px;
  }

  .cabecera__video {
    position: relative;
    width: 100%;
    padding-bottom: 56.25%;
  }

  .cabecera__detalle {
    padding: 50px;
  }
</style>
