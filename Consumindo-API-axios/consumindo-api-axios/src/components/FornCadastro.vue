<template >
    <div id="app">
        <nav>
             <div class="nav-wrapper blue darken-1"> <!-- aqui vai fazer a tela de menu com as cores azul -->
                <a href="#" class="brand-log center ">Produtos do Front-end</a> 
            </div>
        </nav>
        <div class="conteiner">

            <!-- formulario -->
            <form>
                <label>Nome</label>
                <input type="text">
                <label>Quantidade</label>
                <input type="number">
                <label>vValor</label>
                <input type="text">
                 <button class="< waves-effect waves-light btn-small">Salvar <i class="material-icons left">save</i></button> <!--<i class="material-icons left">save</i> vai add icone de salvar -->
            </form>

            <!--fazendo uma tabela de uma coluna e 4 linha-->
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