# SW Lab 4 — GitHub Actions

Робочий репозиторій для лабораторної роботи №4 з дисципліни «Технології створення програмних продуктів».

Цей репозиторій призначений для запуску GitHub Actions. Підсумкові файли та результати потрібно додати до навчального репозиторію у гілку `Lab-4`.

## Сценарії перевірки

- **Print Software Versions** — два jobs: версії Node.js/npm та MongoDB.
- **Data Schema Code Convention** — перевірка `DataSchema.json` або `DataSchemaModified.json` через JSONLint.
- **Program Code Convention** — перевірка `ProgramCode.js` або `ProgramCodeModified.js` через Biome.

Відкрийте **Actions** → оберіть workflow → **Run workflow** → `variant: original` або `variant: modified` → **Run workflow**.

Очікувано `original` завершується успішно, `modified` — з помилками форматування/синтаксису.

**Примітка:** приклад технологій Node.js/MongoDB та продукту Task Manager потребує звірки з UML-діаграмою лабораторної №2; він не був підтверджений вихідними матеріалами.
