# Русский перевод Unraid — языковой пакет ru_RU

[![Unraid](https://img.shields.io/badge/Unraid-7.3-orange)](https://unraid.net/)
[![Language](https://img.shields.io/badge/lang-ru__RU-blue)](limetech/lang-ru_RU.xml)
[![Status](https://img.shields.io/badge/status-updated-brightgreen)](#статус-перевода)

Русский языковой пакет для **Unraid OS 7.3.x**: webGUI, системные разделы и популярные плагины.

Перевод синхронизирован с английскими шаблонами Unraid OS 7.3. В интерфейсе используется привычная русская терминология: `Dashboard` переведён как **«дашборд»**.

## Статус перевода

- Основа: официальный английский репозиторий [`unraid/lang-en_US`](https://github.com/unraid/lang-en_US).
- Актуальность: Unraid OS **7.3.x**.
- Все ключи и help-блоки соответствуют английскому шаблону.
- Незаполненных переводов нет.

## Установка

Установите пакет по ссылке XML. После перезагрузки сервера выбранный язык сохранится.

1. Откройте webGUI своего сервера Unraid.
2. Перейдите в **Tools → Language**.
3. В поле **Enter URL of language pack XML file** вставьте ссылку:

   ```text
   https://raw.githubusercontent.com/sergeylopukhov/unraid-lang-ru_RU/main/limetech/lang-ru_RU.xml
   ```

4. Нажмите **Install**.
5. После установки нажмите **Done**.
6. Перейдите в **Settings → Display Settings**.
7. В поле **Language** выберите **Россия (Russian)**.
8. Нажмите **Apply**.

## Кому подойдёт

- Тем, кому нужен русский интерфейс Unraid OS 7.3.x.
- Пользователям Community Applications, Unassigned Devices и плагинов Dynamix.
- Тем, кто устанавливает языковой пакет `ru_RU` по XML-ссылке.

## Скриншоты установки

### 1. Откройте Tools → Language

<img width="1217" alt="Tools → Language" src="https://user-images.githubusercontent.com/65507155/177131662-f0004fea-cdf2-4f37-a5f1-6fbf8aab93a1.png">

### 2. Вставьте URL языкового пакета

<img width="1048" alt="Install language pack" src="https://user-images.githubusercontent.com/65507155/177130210-7a2e10a7-e93e-402b-a67f-59ab537e7f59ab.png">

### 3. Завершите установку

<img width="973" alt="Done" src="https://user-images.githubusercontent.com/65507155/177130540-c9c878d5-c85a-4118-b999-b8b6cd2a2432.png">

### 4. Откройте Display Settings

<img width="1784" alt="Settings → Display Settings" src="https://user-images.githubusercontent.com/65507155/177131039-133ae810-f2d3-4b76-ad20-a9705863dbdb.png">

### 5. Выберите русский язык

<img width="1062" alt="Language: Russian" src="https://user-images.githubusercontent.com/65507155/177131379-e52ebb82-7a45-446b-99bf-bd78a1aaa7cc.png">

### 6. Примените настройки

<img width="970" alt="Apply display settings" src="https://user-images.githubusercontent.com/65507155/177133996-21a80dc9-2e2a-4357-a4c4-534de55ae0c8.png">

## Пример интерфейса

<img width="1748" alt="Русский интерфейс Unraid" src="https://user-images.githubusercontent.com/65507155/177136454-233037eb-63fc-4fdb-a970-270bc2bac868.png">

## Что переведено

Перевод покрывает основные разделы Unraid:

- `translations.txt` — общие строки интерфейса;
- `helptext.txt` — справка и подсказки;
- `dashboard.txt` — дашборд;
- `main.txt`, `shares.txt`, `users.txt`, `settings.txt`, `plugins.txt`;
- `docker.txt`, `vms.txt`, `tools.txt`;
- `javascript.txt`, `scripts.txt`;
- `Community Apps` и поддерживаемые плагины.

В пакет также входят `Cleanup Appdata`, `Gui Search`, `Unassigned Devices Preclear`, `Dynamix File Integrity`, `Dynamix S3 Sleep`, `Dynamix System Stats`, `Dynamix System Temp` и другие актуальные файлы.

## Для переводчиков

Формат однострочных переводов:

```text
English source text=Русский перевод
```

Левую часть до `=` менять нельзя. Перевод находится справа.

Многострочные блоки выглядят так:

```text
:unique_tag_name_help:
Текст перевода.
:end
```

Теги `:unique_tag_name_help:` и `:end` удалять или переименовывать нельзя. Внутри help-блоков нужно сохранять Markdown, HTML-ссылки и служебные переменные.

## Локальная проверка

Для временной проверки соберите ZIP-архив языкового пакета и загрузите его через **Tools → Language** в режиме разработчика.

При локальной установке из ZIP язык может сброситься после перезагрузки. Для постоянной установки используйте XML-ссылку из раздела «Установка».

## Терминология

- `Dashboard` — **дашборд**.
- `webGUI` не переводится.
- `Community Applications` можно сокращать до `CA`.
- `Flash` в контексте загрузочного устройства — `USB Flash` или `Flash-накопитель`.
- Названия кнопок и пунктов меню иногда оставлены на английском, если это точные UI-labels Unraid.

## Обратная связь

Если нашли неточность, создайте issue или pull request. Укажите файл, строку, английский оригинал и предлагаемый перевод.
