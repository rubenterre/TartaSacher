<script>

</script>

<div class="detalles">
    <div class="detalles__left">
        <p class="dificultade"><span class="icono"><img src="dificultad_icono.webp" alt="Logo de dificultade da receita"></span>Media</p>
        <p class="preparacion"><span class="icono"><img src="tiempo_icono.webp" alt="Logo de tempo de preparación da receita"></span>30 min. de preparación</p>
    </div>
    <div class="detalles__right">
        <p class="personas"><span class="icono"><img src="personas_icono.webp" alt="Logo de para cantas persoas é a receita"></span>10-12 personas</p>
        <p class="cocion"><span class="icono"><img src="coccion_icono.webp" alt="Logo de tempo de cocción da receita"></span>50 min. de cocción</p>
    </div>
</div>

<style>
    .detalles{
        width: 497px;
        height: 71.7px;
        display: flex;
        justify-content: space-between;
        background-color: var(--cor-principal);
        margin-top: 31px;
    }

    .detalles__left, .detalles__right{
        display: flex;
        flex-direction: column;
        justify-content: space-between;
    }

    p{
        font-family: var(--fonte-principal);
        display: flex;
        align-items: center;
    }

    img{
        width: 34px;
    }

    .icono{
        margin-right: 16px;
        display: flex;
        align-items: center;
    }
</style>