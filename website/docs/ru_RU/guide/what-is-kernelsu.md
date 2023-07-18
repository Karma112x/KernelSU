# Что такое KernelSU? {#introduction}

KernelSU - это root-решение для устройств Android GKI, работающее в режиме ядра и предоставляющее root-права пользовательским приложениям непосредственно в пространстве ядра.

## Особенности {#features}

Основной особенностью KernelSU является то, что он **основан на ядре**. KernelSU работает в режиме ядра, поэтому он может предоставить интерфейс ядра, которого раньше не было. Например, мы можем добавить аппаратную точку останова любому процессу в режиме ядра; мы можем получить доступ к физической памяти любого процесса без чьего-либо ведома; мы можем перехватить любой syscall в пространстве ядра; и т.д.

Кроме того, KernelSU предоставляет систему модулей через overlayfs, что позволяет загружать в систему пользовательские плагины. Также предусмотрен механизм модификации файлов в разделе `/system`.

## Как использовать {#how-to-use}

Пожалуйста, обратитесь к: [Установка](installation)

## Как собрать {#how-to-build}

[Как собрать](how-to-build)

## Обсуждение {#discussion}

- Telegram: [@KernelSU](https://t.me/KernelSU)