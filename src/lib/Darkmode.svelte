<script>

    let isDarkMode=false;
    function cambiarModo(){
        isDarkMode = !isDarkMode;
    }

</script>

<div class="container" class:dark-mode={isDarkMode} class:light-mode={!isDarkMode}>

    <button on:click={cambiarModo}>
        Cambiar a {isDarkMode ? 'Modo Oscuro' : 'Modo Claro'}
    </button>

    <p>dfgdgdfghfhgyjyhjyjyjyjhnghgfghfgh</p>
    <p>dfgdgdfghfhgyjyhjyjyjyjhnghgfghfgh</p>
    <p>dfgdgdfghfhgyjyhjyjyjyjhnghgfghfgh</p>
    <p>dfgdgdfghfhgyjyhjyjyjyjhnghgfghfgh</p>

</div>


<style>

   

    .dark-mode{
        background-color: aliceblue;
        color: black;
        
    }

    .light-mode{
        background-color: black;
        color: white;   
        
    }

</style>