# Front-end Livraria - Cliente (Exercicio 8.3)

Este repositorio contem a aplicacao Front-end (Cliente) do sistema de livraria. O projeto foi refatorado para implementar a Arquitetura Cliente-Servidor, tornando-se 100% independente e consumindo os dados via rede através de uma API REST.

Aviso: Para que esta interface funcione corretamente e exiba os livros e o historico, o projeto do Back-end (API em Python/Flask) precisa estar em execucao simultaneamente na porta 5000.

## Tecnologias Utilizadas
* HTML5: Estruturacao das paginas da loja.
* CSS3: Estilizacao e layout responsivo dos cartoes de livros e interface.
* JavaScript (Vanilla): Logica de programacao no lado do cliente.
* Fetch API: Utilizada para realizar as requisicoes HTTP assincronas para o Back-end e manipular os retornos em JSON.

## Estrutura do Projeto
A interface e composta por arquivos estaticos simples:
* index.html: Vitrine da loja que busca e exibe o catalogo de livros disponiveis na API.
* compra.html: Pagina de transicao que envia o ID do livro escolhido para a API e exibe o recibo de sucesso ou mensagem de erro.
* compras.html: Pagina que consome a rota de historico da API e exibe todas as compras ja realizadas e salvas no servidor.

## Como Executar o Projeto

Diferente do Back-end, este projeto Front-end nao exige instalacao de dependencias ou servidores complexos, pois e formado apenas por arquivos estaticos.

1. Clone o repositorio:
git clone [COLE_AQUI_O_LINK_DO_SEU_REPOSITORIO_FRONTEND]

2. Inicie o Back-end primeiro:
Certifique-se de que o seu projeto Python (app.py) esta rodando no terminal (http://127.0.0.1:5000).

3. Abra a Interface:
Basta dar um duplo clique no arquivo `index.html` ou clicar com o botao direito e selecionar "Abrir com o navegador" (Chrome, Edge, Firefox, etc). 
A pagina fara a conexao com a API automaticamente.

---
Projeto desenvolvido para a disciplina de Engenharia de Software.
