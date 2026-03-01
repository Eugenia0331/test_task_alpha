# test_task_alpha

# Установка
npm init -y
npm install -D @playwright/test
npx playwright install

# Запуск теста
npx playwright test

# Ожидаемый результат
Тест успешно выполняется в:

Chromium

Firefox

И проходит проверку заголовка страницы:
✓  [Chromium] › title.spec.js
✓  [Firefox] › title.spec.js
