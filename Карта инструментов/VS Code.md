---
tags:
  - инструмент
  - окружение
сайт: https://code.visualstudio.com
документация: https://code.visualstudio.com/docs
связи:
  - "[[pico-sdk]]"
  - "[[CMake]]"
  - "[[GCC (Arm GNU Toolchain)]]"
---

>[!note] Описание
>**Visual Studio Code** (VS Code) — свободный редактор кода компании Microsoft с системой расширений: компилятор и отладчик в него не входят, поддержка языков, систем сборки и отладчиков подключается отдельными модулями. Не путать с Visual Studio — отдельным продуктом Microsoft.
^def

## Роль в курсе

Рабочая среда на хосте: редактирование кода, сборка и загрузка прошивки.

## Установка

Подойдёт любая версия. Проверка — `code --version`.

### Все три ОС

Скачайте дистрибутив для своей системы с https://code.visualstudio.com/download и установите обычным для системы способом.

>[!warning] Команда `code` должна работать в терминале
>В Windows и Linux установщик добавляет её сам. В macOS команду нужно включить вручную: откройте VS Code, нажмите `Cmd+Shift+P` и выполните **Shell Command: Install 'code' command in PATH**.

## Ссылки

- Расширение Raspberry Pi Pico: https://marketplace.visualstudio.com/items?itemName=raspberry-pi.raspberry-pi-pico
