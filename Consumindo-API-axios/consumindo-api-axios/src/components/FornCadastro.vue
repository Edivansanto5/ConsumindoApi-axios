<template >
    <div id="app">
        <nav>
             <div class="nav-wrapper blue darken-1"> <!-- aqui vai fazer a tela de menu com as cores azul -->
                <a href="#" class="brand-log center ">Produtos do Front-end</a> 
            </div>
        </nav>
        <div class="conteiner">
            <form>
                <label>Nome</label>
                <input type="text">
                <label>Quantidade</label>
                <input type="text">
                <label>vValor</label>
                <input type="text">
            </form>
            <thead>
                <tr>
                    <th></th>
                    <th></th>
                    <th></th>
                    <th></th>
                </tr>
            </thead>
        </div>

    </div>
</template>

<script>
export default {
    name:'FornCadastro',
}
</script>