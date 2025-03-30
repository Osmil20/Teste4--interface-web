Busca de Operadoras - Interface Web em Vue.js
Este é um projeto em Vue.js que fornece uma interface web simples para buscar operadoras através de uma API em Python. A interface permite ao usuário pesquisar operadoras pelo nome e visualizar informações como o nome fantasia, razão social e CNPJ.

Funcionalidades:
Busca por Operadoras: O usuário pode digitar o nome de uma operadora e buscar informações relacionadas a ela.

Exibição de Resultados: Exibe o nome fantasia, razão social e CNPJ das operadoras encontradas.

Mensagens de Erro: Exibe mensagens de erro caso o parâmetro de busca seja vazio ou ocorra algum erro na requisição.

Tecnologias:
Frontend: Vue.js

Backend: API em Python (não incluída no código, mas esperada para fornecer dados)

Como funciona:
O usuário digita o nome de uma operadora no campo de pesquisa.

Ao clicar no botão "Buscar", a aplicação faz uma requisição GET para a API Python (esperada na URL http://localhost:5000/search?q={query}).

A resposta da API é exibida na tela. Caso ocorra algum erro ou não haja resultados, uma mensagem é exibida.
