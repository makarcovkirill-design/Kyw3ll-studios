# Kyw3ll Studio V8

## Запуск на iPhone через GitHub Pages

1. Создай/открой GitHub-репозиторий.
2. Загрузи **все 3 файла**: `index.html`, `manifest.json`, `sw.js`.
3. GitHub → Settings → Pages → Deploy from branch → `main` → `/ (root)` → Save.
4. Открой выданный адрес `https://...github.io/.../` в Safari.
5. Нажми «＋ Импорт» → «📂 Выбрать аудиофайл».
6. После выбора нажми «Добавить на BEAT».
7. Для микрофона обязательно используй HTTPS-адрес GitHub Pages.
8. В Safari можно нажать «Поделиться» → «На экран Домой».

V8 специально использует настоящий HTML `<input type=file>` + `<label>`, а не программный `.click()`.
