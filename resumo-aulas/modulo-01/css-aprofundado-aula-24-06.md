# CSS Aprofundado – Aula 24/06

## 1. **Recapitulação inicial**
- Revisão breve sobre CSS básico: sintaxe, seletores, box model (content, padding, border, margin).
- Trabalhos com cores (hexadecimal, rgba).
- Propriedades de fontes (`font-family`, `font-size`, etc).

## 2. **Presença e acompanhamento da plataforma**
- Discussão sobre problemas na visualização e monitoramento das presenças na plataforma.
- Sugestões de melhorias.

## 3. **Posicionamento de elementos com CSS**
- Diferenças entre `display: block`, `inline` e `inline-block`:
  - **Block:** ocupa toda a largura disponível e inicia nova linha.
  - **Inline:** ocupa apenas o espaço necessário, sem quebra de linha.
  - **Inline-block:** mistura dos dois; permite definir largura e altura e fica na mesma linha.
- Demonstração prática com `div`s, explicação visual e exemplos da plataforma usada pelo curso.

## 4. **Uso do `display: none`**
- Utilizado para esconder elementos do fluxo visual e de interação da página.
- Boas práticas para responsividade: esconder elementos em telas menores e substituí-los (ex: menu hambúrguer).
- Recomendação: evitar carregar conteúdo desnecessário no front-end.

## 5. **Flexbox (`display: flex`)**
- Organização de elementos em uma dimensão (linha ou coluna).
- Estrutura:
  - **Container (pai)**
  - **Itens (filhos)**
- Propriedades do container:
  - `flex-direction`: `row`, `column`, `row-reverse`, `column-reverse`.
  - `justify-content`: `flex-start`, `flex-end`, `center`, `space-between`, `space-around`.
  - `align-items`: `flex-start`, `flex-end`, `center`, `baseline`, `stretch`.
  - `flex-wrap`: `nowrap`, `wrap`, `wrap-reverse`.
  - `gap`: espaçamento entre os itens.
- Propriedades dos itens:
  - `flex-grow`
  - `flex-shrink`
  - `flex-basis`
  - `order`
  - `align-self`
- Exemplos práticos e uso de ferramentas online para experimentar.
- Dicas de uso comum no desenvolvimento moderno.
- Atividade com o site **Flexbox Froggy**.

## 6. **Grid Layout (`display: grid`)**
- Organização de elementos em duas dimensões: linhas e colunas.
- Estrutura:
  - **Container grid**
  - **Grid items** (filhos diretos)
- Propriedades principais:
  - `grid-template-columns` e `grid-template-rows` (px, fr)
  - `gap`: espaçamento entre linhas e colunas.
  - `grid-column` e `grid-row`: posicionamento dos itens.
  - `grid-template-areas`: nomeação de áreas.
- Comparação com Flexbox: Grid trabalha em **2D**, Flexbox em **1D**.
- Demonstração prática de layout completo (cabeçalho, barra lateral, conteúdo principal, rodapé).
- Correção de erros comuns com uso do **DevTools**.

## 7. **Responsividade com Media Queries**
- Uso da regra `@media` para aplicar estilos conforme o tamanho da tela.
- Exemplos:
  - Adaptação de layout Grid para coluna única em telas pequenas.
- `max-width` e `min-width` para definir breakpoints.
- Abordagem **mobile-first**:
  - Primeiro para telas pequenas, depois adapta para maiores.
- Breakpoints sugeridos:
  - Mobile, tablet, notebook, desktop.
- Uso do DevTools para simular diferentes resoluções.
- Melhores práticas para mostrar/ocultar elementos conforme o dispositivo.

## 8. **Ferramentas e recursos recomendados**
- Sites:
  - [Origamid](https://origamid.com)
  - [Flexbox Froggy](https://flexboxfroggy.com)
  - [CSS Grid Garden](https://cssgridgarden.com)
  - [CSS-Tricks](https://css-tricks.com)
- Ferramentas:
  - DevTools do navegador (inspeção, medições, simulação de dispositivos)
- Dica final: prática constante é essencial para fixar os conceitos.

---

> **Nota:** O Matheus reforçou a importância do estudo e prática contínua, já que o conteúdo é extenso e muitas propriedades são melhor aprendidas com exercícios práticos.
