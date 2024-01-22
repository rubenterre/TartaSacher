<script>
import Popup from "./Popup.svelte";
let popupVisible = false;

function showPopup() {
  popupVisible = true;
}
</script>

<div class="aporte">
  <p class=" titulo">Qué me aporta esta receta…</p>
  <button  class="contenidoNutriconal" on:click={showPopup}>
    <p class="informacion">Información nutricional</p>
    <button class="boton"><img src="+.svg" alt="" /></button>
  </button>
</div>
<Popup bind:visible={popupVisible}/>

<style>

  .aporte{
    margin-top: 50px;
  }

  .titulo {
    color: #000000;
    font-family: Nunito;
    font-size: 20px;
    font-style: normal;
    font-weight: 700;
    line-height: normal;
    margin-bottom: 30px;
  }

  .contenidoNutriconal {
    display: flex;
    width: 628px;
    height: 44px;
    flex-shrink: 0;
    border: 1px solid #979797;
    background: #fff;
    justify-content: space-between;
    padding-right: 11px;
  }

 .informacion {
    color: #000;
    font-family: Nunito;
    font-size: 16px;
    font-style: normal;
    font-weight: 400;
    line-height: normal;
    width: 300px;
    height: 22px;
    padding-top: 11px;
    padding-bottom: 11px;
    padding-left: 9px;
  }

 .boton {
    color: #000;
    border: none;
    background-color: #fff;
    padding-bottom: 11px;
    padding-top: 11px;
  }
</style>
