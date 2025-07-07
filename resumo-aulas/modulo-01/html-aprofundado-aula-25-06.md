# HTML Aprofundado – Aula 25/06  
**Resumo dos tópicos técnicos abordados por Matheus**

---

## 1. *Formulários HTML*

- **Introdução:**
  - Importância e usos comuns: login, cadastro, envio de mensagens, campos de busca.
  - Estrutura básica: tag `<form>` como container pai dos elementos de entrada.
  - Tags utilizadas: `<input>`, `<textarea>`, `<select>`, `<option>`.

- **Atributos da tag `<form>`:**
  - `action`: define para onde os dados serão enviados.
  - `method`: `get` (dados visíveis na URL) ou `post` (dados sensíveis, não aparecem na URL).

- **Atributos importantes dos `<input>`s:**
  - `type`, `name`, `id`, `placeholder`, `value`, `required`, `maxlength`, `minlength`, `max`, `min`.

- **Tipos de `<input>`s:**
  - Texto simples, `email`, `number`, `date`, `checkbox`, `radio`, `file`.

- **Botões de formulário:**
  - `submit`, `reset`, `button`.

- **Prática:**
  - Exemplos demonstrando funcionamento, validações, usabilidade e vínculo com `<label>`.

---

## 2. *Tabelas HTML*

- **Estrutura semântica:**
  - `<table>`, `<thead>`, `<tbody>`, `<tfoot>`, `<tr>`, `<th>`, `<td>`.

- **Prática com HTML e CSS:**
  - Criação de linhas/colunas.
  - Estilização: bordas, alinhamento, espaçamento, cores alternadas com `:nth-child(odd)` e `:nth-child(even)`.
  - Negrito e cores em colunas específicas com `td:nth-child(n)`.

- **Observação:**
  - HTML para tabelas pode ser repetitivo e pouco intuitivo, exige atenção.

---

## 3. *Favicons (Ícones de Favoritos)*

- **Conceito:**
  - Ícone pequeno que aparece na aba do navegador, histórico e favoritos.

- **Implementação:**
  - `<link rel="shortcut icon" href="caminho_do_icon.svg">` dentro do `<head>`.

- **Formatos suportados:**
  - SVG (preferido), PNG, ICO, JPG.

- **Recursos recomendados:**
  - [Phosphor Icons](https://phosphoricons.com)
  - [Google Fonts Icons](https://fonts.google.com/icons)
  - [Font Awesome](https://fontawesome.com)
  - [Bootstrap Icons](https://icons.getbootstrap.com)

- **Dicas práticas:**
  - Incluir o favicon em todas as páginas.
  - Testes com links externos funcionaram corretamente.

---

## 4. *Metadados – Open Graph*

- **O que é:**
  - Protocolo criado pelo Facebook para controlar como o link aparece em redes sociais.

- **Uso:**
  - Tags `<meta property="og:xxx" content="...">` dentro do `<head>`.

- **Principais propriedades:**
  - `og:title`, `og:description`, `og:image`, `og:url`, `og:type`.

- **Importância:**
  - Melhora a apresentação em compartilhamentos, aumenta cliques e engajamento.

- **Ferramentas:**
  - Geradores automáticos de tags OG.
  - Exemplos práticos no Facebook, LinkedIn e WhatsApp.

- **Relevância para empresas:**
  - Impacto direto em visibilidade, identidade visual e SEO.

---

## 5. *Boas práticas e acessibilidade*

- **HTML semântico e acessível:**
  - Uso correto de `<label>` vinculado ao `id` dos campos.

- **Validação:**
  - HTML já possui validações nativas, mas deve ser complementado no back-end.

- **Organização:**
  - Código claro, bem estruturado e comentado facilita manutenção e colaboração.

---

## Observações Finais

- **Todos os conceitos foram demonstrados com exemplos no VS Code.**
- **Matheus reforçou a importância de aplicar boas práticas desde o início.**
- **Destaque para acessibilidade, validação e consistência visual como pilares do front-end.**
