# Hepta · site

Landing page da Hepta (social media para pequenos negócios, Zona Leste de SP).
Site estático: HTML + CSS, sem build.

```
index.html          página
assets/styles.css   estilos (cores do sistema Hepta em :root)
assets/favicon.svg  ícone (heptágono)
```

## Rodar localmente

```
python3 -m http.server 8000
```
e abra http://localhost:8000

## Publicar

Qualquer hospedagem estática serve (GitHub Pages, Netlify, Vercel, Cloudflare Pages):
- **GitHub Pages:** Settings › Pages › Deploy from a branch › `main` / `(root)`.
- **Netlify / Vercel:** importe o repositório; não há comando de build, a pasta de publicação é a raiz.

## Editar

- **WhatsApp:** número e mensagens no `<script>` ao fim do `index.html` (`NUMERO`, `PADRAO`).
  Os botões de plano mandam uma mensagem citando o plano.
- **Preços e planos:** seção `#planos` do `index.html`.
- **Cores:** variáveis em `:root` no `assets/styles.css`.
