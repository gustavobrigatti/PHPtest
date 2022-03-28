# PHPtest

Teste de seleção para vaga PHP

## Faça um fork desse projeto e siga as intruções a seguir utilizando esse projeto.

Construir uma aplicação web para buscar endereço. Aplicação deve fazer uma chamada na API via cep : https://viacep.com.br/.
Premissas:

  ● Usar PHP 5.6 ou superior.
  
  ● Usar Bootstrap.
  
  ● JavaScript (Não usar framework).
  
  ● Retorno deve ser em xml.
  
  ● Salvar os dados em uma base e antes de uma nova consulta verificar se o cep já foi consultado, caso tenha sido, trazer    informação da base e não deve efetuar uma nova consulta.
  
  ● Tratar o erro. Dar um retorno amigável para usuário leigo.
  
  
## PS: Valorizamos a criatividade no layout.

# Entrega: 
 * Disponibilizar um link do repositório no GitHub e encaminhar para developer@cd2.com.br

## INSTALAÇÃO

A aplicação deve ser executada em um servidor php 5.6 ou superior a partir do diretório public/index.php<br><br>

Banco de dados deve ser criado um banco com o nome "busca-cep" com a collaction "utf8mb4_general_ci" com as seguintes configurações:<br>
<ul>
<li>DB_HOST=127.0.0.1</li>
<li>DB_PORT=3306</li>
<li>DB_DATABASE=busca-cep</li>
<li>DB_USERNAME=root</li>
<li>DB_PASSWORD=</li>
</ul>
Caso alguma informação não esteja igual a lista acima, deve-se alterar esses dados no arquivo ".env"<br><br>
Após feito isso, deve-se executar o seguinte comando:<br>
<ul>
    <li>PHP ARTISAN MIGRATE</li>
</ul>
