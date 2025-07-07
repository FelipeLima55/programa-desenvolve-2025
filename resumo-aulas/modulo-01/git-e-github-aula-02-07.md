# Resumo Técnico – Aula Git e GitHub (02/07)  
**Comandos, conceitos e práticas apresentadas por Matheus**

---

## 1. *Introdução ao Git e GitHub*

- **Git**: software instalado localmente para controle de versão. Rastreia alterações nos arquivos.
- **GitHub**: plataforma online para hospedar repositórios. Permite colaboração e backup remoto.
- A combinação Git local + GitHub remoto é o padrão mais utilizado atualmente.

---

## 2. *Conceitos básicos do Git*

- **Workspace**: pasta local do projeto.
- **Staging area**: área onde as alterações são preparadas para commit.
- **Commit**: registro definitivo de alterações no histórico.
- **Comandos principais**:
  - `git status`: mostra estado atual dos arquivos.
  - `git add [arquivo]`: adiciona arquivo ao stage.
  - `git add .`: adiciona todos os arquivos modificados.
  - `git commit -m "mensagem"`: realiza commit com descrição.

---

## 3. *Configurações iniciais do Git*

```bash
git config --global user.name "Seu Nome"
git config --global user.email "email@exemplo.com"
```

- Essas configurações identificam quem está fazendo os commits.

---

## 4. *Visualização do histórico*

- `git log`: mostra histórico completo de commits com hash, autor, data e mensagem.

---

## 5. *Fluxo básico para criar e versionar um projeto*

1. Criar pasta do projeto.
2. Inicializar repositório: `git init`
3. Criar/modificar arquivos.
4. Verificar alterações: `git status`
5. Adicionar ao stage: `git add .`
6. Fazer commit: `git commit -m "mensagem"`

---

## 6. *Uso do Git integrado ao VS Code*

- Terminal integrado com suporte a Git.
- Interface visual para adicionar arquivos ao stage, escrever mensagens e fazer commits.
- Visualização gráfica da linha do tempo.
- Extensão recomendada: **GitLens** para ver histórico por linha de código.

---

## 7. *Criação e configuração de chave SSH para GitHub*

```bash
ssh-keygen -t rsa -b 4096 -C "email@exemplo.com"
eval $(ssh-agent -s)
ssh-add ~/.ssh/id_rsa
cat ~/.ssh/id_rsa.pub
```

- Colar chave em: GitHub > Settings > SSH and GPG Keys  
- Testar conexão: `ssh -T git@github.com`

---

## 8. *Conectar repositório local ao GitHub*

```bash
git remote add origin git@github.com:usuario/nome-repositorio.git
git remote -v
git push -u origin main
```

- Depois disso, use `git push` para atualizações futuras.

---

## 9. *Uso do arquivo `.gitignore`*

- Arquivo usado para ignorar arquivos/pastas sensíveis ou desnecessários no repositório.
- Exemplo:
```gitignore
.env
node_modules/
*.log
```

---

## 10. *Dicas gerais e boas práticas*

- Faça commits pequenos, frequentes e com mensagens claras.
- Use `git status` regularmente.
- Comunique-se em times para evitar conflitos.
- Resolva conflitos com diálogo e análise.
- Prefira `main` como branch padrão por inclusão.

---

## ✅ Conclusão

- A aula cobriu desde fundamentos teóricos até práticas de configuração, versionamento local e integração com GitHub.
- Comandos essenciais, fluxo de trabalho, chave SSH e Git no VS Code foram demonstrados na prática.

---
