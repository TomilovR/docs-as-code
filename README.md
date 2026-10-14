# Docs as Code

Практическая работа по настройке среды Docs as Code и документированию ИИ-проекта.

Автор: Роман Томилов

## Что внутри

- Документация на [MkDocs](https://www.mkdocs.org/) с темой [Material](https://squidfunk.github.io/mkdocs-material/), исходники в папке `docs/`.
- Проект, который документируется: чат-бот, подбирающий примеры реплик с помощью реранкера (см. `docs/project/overview.md`).
- Скриншоты результата в папке `screenshots/`.

## Запуск

```bash
python -m venv .venv
.venv/Scripts/activate        # Linux и macOS: source .venv/bin/activate
pip install -r requirements.txt
mkdocs serve
```

После запуска сайт доступен по адресу, который напечатает `mkdocs serve` (по умолчанию http://127.0.0.1:8000).
