# Colibri Qt — сборки для Windows

Здесь только готовые сборки. Исходный код — в приватном репозитории `colibri-qt`.

## Скачать

**Последняя сборка:** https://github.com/sj0404-collab/colibri-qt-downloads/releases/latest

1. Откройте ссылку выше, скачайте `ColibriQt-windows-onedir-<версия>.zip`.
2. Распакуйте в любую папку (например `C:\ColibriQt`).
3. Запустите `ColibriQt\ColibriQt.exe`.

## Что внутри

- локальный чат на GGUF-моделях: llama.cpp, mmap-стриминг весов, экономия RAM;
- встроенный API-сервер для opencode: `http://127.0.0.1:8099/v1`;
- агент opencode **в главном окне и в том же чате** — кнопка «Агент opencode» или `Ctrl+Shift+G`.

Для агента нужны Node.js и opencode: `npm install -g opencode-ai`.

## Сборки

| Версия | Что важно |
|---|---|
| `v-b703be0` | сторож зависаний («⏳ молчит N с»), папка проекта в запросе, ответ из сессии |
| `v-e5bceca` | агент opencode в главном окне и в том же чате |
