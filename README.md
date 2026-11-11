# Rotas de Clientes

App web para celular: tabelas tipo Excel (Cliente, Local, Endereço, CEP) com atalho para Google Maps e Apple Maps.

## Estrutura

```
rotas-clientes/
├── index.html              # app inteiro (HTML + CSS + JS)
├── manifest.webmanifest    # permite instalar na tela inicial
├── README.md
└── assets/
    └── icons/              # icon.svg (original) e PNGs 180, 192, 512, 1024
```

## Publicar no GitHub Pages

1. Envie **o conteúdo desta pasta** (com `index.html` na raiz do repositório).
2. Settings > Pages > Deploy from a branch > `main` / `(root)`.
3. Acesse `https://SEU-USUARIO.github.io/NOME-DO-REPO/`.

## Para crescer depois

Quando o `index.html` ficar grande, separe em `css/style.css` e `js/app.js` e adicione outras pastas dentro de `assets/`.
