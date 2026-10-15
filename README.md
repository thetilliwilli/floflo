# floflo

GitHub Pages для редактора DAG Flow: https://thetilliwilli.github.io/floflo/

Исходники живут в приватном репозитории `thetilliwilli/dagflow`. Workflow
`.github/workflows/pages.yml` берёт ветку `master`, собирает редактор с
`--base=/floflo/` и публикует на Pages. Запуск вручную:

```
gh workflow run pages.yml -R thetilliwilli/floflo
```
