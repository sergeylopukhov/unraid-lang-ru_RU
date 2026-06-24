# Найденные ошибки перевода

| Файл | Было | Проблема | Лучше |
|---|---|---|---|
| `translations.txt` | `Download=Загрузить` | `Download` — это скачивание на устройство, а не загрузка на сервер | `Download=Скачать` |
| `translations.txt` | `Acknowledge=Признать` | В интерфейсе это подтверждение условия/предупреждения, не «признание» | `Acknowledge=Подтвердить` |
| `translations.txt` | `Blacklisted USB Flash GUID=В черном список USB Flash GUID` | Грамматическая ошибка и калька | `Blacklisted USB Flash GUID=GUID USB Flash в чёрном списке` |
| `translations.txt` | `bond down=связаться вниз` | Неверный перевод сетевого состояния | `bond down=bond-интерфейс отключён` |
| `translations.txt` | `Formatting devices=Устройства форматирования` | Переведён объект вместо процесса | `Formatting devices=Форматирование устройств` |
| `translations.txt` | `DNS issue, unable to resolve mothershipunraidnet=Проблема DNS не удается решить mothership.unraid.net` | «resolve» в DNS — «разрешить имя», не «решить» | `Проблема DNS: не удаётся разрешить mothership.unraid.net` |
| `translations.txt`, `dashboard.txt`, `helptext.txt` | `Dashboard=Панель` в свежем upstream-переводе | По требованию проекта `Dashboard` нужно передавать как «дашборд» | `Dashboard=дашборд`, в тексте — «дашборд» |
| `README.md` | `Панели инструментов`, `графический интерфейс`, `ЦС` | Неудачная терминология для Unraid UI и CA | Лучше: «дашборд», `webGUI`, `CA` / `Community Applications` |
| `Parity Check Tuning/paritychecktuning.txt` | `Parity Check Tuning=Чётность Проверка Tuning` | Машинная калька и неверный порядок слов | `Настройка проверки чётности` |
| `Parity Check Tuning/paritychecktuning.txt` | `Following drives overheated=Following диски overheated` | Английские остатки в русской строке | `Следующие диски перегрелись` |
| `Dynamix File Integrity/fileintegrity.txt` | `Day of the month=День Луны` | Неверное значение: month — месяц, не луна | `День месяца` |
| `Dynamix File Integrity/fileintegrity.txt` | `Placement of file integrity control=Расположение of файл целостность управление` | Непереведённые части и калька | `Расположение управления целостностью файлов` |
| `Open Files/openfiles.txt` | `May prevent shutdown=May prevent выключение`, `Kill=Вбить` | Непереведённая фраза и неверный термин кнопки | `Может помешать выключению`, `Завершить` |
| `main.txt` | `Parity-SyncData-Rebuild in progress=Чётность-Sync/Данные-Rebuild in ход выполнения` | Смешанный машинный перевод | `Выполняется синхронизация чётности или восстановление данных` |
| `main.txt` | `will pause the Read-Check=s` | Повреждённое значение перевода | `приостановит проверку чтения` |
| `settings.txt` | `No encrypted disks found=Нет зашифровано диски found` | Английские остатки и неверная грамматика | `Зашифрованные диски не найдены` |
| `settings.txt` | `Both Web Virt-Manager Remote Viewer=Both Web & Virt-Manager Удалённый Viewer` | Смешение языков | `Web и Virt-Manager Remote Viewer` |
| `dashboard.txt` | `No VMs running=Нет VMs выполняется` | Неверный порядок слов и смешение языков | `Нет запущенных VM` |
| `dashboard.txt` | `Percent usage of Docker folder=Percent usage of Docker folder=...` | Дублирование исходного ключа в значении | `Процент использования папки Docker` |
| `tools.txt` | Блоки `registration_8_plug`, `registration_9_plug` оставались на английском | Непереведённый help-текст регистрации | Перевести полностью, сохранив ссылки и `Replace Key` как UI label |
| `Cleanup Appdata/cleanupappdata.txt` | Длинное примечание про ранее установленные Docker containers оставалось на английском | Непереведённый текст предупреждения | Перевести полностью, сохранив смысл про abandoned appdata folders |
