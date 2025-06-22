# Portfólio Nickolas Selhorst

Este projeto é um portfólio estático em HTML/CSS/JS.

## Como publicar no GitHub Pages

1. **Crie um repositório no GitHub** (ex: `nickoboco/portfolio`).
2. **Faça upload de todos os arquivos** do seu projeto (incluindo `home.html`, imagens, etc).
3. **Renomeie `home.html` para `index.html`** (o GitHub Pages procura por `index.html` na raiz).
4. No GitHub, vá em **Settings > Pages**.
5. Em "Source", selecione a branch (ex: `main`) e a pasta `/root` (ou `/docs` se preferir).
6. Clique em "Save". O GitHub Pages irá gerar um link do tipo:  
   `https://seu-usuario.github.io/nome-do-repositorio/`
7. Acesse o link para ver seu portfólio publicado.

**Dica:**  
Se quiser manter o arquivo original, apenas faça uma cópia de `home.html` para `index.html`:

```sh
cp home.html index.html
```

Pronto! Seu portfólio estará online via GitHub Pages.

## Passo a passo para substituir tudo no seu repositório GitHub

1. **No seu computador, entre na pasta do projeto:**
   ```sh
   cd c:/tmp/PORTIFOLIO
   ```

2. **Inicialize o repositório (se ainda não fez):**
   ```sh
   git init
   ```

3. **Adicione o repositório remoto do GitHub:**
   ```sh
   git remote add origin https://github.com/nickoboco/portifolio_projetos.git
   ```

   Se já existe um remoto chamado `origin`, use:
   ```sh
   git remote set-url origin https://github.com/nickoboco/portifolio_projetos.git
   ```

4. **Adicione todos os arquivos do seu projeto:**
   ```sh
   git add .
   ```

5. **Faça o commit das alterações:**
   ```sh
   git commit -m "Atualiza portfólio com nova versão"
   ```

6. **Envie para o GitHub, sobrescrevendo tudo:**
   ```sh
   git push -u origin main --force
   ```
   > ⚠️ O parâmetro `--force` sobrescreve o conteúdo remoto. Use apenas se tiver certeza!

7. **No GitHub, renomeie `home.html` para `index.html` se ainda não fez.**

8. **Configure o GitHub Pages conforme o README.**

Pronto! Seu portfólio estará publicado e atualizado no GitHub Pages.
