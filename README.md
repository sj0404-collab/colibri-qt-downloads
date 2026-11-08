# Colibri Qt — сборки для Windows

Здесь лежат только готовые сборки. Исходный код — в приватном репозитории `colibri-qt`.

## Как скачать

1. Откройте [Releases](../../releases).
2. Скачайте `ColibriQt-windows-onedir-<версия>.zip`.
3. Распакуйте в любую папку (например `C:\ColibriQt`) и запустите `ColibriQt\ColibriQt.exe`.

## Что внутри

- локальный чат на GGUF-моделях (llama.cpp, mmap-стриминг весов, экономия RAM);
- встроенный API-сервер для opencode: `http://127.0.0.1:8099/v1`;
- агент opencode **в главном окне и в том же чате** (кнопка «Агент opencode» / `Ctrl+Shift+G`).

Для агента нужен Node.js и opencode: `npm install -g opencode-ai`.
