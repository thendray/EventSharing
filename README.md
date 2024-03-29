# EventSharing
**EvantSharing** - Быстро Удобно Просто

***
Перейти на сайт вы можете, использую qr код или по ссылке.

**QR**

![](https://github.com/thendray/EventSharing/blob/main/img/qrSite.png)

**Прямая ссылка на сайт**

https://eventsharing.azurewebsites.net/

**Ссылка на код**

https://github.com/thendray/EventSharingFinal
***

  Почти каждый человек хочет, чтобы его жизнь была насыщенной, интересной, разнообразной. Для этого существует огромное колличество разнообразных видов досуга. Однако их поиск может занимать много времени.

Представьте, что у каждого мероприятия есть свой сайт или объявление на разных площадках. Информация собрана на различных ресурсах, с разными вводными данными и описанием. Найти что-то подходящее для себя становится проблематично. Существует большой шанс, что вы просто не увидите/не найдёте именно то событие, которое искали. 

Мы предлагаем Вам наш сервис, где с помощью фильтров и интерактивной карты Вы сможете с легкостью подобрать интересные для Вас события. Также отличительной чертой нашего продукта станет возможность каждому пользователю путем нехитрых действий добавлять информацию о проходящих ивентах. Это позволит увеличить разнообразие предлагаемого контента для людей, которые ищут событие, а также даст возможность самим организаторам/участникам делиться с пользователями информацией о их крутых мероприятих.

Event Sharing, в первую очередь, это сервис доступный каждому. Мы хотим, чтобы любой человек мог найти для себя что-нибудь на платформе. Концепция проекта достаточно гибкая. Сервис можно использовать стандартно - зайти на сайт, воспользоваться поиском, присоединиться к мероприятию и наслаждаться или во время прогулки воспользоваться поиском и разнообразить ее посещением ближайщих мероприятий вокруг вас.
***
### Актуальность
  Изучив рынок, мы отметили для себя некоторых аналогов нашему сервису(KudaGo, KudaMoscow). Однако почеркнули для себя их явные недостатки, которые выявили сами и которые указывали пользователи в одзывах. Стоит отметить, что посещаемость у сайтов неплохая, но учитывая не самые хорошие отзывы, мы сделали вывод, что спрос есть, но он неудолетвоер должным образом, а значит подобная идея актуальна для населения.
То что мы предлагаем, может стать хорошим толчком для начинающих "проектов": мероприятий, которые только выходят на рынок, часные события, выступления, выставки начинающих творческих единиц и т.д. Сервис может помочь набрать аудиториюю или прибавить новую. Это актуально, так как тенденция развития современного исскуства растет, и тем более среди молодежи. Они все больше интересуются, пробуют, развиваются в этом направлении, что-то создают, а значит им необходима какая-то площадка. Хороший ассортимент, выбор всегда ценился и был актуален - мы стимулируем это за счет свободного распростарнения и добавления информации. Вы владелец, организатор, участник или просто неравнодушный человек, желающий поделиться с миром информацией о крутом событии - вперед, у вас есть такая возможность. Проект в большей степени нацелен на активную аудиторию, готовую проводить время не только дома, но как уже отмечалось, каждый может найти для себя что-то.

### Бизнес-модель
  На данном этапе, расходы проекта в месяц оцениваются как 17 600 рублей. В них входят аренда базы данных (800р), облачное решение хранения (6800р) и использование Яндекс API, за что на текущем(начальном этапе) надо платить 10 000р. Монетизация планируется в виде платных подписок. Но важно отметить, что подписки не будут дискриминировать пользователей в ключевом функционале сайта. Назовем это "free to use" (почти как в играх "free to play"). Предлагаемый дополнительный функционал больше нацелен на комфорт, но не на получение каких-то ключевых преимуществ. Итак: планируется 2 подписки - премиум и корпоративная. 
 
 **Премиум** - включает в себя возможность кастомизации меток и информации на ней + возможность создания диалогов при создании события
 
 **Корпоративная** - подписка для компаний и корпораций, обладающих большим количеством мероприятий. В подписку входит функционал премиум + безлимитная публикация событий и мероприятий, а также ускоренная верификация
***
## Анализ доменной области
### Введение
Требуется разработать онлайн-сервис по поиску, размещению и продвижению мероприятий и ивентов с использованием интерактивной карты. Далее представлены описание объектов и их взаимодействие. Собранная информация будет использована для разработки продукта.
### Глоссарий
* ***Мероприятие/ивент*** - организованное событие, с участием некоторого количества человек.
* ***Пользователь*** - человек, использующий функционал сервиса в целях **н**айти мероприятие/**р**азместить информацию о мероприятии.
* ***Интерактивная карта*** - карта с метками событий, содержащая необходимую информацию.
* ***Молодежь*** - люди в возрасте от 18 до 24 лет. 
### Общие знания о домене
* Огромное количество различных мероприятий и событий
* Информация размещена и разбросана на многочисленных сервисах и ресурсах
* Карта один из удобных вариантов визуализации информации
* Каждое мероприятие, отображенное на карте, имеет свое имя, дату, место проведения и общую информацию
* События видны всем пользователям
* Прошедшие мероприятия не представляют интереса и удаляются
### Клиенты и пользователи
Потенциальные пользователи относятся к двум категориям: люди, которые ищут интересное времяпровождение и не хотят пропустить различные интересные мероприятия. Вторая группа – это люди или компании, желающие рассказать о своём мероприятии, организованном событии и привлечь людей.

Для примера: в России более 60% молодежи интересуются современным исскуством, половина - хочет развиваться в творческих направлениях. Тогда одни смогут размещать информацию о своих выступлениях/шоу/выставках с помощью сервиса, а другие узнавать об этом и посещать понравившиеся ивенты.
### Окружающая среда
Каждый пользователь сможет воспользоваться услугами сервиса с мобильного устройства, персонального компьютера или ноутбука. Необходимо устойчивое интернет-соединение.
### Задачи и процедуры
* Информирование пользователей о проводимых мероприятиях: Организатор/участник мероприятия публикует информацию о событии, которую может увидеть любой пользователь.
Такой способ информирования и получения информации удобен тем, что всё собрано в одном месте и каждый пользователь может с лёгкостью выбрать для себя подходящее мероприятие.
* Распространение информации и большой охват аудитории для организаторов.
### Конкурирующее программное обеспечение
Существуют несколько конкурирующих программных обеспечений, но большинство из них завязано на определенную локацию, например мероприятия собраны только для Москвы или предоставляемый спектр выбора мероприятий не обширен из-за продвижения только крупных, и не всегда интересных проектов.
### Сходство с другими областями
У каждого человека есть предпочтения как провести его свободное время, чем заняться и т.д. Иногда хочется сменить рутинный образ жизни, сходить куда-то. Тогда человек начинает заниматься поиском мест, мероприятий, которые ему могли бы понравиться. Он может писать, звонить друзьям, узнавать, чтобы они могли рекомендовать.
***
## Use Cases
#### [1. Пользователь регистрируется на сайте](#usecase_1)
#### [2. Пользователь авторизуется на сайте](#usecase_2)
#### [3. Пользователь ищет мероприятие по местоположению](#usecase_3)
#### [4. Пользователь ищет мероприятие по фильтрам](#usecase_4)
#### [5. Пользователь присоединяется к чату участников мероприятия](#usecase_5)
#### [6. Пользоваетль размещает на сайт мероприятие от лица организатора](#usecase_6)
#### [7. Пользователь размещает на сайт мероприятие от 3его лица](#usecase_7)
---
<a name = "usecase_1"></a>
### 1. Пользователь регистрируется на сайте
**Название** - Пользователь регистрируется на сайте

**Описание** - Если у пользователя нет аккаунта, он может его создать путем регистрации на сайте

**Участники взаимодействия** - Пользователь/Система

**Результат** - У пользователя появляется персональный аккаунт

**Успешный сценарий**
1. Пользователь нажимает на кнопку "Регистрация"
2. Система предлагает форму для заполнения
3. Пользователь заполняет поля для ввода
4. Система проверяет корректность введенных данных
5. Система дает разрешение на вход под созданным логином

**Альтернативный сценарий**

**(3)** Если поля остаются не заполненными, система выводит соответствующее сообщение и не разрешает зарегистрировать аккаунт.

**(4)** Если данные некорректны (такой логин/пароль уже существует или допущены ошибки при введении данных), система выводит соответствующее сообщение и не разрешает зарегистрировать аккаунт.
<a name = "usecase_2"></a>
### 2. Пользователь авторизуется на сайте
**Название** - Пользователь авторизуется на сайте

**Описание** - Если у пользователя существует аккаунт, он входит на сайт используя логин и пароль

**Участники взоимодействия** - Пользователь/Система

**Результат** - Пользователь входит на сайт под своим аккаунтом

**Успешный сценарий**
1. Пользователь нажимает на кнопку "войти"
2. Система предлагает заполнить поля "логин" и "пароль"
3. Пользоваетель вводит данные
4. Система разрешает вход на сайт

**Альтернативный сценарий**

**(4)** Если пользователь вводит некорректные данные, то система выводит соответствующее сообщение и не разрешает войти на сайт.
<a name = "usecase_3"></a>
### 3. Пользователь ищет мероприятие по местоположению
**Название** - Пользователь ищет мероприятие по местоположению

**Описание** - Пользователь получает информацию о мероприятиях вокруг его местоположения

**Участники взаимодействия** - Пользователь/Система

**Результат** - Метки на карте, удовлетворяющие расположению относительно пользователя

**Успешный сценарий**
1. Пользователь нажимает кнопку "найти по местоположению"
2. Пользователь может указать радиус поиска и точку "отсчёта"
3. Система выдает ближайшие мероприятия вокруг пользователя/точки "отсчёта"

**Альтернативный сценарий**

**(2)** По умолчанию точка отсчёта - текущее местоположение пользователя. Если не включена геопозиция и поле точки отсчёта пустое, система выдаёт соответствующее сообщение с просьбой включить геолокацию или указать точку отсчёта
<a name = "usecase_4"></a>
### 4. Пользователь ищет мероприятие по фильтрам
**Название** - Пользователь ищет мероприятие по фильтрам

**Описание** - Пользователь получает информацию о мероприятиях согласно указаным фильтрам для поиска

**Участники взаимодействия** - Пользователь/Система

**Результат** - Метки на карте, удовлетворяющие фильтрам поиска

**Успешный сценарий**
1. Пользователь вводит название в поисковую строку или настраивает фильтры
2. Система выдаёт метки на карте, соответствующие запросу
3. Пользователь может выбрать мероприятие на карте или из списка событий рядом

**Альтернативный сценарий**

**(2)** Если ни одно мероприятие не соответствует запросу, система выводит соответствующее сообщение
<a name = "usecase_5"></a>
### 5. Пользователь присоединяется к чату участников мероприятия
**Название** - Присоединение к чату участников мероприятия

**Описание** - Пользователь выбирает мероприятие и может присоединиться к чату или обсуждению, если такое предполагается организаторами

**Участники взаимодействия** - Пользователь/Система

**Результат** - Пользователь вступает в чат мероприятия

**Успешный сценарий**
1. Пользователь выбирает интересующее его мероприятие
2. Система выдает информацию о выбранном событии
3. Пользователь нажимает на кнопку "Присоединиться к обсуждению"
4. Система добавляет пользователя в чат

**Альтернативный сценарий**

**(3)** Если организатор не подразумевает наличие чата, то кнопки "присоединиться к обсуждению" не будет

**(4)** Если пользователь не авторизован, то система не добавит его в чат, а выведет соответствующее сообщение с предложением авторизоваться
<a id = "usecase_6"></a>
### 6. Пользоваетль размещает на сайт мероприятие от лица организатора
**Название** - Пользователь размещает на сайт мероприятие от лица организатора

**Описание** - Пользователь - орагнизатор мероприятия, публикует/добавляет информацию о своём мероприятии

**Участники взоимодействия** - Пользователь/Система

**Результат** - Мероприятие появляется в базе данных сервиса

**Успешный сценарий**
1. Пользователь заходит в свой профиль
2. Пользоваетль нажимает на кнопку "Добавить мероприятие"
3. Система выдаёт форму для заполнения информации о своём мероприятии
4. Пользователь вводит требуемую информацию и нажимает подтвердить
5. Система сохраняет мероприятие

**Альтернативный сценарий**

**(1)** Если пользователь не авторизован, система предлагает войти в свой аккаунт

**(4)** Если пользователь вводит некорректную информацию, система сообщает об этом и предлагает повторное заполнение формы
<a id = "usecase_7"></a>
### 7. Пользователь размещает на сайт мероприятие от 3его лица
**Название** - Пользователь размещает на сайт мероприятие от 3его лица

**Описание** - Пользоваетль - участник или осведомленный, публикует/добавляет информацию о мероприятии в котором участвует/ о которм знает

**Участники взоимодействия** - Пользователь/Система

**Результат** - Мероприятие появляется в базе данных сервиса

**Успешный сценарий**
1. Пользователь заходит в совй профиль
2. Пользоваетль нажимает на "добавить мероприятие"
3. Система выдает форму для заполнения информации о известном пользователю мероприятии
4. Пользователь вводит требуемую информацию и нажимает потвердить
5. Система отправляет информацию на дополнительную проверку
6. По результатам проверки, система добавляет мероприятие или отклоняет его

**Альтернативный сценарий**

**(1)** Если пользователь не авторизован, система предлагает войти в свой аккаунт

**(4)** Если пользователь вводит некорректную информацию, система сообщает об этом и предлагает повторное заполнение формы

---
## Функциональные требования
1. Пользователь должен иметь возможность авторизоваться на сайте или войти без регистрации
2. Пользователи, не зарегистрированные на сайте, не могут присоединяться к диалогам и обсуждениям
3. Пользователи, не зарегистрированные на сайте, не могут добавлять информацию о мероприятиях
4. Программа должна удалять информацию о прошедших событиях с карты и сохранять в архив
5. Сайт должен работать в последних версиях браузеров Chrome, Firefox, Safari
6. Программа не должна допускать дублирование событий
7. Пользователь должен иметь возможность проводить поиск необходимых ему мероприятий и событий по всему множеству хранимых данных
8. В случае отсутствия результатов, удовлетворяющих запросу пользователя, вывести соответствующее сообщение
9. Программа должна предоставить пользователю результат запроса в виде точек на карте с пометками и списком событий
10. Пользователь должен иметь возможность добавить информацию о своем мероприятии
11. Программа должна предоставить поля для заполнения информации: такие как название мероприятия, время, дата, адрес, общая информация о мероприятии, информация об организаторе
12. Программа должна проверять на корректность входные данные
13. Программа должна сохранять введённые пользователем данные о мероприятии в базе данных
14. Если информация о мероприятии размещается не с корпоративных аккаунтов или с не подтверждённых на сайте аккаунтов, программа должна отправлять данные на дополнительную проверку

---
## Нефункциональные требования
1. Веб сайт не должен загружаться более 10 секунд
2. Поиск мероприятия по корректным данным не должен занимать более 2 секунд
3. Сайт должен работать 24/7 за исключением редких технических работ в течении года
4. Сайт должен открываться как на мобильных устройствах, так и на ПК или ноутбуках
5. Сервер должен восстановить данные, сохраненные при последнем резервном копировании, если произошел сбой

---
## Компонентная модель
![](https://github.com/thendray/EventSharing/blob/main/img/digramm.png)

---
## Архитектура

![](https://github.com/thendray/EventSharing/blob/main/img/newArch.png)

### Референсная модель
Мы выбрали для использования MVC(Model-View-Controller). Структура архитектуры MVC разделяет приложение на три основных группы компонентов: модели, представлении и контроллеры. Это позволяет реализовать принципы разделения задач. Согласно этой структуре запросы пользователей направляются в контроллер, который отвечает за работу с моделью для выполнения действий пользователей и (или) получение результатов запросов. Контроллер выбирает представление для отображения пользователю со всеми необходимыми данными модели.


![](https://github.com/thendray/EventSharing/blob/main/img/mvc.png)

---

### Azure

Поскольку сервер предполагается деплоить на Azure Cloud, разумным будет рассмотреть для использования компоненты референтной архитектуры, которые он представляет

Сервисы, предлагаемые Azure, которые могут подойти:

Azure Spring Cloud – платформа, обеспечивающая взаимодействие микросервисов между собой и интеграции их в экосистему Azure

Azure Monitor – мониторинг работы приложения, анализ нагрузки и поиск «узких» мест в архитектуре, удобное чтение логов

Azure Application Insights, компонент Azure Monitor, — это расширяемая служба управления производительностью приложений (APM) для разработчиков и специалистов по DevOps. Используйте ее для мониторинга ваших работающих приложений.

Azure Pipelines – сервис, реализует механизмы непрерывной интеграции и поставки (CI/CD), необходимые для выявления и ликвидации ошибок на этапе разработки и внедрения изменений в продукт, в том числе продакшн версию

Azure Gateway – сервис для балансировки нагрузки трафика на модули сервера, оптимизации путей поставки контента и защиту сервера от вредоносных атак

[Архитектура, предлагаемая Microsoft](https://docs.microsoft.com/en-us/azure/architecture/solution-ideas/articles/azure-devops-continuous-integration-and-continuous-deployment-for-azure-web-apps)

Наше решение
![](https://github.com/thendray/EventSharing/blob/main/img/arch.png)


### Docker
Образ приложения на Docker Hub - https://hub.docker.com/repository/docker/korbis5/eventsharing

Запуск приложения на любой машине с установленным Docker:
docker run -d -p 5001:443 korbis5/eventsharing:0.0.3
