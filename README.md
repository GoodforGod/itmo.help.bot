# iTMO.Help.bot 💬

<p align="center">
  <img src="https://media.giphy.com/media/xT9IgjZR0GmgffYgve/giphy.gif" width="256" height="256" align="middle"/>
</p>

Telegram бот расписания занятий *Университета ИТМО*.

*Ссылка* на бота **[iTMO.Help.Bot](https://telegram.me/iTMOHelpBot "iTMO.Help Bot")**

## Content
- [Что, Зачем, Почему](#что-зачем-почему)
- [Features](#features)
  - [Registration](#registration)
  - [Notifications](#notifications)
  - [Address and Routing](#campus-address-and-routing)
- [Commands](#commands)
  - [Lesson Commands](#lesson-commands)
  - [Exam Commands](#exam-commands)
  - [Search Commands](#search-commands)
  - [Settings Commands](#settings-commands)
- [Explanation](#explanation)
  - [Emoji](#emoji)
- [Version History](#version-history)
- [Info](#info)

## Что, Зачем, Почему

Зачем тебе нужен бот, спросишь ты? Естественно потому что это круто, но ты также можешь найти в нем очень крутые особенности и сделать свою жизнь чуточку лучше.

*Ты только подумай о...*
* Мгновенное расписание по твоему щелчку в твоем **любимом мессенджере**.
* **Ежедневная утренняя** порция расписания от бота, только для тебя.
* Адреса кампусов **на карте** с возможностью проложить **маршрут** в считанные секунды. 
* **Кросс-платформенный** доступ к расписанию и уведомлениям.
* Возможность **легко делиться** расписанием со своими коллегами (если эти бедняги еще не знают о боте).
* Ну что тебе еще нужно, правда, тебе ведь уже не терпиться попробовать его. *Just do it!* -> **[Bot](https://telegram.me/iTMOHelpBot "iTMO.Help Bot")**

<p align="center">
  <img src="https://media.giphy.com/media/m8jdGkV9YSWVd4qwFb/giphy.gif" align="middle"/>
</p>

## Возможности

Бот обладает всеми основными функциями:
* Полная информация о *твоем* расписании и *ежедневные уведомления*.
* Богатый набор команд для работы с *расписанием*.
* Расписание *твоих экзаменов* и уведомления о них и *консультациях*.
* Поиск расписания занятий по *группе и преподавателю*.
* Поиск экзаменов по *группе и преподавателю*.
* Доступ к *адресу кампусов на карте* и возможность мгновенно проложить *машрут* до него.
* Поддержка нескольких языков (*Русский\Английский*).
* И это еще не все..
 
### Первый Контакт

<img src="https://media.giphy.com/media/etKVHaFU6sXFatmm32/giphy.gif" align="middle"/>

### Уведомления

Ежедневные уведомления об расписании занятий или экзаменов.

<img src="https://media.giphy.com/media/6E8XSP4gtbdIi9Jf5h/giphy.gif" align="middle"/>

### Адреса кампусов и построение маршрута

Поддерживается как на *телефоне так и ПК* через сервис *Google Map*.

<img src="https://media.giphy.com/media/TgMKRdf8po8WSr6el5/giphy.gif" align="middle"/>
 
## Туториал

Детальный туториал по структуре сообщения об расписании затяний и экзаменов **[Guide](http://telegra.ph/Getting-Started-RUS-03-14 "Guide (RUS)")**
 
## Команды

Каждая команда начинается с символа **/** как и у других ботов в Telegram.
Команды доступны через меню или при вводе в ручную.

### Команды Расписания Занятий

Эти команды используетюся для доступа к расписанию занятий и работы с ним.

* */group_all* - Показывает все расписание занятий.
* */group_week* - Показывает все расписание занятий на *текущую неделю*.
* */group_today* - Расписание занятий на *сегодняшний день*.
* */group_tomorrow* - Расписание занятий на *завтрашний день*.
* */group_remain* - Показывает *оставшееся* расписание занятий на *текущую неделю*.
* */group_select* - Расписание занятий на *конкретный день* или на *все дни*.
* */set_group* - Изменить свою **ИСУ** группу *(Пример группы: "**B3100**")*

<img src="https://media.giphy.com/media/2tQXuMCCnOpjmXi26t/giphy.gif" align="middle"/>

### Команды Экзаменов

Команды для работы с *экзаменами*.

* */exam_all* - Показывается *все* экзамены.
* */exam_remain* - Показывается *оставшиеся* экзамены.
* */exam_next* - Показывает *следующний* экзамен.

<img src="https://media.giphy.com/media/LTDIFPM4qn57EudFzQ/giphy.gif" align="middle"/>

### Команды Поиска

Эти команды позволяют искать *расписание занятий* для конкретной *группы* или *преподавателя*.
Также искать *экзамены* для конкретной *группы* или *преподавателя*.

**Поиск по преподавателю** принимает *ФИО* учителя **только в данном порядке** like (*Лебедев Иван Иванович - Фамилия Имя Отчество*).

Вы можете искать как по **фамилии** только, так и по **фамилии + имени** или **фамилии + имени + отчеству**.

#### Занятия
* */find_group* - Ищет *расписание занятий* для **конкретной группы** *(Пример группы: "**B3100**")*
* */find_teacher* - Ищет *расписание занятий* для **преподавателя**.

#### Экзамены
* */find_exam* - Ищет *экзамены* для **конкретной группы** *(Пример группы: "**B3100**")*
* */find_teacher_exam* - Ищет *экзамены* для **преподавателя**.

<img src="https://media.giphy.com/media/7JapcjYVTTzKoxogxz/giphy.gif" align="middle"/>

### Команды Настроек

Данные команды используются для *настройки* параметров работы бота, смены языка, вызова помощи и так далее.

* */help* - Даст вам граткую справку и ссылку на полную статью с информацией о боте.
* */lang* - Позволит вам **сменить язык**.
* */feedback* - Позволит отправить *отзыв/сообщение об ошибке*.
* */silent* - Вкл/Выкл все уведомления от бота.
* */menu* - Вызовет главное меню если оно вдруг пропало.
* *Уведомлнять (Когда не занятий)* - Позволит вам сказать боту стоит ли **уведомлять вас** или нет в **случае отсутствия занятий** в данный день.

<img src="https://media.giphy.com/media/4ZogUfsrvXj3fEK2kc/giphy.gif" align="middle"/>

## Информация

Эта секция описывает структуру информации и эмодзи которые использует бот. 

### Эмодзи

Описание всех эмодзи что используется бот.

#### Занятия
* 🌕 - Означает что занятие проводится только по **нечетным (Odd)** неделям.
* 🌑 - Означает что занятие проводится только по **четным (Even)** неделям.
* 🌗 - Означает что занятие проводится **каждую неделю**.
* 📯 - Означает **сегодняшний** день в расписаниию.
* 📆 - Означает любой другой день в расписании (для красоты).
* 📍 - Означает **адресс** и **кабинет** где проводится занятие.
 
* 👨‍🔬 - Означает что тип занятие - **лабораторная**.
* 👨‍🏭 - Означает что тип занятие - **практика**.
* 👨‍🏫 - Означает что тип занятие - **лекция)**.

#### Экзамены
* 🔥 - Означает что **экзамен или косультация** будут сегодня.
* 🗣 - Означает информацию об дне **консультации**.

# История Версий

Текущая - *1.0.0*

Бот трудится для вас в полную силу.
Не забывайте делиться замечаниями, отзывами, предложениями через команду **/feedback**.

Исходный код будет доступен спустя пару месяцев после релиза.
