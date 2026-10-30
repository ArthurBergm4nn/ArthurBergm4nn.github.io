# Guia Prático: Como Publicar no GitHub Pages (PASSO_A_PASSO_GITHUB.md)

Este guia didático foi preparado para o **Arthur Bergmann de Oliveira** publicar o seu site de portfólio no **GitHub Pages** de forma 100% gratuita.

---

## 📌 Passo 1: Criar uma Conta no GitHub
1. Acesse [github.com](https://github.com) e crie uma conta gratuita (caso ainda não possua).
2. Confirme o seu e-mail.

---

## 📌 Passo 2: Criar um Novo Repositório
1. No canto superior direito do GitHub, clique no ícone **`+`** e selecione **"New repository"** (Novo repositório).
2. Preencha os campos:
   - **Repository name:** Você pode escolher:
     - `portfolio` (seu site ficará: `https://seu-usuario.github.io/portfolio/`), OU
     - `seu-usuario.github.io` (substitua `seu-usuario` pelo seu nome de usuário no GitHub; seu site ficará direto na raiz: `https://seu-usuario.github.io/`).
   - **Visibility:** Deixe marcado como **Public** (Público).
   - Não marque a opção de adicionar README (o repositório deve ser criado em branco).
3. Clique no botão verde **"Create repository"**.

---

## 📌 Passo 3: Enviar os Arquivos do Projeto

### Opção A (Mais fácil - Direto pelo Navegador):
1. Na tela do repositório recém-criado, procure pelo link que diz: **"uploading an existing file"** (carregar um arquivo existente).
2. Abra a pasta do seu projeto no Windows (`C:\Users\silbe\.gemini\antigravity\scratch\portfolio-administracao`).
3. Arraste todos os arquivos e pastas para dentro da página do GitHub:
   - Arquivo `index.html`
   - Pasta `assets/` (com `css`, `docs`, `images` e `js`)
   - Arquivos `SPEC.md`, `AGENTS.md`, `ToDo.md` (opcionais, mas bons para documentação)
4. No campo inferior *"Commit changes"*, digite: `Primeira versão do portfólio`.
5. Clique no botão verde **"Commit changes"**.

### Opção B (Via Terminal Git):
Se você tiver o Git instalado no Windows:
```bash
cd C:\Users\silbe\.gemini\antigravity\scratch\portfolio-administracao
git init
git add .
git commit -m "Publicação inicial do portfólio"
git branch -M main
git remote add origin https://github.com/SEU-USUARIO/NOME-DO-REPOSITORIO.git
git push -u origin main
```

---

## 📌 Passo 4: Ativar o GitHub Pages
1. Na página do seu repositório no GitHub, clique na aba **"Settings"** (Configurações) no menu superior.
2. Na barra lateral esquerda, clique em **"Pages"** (na seção *Code and automation*).
3. Na seção **"Build and deployment"**:
   - **Source:** Selecione `Deploy from a branch`.
   - **Branch:** Escolha `main` (ou `master`) e mantenha a pasta como `/(root)`.
   - Clique em **Save** (Salvar).

---

## 🚀 Passo 5: Acessar o Seu Site no Ar!
- O GitHub levará cerca de **1 a 3 minutos** para processar.
- Atualize a página de configurações (*Settings > Pages*). No topo aparecerá uma caixa verde com a mensagem:
  > **"Your site is live at https://seu-usuario.github.io/..."**
- Clique no link gerado e o seu portfólio estará online para qualquer pessoa ou recrutador no mundo ver!
