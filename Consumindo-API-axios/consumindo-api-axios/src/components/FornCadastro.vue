
<template>
    <div id="app">
  
      <nav>
        <div class="nav-wrapper blue darken-1">
          <a href="#" class="brand-logo center">Produtos Front</a>
        </div>
      </nav>
  
      <div class="container">
  
        <form>
  
            <!-- <label>Nome</label> -->
            <input type="text" placeholder="Nome do Produto">
            <!-- <label>Quantidade</label> -->
            <input type="number" placeholder="Quantidade de Produtos">
            <!-- <label>Valor</label> -->
            <input type="text" placeholder="Valor do ptoduto">
  
            <button class="waves-effect waves-light btn-small">Salvar<i class="material-icons left">save</i></button>

        </form>
  
        <table>
        <thead>
  
            <tr>
              <th>NOME</th>
              <th>QUANTIDADE</th>
              <th>VALOR</th>
              <th>OPÇÕES</th>
            </tr>
  
        </thead>
  
          <tbody>
  
            <tr>
  
              <td>Arduino</td>
              <td>100</td>
              <td>50.00</td>
              <td>
                <button class="waves-effect btn-small blue darken-1"><i class="material-icons">create</i>Editar</button>
                <button class="waves-effect btn-small red darken-1"><i class="material-icons">delete_sweep</i>Deletar</button>
              </td>
  
            </tr>
  
          </tbody>
        
        </table>
  
      </div>
  
    </div>
  </template>
  
  <!-- <template >
    <div id="app">
        <nav>
             <div class="nav-wrapper blue darken-1"> 
                <a href="#" class="brand-log center ">Produtos do Front-end</a> 
            </div>
        </nav>
        <nav>
        
        <div class="container">

            <form>
                <label>Nome</label>
                <input type="text" placeholder="Nome do Produto">
                <label>Quantidade</label>
                <input type="number" placeholder="Qauntidade de produtos">
                <label>Valor</label>
                <input type="text" placeholder="Valor do produto">

                 <button class="< waves-effect waves-light btn-small">Salvar <i class="material-icons left">save</i></button>
                
            </form> 
            
            <thead>
                <tr> 
                    <th>HOME</th>
                    <th>QUANTIDADE</th>
                    <th>VALOR</th>
                    <th>OPÇÕES</th>
                </tr>
            </thead>

            <thead>
  
            <tbody>
                <tr>
                    <td>Arduino</td>
                    <td>45</td>
                    <td>25000</td>
                    <td>
                        <button class="waves-effect btn-small blue darken-1"><i class="material-icons">create</i>Editar</button>
                        <button class="waves-effect btn-small red darken-1"><i class="material-icons">delete_sweepp</i>Deletar</button>
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
</script> -->