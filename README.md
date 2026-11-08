# Site Karyvon

Site estático (HTML, CSS e JavaScript puros). Não precisa de build.

## Estrutura

```
index.html        página principal
earth/            texturas da Terra (imagens NASA, domínio público)
brand/k.png       logo usada na bola de neve
brand/favicon.png ícone da aba
```

## Testar no computador

Abra a pasta no VS Code e use a extensão Live Server, ou rode:

```
npx serve .
```

Abrir o `index.html` com dois cliques não carrega as texturas da Terra (o navegador bloqueia por segurança). Use um servidor local.

## Publicar

1. **GitHub:** crie um repositório, envie esta pasta (`git init`, `git add .`, `git commit -m "Site Karyvon"`, `git push`).
2. **Hostinger:** em hPanel → Sites → Gerenciador de arquivos, envie o conteúdo desta pasta para `public_html`. Ou use hPanel → Avançado → Git para puxar direto do repositório.

## Antes de publicar

- Troque o e-mail provisório `contato@karyvon.com.br` no `index.html`.
- O formulário de contato ainda não envia mensagens. Ele precisa ser ligado a um serviço (por exemplo, um script PHP na Hostinger ou Formspree).
