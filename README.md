# Зорянський академічний ліцей — сайт (Material Design)

Статичний сайт у темному Material Design 3. Готовий до GitHub Pages.

## Розгортання
1. Завантажте вміст цієї папки в репозиторій (гілка `main`).
2. Settings → Pages → Source: **GitHub Actions**. Workflow опублікує сайт автоматично.
   Або: Source → Deploy from a branch → main / (root) — файл `.nojekyll` уже доданий.

## Структура
```
index.html / stem.html / filolog.html / statut.html
style.css            Material Design 3 (dark) токени та компоненти
assets/app.js        мобільне меню + scroll-reveal анімації
assets/img/          зображення (профілі, лабораторія, життя ліцею)
assets/docs/         PDF статуту
```

## Зображення
- `profile-math/phil/hist.png` — підкладки профілів (line-art)
- `lab-engineering.png` — фото інженерної лабораторії
- `life-1.png`, `life-2.png` — фото «Життя ліцею»
- BioTech-лабораторія та 3-тє фото галереї — поки плейсхолдери,
  додайте `lab-biotech.png` / `life-3.png` у `assets/img/` і впишіть шлях у HTML.
