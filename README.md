# Node.js
## Создание масштабируемых приложений на JavaScript
### Pedro Teixeira, WILEY, 2013

## Оглавление

* **Введение**

### Часть I. Введение и установка

* **Глава 1. Установка Node**
* **Глава 2. Введение в Node**

### Часть II. Базовый API Node

* **Глава 3. Загрузка модулей**
* **Глава 4. Использование буферов для манипуляции, кодирования и декодирования двоичных данных**
* **Глава 5. Использование шаблона генератора событий для упрощения обработки событий**
* **Глава 6. Планирование выполнения функций с помощью таймеров**

### Часть III. Файлы, процессы, потоки и сеть

* **Глава 7. Запрос, чтение и запись файлов**
* **Глава 8. Создание и контроллирование внешних процессов**
* **Глава 9. Чтение и запись потоков данных**
* **Глава 10. Создание TCP-серверов**
* **Глава 11. Создание HTTP-серверов**
* **Глава 12. Создание TCP-клиента**
* **Глава 13. Выполнение HTTP-запросов**
* **Глава 14. Использование дейтаграмм (UDP)**
* **Глава 15. Защита TCP-сервера с помощью TSL/SSL**
* **Глава 16. Защита HTTP-сервера с помощью HTTPS**

### Часть IV. Построение и отладка модулей и приложений

* **Глава 17. Тестирование модулей и приложений**
* **Глава 18. Отладка модулей и приложений**
* **Глава 19. Контроль потока вызовов**

### Часть V. Построение веб-приложений

* **Глава 20. Создание и использование HTTP-прослоек**
* **Глава 21. Создание веб-приложения с помощью express.js**
* **Глава 22. Создание универсальных веб-приложений реального времени с помощью socket.io**

### Часть VI. Соединение с базами данных

* **Глава 23. Работа с MySQL с помощью node-mysql**
* **Глава 24. Работа с CouchDB с помощью nano**
* **Глава 25. Работа с MongoDB с помощью mongoose**

>Эта книга посвящается моей жене, Сюзанне.

> Все эти годы она была для меня примером силы и стойкости.


## Об авторе

Педро Тейксеира — продуктивный opensource-программист и автор множества модулей Node.js. После получения степени в разработке программного обеспечения более 14 лет назад, он работал консультантом, программистом и был активным всемирно-известным членом сообщества Node.js.

Он является сооснователем The Node Firm и ведущим разработчиком в Nodejitsu Inc., основном поставщике PAAS для Node.js. Также, он — автор популярных уроков Node Tuts.

Когда Педро был 10 лет, отец показал ему как програмировать для ZX Spectrim, и с тех пор он не хотел останавливаться. Он научился программировать на Apple IIc своего отца, а затем перешел в эру PC. В колледже он познакомился с вселенной UNIX и open-source и серьезно подсел на них. В своей профессиональной жизни он разрабатывал системы и продукты на Visual Basic, C, C++, Java, PHP, Ruby и JavaScript для больших телекоммуникационных компаний, банков, гостиничных сетей и других.

Он стал энтузиастом Node.js с первого выпуска, создал много приложений и хорошо известных модулей, таких как Fugue, Alfred.js, Carrier, Nock и других.

## О техническом редакторе

Мэнуел Кисслинг — лидер команд разработки программного обеспечения и системного администрирования, он использует и обучает гибким методологиям (agile practice) в обеих областях. Он запустил несколько open-source проектов, является активным блогером, и написал свободно доступную книгу Node для новичков (Node Beginner Book). В настоящее время он живет близ Кельна, Германия, со своей женой и двумя детьми.

Он также является соавтором главы 22, "Создание универсальных приложений реального времени с использованием Socket.IO", и главы 23, "Соединение с MySQL с помощью модуля node-mysql".

## Над книгой работали:

ACQUISITIONS EDITOR
Mary James

PROJECT EDITOR
Tora Estep

TECHNICAL EDITOR
Manuel Kiessling

PRODUCTION EDITOR
Daniel Scribner

COPY EDITOR
Kezia Endsley

EDITORIAL MANAGER
Mary Beth Wakefi eld

FREELANCER EDITORIAL MANAGER
Rosemarie Graham

ASSOCIATE DIRECTOR OF MARKETING
David Mayhew

MARKETING MANAGER
Ashley Zurcher

BUSINESS MANAGER
Amy Knies

PRODUCTION MANAGER
Tim Tate

VICE PRESIDENT AND EXECUTIVE
GROUP PUBLISHER

Richard Swadley
VICE PRESIDENT AND EXECUTIVE

PUBLISHER
Neil Edde

ASSOCIATE PUBLISHER
Jim Minatel

PROJECT COORDINATOR, COVER
Katie Crocker

PROOFREADER
Nicole Hirschman

INDEXER
Ron Strauss

COVER DESIGNER
Ryan Sneed

COVER IMAGE
© Gregory Olsen/iStockPhoto

## Благодарности

Во-первых, я благодарю мою жену, Сюзану, и моих детей, енрика и Беатрис. Вы дали мне смелость и стойкость, напоминая о том, что действительно важно в жизни.

I’d also like to thank my Acquisitions Editor at Wiley, Mary E. James, for having faith in me and signing me up to write this book.

I want to thank my good friend and former colleague, programmer and photographer Pedro Mendes, who persuaded me to start writing a book about Node.js over a few beers in Lisbo .

I also want to thank my good friend Nuno Job, who has been my companion in this open source and Node.js crusade for these last few years.

A big word of appreciation also goes out to the Node.js community in general. You are the best, most welcoming, appreciative, and fun programming community I have been a part of.

Lastly, I want to thank you, the reader, for buying this book. I hope it helps you in learning about the ins and outs of the wonderful world of programming in Node.js.