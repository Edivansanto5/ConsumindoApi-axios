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
                <input type="text" placeholder="Nome do Produto">
                <label>Quantidade</label>
                <input type="number" placeholder="Qauntidade de produtos">
                <label>Valor</label>
                <input type="text" placeholder="Valor do produto">

                <button class="< waves-effect waves-light btn-small">Salvar <i class="material-icons left">save</i></button> <!--<i class="material-icons left">save</i> vai add icone de salvar -->
            </form>

            <!--fazendo uma tabela 1 linha e 4 colunas -->
            <!--<tr> quantidade de linha e <th> quantidade de colunas-->
            <thead>
                <tr> 
                    <th>HOME</th>
                    <th>QUANTIDADE</th>
                    <th>VALOR</th>
                    <th>OPÇÕES</th>
                </tr>
            </thead>
            <tbody>
                <tr>
                    <td>Arduino</td>
                    <td>45</td>
                    <td>25000</td>
                    <td>
                        <button class="aves-effect btn-small blue darken-1"><i class="material-icons">create</i>Editar</button>
                        <button class="aves-effect btn-small red darken-1"><i class="material-icons">delete_sweepp</i>Deletar</button>
                    </td>
                    
                </tr>
            </tbody>
        </div>

    </div>
</template>

<script>
export default {
    name:'FornCadastro',
}
</script>