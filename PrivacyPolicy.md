# Политика конфиденциальности RannyBot'a
### Какие данные хранятся и используются ботом?
___
\> Информация про роль: отображение отдельно, название, разрешения + права, позиция в иерархии, id, участники, дата создания. Информация о вашей роли сохраняется только на время действия команд или на время включения функции "начальная роль", после выполнения команд/выключения данной функции информация удаляется из базы данных.

\> Информация про каналы и категории. Информация о всех видах каналов берется только один раз. При применении команд с выводом информации она даже не соханяется в базу данных, она просто выводится и все. Информация о списке всех каналов сохраняется на время дейставия функции "приветствие новых участников", при выключении удаляется из базы данных.

\> Информация про сервер: дата создания, уровень верификации, описание, роли, эмодзи, стикеры, уровень буста, участники, категории, все виды каналов, язык, NSFW, id, аватарка. Эти данные будут храниться на время нахождения бота на сервере, для приминения настроек. Информация будет использоваться один раз, при применении информационных команд.

\> Информация о пользователе: id, роли, дата создания аккаунта, дата захода на сервер, аватарка. Эти данные храняться в базе данных на время действия "временных" команд (/temp_role, /ban и т.п.), нужно это для корректной работы функции у бота, после истечения времени информация удаляется.

\> Информация о сообщении: id сообщения, id отправителя, содержание сообщения. Данные используются один раз, при выполнении команд/работы фильтра на сообщение (в базе данных не хранятся).

\> Использование команд: Все используемые вами команды сохраняются в логи, а конкретно сохраняются: название сервера, ник пользователя, название команды. Доступ к логам имеет ТОЛЬКО владелец бота и никто другой. ВАЖНО, сохраняется ПОЛНОЕ содержание команд с ИИ (/ask, /imagine). Нужно это для точечной блокировки пользователей, в случае нарушения правил сообщества или NSFW запросов.
___
Никакие данные не распространяются третьим лицам и используются только ботом и владельцем. Все данные о вашем сервере будут удалены с базы данных, если бот покинет ваш сервер.
