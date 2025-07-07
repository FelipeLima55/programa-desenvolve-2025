# Resumo Técnico – Aula de Terminal (01/07)  
**Comandos de Terminal Apresentados por Matheus**

---

## 1. Conceitos Iniciais

- Terminal (também chamado de **Shell**, **CLI**, ou **Prompt**) é uma interface de texto para interagir com o sistema operacional.
- Usado para **navegar**, **criar**, **mover**, **copiar**, **renomear** e **excluir** arquivos e pastas via comandos.
- Fundamental para **automatizações**, **desenvolvimento** e uso de ferramentas como **Git**, **npm**, entre outras.

---

## 2. Comandos Básicos de Navegação e Visualização

- `pwd`: exibe o diretório atual (*print working directory*).
- `cd [diretório]`: entra no diretório especificado.
- `cd ..`: volta para o diretório pai.
- `ls`: lista arquivos e pastas do diretório atual.
- `ls -l`: lista com detalhes (permissões, proprietário, tamanho, data).
- `ls -a`: inclui arquivos ocultos.
- `ls -la` ou `ls -al`: combina detalhes + arquivos ocultos.

---

## 3. Criação de Arquivos e Pastas

- `mkdir [nome_da_pasta]`: cria uma nova pasta.
- `mkdir pasta1 pasta2 ...`: cria múltiplas pastas ao mesmo tempo.
- `touch [nome_do_arquivo]`: cria um arquivo vazio.

---

## 4. Manipulação de Arquivos e Pastas

- `cp [origem] [destino]`: copia arquivos.
- `cp -r [origem] [destino]`: copia pastas com todo o conteúdo.
- `mv [origem] [destino]`: move ou renomeia arquivos e pastas.

---

## 5. Exclusão de Arquivos e Pastas

- `rm [arquivo]`: remove arquivos.
- `rm -r [pasta]`: remove pastas e conteúdo interno (atenção: irreversível).
- `rmdir [pasta]`: remove pastas vazias.

---

## 6. Comandos de Auxílio e Atalhos

- **Tecla TAB**: autocompleta nomes de arquivos/pastas.
- **Setas ↑ ↓**: navega pelo histórico de comandos.
- `clear` ou **Ctrl + L**: limpa a tela.
- **Ctrl + C**: interrompe o comando atual.
- `history`: exibe o histórico de comandos digitados.
- **Ctrl + R**: busca reversa por comandos anteriores.

---

## 7. Dicas e Observações

- **Caminho absoluto**: caminho completo desde a raiz.  
  Ex: `C:\Users\usuario\Documentos\arquivo.txt`
- **Caminho relativo**: baseado na pasta atual.
- **Símbolos úteis:**
  - `.` → diretório atual
  - `..` → diretório pai
- **Git Bash no Windows**: recomendado para ter comandos compatíveis com Unix/Linux.
- **Compatibilidade**: comandos funcionam no Windows (via Git Bash ou PowerShell), Linux e MacOS (com pequenas variações).

---

## 8. Ferramentas e Recursos Adicionais

- `code .`: abre a pasta atual no VS Code (VS Code precisa estar instalado e configurado no PATH).
- Sites recomendados:
  - [https://linuxjourney.com](https://linuxjourney.com)
  - [https://explainshell.com](https://explainshell.com)

---
