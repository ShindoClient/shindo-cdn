# Shindo Client CDN

Landing estática convertida para **Nuxt 3** contendo apenas o aviso institucional do CDN e os ativos expostos em `public/`.

## Desenvolvimento

```bash
npm install
npm run dev
```

A página fica disponível em `http://localhost:3000`.

## Build e deploy

```bash
npm run build
npm run preview # opcional para validar o build gerado
```

O Vercel pode usar o output padrão `.output/public` gerado pelo build. Toda a árvore de arquivos servidos pela CDN (`/data`, `/assets`, `404.html`, etc.) continua dentro de `public/`, preservando os mesmos caminhos utilizados anteriormente.
