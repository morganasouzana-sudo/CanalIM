README — Canal IM (instruções rápidas)

Arquivos:
- index.html
- insights_bares_restaurantes.html
- insights_varejo_moda.html
- insights_minimercados.html
- assets/ (pasta com imagens)

Assets esperados (coloque na pasta assets/):
- hero-minimercado.webp   (opcional — imagem hero usada anteriormente)
- Você pode usar apenas um arquivo: ./assets/hero-minimercado.webp — o index.html já aponta para ele nas tiles.

Como publicar no GitHub Pages (web):
1. Vá ao repositório no GitHub.
2. Clique em Add file → Upload files e arraste a pasta /assets e os arquivos .html.
3. Commit changes.
4. Vá em Settings → Pages → Source: selecione branch `main` (ou `gh-pages`) e root `/` → Save.
5. Acesse https://<seu-usuario>.github.io/<seu-repo>/

Como publicar via Git (CLI):
1. cd path/to/CanalIM
2. git init
3. git add .
4. git commit -m "Canal IM initial"
5. git branch -M main
6. git remote add origin git@github.com:<usuario>/<repo>.git
7. git push -u origin main

Notas:
- Se imagens não carregarem, verifique nomes e maiúsculas/minúsculas (GitHub é case-sensitive).
- Para trocar imagens, altere as tags <img src="./assets/xxx.webp"> no index.html.
- Se quiser que eu gere imagens sugeridas do Unsplash com links prontos para download e nomes apropriados, diga “forneça links das 6 imagens”.
