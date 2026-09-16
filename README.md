# Site pessoal — Pedro Leite

Site estático simples (HTML + CSS puro, sem frameworks), pronto para hospedar
gratuitamente no GitHub Pages.

## Arquivos

- `index.html` — a página inteira (estrutura e estilo)
- `assets/photo.png` — sua foto
- `assets/cv.pdf` — seu currículo (link "CV" na barra lateral)

## Como publicar no GitHub Pages (gratuito)

1. **Crie um repositório novo** em https://github.com/new
   - Se quiser que o site fique em `https://pedroleitebl.github.io` (sem
     subpasta), o nome do repositório precisa ser exatamente
     `pedroleitebl.github.io`.
   - Se preferir um endereço tipo `https://pedroleitebl.github.io/site`,
     pode usar qualquer nome (ex: `site`, `homepage`) — só muda a URL final.
   - Deixe o repositório **público**.

2. **Suba estes 3 arquivos/pastas** para o repositório, mantendo a mesma
   estrutura (o `index.html` na raiz, e a pasta `assets/` junto dele).
   Pode arrastar e soltar na interface do GitHub ("Add file" → "Upload
   files") ou usar `git`:
   ```bash
   git init
   git add .
   git commit -m "primeiro site"
   git branch -M main
   git remote add origin https://github.com/pedroleitebl/pedroleitebl.github.io.git
   git push -u origin main
   ```

3. **Ative o GitHub Pages:**
   - No repositório, vá em **Settings → Pages**.
   - Em "Build and deployment", selecione **Deploy from a branch**.
   - Escolha a branch `main` e a pasta `/ (root)`.
   - Salve.

4. Em 1–2 minutos o site estará no ar no endereço mostrado nessa mesma tela
   (algo como `https://pedroleitebl.github.io`).

## Editar depois

Todo o conteúdo (texto, links, seções) está direto no `index.html` — é só
abrir o arquivo em qualquer editor de texto e alterar. Não precisa saber
programação para mudar textos e links; só tome cuidado para não apagar as
tags (as partes entre `< >`).

## Nota

O site foi escrito em inglês, seguindo o padrão comum em páginas pessoais
acadêmicas de economia (como a referência que você indicou) e o idioma do
seu CV. Se preferir em português, é só pedir que eu gero a versão traduzida.
