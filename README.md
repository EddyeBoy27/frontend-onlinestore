# Boas vindas ao repositório do projeto de Front-End Online Store!

## O que foi desenvolvido

Neste projeto criei uma versão simplificada, sem persistência no banco de dados, de uma loja online, desenvolvendo em grupo suas funcionalidades de acordo com demandas definidas em um quadro _Kanban_, em um cenário mais próximo ao do mercado de trabalho. A partir dessas demandas, teremos uma aplicação onde os usuários poderão:
  - Buscar produtos por termos e categorias a partir da _API do Mercado Livre_;
  - Interagir com os produtos buscados de modo a adicioná-los e removê-los de um carrinho de compras em diferentes quantidades;
  - Visualizar detalhes e avaliações prévias de um produto, bem como criar novas avaliações;
  - E por fim, finalizar a compra dos itens selecionados.

---

## Equipe

- [Douglas Henrique](https://www.linkedin.com/in/douglas-he/)

- [Andrey Tsuzuki](https://www.linkedin.com/in/andrey-tsuzuki/)

---

## Requisitos do projeto

### 1. Criar página de listagem de produtos vazia

  - A tela básica da plataforma é a tela de **listagem de produtos**, onde quem usa buscará o que quer para adicionar ao carrinho e filtrará suas buscas.

### 2. Criar página do carrinho de compras

  - Quem usa o site irá adicionar produtos em seu carrinho de compras e finalizar a compra. A listagem de produtos deve ter um ícone de carrinho que, ao ser clicado, leva à página do carrinho. Inicialmente, o carrinho deverá estar vazio.

### 3. Listar as categorias de produtos disponíveis via API na página principal

  - Um endpoint da API do Mercado Livre retorna as categorias de produto disponíveis para busca. Em momento posterior tais categorias serão usadas para filtrar a listagem de produtos. Por hora, elas devem ser listadas na tela da listagem, conforme protótipo.

### 4. Buscar por termos e receber uma listagem de produtos, com dados resumidos, associados a esses termos

  - A alma do site é a sua lógica de busca e listagem de produtos. Após digitar seus termos na caixa de busca uma requisição deverá ser feita à API do Mercado Livre, tendo como parâmetros a frase digitada, e tais produtos deverão aparecer na tela numa exibição resumida, conforme protótipo anexo.

### 5. Selecionar uma categoria e ver somente produtos daquela categoria

  - A página, agora, deve poder usar as categorias recuperadas da API para filtrar os produtos buscados. Os termos e as categorias inseridas por quem usa devem ser usados em conjunto para filtragens mais específicas.

### 6. Clicar na exibição resumida de um produto e ir para uma tela com sua exibição detalhada

  - A exibição detalhada de um produto será a página para exibir tudo o que se tem acerca de um produto específico.

### 7. Adicionar uma quantidade arbitrária de um produto ao carrinho a partir de sua tela de exibição detalhada

  - Poder adicionar produtos ao carrinho a partir de sua tela de exibição detalhada será um canal importante de conversões de venda.

### 8. Avaliar e comentar acerca de um produto em sua tela de exibição detalhada

  - Avaliações positivas de um produto contribuem para boas vendas e nos dão insumos para, no tempo, destacarmos os produtos melhores e fazermos anúncios direcionados. Produtos ruins, de forma análoga, podem eventualmente ser penalizados por avaliações ruins.

### 9. Visualizar a lista de produtos adicionados ao carrinho em sua página e manipular sua quantidade

  - São operações básicas de carrinho a alteração da quantidade de um determinado produto nele e a visualização de tudo o que foi adicionado, com a soma dos valores.

### 10. Adicionar produtos a partir da tela de listagem de produtos

  - Múltiplas formas fáceis de adicionar um produto ao carrinho impactam positivamente nas taxas de conversão.

### 11. Finalizar compra, vendo um resumo dela, preenchendo os meus dados e escolhendo a forma de pagamento

  - O último grande passo do fluxo do e-commerce é a finalização da compra por parte de quem usa.

### 12. Ver junto ao ícone do carrinho a quantidade de produtos dentro dele, em todas as telas em que ele aparece

  - A partir de uma pesquisa com usuários e concorrentes, identificamos que existe a necessidade de uma visualização da quantidade de produtos do carrinho de uma forma dinâmica e acessível.

### 13. Navegar por um e-commerce estilizado em CSS

  - Uma navegação em _wireframes_ não é uma experiência de uso agradável. Uma vez que nenhum design do produto foi especificado, no entanto, cabe a quem programa estilizar o site.

### 14. Ver quais produtos tem frete grátis

  - As pessoas que vendem no Mercado Livre disponibilizam frete grátis a alguns produtos. Devemos incorporar isso ao e-commerce.

### 15. Ter os dados de compra de quem compra validados antes da compra ser efetuada

  - Se os dados de compra de quem usa não são validados automáticamente temos uma quantidade grande de compras estornadas por informações inseridas incorretamente. Não queremos isso.

---
