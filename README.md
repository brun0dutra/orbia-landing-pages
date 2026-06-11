# Landing pages da Orbia

Este repositório contém landing pages estáticas da Orbia, prontas para publicação pelo GitHub Pages sem depender do backend da VPS.

## Estrutura

- `index.html`: landing page genérica/principal.
- `lancherias/index.html`: landing page para lancherias.
- `revendas/index.html`: landing page para revendas.
- `consultorios/index.html`: landing page para consultórios.
- `assets/landing.css`: CSS compartilhado.
- `.nojekyll`: garante que o GitHub Pages publique os arquivos exatamente como estão.

## Navegação

A página principal tem botões no topo para as landing pages específicas:

- `revendas/`
- `lancherias/`
- `consultorios/`

Todos os caminhos internos usam links relativos, então funcionam tanto em domínio próprio quanto em URLs de projeto do GitHub Pages, por exemplo:

```text
https://usuario.github.io/orbia-landing-pages/
```

## Como publicar no GitHub Pages

1. Crie um repositório, por exemplo `orbia-landing-pages`.
2. Envie todo o conteúdo desta pasta para a raiz do repositório.
3. No GitHub, acesse `Settings > Pages`.
4. Em `Build and deployment`, selecione `Deploy from a branch`.
5. Escolha a branch `main` e a pasta `/root`.
6. Salve e aguarde o GitHub Pages gerar a URL.

## Botões de conversão

Os CTAs agora apontam para seções internas (`#comecar`) para não quebrar em GitHub Pages. Quando você tiver uma URL pública do painel/app, substitua esses links pelo endereço final, por exemplo:

```html
<a href="https://app.seudominio.com/ui">Quero organizar meu WhatsApp</a>
```
