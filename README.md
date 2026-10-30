# easy-ai-plugins

Учебный проект — исходный код к видео на YouTube:

[![Видео здесь](https://img.youtube.com/vi/JFI9LhZRS1Y/0.jpg)](https://youtu.be/JFI9LhZRS1Y)

Маркетплейс плагинов для Claude Code и Codex. Пока включает один плагин — `frontend-review` (ревью React/TypeScript компонентов на корректность, доступность, SSR-безопасность и security-проблемы).

## Установка

### Claude Code

Показано в видео через штатную команду `/plugin`

или

с помощью CLI:
```
/plugin marketplace add easy-linux/easy-ai-plugins
/plugin install frontend-review@easy-ai-plugins
```

### Codex

Внутри Codex CLI:

```
/plugin marketplace add easy-linux/easy-ai-plugins
/plugin install frontend-review@easy-ai-plugins
/reload-plugins
```
