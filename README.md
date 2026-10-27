# webcoop.cat

Landing page de [webcoop.cat](https://webcoop.cat): HTML estàtic, sense build.

- `public/` és la web tal com es publica (`index.html`, `img/`, `favicon.ico`).
- Per veure-la en local, obre `public/index.html` al navegador.

## Desplegament

Cada push a `main` publica `public/` amb GitHub Actions
(`.github/workflows/deploy.yml`). Si el missatge del commit conté
`[skip deploy]`, no es desplega. També es pot llançar a mà des de la pestanya
Actions (*Run workflow*).
