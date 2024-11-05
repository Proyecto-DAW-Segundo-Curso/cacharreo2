<script>

    let texto = ''

    const mostrarMsg = () => {
        texto = 'Boton pulsado'
    }
</script>

<h1>{texto}</h1>

<button on:click={mostrarMsg}>Mostrar</button>

