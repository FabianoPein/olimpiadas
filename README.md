# Projeto: Busca de Atletas

## Descrição
Este projeto web permite pesquisar por atletas e esportes, exibindo os resultados de forma clara e organizada. A busca é realizada em tempo real, à medida que o usuário digita no campo de pesquisa.

## Tecnologias Utilizadas
* **HTML:** Estrutura básica da página web.
* **CSS:** Estilização da página, definindo cores, fontes e layout.
* **JavaScript:** Lógica da aplicação, incluindo a função de pesquisa e a manipulação do DOM.

## Como funciona
1. **Interface do usuário:**
   * O usuário digita o nome do atleta ou esporte no campo de pesquisa.
   * Ao clicar no botão "Pesquisar" ou ao pressionar Enter, a função `pesquisar()` é chamada.
2. **Processamento da pesquisa:**
   * A função `pesquisar()` coleta o texto digitado pelo usuário.
   * Ela busca por correspondências no conjunto de dados de atletas (armazenado em `dados.js`).
   * A busca é feita em três campos: título, descrição e tags.
3. **Exibição dos resultados:**
   * Se houver resultados, eles são exibidos em uma seção específica da página, com informações como título, descrição e link para mais detalhes.
   * Se não houver resultados, uma mensagem informativa é exibida.

## Como usar
1. **Clonar o repositório:**
   ```bash
   git clone https://seu-repositorio.git
