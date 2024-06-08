# Nikita Artasov `Web Developer`

> ### Commercial experience: 3-4 years

&nbsp;&nbsp;&nbsp;&nbsp;I am a `Full-stack Web Developer` with a strong focus on `backend`.
Beginning my IT journey with game process automation, I have moved on to more
substantial and complex projects, including web application development and comprehensive
`CRM` systems. I worked at `Accenture` on an outsourcing project. Afterward, I designed and developed
a `CRM` system for an online children's school. I possess strong programming skills,
some understanding of business processes, and the ability to quickly adapt
to new client requirements.

* [Technical Skills](#technical-skills)
* [Development examples](#Development-examples)
* [How I Got Into **IT**](#how-i-got-into-it)
* [My Work Experience](#commercial-work-experience)
* [Education](#education)
* [Contacts](#contacts)
_______________________________________________________________

## Technical Skills:

* **3 - 4 years of experience in commercial writing**
* `Python` `Django` `React` `DRF` `HTTP` `WebSockets` `Docker Compose`<br>
  `REST` `S3 Storage(Minio)` `HTML/CSS/SCSS/Bootstrap` `JS`<br>
  `Redis` `Linux` `Git` `nginx` `gunicorn` `Qt C++` `WinAPI` `selenium`<br>
* Familiar with `SOLID`, `KISS`, `DRY` principles and `design patterns`.
* I distinguish between multithreading and multiprocessing from asynchrony in Python.
* Experienced in auto-documentation with `Swagger` and `Sphinx`.
* Understand `indexes` and `isolations` in databases.
* Heard about `Kubernetes`.
* Have experience integrating `Adyen`, `Braintree`, `GlobalPayments`,
  `Checkout`, and several other payment systems.
_______________________________________________________________
## Development examples
>What I can show

### `Async Django` + `React` + `Docker` - https://github.com/Artasov/xlartas
### Lib for automation on Windows - https://github.com/Artasov/simpleautogui
### I can separately send examples of C++ code for programs described below.
_______________________________________________________________

## How I Got Into `IT`

&nbsp;&nbsp;&nbsp;&nbsp;I had a relatively large gaming `YouTube` channel where I played games.
I wrote simple automations for cursor movements and button presses.
Afterward, I started learning `Python` and could already search for colors and images on the screen
using `OpenCV`. <br>
&nbsp;&nbsp;&nbsp;&nbsp;My first project at the start of learning programming was a game software.
The first version was in `PyQt`, then I switched to `Qt C++`.
These were applications for automating certain gaming processes, where high
performance and timing accuracy were crucial.
I created a website for these desktop applications where they could be purchased on a subscription basis.
By this stage, I was proficient in `Python` and quite skilled in managing
`Qt C++`, signals, classes, `WinAPI`. I configured static builds,
resulting in a single executable file, which is not as simple as it
might seem if you haven't tried it yourself. Then, I set up my first server
on `VDS` and made an `API` for updating my desktop programs and logging into them.
I connected a payment system aggregator, advertised, and sold different types
of subscriptions, and I still make a small income from this project :)<br>
At this time, I was studying at `St. Petersburg State Electrotechnical University 'LETI'`
in `Applied Mathematics and Informatics`.
_______________________________________________________________

## Commercial Work Experience:

1. ### First non-personal project | Freelance `2020-2024`
   &nbsp;&nbsp;&nbsp;&nbsp;A small chain of jewelry salons posted an ad on a freelance
   platform. They needed a web application with promotions, addresses, a current catalog (without online purchasing),
   contact details, etc. Essentially, a multi-page landing page with a catalog.
   We found a designer, created the design, and collectively set up periodic
   product uploads from 1C to our web application. <br>
   `Django` + `DRF` + `Celery` + `PostgreSQL`<br>
   Knowing that `1C` can interact with `Postgre`, it might be possible to use a single database in the future.


3. ### Middle FullStack Dev | Online IT school for children `2022 - 2024`

   &nbsp;&nbsp;&nbsp;&nbsp;When I joined the company,
   there were `AmoCrm` and `HolliHop` (`CRM` system for educational centers).
   Using `GoogleSheets`, various summary scripts, and scripts scattered
   across different parts of the infrastructure, operations were streamlined between departments.<br>
   &nbsp;&nbsp;&nbsp;&nbsp;At that time, the school had over 10,000 students and more than 100
   teachers. For further development and scaling,
   a replacement for `HolliHop` was necessary, which we could
   supplement and modify according to our own requirements.<br>

   &nbsp;&nbsp;&nbsp;&nbsp;Together with the analyst, who is also the
   school director, we chose the technology stack we needed:<br>

    * From `Django`, we used `ORM`, the authorization, authentication, and session system.
      The front-end was built with `React`+`Redux`, developed by two developers.
      The database was `PostgreSQL`. For mail and `Telegram` message distributions, we
      used `Redis` + `Celery`, which also had many other minor periodic tasks.
      Eventually, we had two backend developers and two front-end developers.
      (and a junior developer helping). Used asynchronous `Django` 
      via `daphne`, a lot of the logic for the asynchronous operation of `ORM` was written independently. 
      The same applies to serializers (`adrf` does not help)

   #### Implemented
    * Integration with `AmoCRM`
    * Teacher's personal account, displaying current salary,
      schedules for individual and group lessons, open
      lessons, consultations, etc.
    * Parent and student personal accounts. Parents could see teacher's comments about their child,
      while students received current homework and notifications in
      `WhatsApp`, `Telegram`, or `Vk`.
    * Detailed statistics for the sales department managers.
    * Convenient service for `Zoom` conference administrators, allowing tracking of which
      students are expected to attend lessons in the next X minutes,
      in which room, and with which teacher, as well as who has already been late
      and needs to be called.
    * Service for students, allowing those studying individually to request rescheduling of the next
      lesson according to the free time in their teacher's schedule. Teachers receive notification about
      the rescheduling request.
    * Functionality for generating various types of reports.

   #### And many similar features.

## Education

* ### General Secondary Education
* ### St. Petersburg State Electrotechnical University 'LETI' - Applied Mathematics and Informatics `2020 - 2021`
_______________________________________________________________
**Russian**: Native.<br>
**English**: Comfortable reading documentation, conversational 50/50.
_______________________________________________________________

## Contacts

* ### **Telegram**: [@artasov](https://t.me/artasov)
* ### **Email**: ivanhvalevskey@gmail.com
_______________________________________________________________