# AbuBot

## Список ролей (по убыванию прав)
| co-host       | s-adm      | vip | player | bad | 

## Список комманд
 * Имя игрока можно вводить через автодополнение, например !voteban @КОКОРИН
 * Название карты можно вводить не полностью, регистр не важен, например: !map classic, !map racing 8, !map cops
 
* ###  Игровой процесс

| Команда       | Аргумент      | Описание |
| ------------- | ------------- |----------|
| **!q**  |   | Узнать, кто сколько играет и ждет         |
| **!auto**  | <on/off>  | Вкл/Выкл автоматизацию румы         |
| **!state**  |   | Текущие параметры румы (автождоин, автомикс, автостарт)         |
 
* ###  Модерация
  * Баны чистятся раз в час

| Команда       | Аргумент      | Описание |
| ------------- | ------------- |----------|
| **!staff**  |   | Выводит список випов и админов в руме         |
| **!mute**  | _<имя игрока>_  | Замьютить игрока         |
| **!unmute**  | _<имя игрока>_  | Размьютить игрока         |
| **!mutemode, !mm**  |   | Вкл/выкл мьютмод на текущую игру   |
| **!ban**  | _<имя_игрока> <кол-во часов>_  | Забанить игрока         |
| **!permban**  | _<имя_игрока>  | Забанить игрока навсегда        |
| **!clearban**  | _<имя игрока>_  | Убрать бан для ранее забаненного игрока         |
| **!clearbans**  |   | Снять все баны         |
| **!mutelist**  |   | Список замьюченных игроков         |
| **!banlist**  |   | Список забаненных игроков. В скобках указан тот, кто забанил        |

***

* ###  Голосование
  * Для положительного результата необходимо минимум 50% голосов за из числа находящихся в руме игроков

| Команда       | Аргумент      | Описание |
| ------------- | ------------- |----------|
| **!votekick**  | _<имя игрока>_  | Голосование за кик игрока         |
| **!voteban**  | _<имя игрока>_  | Голосование за бан игрока         |
| **!votemute**  | _<имя игрока>_  | Голосование за мьют игрока         |
| **!votemap**  | _<название карты>_  | Голосование за смену карты         |

***

* ###  АФК
  * При отсутствии активности в течение 15 минут - кик

| Команда       | Аргумент      | Описание |
| ------------- | ------------- |----------|
| **!afk**  |  | Уйти/Вернуться из АФК |
| **!afks**  |  | Список АФК |
| **!join, jj**  |   | Кидает в команду        |
| **!c**  |   | Попросить замену  |

***

* ###  Статистика
  * Чтобы не терять статы при смене браузера необходимо записать свой Private Key: [https://www.haxball.com/playerauth](https://www.haxball.com/playerauth). Никому его не показываем. Далее, если статы потеряны, необходимо зайти по вышеуказанной ссылке, нажать Change Key и скопировать туда свой сохраненный Private Key.
  * Статы пишутся только начиная с игр 3 на 3 игрока

| Команда       | Аргумент      | Описание |
| ------------- | ------------- |----------|
| **!stats, !s**  | [full]  | Твоя игровая статистика, full - вся статистика  |
| **!ss**  | [full]  | Твоя игровая статистика, тихий режим  |
| **!postcount, !pc**  |   | Количество сообщений        |
| **!top**  | <стата> [количество] | Топ лучших, gpg - по голам за игру, apg - по ассистам за игру, mgp - по сообщениям за игру, wl - win/loss |
| **!rank**  | [stat]  | Твое место по стате и кто находится рядом  |
| **!worst**  | <стата> [количество] | Топ худших |

***

* ###  Остальное
| Команда       | Аргумент      | Описание |
| ------------- | ------------- |----------|
| **!pm**  | <@имя_игрока> <сообщение>  | Сообщение в ЛС       |
| **!bet**  | [blue,red,draw]  | Сделать ставку       |
| **!odds, !кф**  |  | Узнать коэффициенты       |
| **!roll**  |   | Перекатиться в другую команду. Работает только при перевесе численности в 2 игрока       |
| **!map**  | _<название карты>_  | Смена карты. [Список-карт](https://github.com/syrnique/AbuBot/wiki/Список-карт)         |
| **!discord**  |   | Ссылка на дискорд         |
| **!donate**  |   | Ссылка на донат         |

***

* ###  Для vip, s-adm и co-host
| Команда       | Аргумент      | Описание |
| ------------- | ------------- |----------|
| **!say**  | <сообщение>  | Написать от имени бота      |
| **!deanon**  | <имя_игрока> | Узнать другие ники игрока       |
| **!setprop**  |  | Изменить параметры своего шара (массу, упругость, радиус)      |
| **!colors**  | _<название цвета>_  | Изменить цвет команды. аргумент default возвращает обычные цвета, ls - список цветов, rnd - случайные цвета        |

* ###  Для co-host
| Команда       | Аргумент      | Описание |
| ------------- | ------------- |----------|
| **!setrole**  | <co-host / s-adm / vip / player / bad> <имя_игрока> | Изменить роль      |
