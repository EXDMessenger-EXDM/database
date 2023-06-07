# database
Как работает база данных

# accounts
```
id - ID участника
username - Его ник
discriminator - Его тег (напр. DragonFire#4054)
bio - Его био (обо мне)
email - Почта участника (не показывается)
avatar - Аватарка
banner - Баннер
flags - Флаги, например всякие значки
connected_accounts - Подключенные интеграций, например YouTube, или GitHub
bot_variables - Переменные, доступные только ботам (по сути глобальный localStorage)
status - Статус:
 - 0 (В сети)
 - 1 (АФК, Не активен)
 - 2 (Не беспокоить)
 - 3 (Не в сети или Невидимка)
```

# auth_tokens
```
user_id - ID участника
auth_token - Его токен для входа в его аккаунт
```

# channels
> **Warning**
> 
> Может изменится
```
id - ID канала
guild_id - ID сервера
position - Позиция в списке
type - Тип канала:
 - 0 (Текстовый канал)
 - 1 (Голосовой канал)
name - Название канала
description - Описание канала
```

# guild_invites
```
invited_by - ID участника, который создал приглашение
code - Код приглашения
used - Сколько уже использовали
created - Когда создан
expires - Когда истечёт
```

# guild_members
```
used_id - ID участника, который на сервере
guild_id - ID сервера
```
