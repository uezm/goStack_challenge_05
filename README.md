## <div align="center">:rocket: Desafio 05: Primeiro projeto Node.js </div>

##### <div align="center"> [Tecnologias](#Tecnologias)   |   [Desafio](#Desafio)   |   [Como contribuir](#Desafio)   |   [Licença](#Licença)    </div>

<div align="center"> Desafio sobre Conceitos do Node.js aplicado no Bootcamp GoStack  </div>

<br>

![Work](https://images.unsplash.com/photo-1594729095022-e2f6d2eece9c?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=500&q=60)

## :satellite: Tecnologias 
Esse projeto foi desenvolvido com as seguintes tecnologias: <br>
[- Node.js](https://nodejs.org/en/) <br>
[- Typescript](#) <br>
[- Outras](#) <br>


## :tophat: Desafio
Esse repositório serviu de desafio para treinar a criação de uma aplicação Node.js ao criar o back-end de uma 'transações da conta', colocando em prática alguns conceitos que se aprendeu até agora.


## :: Funcionalidades
Como funcionalidades, temos a criação de duas rotas utilizando os métodos http Post e Get:

- POST: A rota deve receber saldo de entrada (salário, depósitos, ...), saídas (retiradas, compras, ...), e o tipo da transação.  A aplicação não deve permitir a criação de nenhuma transação, se o total em conta for insuficiente.

- GET: Essa rota deve listar todas as transações cadastradas, junto com o valor de soma de entradas, retiradas e total de crédito.


## :memo: Testes aplicados nesse desafio:
Em cada teste tem uma breve descrição no que a aplicação deve cumprir para que o teste passe.

<strong> should be able to create a new transaction:</strong>
Para que esse teste passe, sua aplicação deve permitir que uma transação seja criada, e retorne um json com a transação criada.

<strong> should be able to list the transactions: </strong>
Para que esse teste passe, sua aplicação deve permitir que seja retornado um objeto contendo todas as transações junto ao balanço de income, outcome e total das transações que foram criadas até o momento.

<strong> should not be able to create outcome transaction without a valid balance: </strong>
Para que esse teste passe, sua aplicação não deve permitir que uma transação do tipo outcome extrapole o valor total que o usuário tem em caixa, retornando uma resposta com código HTTP 400 e uma mensagem de erro no seguinte formato: { error: string }


## :computer: Como contribuir
- Faça um fork desse repositório;
- Cria uma branch com a sua feature: git checkout -b minha-feature;
- Faça commit das suas alterações: git commit -m 'feat: Minha nova feature';
- Faça push para a sua branch: git push origin minha-feature.
- Depois que o merge da sua pull request for feito, você pode deletar a sua branch.



## :file_folder: Licença
Esse projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE.md) para mais detalhes.

<br>

#### <div align="center">#usemascara :mask: </div>
