# AbuBot

## Список комманд
 * Имя игрока можно вводить через автодополнение, например !voteban @КОКОРИН
 * Название карты можно вводить не полностью, регистр не важен, например: !map classic, !map racing 8, !map cops
  
* ###  Модерация
  * Баны чистятся раз в час

| Команда       | Аргумент      | Описание |
| ------------- | ------------- |----------|
| **!mute**  | _<имя игрока>_  | Замьютить игрока         |
| **!unmute**  | _<имя игрока>_  | Размьютить игрока         |
| **!mutemode, !mm**  |   | Вкл/выкл мьютмод на текущую игру   |
| **!ban**  | _<кол-во часов> <имя игрока>_  | Забанить игрока         |
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
  * Чтобы не терять статы при смене ip или браузера необходимо записать свой Private Key: [https://www.haxball.com/playerauth](https://www.haxball.com/playerauth). Никому его не показываем. Далее, если статы потеряны, необходимо зайти по вышеуказанной ссылке, нажать Change Key и скопировать туда свой сохраненный Private Key.
  * Статы пишутся только начиная с игр 2 на 2 игрока

| Команда       | Аргумент      | Описание |
| ------------- | ------------- |----------|
| **!stats, !s**  | [full]  | Ваша игровая статистика, full - вся статистика  |
| **!ss**  | [full]  | Ваша игровая статистика, тихий режим  |
| **!postcount, !pc**  |   | Количество сообщений        |
| **!top**  | <стата> [количество] | Топ лучших, gpg - по голам за игру, apg - по ассистам за игру, mgp - по сообщениям за игру, wl - win/loss |
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
| **!colors**  | _<название цвета>_  | Изменить цвет команды. аргумент default возвращает обычные цвета, ls - список цветов, rnd - случайные цвета        |
| **!auto**  | <on/off>  | Вкл/Выкл автоматизацию румы         |
| **!state**  |   | Текущие параметры румы (автождоин, автомикс, автостарт)         |

***

* ###  Для вип-игроков
| Команда       | Аргумент      | Описание |
| ------------- | ------------- |----------|
| **!say**  | <сообщение>  | Написать от имени бота      |
| **!deanon**  | <имя_игрока> | Узнать другие ники игрока       |
