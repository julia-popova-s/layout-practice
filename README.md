# Окна Хаус. Описание проекта:

Цель проекта - реализовать вёрстку [landing page](https://julia-popova-s.github.io/layout-practice/). Технологии HTML, CSS/SCSS.

## Клонирование репозитория

1. Склонируйте репозиторий проекта на свой компьютер с помощью следующей команды:

```bash
git clone https://github.com/julia-popova-s/layout-practice.git
```

2. Перейдите в папку проекта

```bash
cd layout-practice
```

## Visual Studio Code (VSCode):

### Установите расширения Live Sass Compiler, Live Server

1. В файле настроек VSCode (File > Preferences > Settings) добавьте следующую строку:

```json
"liveSassCompile.settings.formats": [
    {
      "format": "expanded",
      "extensionName": ".css",
      "savePath": "~/../css"
    },
    {
      "format": "compressed",
      "extensionName": ".min.css",
      "savePath": "~/../css"
    }
  ],
```

2. Нажмите кнопки **Watch Sass** (компилирует CSS) и **Go Live** (запускает сервер) на строке состояния VSCode.
