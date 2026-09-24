# TaskMaster

![Version](https://img.shields.io/badge/version-1.0.0-blue.svg)
![License](https://img.shields.io/badge/license-MIT-green.svg)
![Node](https://img.shields.io/badge/node-%3E%3D14.0.0-brightgreen.svg)

TaskMaster — это простое приложение для записи и отслеживания задач.
Оно помогает не забывать о важных делах: от «купить молоко» до «сдать домашку».
Программу можно запустить в терминале через команды или открыть в браузере.

## Возможности

- Добавление, редактирование и удаление задач
- Отметка задач как выполненных
- Просмотр списка всех задач
- Простые команды в терминале

## Как установить

1. Скачайте проект с GitHub:
   ```bash
   git clone https://github.com/taskmaster-team/taskmaster.git
   ```
2. Перейдите в папку проекта:
   ```bash
   cd taskmaster
   ```
3. Установите нужные библиотеки:
   ```bash
   npm install
   ```

## Как использовать

Запустите программу:

```bash
node index.js
```

Примеры команд:

```bash
node index.js add "Купить молоко"
node index.js list
node index.js done 1
```

## Лицензия

TaskMaster распространяется под лицензией **MIT**.
Подробнее см. в файле [LICENSE.md](LICENSE.md).

## Контакты

Есть вопросы или идеи? Пишите в **Issues** на GitHub:
[github.com/taskmaster-team/taskmaster/issues](https://github.com/taskmaster-team/taskmaster/issues)

Хотите помочь с кодом? Прочитайте [CONTRIBUTING.md](CONTRIBUTING.md).
