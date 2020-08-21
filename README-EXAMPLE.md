<img alt="GoStack" src="https://storage.googleapis.com/golden-wind/bootcamp-gostack/header-desafios.png" />

<h3 align="center">
  Resolução: Desafio 08 - Fundamentos de React Native
</h3>

<p align="center">
  <img alt="GitHub language count" src="https://img.shields.io/github/languages/count/rocketseat/bootcamp-gostack-desafios?color=%2304D361">

  <img alt="License" src="https://img.shields.io/badge/license-MIT-%2304D361">
</p>

<p align="center">
  <a href="#tecnologias-utilizadas">Tecnologias Utilizadas</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#funcionalidades-da-aplicação">Funcionalidades da Aplicação</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#especificações-dos-testes">Especificações dos Testes</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#memo-licença">Licença</a>
</p>

## Tecnologias Utilizadas

- [React Native](https://reactnative.dev/);
- [ESLint](https://eslint.org)
- [Prettier](https://prettier.io)
- [Typescript](https://typescriptlang.org)

### Funcionalidades da Aplicação

- **`Listar os produtos da fake API`**: A página Dashboard exibe uma listagem através de uma tabela, com os campos title, image_url e price.

- **`Adicionar itens ao carrinho`**: Em toda a aplicação, é utilizado um Contexto chamado.

- **`Exibir itens do carrinho`**: A página Cart exibe todos os itens do carrinho, junto com a quantidade, valor único, valor subtotal dos itens e total de todos os items.

- **`Aumentar quantidade de itens do carrinho`**: A página Cart permite que o usuário aumente a quantidade de itens do mesmo produto.

- **`Diminuir quantidade de um item do carrinho`**: A página Cart permite que o usuário decremente a quantidade de itens de um produto.

- **`Exibir valor total dos itens no carrinho`**: Tanto na página Dashboard, quanto na página Cart você é exibido o valor total de todos os itens que estão no carrinho.

### Específicações dos testes

- **`should be able to list the products`**: Para que esse teste passe, a aplicação deve permitir que sejam listados na sua tela Dashboard, toda os produtos que são retornadas do Fake API. Essa listagem deve exibir o title e o price que deve ser formatado utilizando a função Intl.

- **`should be able to add a product to the cart`**: Para que esse teste passe, deve ser possível adicionar produtos da Dashboard ao carrinho, utilizando o contexto de cart disponibilizado.

- **`should be able to list the products on the cart`**: Para que esse teste passe, deve ser possível listar os produtos que estão salvos no contexto do carrinho na página Cart, nessa página é exibido o nome do produto e o subtotal total de cada produto (price \* quantity).

- **`should be able to calculate the cart total`**: Para que esse teste passe, tanto na página Dashboard, quanto na página Cart deve ser exibido o valor total de todos os itens que estão no carrinho.

- **`should be able to show the total quantity of itens in the cart`**: Para que esse teste passe, tanto na página Dashboard, quanto na página Cart deve ser exibido o número total de itens que estão no carrinho.

- **`should be able to increment product quantity on the cart`**: Para que esse teste passe, deve ser possível incrementar a quantidade de um produto do carrinho, utilizando o contexto de cart disponibilizado.

- **`should be able to decrement product quantity on the cart`**: Para que esse teste passe, deve ser possível decrementar a quantidade de um produto do carrinho, utilizando o contexto de cart disponibilizado.

- **`should be able to navigate to the cart`**: Para que esse teste passe, o componente FloatingCart na Dashboard, você deve permitir que ao clicar no botão de carrinho com o testID de navigate-to-cart-button, o usuário seja redirecionado para a página Cart.

- **`should be able to add products to the cart`**: Para que esse teste passe, o arquivo onde contém o contexto do carrinho, deve permitir que a função addToCart adicione um novo item ao carrinho.

- **`should be able to increment quantity`**: Para que esse teste passe, o arquivo onde contém o contexto do carrinho, deve permitir que a função increment incremente em 1 unidade a quantidade de um item que está armazenado no contexto.

- **`should be able to decrement quantity`**: Para que esse teste passe, o arquivo onde contém o contexto do carrinho, deve permitir que a função decrement decremente em 1 unidade a quantidade de um item que está armazenado no contexto.

- **`should store products in AsyncStorage while adding, incrementing and decrementing`**: Para que esse teste passe, o arquivo onde contém o contexto do carrinho deve permitir que todas as atualizações que forem feitas no carrinho, sejam salvas no AsyncStorage. Por exemplo, ao adicionar um item ao carrinho, adicione-o também no AsyncStorage. O valor do AsyncStorage deve ser atualizado quando for incrementado ou decrementado a quantidade de um item.

- **`should load products from AsyncStorage`**: Para que esse teste passe, o arquivo onde contém o contexto do carrinho, deve permitir que todos os produtos que foram adicionados sejam buscados do AsyncStorage.

## :memo: Licença

Esse projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

---
