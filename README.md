# Encantto Studio

Site da **Encantto Studio** — gráfica criativa e papelaria personalizada (São Gonçalo do Amarante - CE).
*Sua ideia, nossa criação!*

Página única (HTML, CSS e JavaScript puros, sem dependências), pensada para celular.

## O que faz
- Catálogo por categorias com preços iniciais
- Orçamento com preço estimado
- Carrinho (salvo no navegador)
- Finalização pelo WhatsApp (mensagem do pedido pronta)
- Avaliações enviadas pelo WhatsApp

## Como publicar no GitHub Pages
1. Envie estes arquivos para a raiz do repositório.
2. No GitHub: **Settings → Pages → Build and deployment**.
3. Em *Source*, escolha **Deploy from a branch**, branch `main`, pasta `/ (root)`, e salve.
4. Em alguns minutos o site abre em `https://SEU-USUARIO.github.io/NOME-DO-REPOSITORIO/`.

## Como editar
- Preços e produtos: no `index.html`, procure a lista `P=[` dentro do `<script>`.
- Número do WhatsApp: procure `var WA=`.

## Limitações
Pedidos ficam só no navegador do cliente (não há banco de dados nem painel administrativo nesta versão).
