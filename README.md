# Landing pages da Orbia

Esta pasta guarda as landing pages que foram removidas do backend para não entrarem mais na imagem/container da VPS.

## Estrutura pronta para GitHub Pages

- `index.html`: landing page genérica.
- `lancherias/index.html`: landing page para lancherias.
- `revendas/index.html`: landing page para revendas.
- `consultorios/index.html`: landing page para consultórios.
- `assets/landing.css`: CSS compartilhado.

## Como publicar em um repositório separado

1. Crie um novo repositório, por exemplo `orbia-landing-pages`.
2. Copie todo o conteúdo desta pasta para a raiz do novo repositório.
3. No GitHub, acesse `Settings > Pages`.
4. Em `Build and deployment`, selecione `Deploy from a branch`.
5. Escolha a branch `main` e a pasta `/root`.
6. Salve e aguarde o GitHub Pages gerar a URL.

## Atenção aos botões do painel

Os CTAs ainda apontam para `/ui`, que funcionava quando as LPs estavam no mesmo backend.
Ao publicar fora da VPS, troque esses links pela URL pública do app, por exemplo:

```html
<a href="https://app.seudominio.com/ui">Quero organizar meu WhatsApp</a>
```
