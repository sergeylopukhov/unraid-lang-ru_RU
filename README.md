# lang-ru_RU

### ПРОЧИТАЙТЕ ЭТО, ЕСЛИ ХОТИТЕ СДЕЛАТЬ СВОЙ ПЕРЕВОД НА ДРУГОЙ ЯЗЫК

В этом хранилище содержится шестнадцать основных текстовых файлов, каждый с собственным разделом переводов:

- translations.txt -- это общие переводы, которые загружаются каждый раз
- helptext.txt -- это все разделы справочного текста, которые загружаются каждый раз
- dashboard.txt -- это переводы для раздела Панели инструментов
- main.txt -- это переводы основного раздела
- shares.txt -- это переводы раздела shares
- users.txt -- это переводы для раздела пользователей
- settings.txt -- это переводы раздела настроек
- plugins.txt -- это переводы раздела плагинов
- docker.txt -- это переводы раздела docker
- vms.txt -- это переводы раздела vms
- tools.txt -- это переводы раздела инструментов
- javascript.txt -- это переводы для сценариев javascript
- scripts.txt -- это переводы для локальных скриптов
- apps.txt -- это переводы для раздела CA (в папке Community Apps)
- ca_settings -- это переводы настроек ЦС (в папке Community Apps)
- javascript.ca.txt -- это переводы для CA javascript (в папке Community Apps)
Все имена файлов пишутся в нижнем регистре и должны быть включены в репозиторий, чтобы переводы были полными.

Удаление определенного файла означает, что переводы для этого раздела не будут доступны, а графический интерфейс будет отображать текст на оригинальном английском языке.

### ПЕРЕВОДЫ

Каждый текстовый файл содержит обычные текстовые строки, хранящиеся в формате UTF-8 с окончаниями строк Linux. Используйте текстовый редактор, который поддерживает формат UTF-8 и linux, например notepad++

Содержимое каждого текстового файла разделено на две части

### ЧАСТЬ 1

Это однострочные записи в формате:

`оригинал английского текста=переведенный иностранный текст`

Измените текст после знака равенства (=) и оставьте оригинальный английский текст слева. Удаление строки или пробел перевода после знака равенства приводит к тому, что графический интерфейс отображает эту строку с оригинальным английским текстом.

Переведенный текст может содержать специальные символы», такие как косые черты, круглые скобки или скобки, которые не входят в основной текст, но которые используются для отображения текста соответственно. напр.

`Параметры см. Help=Options (см. справку)`

Символы \* и \*\* используются для отображения текста курсивом и жирным шрифтом соответственно. напр.

`Массив должен быть остановлен для изменения=массив должен быть **остановлен** для изменения`

Рекомендуется делать переводы на раздел, то есть по одному файлу за раз, и проверять правильность переводов в графическом интерфейсе. прежде чем перейти к следующему разделу.

Помните о длине переводов и старайтесь сделать их такой же длиной, как и оригинальный текст, и избегайте проблем с пространством в графическом интерфейсе.

### PART 2

Это многострочные записи, используемые для одновременного перевода нескольких строк. Многострочный перевод имеет уникальный открывающий и закрывающий тег:

**:unique_tag_name_plug:** - уникальный начальный тег, который используется для любого многострочного текстового раздела

**:end**    - закрывающий тег

Не удаляйте и не изменяйте эти теги, а переводите только текст между начальным и закрывающим тегами!

### ФАЙЛ HELP

Весь текст справки GUI хранится в одном файле *helptext.txt*.

Этот файл имеет несколько разделов справочного текста. Каждый раздел заключен уникальным открывающим тегом и соответствующим закрывающим тегом.

**:unique_tag_name_help:** - уникальный начальный тег, используемый для текстового раздела справки

**:end**    - соответствующий закрывающий тег

Не удаляйте и не изменяйте эти теги, а переводите только текст между начальным и закрывающим тегами!

Имейте в виду, что используется синтаксис стиля Markdown, его нужно сохранить.

### ЛОКАЛЬНОЕ ТЕСТИРОВАНИЕ

Когда переводы завершены, и вы хотите локально проверить (промежуточные) результаты, текстовые файлы нужно заархивировать в один ZIP-файл. Дайте файлу ZIP название вашего языка, напр. French.zip.

В графическом интерфейсе перейдите к: Инструменты -> Языки (перейдите к просмотру разработчика)

- По умолчанию устанавливается только английский язык (встроенный)
- Выберите файл ZIP, который вы создали ранее, как исходный файл
- Если название языка распознается, оно будет выбрано автоматически, в противном случае выберите название языка из раскрывающегося меню для установки.
- Нажмите «Загрузить», чтобы добавить ваши переводы графического интерфейса под названием выбранного языка

NOTE: Если ваш язык недоступен в раскрывающемся меню, отправьте запрос на форум [Unraid forum](https://forums.unraid.net/forum/75-multi-language-section/)

Теперь ваш язык доступен для локального тестирования!

В графическом интерфейсе перейдите к: Настройки -> Настройки дисплея -> Язык

- Выберите желаемый язык из раскрывающегося меню. Обратите внимание, что здесь отображаются только доступные языковые варианты.
