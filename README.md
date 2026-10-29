# SSH Button Next

**SSH-команды на Android — одним нажатием.**

SSH Button Next — бесплатное приложение для быстрого запуска заранее настроенных команд на собственных серверах и устройствах через SSH.

### Возможности

- Кнопки SSH-команд, группировка, отдельная перестановка кнопок и групп, включая «Кнопки без группы»; перетаскивание серверов. Свёрнутые группы раскрываются при удержании перетаскиваемой кнопки над заголовком около 0,6 секунды; заголовок остаётся видимым с мягкой подсветкой. Перенос через заголовок меняет группу кнопки и сохраняет фактическое место вставки. Свёрнутые промежуточные группы не мешают переносить кнопку дальше; при автоматическом раскрытии место вставки появляется сразу.
- Подключение по паролю или приватному SSH-ключу.
- Подтверждение запуска, тайм-ауты, прерывание выполнения и просмотр результата команды.
- История выполнений по календарным датам: сохраняются последние 30 разных дат с записями; удаление отдельных записей и суток свайпом с подтверждением, без сохранения SSH-вывода и секретов.
- Проверка подключения и авторизации SSH-сервера без выполнения команды, с понятной диагностикой и раскрываемыми техническими подробностями.
- Виджет для быстрого запуска с рабочего стола.
- Светлая и тёмная темы, английский и русский интерфейсы.
- Скачивание обновлений из GitHub Releases с возможностью отмены. Кнопка «Добавить» перемещается горизонтально удержанием; окно обновления сохраняет размер. Автопрокрутка при перетаскивании замедлена на 40%, а анимации групп стали плавнее. При удержании «+» появляется синее свечение; удержание команд, серверов и групп сопровождается мягким виброоткликом. Меню ⋮ не меняет пункты во время закрытия.
- Локальное защищённое хранение настроек, экспорт без секретов и полная зашифрованная резервная копия с отдельным паролем. Выбор группы, сервера и значка подтверждается сохранением.

### Скачать и установить

Подписанные установочные файлы Android доступны в разделе **[Releases](https://github.com/lKlElNlGl/ssh-button-next-releases/releases)**. Актуальная версия — **[v0.2.16](https://github.com/lKlElNlGl/ssh-button-next-releases/releases/tag/v0.2.16)**.

1. Выберите последний релиз и скачайте файл `*-signed.apk`.
2. Установите APK на телефон. При необходимости разрешите установку из выбранного источника в настройках Android.
3. Добавьте свой SSH-сервер, создайте кнопку и укажите команду.

**Требуется Android 8.0 или новее и доступ к вашему SSH-серверу.** Приложение не предоставляет сервер и не является полноценным интерактивным терминалом.

---

## English

**SSH commands on Android — one tap away.**

SSH Button Next is a free Android app for running predefined SSH commands on your own servers and devices.

### Features

- Custom SSH command buttons, draggable groups (including Ungrouped), and draggable server cards. Collapsed groups expand after hovering a dragged command over the header for about 0.6 seconds, with the header visible and softly highlighted. Crossing a header now moves a command to the adjacent group and saves the visible position. Collapsed intermediate groups do not block dragging to a later group, and auto-expansion immediately reveals the insertion slot.
- Password or private-key authentication.
- Run confirmations, timeouts, command interruption and command output.
- Calendar-day execution history retaining the last 30 recorded dates, with confirmed swipe-to-delete for entries or entire days; no SSH output or credentials.
- Test SSH connectivity and authentication without executing commands, with understandable error diagnostics and expandable technical details.
- Home-screen widget for quick access.
- Light and dark themes with English and Russian interfaces.
- In-app GitHub release updates with cancellable downloads. The Add button can be moved horizontally; the update dialog stays the same size. Drag auto-scrolling is 40% slower, and group animations are smoother. Long-pressing Add shows a blue glow; long-press actions provide gentle haptic feedback. The overflow menu keeps its entries during closing.
- Encrypted local settings, secrets-free configuration export, and full password-encrypted backup. Server, group and icon choices are confirmed with Save.

### Download and install

Signed Android packages are available under **[Releases](https://github.com/lKlElNlGl/ssh-button-next-releases/releases)**. Current release: **[v0.2.16](https://github.com/lKlElNlGl/ssh-button-next-releases/releases/tag/v0.2.16)**.

1. Open the latest release and download the `*-signed.apk` file.
2. Install it on your Android device, allowing installation from that source if prompted.
3. Add your SSH server and create a command button.

**Requires Android 8.0+ and access to your own SSH server.** The app does not provide a server or a full interactive terminal.
