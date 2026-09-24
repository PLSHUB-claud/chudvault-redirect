# chudvault-redirect

Projeto de redirecionamento no Cloudflare Pages.

## Como funciona

O arquivo `_redirects` redireciona todo o tráfego para `https://nazistas.online`.

O `index.html` serve como fallback caso o redirect não funcione.

## Deploy

1. Clone este repositório
2. Vá para [Cloudflare Pages](https://dash.cloudflare.com/a84554bb8f62afb32920dfe96a991549/workers-and-pages/create/pages)
3. Conecte este repositório do GitHub
4. Framework preset: None
5. Build command: (deixe vazio)
6. Build output directory: `/` (raiz)
7. Deploy

Você receberá um domínio no formato `chudvault-redirect.pages.dev` que pode ser compartilhado.
