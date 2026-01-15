# Правила, команди та навички для Agentic IDE

Презентація створена за допомогою [Slidev](https://sli.dev/)

## Локальний запуск

```bash
cd slidev
npm install
npm run dev
```

## Експорт до PDF

```bash
cd slidev
npm run export -- --format pdf
```

## Деплой на GitHub Pages

Презентація автоматично деплоїться на GitHub Pages при push в `main`/`master` через GitHub Actions.

**Налаштування:**
1. Перейдіть в **Settings** → **Pages**
2. У **Source** виберіть **GitHub Actions**
3. Після першого деплою слайди будуть доступні за URL: `https://<username>.github.io/<repository-name>/`

Детальніше: `.cursor/skills/deploy-github-pages.mdc`
