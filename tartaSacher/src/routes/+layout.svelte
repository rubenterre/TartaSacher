<script>
  import Header from "./components/Header.svelte";


</script>
<Header/>
<slot/>

<style>

@font-face{
    font-family: Nunito;
    src: url(font/Nunito-VariableFont_wght.ttf);
}

:root{
    --cor-principal: #979797;
    -cor-secundario: #343239;
    --fonte-principal: Nunito;
}

:global(*){
    margin:0px;
    padding: 0px;
    box-sizing: border-box;
}

:global(body){
    background: white;
    font-size: 16px;
}

</style>