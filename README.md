# 📁 EZ_FIX — Простой фикс ваших проблем + ЮТУБ! (НОВАЯ ВЕРСИЯ - ПОЧТИ РЕЛИЗ!)

Данная программа очень легко исправляет блокировку Discord + Youtube в России. Вы сможете легко и быстро общаться в войсе, без каких-либо проблем и танцев с бубном.

---

https://cdn.discordapp.com/attachments/1297577463894773811/1302602075594686534/hgfghdfghdfghdfh.PNG?ex=6728b637&is=672764b7&hm=06e6c14a78e34ffbc6c5818d2ee82dc67aa1a11290bda4aaadceb15089706041&

## ✨ Наши плюсы:

### ✅ Простой запуск
Вы можете просто скачать и запустить **ez_fix.exe** (Discord) — и вуаля! Discord и YOUTUBE! работает. (выберите метод запуска на сайте)

### ✅ Отсутствие вирусов
Программа проверена на вирусы, и как показывает VirusTotal, есть всего 2 детекта. И вот откуда они:
- Используется шаблон **goodbyedpi + изучено как создан zapret** — это проверенное решение для обхода блокировок, но с некоторыми изменениями:
  - Я модифицировал **dll** файлы **WinDivert**, чтобы улучшить производительность и работу с фильтрами на высоком уровне!
  - **WinDivert** работает только с сетевыми пакетами DPI и не имеет доступа к личным данным/вашему пк/чему либо ещё кроме сетевых драйверов
  - Официальный репозиторий **WinDivert** на GitHub, который использован в программе, скачан более 10.000 раз: [https://github.com/basil00/WinDivert](https://github.com/basil00/WinDivert)

### ❌ По поводу файлов windivert
- Да, в описании одного из файлов windivert указан bitcoin кошёлек создателя windivert. Это сделано для того, чтобы поддержать разработчика **WinDivert** (он добровольно размещает свой кошелёк, никнейм создателя - basil.)

### 💡 Если не удаётся удалить файлы
- Если вы не можете удалить файлы ez_fix, то причиной может быть драйвер **windivert.sys**, который работает как системный драйвер. Для его принудительного отключения откройте **cmd** ОТ ИМЕНИ АДМИНИСТРАТОРА и выполните команду:

    `sc stop windivert`

 ### ✅ Частые обновления
- Я регулярно обновляю программу, добавляя новые сайты для обхода блокировок. На данный момент доступен только Discord и YouTube, но в будущем планируется поддержка других сервисов (например, Twitter/TikTok)

 ### 📂 Содержание программы
- EZ-FIX.exe — обход блокировки Discord/Youtube в зависимости выбора на сайте.
- settings — папка со всеми исходными файлами для работы с DPI пакетами. НЕ рекомендуется трогать.
- static - папка для дизайна сайта на css. Нужна для flask (py библиотека)
- templates - папка для разверкти сайта на html. Нужна для flask (py библиотека)
## 📢 ВСЕ ВОПРОСЫ ЗАДАВАЙТЕ ЧЕРЕЗ ISSUES. Я постараюсь ответить и помочь!

