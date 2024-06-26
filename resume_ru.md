# Никита Толпегин `Web Developer`
> ### Коммерческий опыт: 3-4 года

&nbsp;&nbsp;&nbsp;&nbsp;Я `Full-stack Web Developer` с сильным уклоном в сторону `backend`. 
Начав свой путь в IT с автоматизации игровых процессов, я пришел к более масштабным и 
сложным проектам, включая разработку веб-приложений и комплексных `CRM` систем. После проектировал и разрабатывал 
`CRM` систему для детской онлайн-школы. У меня есть уверенные навыки 
программирования, некоторое понимание бизнес-процессов и способность быстро адаптироваться 
к новым требованиям клиента.

* [Технические навыки](#технические-навыки)
* [Примеры разработки](#примеры-разработки)
* [Как попал в **IT**](#как-попал-в-it)
* [Мой опыт работы](#коммерческий-опыт-работы)
* [Образование](#Образование)
* [Контакты](#контакты)
_______________________________________________________________
## Технические навыки:
* **Опыт в написании коммерческого кода 3 - 4 года**
* `Python` `Django` `React` `DRF` `HTTP` `WebSockets` `Docker Compose`<br>
  `REST` `S3 Storage(Minio)` `HTML/CSS/SCSS/Bootstrap` `JS`<br>
  `Redis` `Linux` `Git` `nginx` `gunicorn` `Qt C++` `WinAPI` `selenium`<br>
* Знаю принципы `SOLID`, `KISS`, `DRY` и `паттерны проектирования`.
* Отличаю многопоточность и многопроцессность от асинхронности в Python.  
* Делал авто-документацию через `Swagger` и `Sphinx`.
* Знаю что такое `kuber` и `swarm`, но лично не применял.
* Был опыт подключения `Adyen`, `Braintree`, `globalpayments`, 
`checkout` и нескольких других крупных платежек.
_______________________________________________________________
## Примеры разработки
> То, что могу показать

### `Async Django` + `React` + `Docker` - https://github.com/Artasov/xlartas
### Либа для автоматизации на Windows - https://github.com/Artasov/simpleautogui
### Могу отдельно прислать примеры C++ кода программ о которых ниже.
_______________________________________________________________
## Как попал в `IT`

&nbsp;&nbsp;&nbsp;&nbsp;Начал с того, что писал простые автоматизации движений курсора и нажатий кнопок
через банальный autohotkey. 
После учил `Python`, искал цвета и изображения на экране
с помощью `OpenCV`, управлял браузером через `Selenium`, и брал заказы на фрилансе(парсеры, лендинги и т.п.). <br>
&nbsp;&nbsp;&nbsp;&nbsp;Первым проектом на старте изучения программирования стал софт 
для игры. Сначала на `PyQt`, потом он же на `Qt C++`.
Это были приложения для автоматизации некоторых игровых процессов, где важна 
большая производительность и точность по времени. Использовал многопоточность через QThread, QThreadPool,
сделал вход по логину паролю в программы и регистрацию через сайт, а также покупку подписок с подключением 
платежного агрегатора. Еще был игровой 100к подписчиков
канал, куда можно было эти программы продавать. Я так и делал.<br> 
&nbsp;&nbsp;&nbsp;&nbsp;В это время я хорошо владел `Python` и довольно хорошо управлялся 
с `Qt C++`, сигналами, классами, `WinAPI`. Настроил статическую сборку,
чтобы в итоге был один исполняемый файл, что не так просто, как может 
показаться. Сервис до сих пор работает.<br> 
В это время уже учился в `СПбГЭТУ 'ЛЭТИ'` на `Прикладной математике и информатике`.
_______________________________________________________________
## Коммерческий опыт работы:

1. ### Первый проект не для себя | Freelance `2020-2024`
   &nbsp;&nbsp;&nbsp;&nbsp;Требовалось написать для небольшой сети 
   ювелирных салонов web-приложение, в котором будут
   акции, адреса, актуальный каталог (без онлайн-покупки), 
   контактные данные и т.д. Скажем так, многостраничный лэндинг с каталогом.
   Нашли дизайнера, сделали дизайн и общими усилиями настроили периодическую
   выгрузку товаров из `1C` на наше web-приложение. <br>
   `Django` + `DRF` + `Celery` + `PostgreSQL`<br>
   Зная, что `1C` умеет взаимодействовать с `Postgre`, возможно в будущем 
   используем это.


3. ### Middle FullStack Dev | Онлайн-школа IT для детей `2022 - 2024`
 
   &nbsp;&nbsp;&nbsp;&nbsp;Когда пришел в компанию, 
   было `AmoCrm` и `HolliHop` (`CRM`-система для учебных центров).
   С помощью `GoogleSheets`, разных сводных и разных скриптов, разбросанных
   по разным частям инфраструктуры, была отлажена работа между отделами.<br>

   &nbsp;&nbsp;&nbsp;&nbsp;На тот момент в школе было более 20000 учеников и более 200 
   преподавателей. Для дальнейшего развития и масштабирования 
   была необходима замена для `HolliHop`, которую мы смогли бы 
   дополнять и изменять под собственные требования.<br>

   &nbsp;&nbsp;&nbsp;&nbsp;Вместе с аналитиком, который также является 
   директором школы, мы выбрали нужный нам стек технологий:<br>
   Из `Django` мы использовали `ORM`, систему авторизации, аутентификации и сессии. 
   К `Django` был привязан фронт на `React`+`Redux`, над которым работали двое разработчиков. 
   База данных - `PostgreSQL`. Для реализации рассылок почты и сообщений в мессенджеры мы 
   использовали `Redis` + `Celery`, на котором также было много других мелких периодических задач. 
   В итоге у нас получилось два backend-разработчика и два frontend-разработчика 
   (и помогающий джун). Использовался асинхронная `Django` через `daphne`, много логики для асинхронной работы
   `ORM` писалось самостоятельно. То же самое касается и сериалайзеров(`adrf` не спасает)

   #### Было реализовано
   * Интеграция с `AmoCRM`
   * Личный кабинет для преподавателя, в котором отображается актуальная зарплата, 
     расписание индивидуальных и групповых уроков, открытых 
     уроков, консультаций и т.п.
   * Личный кабинет родителя и ученика. У родителя видны комментарии преподавателя к ученику, 
     а ученик получает актуальные домашние задания и уведомления в
     `WhatsApp`, `Telegram` или `Vk`.
   * Подробная статистика для менеджеров отдела продаж.
   * Удобный сервис для администраторов `Zoom`-конференций, позволяющий отслеживать, кто из 
     учеников должен прийти на урок в течение следующих X минут, 
     в какой зал, к какому преподавателю, а также кто уже опоздал 
     и нужно звонить ученику.
   * Сервис для учеников, позволяющий, занимаясь индивидуально, запрашивать перенос следующего 
     урока в соответствии со свободным временем в расписании 
     их преподавателя. Преподавателю приходит уведомление о 
     запросе на перенос. 
   * Функционал для формирования различных видов отчетов.
   
   #### И много подобных фич.

 
## Образование
* ### Среднее общее
* ### СПбГЭТУ 'ЛЭТИ' ИМ. В.И. Ульянова (Ленина) - Прикладная математика и информатика `2020 - 2021`
_______________________________________________________________
**Русский**: родной.<br>
**Английский**: легко читаю документации, разговорный 50 на 50.
_______________________________________________________________
## Контакты

* ### **Telegram**: [@artasov](https://t.me/artasov)
* ### **Email**: ivanhvalevskey@gmail.com
_______________________________________________________________