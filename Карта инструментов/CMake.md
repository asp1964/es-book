---
tags:
  - инструмент
  - сборка
сайт: https://cmake.org
документация: https://cmake.org/documentation/
понятия:
  - "[[Система сборки]]"
связи:
  - "[[Make]]"
  - "[[GCC (Arm GNU Toolchain)]]"
  - "[[pico-sdk]]"
---

>[!note] Описание
>**CMake** — кроссплатформенная система сборки: по описанию проекта в файле `CMakeLists.txt` генерирует файлы для сборщика (Make, Ninja), который и вызывает компилятор и компоновщик.
^def

## Роль в курсе

Штатная система сборки pico-sdk: каждый проект курса описывается файлом `CMakeLists.txt`, сборка выполняется командами `cmake` и `make` вместо ручного вызова компилятора. Кросс-компиляция настраивается подключением файла `pico_sdk_import.cmake`, который указывает набор инструментов и путь к SDK.

## Установка

Подойдёт любая версия. Проверка — `cmake --version`.

### Windows

Скачайте установщик с https://cmake.org/download/ (файл вида `cmake-*-windows-x86_64.msi`). При установке выберите **Add CMake to the system PATH**.

### macOS

``` bash
brew install cmake
```

### Linux

``` bash
sudo apt update
sudo apt install cmake
```

## Ссылки

- Учебник: https://cmake.org/cmake/help/latest/guide/tutorial/
