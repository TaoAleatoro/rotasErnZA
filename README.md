# Padronização de rotas

## Login
{main}/{login {token_acesso}}/{dashboard}/{index.html}
## Dashboard
{dashboard}/{load:{index.js {getData()}}}
# Regras de Negócio
<table> <!-- Cria uma tabela -->
  <tr>  <!-- Cria uma nova linha -->
    <td> Identificador </td><!-- Cria uma nova coluna dentro da linha -->
    <td> RN001 </td>
  </tr>
  <tr>
    <td> Nome </td>
    <td> Login </td>
  </tr>
  <tr>
    <td> Data </td>
    <td> 28/10/2022 </td>
  </tr>
  <tr>
    <td> Autor </td>
    <td> João Neto </td>
  </tr>
    <tr>
    <td> Data da ultima alteração </td>
    <td> N/A </td>
  </tr>
   </tr>
    <tr>
    <td> Versão </td>
    <td> 1 </td>
  </tr>
  <tr>
    <td> Dependências </td>
    <td> N/A </td>
  </tr>
  <tr>
    <td> Descrição </td>
    <td> Quando entrar no site, o usuário deverá preencher preencher os campos de login e senha. Estes dois campos são obrigatórios. O usuário pode sair ao apertar o botão de login. </td>
  </tr>
  <tr>
    <td> Requisitos </td>
    <td> O login já deve estar cadastrado no banco de dados pelo ADM
      
      Caso o usuário digite um login não registrado, vai aparecer uma mensagem de login não cadastrado no sistema.
      
A senha deve ser preenchida corretamente.
      
      Caso o usuário erre no preenchimento da senha, vai aparecer a mensagem de senha incorreta </td>
  </tr>
  
  
</table>
<table>
<tr>  <!-- Cria uma nova linha -->
    <td> Identificador </td><!-- Cria uma nova coluna dentro da linha -->
    <td> RN002 </td>
  </tr>
  <tr>
    <td> Nome </td>
    <td> Dashboard </td>
  </tr>
  <tr>
    <td> Data </td>
    <td> 28/10/2022 </td>
  </tr>
  <tr>
    <td> Autor </td>
    <td> João Neto </td>
  </tr>
    <tr>
    <td> Data da ultima alteração </td>
    <td> N/A </td>
  </tr>
   </tr>
    <tr>
    <td> Versão </td>
    <td> 1 </td>
  </tr>
  <tr>
    <td> Dependências </td>
    <td> RN001 </td>
  </tr>
  <tr>
    <td> Descrição </td>
    <td> Após o Login o usuário terá acesso ao dashboad pincipal e assim poderá realizar suas análises. </td>
  </tr>
  <tr>
    <td> Requisitos </td>
    <td> O úsuário só terá acesso ao dashboard se tiver realizado o login </td>
  </tr>
  
