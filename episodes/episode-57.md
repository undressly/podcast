# Выпуск №57. 27 февраля 2017

Safari TP24, браузеры в 2017, кастомные свойства, make great again, новый HTML-заголовок, нервный опенсорс, W3C против WHATWG.

- Ольга Алексашенко
- Вадим Макеев
- Алексей Симоненко

[Слушайте на SoundCloud](https://soundcloud.com/web-standards/episode-57), [обсуждайте в Слаке](https://web-standards.slack.com/messages/podcast/).

## 00:12 События

- [Видео с Rolling Scopes в Минске](https://youtu.be/CGfnGczxKAI?list=PLe--kalBDwjiiVq-AxoChmYbArhioKhQw)
- [Pitercss №10 в Питере](https://pitercss.timepad.ru/event/442550/)
- [Moscowcss №1 в Москве 2 марта](https://moscowcss.timepad.ru/event/443474/)
- [Frontend Fellows №11 в Ижевске 3 марта](https://frontendfellows.timepad.ru/event/448864/)
- [React Amsterdam 21 апреля](https://react.amsterdam/)
- [Выигрышная ошибка](https://github.com/pitercss/pitercss.com/issues/10)

## 05:04 Safari TP24

- [Release Notes for Safari Technology Preview 24](https://webkit.org/blog/7423/release-notes-for-safari-technology-preview-24/)
- [Статья](ссылка)

## 08:43 Как работают браузеры в 2017

- [Optimising the front end for the browser](https://dev.to/sanjsanj/optimising-the-front-end-for-thebrowser)
- [Оптимизация фронтенда под браузеры](https://habrahabr.ru/company/badoo/blog/322988/) - перевод статьи в блоге компании Badoo на Хабре
- [How Browsers Work (2011)](https://www.html5rocks.com/en/tutorials/internals/howbrowserswork/)

## 18:56 Кастомные свойства

- [Трюк: раздельные функции CSS-трансформации](http://css-live.ru/tricks/tryuk-razdelnye-funkcii-css-transformacii.html)
- [PostCSS Transform Shortcut](https://github.com/jonathantneal/postcss-transform-shortcut)
- [CSS Custom Properties as your API](https://sgom.es/posts/2017-02-17-css-custom-properties-as-your-api/)

## 36:16 Make great again

- [Make as a front-end development build tool](http://eprev.org/2017/02/20/make-as-a-front-end-development-build-tool/)

## 45:28 Новый HTML-заголовок

- [Нужен ли нам новый заголовочный элемент?](http://css-live.ru/html5/nuzhen-li-nam-novyj-zagolovochnyj-element.html)
- [w3c/html: Add `<h>` element](https://github.com/w3c/html/issues/774)
- [Вложенные `<h1>`](https://jsbin.com/jucorev/edit?html,output)

## 59:36 Нервный опенсорс

- [Casper: No `lang` attribute](https://github.com/TryGhost/Casper/issues/286)

## 01:14:00 W3C против WHATWG

- [What is the difference between the W3C and the WHATWG?](https://redd.it/5swe9b)
- [HTML Living Standard](https://html.spec.whatwg.org/multipage/)
- [HTML 5.1 W3C Recommendation](https://www.w3.org/TR/html51/)
- [Логотипы WHATWG](https://resources.whatwg.org/)

---

**Оля.**
Привет, с Вами 57 выпуск подкаста «Веб-стандарты» и его постоянные ведущие Вадим Макеев и Алексей Симоненко из HTML Academy.

**Вадим.**
И Ольга Алексашенко - верстальщик руками из EXANTE.

## 00:12 События

**Вадим.**
Прошлый выпуск мы записывали на [Rolling Scopes в Минске](https://youtu.be/CGfnGczxKAI?list=PLe--kalBDwjiiVq-AxoChmYbArhioKhQw).
Было очень интересно, я там посмотрел на Акселя Раушмайера, на Виталия Фридмана, в очередной раз, и мне очень понравилось.
Там было очень много зарубежных докладчиков, много русскоязычных.
Основной поток был, в основном, по-английски, но меня на него поставили докладывать по-русски.
В общем, вывод такой - это был мой первый Rolling Scopes и мне очень понравилось.
Наверно, можно назвать второй главной конференцией в Белоруссии.
Первая, конечно-же Web Standards Days, ну ладно, можем назвать Rolling Scopes местной отличной конференцией двухдневной.
Я обязательно приеду в следующий раз, мне понравилось.

Мы провели [Pitercss №10](https://pitercss.timepad.ru/event/442550/) 21 февраля в офисе Selectel, видео и слайды выложим вместе с подкастом в понедельник.
Представляете, видео смонтировали, довольно быстро даже.
Трансляция, как обычно не завелась, нам наверно надо плюнуть на это дело уже, ну ладно, будем пытаться.

Pitercss №11 пройдёт уже 21 марта, не знаю почему тоже 21-го, но вот так. Всё пройдёт в офисе SIB Russia<!-- TODO: Уточнить название локации -->.
Мы доклады на эту встречу, неверно, уже не ищем, потому что прислали нам много чего за последнее время.
Но мы продолжаем искать на следующий, потому что у нас на апрельскую, по-моему, докладов ещё нет.
Так что обязательно пишите если вы в Питере или хотите заехать посмотреть на то, какая красивая в Петербурге весна.

На этой неделе мы поедем в Москву на [Moscowcss №1](https://moscowcss.timepad.ru/event/443474/) в Москве с Лёшей и 2 марта, собственно, пройдёт конференция, ладно, конференция громко сказано - митап.
Там уже есть 2 доклада в программе.
CSS-методологии Алексея Охрименко, то что он читал на WSD в Питере, видео откуда пока...пока его нет.
И про несколько фишечек CSS, про которые вы могли не знать, расскажет Людмила Мжачих.
И третий доклад, я думаю, мы анонсируем на этой неделе, откроем еще немножко регистраций.

[Frontend Fellows №11](https://frontendfellows.timepad.ru/event/448864/) пройдёт  в Ижевске 3 марта на следующий день после московского Moscowcss №1.
Радостно, что эта идея растёт и живёт.
Там, в основном, будут говорить, конечно, про React и всякие `WebVR`, но я думаю они когда-нибудь они дойдут до полноценного фронтенда во всю ширь тематическую.

Ну и Reackt в Амстердаме, напоминаем, 21 апреля, и в прошлом выпуске, если помните, мы обещали разыграть билет и кто-же, кт-же его выиграл?

**Лёша.**
Может быть, сначала обсудим вообще что же нам прислали, насколько плохо мы сделали сайт?

**Вадим.**
Ну да.
Мы попросили в прошлом выпуске посмотреть на сайт [pitercss.com](https://pitercss.com/) - на сайт конференции, которая пройдёт 16 июня в Питере и поискать какие-то ошибки.
И прислали, по моему, 8 ошибок нам, из которых много чего мы обязательно поправим.
Большинство, в общем-то, прям ошибки найдены.
Самые большие ошибки у нас, кажется, в Internet Explore и в Edge потому что мы по <!-- TODO: Неразборчиво --> верстали плохо поглядывая на другие браузеры операционных систем.
Но в общем сайт для разработчиков, думали мы, и так сойдёт, да?

**Лёша.**
Ну да. Ну а что ты говоришь такими уловками: «плохо поглядывали». Да не поглядывали.

**Вадим.**
Я тестировал в Edge на виртуальной машине, но вот чё-то видимо не хватило.

**Лёша.**
Ну и кстати, там ведь не только 8 ишьей прислали - там их больше.
Просто именно те кто хотят поехать в Амстердам, потому что, конечно, нам прислали ещё небольшая пачечку ишьей от ребят, которые не хотят поехать в Амстердам, и им нравится там где они сейчас.

**Вадим.**
Ну да, может быть для кого-то проблемы не в стоимости билета, а в том что, не знаю, Амстердам это слишком далеко или React это не так интересно как хотелось бы.
В общем, разные штуки, где-то иконки, где-то там какие-то полосочки, где-то там атрибут `require` в Safari не работает.
Ну, разные-разные штуки, там, выравнивание кнопок.
Но, самым интересным нам показалось, баг, который не просто такая косметическая штуковина, а которая мешает смотреть сайт с самого начала, сайт неправильно загружается.
Мы забыли поставить `initial-scale` на вьюпорте, мы просто написали `width=device-width`.
Соответственно, страница загружаясь, конечно, принимает вьюпорт, но по умолчанию скейлится как минимум в мобильном Edge, мобильном IE неправильно.
Поэтому, виктория из Санкт-Петербурга предложила нам добавить initial-scale=1 и была совершенно права
И поздравляю Вас, Виктория, езжайте в Амстердам на React Amsterdam и напишите нам, мы Вам выдадим промо-код, бесплатно получите билет.

## 05:04 Safari TP24

**Лёша.**
Safari Technology Preview 24 показали на этой неделе.
Они прям всё чётко делают каждую среду через одну среду, и в этот раз не забыли. Показали много интересного в этой версии.

Показали `Perfomance API` - это возможность прокидывать какую-то статистику, собирать её в более удобном виде.
Её можно, например, отправлять во всякую аналитику, в свою собственную статистику, или самим собирать, в общем, удобная штука, которой в Safari не было.

Добавили `<link preload>` как экспериментальную фичу, но вроде как я видел обсуждение в Twitter, что хоть это и фича экспериментальная, но вроде как она не за флагом, а включена сразу же, что-то такое было, вот.
И, конечно, самое большое, ну прости, Вадим, я понимаю, что это не для тебя самое большое, но самое большое для всех остальных - это то что добавили динамические импорты для ES6 модулей.
Это, всё-таки, важно и Safari тут, что странно на самом деле, показывается таким идущим впереди всех браузеров.

Ну и конечно же куча всего поправили, я уже даже сталь мельком читать эти чейнджлоги, потому что уже хочется чтобы они зарелизили Safari 10.1 и уже дали бы поиграть нам.
Потому что, ну сколько можно, когда они обещали - в марте?
А, они же не обещали, да, а есть только какие-то спекуляции?

**Вадим.**
Ну есть уже бета-версии Mac OS и iOS в которой этот Safari Technology Preview просто встроенный обычный браузер Safari и в общем, в принципе, есть какое то расписание у этих бет.
То есть можно примерно представить у них там релиз-кандидаты этих бет и разные-разные состояния.
То есть можно в принципе прямо сейчас поставить и получить свои динамические импорты.
Но, я думаю, лучше дождаться конечно финального и предположения про март вполне себе обоснованы

**Лёша.**
Не, ну динамические импорты это, конечно, хорошо что они появятся в Safari, но это не то ради чего мы ждём его.
Потому что ты же не сможешь их использовать сразу сейчас если у всех остальных браузеров всё отвалится.
Я бы, конечно, хотел, но увы не могу.

**Вадим.**
Ну как, подожди, если у меня работает, значит, у всех заработает.
Разве не так?

**Лёша.**
А, ну это ты как с вёрсткой pitercss.com

**Вадим.**
Ну, типа того.
Меня в этом релизе больше всего, конечно же, порадовал `<link preload>`, потому что вы можете не пользоваться всякими трюками, скриптами и прочим для предзагрузки ресурса, а можете их вполне себе удобно планировать.
Там ведь можно подгружать картинки, можно подгружать шрифты, стили, и так далее, и оно всё очень хорошо работает в браузере если вы  понимаете что на странице потребуется что-то другое или третье.
Как мы раньше подгружали картинки, помните?
Это скрипты Macromedia, в `img.src` создавался объект и загружался, ну в общем, безумные способы мы всегда использовали, а тут вполне себе удобная штука и браузер про неё с самого начала знает.
Он читает в шапке и понимает, что какой-то ресурс нужно предзагрузить, а не вы используете какие-то хаки, чтобы заставить браузер, поэтому он может планировать.
Соответственно, когда браузерные алгоритмы изменятся, соответственно, изменятся и алгоритмы `<link preload>`, потому что они будут учтены при изменениях.
Вот главный плюс встроенных фич в браузер, что они образуют единую систему, а не вам нужно на каждые изменения браузера подстраивать вот эти свои трюки и хаки.

## 08:43 Как работают браузеры в 2017

**Оля.**
На этой неделе вышла огромная статья Санджая Пурсвани [Оптимизация фронтенда для браузеров](https://dev.to/sanjsanj/optimising-the-front-end-for-thebrowser).
Действительно, огромная, очень подробная, очень, такая вот, чётко всё рассказывающая статья на английском языке пока, но, наверняка, кто-нибудь переведёт в скором времени.
Я когда её читала, конечно, у меня возникло впечатление, что это было сказано уже 10 лет назад всякими корифеями нашего фронтенда.
Но, тем не менее, если вы новичок - это очень хорошее руководство о том как сделать загрузку ваших сайтов гораздо быстрее.

**Вадим.**
Мне эта штука напоминает скорее такое, знаете, исследование, которое Санджай провёл для того чтобы оптимизировать фронтенд какого-то своего проекта.
То есть он сел и скомпилировал, и изучил вообще всё что на эту тему есть, и вот в виде такой штуки сделал.
В принципе, из неё можно сделать чек-лист, довольно легко по структуре.
Там это 6 шагов: оптимизация от HTML до конечной отрисовки.
Поэтому, наверно, это действительно просто пути оптимизации его собственного проекта, и подобные исследования можно взять за основу если у вас есть новый проект, и вы готовы, и вы хотите сделать его лучше, видимо можно, вполне себе, пройтись по  этой статье и понять, что вы можете сделать, что вы уже сделали.
Оно, действительно, напоминает многие другие исследования, то есть там «как работает браузер», и доклады, и статьи были, и много чего интересного я на эту тему читал.
Обычно все эти статьи огроменные и вот эта вот тоже на них похожа.
Но, в целом, я бы, наверно, не рекомендовал прям новичкам, потому что новичкам лучше, конечно, полагаться на то как браузер сам всё оптимизирует и идти по спецификации, допустим.
А вот если вы прям вот серьёзно взялись оптимизировать, то это такое комплексное решение, ещё и с картинками если вам понимание важно, а не просто сухой чек-лист.
Так что, интересный труд.
Я прям вижу в каком-нибудь блоге Mail.ru на Хабре переведённое в ближайшие пару недель, потому что ребята оттуда берутся переводить очень большие статьи и прям вот такие монолитные штуки выходят.
Вот недавно	Эдди Османи труд про [оптимизацию старта JavaScript](https://habrahabr.ru/company/mailru/blog/321748/) вот тоже в мэйловском блоге. Так что ждём, ребята, перевода.

**Лёша.**
Ты думаешь, что ребята из Mail.ru просто нас слушают и статьи переводят?

**Вадим.**
А что, нас кто-то не слушает, подожди?

**Лёша.**
Ладно, Бог с ним.
На самом деле, я не согласен с тобой.

**Вадим.**
Первый раз.

**Лёша.**
Угу, вот так новость!
Ты просто говоришь, что новичкам ты не советуешь, а я не знаю.
Мне вот кажется что, ты вот просто говоришь, что «отдать на откуп браузеру, он там сам всё оптимизирует».
Но тут ведь немножко глубже, тут не какие-то трюки, которые тебе нужно делать чтобы на несколько наносекунд всё было быстрее. Нет!
Тут же просто оптимизация от глубокого понимания как оно всё работает.
То есть, что за чем начинается, где когда что останавливается, что когда кого ждёт там и так далее.
И когда ты это понимаешь, это не какая-то конкретика, это когда у тебя есть это понимание ты просто более правильно используешь те вещи, которые ты знаешь и, не знаю, ты можешь впихнуть стили куда угодно, заинлайнить всё подряд или в `base64` сделать картинки все и вставить их прямо в контент или, я не знаю, всё скриптами, кучу файлов сделать.
Это вот новичок легко может сделать и браузер ему тут не поможет, и какое-то общее понимание что за чем идёт, мне кажется, оно полезно.

**Вадим.**
Мне кажется, что  новичку не стоит знать про дерево рендеринга и про всякие `CSS Object Model` и прочие истории, потому что есть ведь другая крайность.
Можно ведь увлечься и переоптимизировать всё настолько, что сделать очень много ручной работы, которой в итоге занимается браузер.

**Оля.**
Мы перед выпуском говорили, что на этой неделе у всех бомбит.
Вот у меня сейчас просто бомбануло, Вадик, от твоих слов, серьёзно!
Нет, новичку обязательно надо знать как работает браузер, как он рендерит страницу, прям вот, я считаю, что это первое что он должен узнать, потому что это базовая какая-то вещь.

**Лёша.**
Это не практическое какое-то руководство, а именно понимание.
То есть, как работает тот инструмент с которым они собираются работать ближайшие несколько лет.

**Вадим.**
Наверно, у нас разное с вами понимание про новичка.
Для меня новичок - это человек, который вчера ничего не знал про браузеры, а сегодня сел и написал свою первую страницу.
Видимо, для вас новичок это человек, который уже может сверстать что-то, сделать что-то, и, в принципе, он уже может работать, но он мало что знает, да?

**Оля.**
Знаешь, мне кажется, что есть некая разница.
Мы, наверно, с Лёшей рассматриваем образование более фундаментально, да?
То есть нужно дать фундамент новичку прежде чем он начнёт делать свою первую страницу.
А ты, видимо, идёшь от практики.

**Вадим.**
Ну да, я просто с самого начала и шёл от практики.
Я думаю, все сидящие здесь начинали с того что они просто пробовали, методом тыка понимали что как на самом деле работает.
И это, естественно, кажется нам более естественным путём развития обучения.
Но если прям лезть в такие хорошие большие статьи, наверно, она может, если её грызть по кускам - вот её масштабы тоже немножко могут ошеломить - если её грызть по кускам, типа «сегодня я пошёл шаг первый - я знаю как работает HTML», наверно, она зайдёт.
Просто, правда, монолитная такая большая штуковина.

**Оля.**
Ну, честно, мне не показалось что это какая-то Rocket science, какие-нибудь основы сетей, которые дают в любом университете гораздо сложнее.
А здесь, ну прям, всё очень просто.

**Лёша.**
Просто посмотри на то как разбирают вот каждый этот этап.
И тут же он и советы даёт.
Например, подключать стили в начале, а скрипты в конце.
Ну, какой здесь Rocket science?
Это понятно, так и надо делать.
Ты просто исходишь из мысли того, что новички это и так откуда-то узнают.
А может они это узнают как раз отсюда.
Или ты хочешь чтобы они подключали скрипты наверху, а стили внизу?

*Вадим.*
Не, я хочу чтобы была отдельная статья, типа «Пишем HTML правильно».
Через неделю: «Пишем CSS правильно» и так далее.
А вот это вот большое монолитное, монолитный труд: «Мои 6 шагов к быстрому рендерингу страницы», - они могут ошеломить.
Вот, только об этом.

**Лёша.**
Как ты объяснишь разницу в джаваскриптовых подключений просто с атрибутом `async`, с атрибутом `defer` если ты не понимаешь?
Там вся разница за счёт того как происходит рендеринг страницы.
Иначе не объяснишь.
Ты сказал про 6 этапов, но на самом деле 6 этапов это только половина статьи.
Вторая половина статьи она про нетворкинг, который не про эти 6 этапов, а про то что эти 6 этапов проходит каждый ресурс, и как эти ресурсы подключаются, как они встраиваются в этот процесс, как они в этой пачке появляются.
И это тоже важно.
То есть, какие ресурсы когда браузер подключает, почему основное правило выносить - всё кроме важных стилей и важных скриптов куда-то в асинхронные, загружать картинки после, загружать дополнительные скрипты после, стили загружать после, по возможности, шрифты, обязательно, после загружать.
Это ж всё почему так происходит?
Потому что есть понимание того как браузер это загружает.
А почему это важно - потому что каждый кусочек этого ресурса будет проходить все эти 6 этапов.
И чтобы показать вашу страницу, нужно пройти через всё это.
Это достаточно сложно, долго, и когда у тебя есть вот это вот понимание, как это всё строится, тебе потихонечку становится легче.
И более того, на тех же самых базовых интенсивах Академии, Вадим, на первой лекции, объясняется как браузер работает.
Вот эта вот любимая статья: «Что делает браузер, когда я ввожу URL-адрес?», - там ведь куча всего.
И про нетвокинг там объясняется.
Это очень рано, да, люди, возможно, только что, я не знаю, статьи на журфаке писали.
А сейчас им рассказывается какая-то жесть.
Ну, без этого никуда, как иначе?

**Вадим.**
Ну, и если вам эта статья кажется знакомой, то вы возможно видели статью «Как работает браузер», Санджай упоминает её и, на самом деле да, есть совместно большая [статья на HTML5 Rocks](https://www.html5rocks.com/ru/tutorials/internals/howbrowserswork/), в общем-то есть и видео встроенное и он ссылается.
Поэтому, если вы читали ту самую статью 2011 года, господи, как давно это было, то, может быть, вы узнаете что-то новое из этой, потому что, видимо, она посвежее.
Тут упомянуты какие-то реализации, какие-то новые механизмы.
Ладно, уговорили, буду рекомендовать новичкам, отстаньте уже!

**Лёша.**
Ну, на самом деле, перевод был бы, и правда, здесь полезен, потому что она такая, она хорошая, здесь есть много очень простых концепций, а есть очень сложные концепции, типа, я не знаю, сколько байт в одном TCP-пакете и почему нужно пытаться укладываться в него и так далее, что вот уже to-match, но есть и простые концепции.

**Оля.**
Ну, в общем, мы желаем читателям не ошеломляться, а постараться это всё осилить.

## 18:56 Кастомные свойства

**Оля.**
Ну и к слову о Rocket science.
На CSS-live вышел перевод статьи [Трюк: раздельные функции CSS-трансформации](http://css-live.ru/tricks/tryuk-razdelnye-funkcii-css-transformacii.html) и вот я прям осилила, на самом деле, с трудом.
Тут весь смысл в том, что для CSS-трансформаций предлагается использовать CSS-переменные.
Я каждый раз когда вижу CSS-переменные вот эти вот в чистом виде, у меня просто мозг заклинивает и там что-то происходит, вообще очень сложно.
Вадим, может ты мне объяснишь на простых словах, что там происходит?

**Вадим.**
Ну, представь себе что, допустим, у нас есть свойство `background` а в нём есть там `url()`, координаты, повторять/не повторять, масштабирование и всё остальное.
И представь, что у нас нет отдельных свойств `background`: `background-color`, `background-position`, `background-repeate` и так далее.
Это очень неудобно.
Тогда нам приходится задавать одним свойством `background` и если мы хотим дополнить, то есть, в каком-то месте сменить координаты, в каком-то месте переключить повторение или ещё что-нибудь такое, картинку просто поменять - нам приходится переписывать всё свойство и дублировать код.
Это было бы очень неудобно.
И такая ситуация у нас, на самом деле, есть со многими свойствами, которые принимают несколько значений, разделённые пробелами, и отдельно эти значения не поменять.
По какой-то причине авторы спецификации не разделили их на части.
Из этого есть разные выходы.
Вот, допустим, свойство `transform` - его порубили на части и у нас есть отдельные функции `translate`, `rotate` и `scale`,  которые уже поддерживаются в Chrome Canary и когда-нибудь будут поддерживаться во всех остальных браузерах.
Допустим, вам нужно элемент повернуть: вам не нужно писать свойство `transform`, а сразу вы используете такое вот свойство, я не знаю, `rotate` и задаёте градусы, то есть не функцию.
Соответственно удобно.
У вас элемент уже повёрнут, допустим, он трансформирован как-то, а вам нужно его повернуть - вы берёте и добавляете поворот или меняете поворот, а не переписываете всё свойство.
И в этой ситуации, понятно что, помогают отдельные свойства, но отдельные свойства есть не для всех свойств, которые хочется разделить на части.
Отдельные свойства до сих пор не поддерживаются и, возможно, вместо отдельных свойств туда можно в эти функции прокидывать переменные и менять уже переменные.
Поскольку всё происходит в runtime а не PostCSS-ный вариант какой-нибудь, соответственно, вы получаете живые свойства, допустим, в этом случае с трансформацией.
Что интересно, из-за того что все эти `rotate`, `scale` и `traslate` они, на самом деле, в итоге складываются в матрицу, которая браузером пересчитывается динамически и изменяет положение объектов в пространстве вашей страницы.
Как бы вы там не меняли порядок применения этих отдельных свойств - `rotate`, `traslate` и `scale` - в итоге браузер, по-моему, всё равно применит как если бы вы записали их в порядке `traslate`, `rotate` и `scale`.
И в итоге, если вы туда прокидываете CSS-переменные, вы всё равно получаете определённый жёсткий порядок.
А если вы хотите прям вот менять порядок применения трансформаций, вам нужно уже внутри `transform` писать целиком свойства.
В общем, с одной стороны получается гибко, что мы можем менять отдельные свойства.
С другой стороны, получается, что мы всё равно не можем нормально управлять так же гибко, поэтому приходится менять свойства внутри `transform`.

**Лёша.**
Ты немного ошибся: там `translate`, `scale`, `rotate` - `scale` с `rotate` наоборот, ну, `translate`, я помню, что он первым всегда идёт.
И интересно, что эти вот отдельные свойства не позволяют отдельно ещё писать XYZ-координаты, то есть это пока не решено в спецификации.

**Оля.**
Ну на самом деле это вот первый случай который я вижу, где CSS-переменные очень годно применены.
Вот в остальных всех случаях, там, цвет ссылочки можно и так поменять, а здесь прям вот по делу.
Кстати, где они поддерживаются сейчас?

**Вадим.**
Во всех браузерах зеленоватых - браузерах которые часто обновляются они поддерживаются.
В ночных сборках, ладно, не в ночных - в тестовых сборках Edge уже поддерживаются кастомные свойства.
Так что всё хорошо.

**Лёша.**
Ну да, то есть во всех браузерах поддерживаются кроме Edge.
Edge на подходе.

**Оля.**
Ну, относительно.
Вы так говорите как будто IE 11 там никому не нужен и Edge обычный стабильный тоже никому не нужен.
На самом деле, там большая аудитория сидит.

**Вадим.**
На самом деле, скорее, в этих статьях и в похожих докладах или исследованиях мы просто нащупываем, как мы в итоге сможем применять CSS-переменные или кастомные свойства так, чтобы они имели смысл.
Потому что за ними чувствуется какая-то мощь и потенциал, но вот мы сейчас нащупываем зачем они нам нужны.

**Лёша.**
Мне кстати кажется что вот эта вот спецификация новая с отдельными свойствами для `transform` - это идеальный случай для [плагина на PostCSS](https://github.com/jonathantneal/postcss-transform-shortcut "PostCSS Transform Shortcut").
Вот прям по-моему лучше придумать нельзя.
Потому что ты хочешь использовать их уже сейчас, поведение никак не меняется, а меняется только синтаксис.
Но ты не можешь использовать их сейчас потому что ну только в Canary это поддерживается, в остальных браузерах фиг знает когда это будет.
И это очень похоже на `autoprefixer`.
То есть ты используешь раньше чем браузеры могут, но так как у тебя этот функционал и так есть, а тебе просто синтаксис нравится новый, вот, по-моему, идеальный вариант для PostCSS плагина, и по-моему он есть.

**Вадим.**
Да, плагин точно есть, но тут вот есть терминологическая сложность.
Я читаю свой доклад про ванильный CSS, называю вот эти такие штуки «сахаром», «синтаксическим сахаром».
Но ведь есть сахар который как бы совсем безобидный в ситуации вот с этим `transform` и отдельными функциями.
А есть сахар который убирает точки с запятой, скобочки фигурные и прочее.
Видимо, нам нужно разделить, придумать какое-то название, допустим, «синтаксический сахар» и «синтаксический сироп», или там не знаю, «синтаксический клей» какой-нибудь.
Ну, потому что некоторые вещи, вот как ты сказал, действительно, помогают писать удобнее, но по сути не меняют порядка применения и не мешают нам потом от исправлений с помощью PostCSS.
А некоторые прям сильно мешают и прививают какую-то зависимость от синтаксических решений.

**Лёша.**
Я не зря привёл в пример `autorefixer` потому что тут как раз таки именно то как используется он - вы используете его пока браузер не поддерживает, потом выкидываете и всё.
То есть максимально не думаете об этом.
И это то что будет в браузерах, поэтому я не знаю, стоит ли отдельно придумывать какое-то название тому, что никогда не будет в браузерах.
Ведь есть просто «по спеке» и «не по спеке».
Этого не достаточно?

**Вадим.**
Ну нет, просто мы смотрим на свойства какое-нибудь, функцию в CSS и думаем: «она по спеке».
Но то как она работает в итоге, мы либо используем её не полностью, и мы не используем её динамический потенциал, как с CSS-переменными, которые в PostCSS можно использовать сейчас - они будут статическими.
То есть как будто мы используем их, но на самом деле нет - мы используем только малую их часть и не самую мощную.
То есть тут в этом месте очень легко запутаться и в итоге потерять огромный потенциал фичи, когда она станет доступна динамически.

**Лёша.**
Я ещё хотел вернуться вот к этому решению на CSS-переменных.
Не знаю, мне оно кажется каким-то большим оверхэдом.
То есть, возможно, оно как пример как мы можем использовать кастомные свойства - Ок, но в плане применимости, вот в конкретном случае, ну это реально какой то оверхэд.
Потому что, что тебе мешает написать `transform` просто?
Ведь разницы никакой.
То что тебе нужно где-то в переопределениях повторить это - ну да, ну ничего страшного.
С другой стороны, если у тебя `autoprefixer` уже  стоит, и PostCSS уже стоит, то тебе вообще об этом думать не нужно.
Ты можешь просто это использовать сейчас.
А наворачивать эти кастомные свойства, у которых поддержка не такая хорошая как у `transform`, ну вот знаешь, решение оно такое, да, посмотреть как можно будет использовать когда-то в будущем CSS-переменные - Ок
Но вот для того чтобы использовать новые свойства для трансформации - вообще не нужно, мне кажется это даже контрпродуктивно.

**Вадим.**
Ну я помню, что я регулярно ошибался из-за того что мне приходилось такие монолитные свойства повторять, и потом я забывал в каком-то месте поменять значения - это приводило к ошибкам.
Там по `hover` надо сменить трансформацию, а ты её описал раньше, и тебе нужно её целиком скопировать и потом не забыть её поменять если вновь в первом месте меняешь тоже.
Но, на самом деле, в этой статье уже проклёвывается, проглядывается момент, когда мы можем начинать проектировать наши компоненты в CSS.
Не просто писать код, а проектировать, то есть заводить какие-то переменные в начале в контексте `root` или в контексте нашего компонента, продумывать их значения, обозначать их переменными, а потом уже использовать, менять и так далее.
То есть, это немножечко ещё архитектурный подход, когда у вас что-то сложное происходит, и вы можете обозначить это переменными а потом модифицировать, присваивать, переназначать и так далее.
Мне кажется, это сделает CSS более похожим на языки программирования, с одной стороны.
С другой стороны, мы не будем повторяться, мы будем допускать меньше ошибок.
Ну ладно, понятно что это всё направлено на будущее и...

**Оля.**
Не, ну подожди, препроцессоры нас этому уже научили, уже сколько лет этим препроцессорам?
Мы там делаем всё то же самое, точно так же проектируем.
Выделяем какие-то миксины, инклюды и так далее, считаем, делаем функции.
Просто сейчас это будет нативно, но, я думаю, многие уже и так умеют всё это делать.

**Вадим.**
Ну, проблема с подходом препроцессорным в том, что они сильно ограничивают возможность переопределения, доопределения, изменения динамического этих переменных.
То есть, они просто делают невозможным это.
Поэтому нам нужно сделать следующий шаг, понять что это может происходить динамически в runtime.
То есть, мы можем в зависимости от какого-нибудь `hover` взять и поменять очень много всего, не писать всю батарею кода, типа, в каком-нибудь `hover` ты можешь взять и изменить значение переменной, и у тебя весь предыдущий код изменится тоже, основанный на этой переменной.
Вот я к этому веду, мы этого пока не понимаем.

**Оля.**
Ну почему, ты с препроцессорами тоже ничего не пишешь, происходит компиляция и то что тебе там выдано.
Ну да, там кода больше, чем если бы ты написал нативно, но всё равно, когда ты пишешь CSS код, ты этого не делаешь.

**Лёша.**
Тут основная разница в том, что в препроцессорах ты получаешь в итоге CSS готовый, скомпиленный, а с кастомными свойствами ты получаешь возможность ими манипулировать прямо там, на странице в браузере.
С помощью JS, с помощью других изменений.
С препроцессорами ты этого не получаешь.
Это, в принципе, основная разница.
Там  есть ещё всякие разные штуки, типа как каскадность и всякой такой фигни.
Но ладно, давай это опустим.
Просто, ты не можешь манипулировать своими SASS-переменными из JS.
Не можешь ведь?

**Оля.**
Нет, но зачем это делать если ты можешь менять CSS.

**Лёша.**
Вот!
Зачем это делать?
Понимание зачем это делать ещё не пришло, потому что это то, что будет в будущем.
Сейчас нельзя это использовать, IE 11, как ты говоришь, не поддерживает, текущий Edge не поддерживает.
Поэтому никто даже пока не думает из, ну так, условно назовём это, практиков, кто каждый день фигачит лэндинги не думает о том как это им изменит потом их подходы.
Так как `flexbox`, ты долгое время не думала о них, а потом поняла и влюбилась в них, ну например.

**Оля.**
Нет, я хотела просто защитить нашу привычку к архитектурному подходу.
Она есть, и она есть уже много лет.
А то что в runtime этим можно пользоваться, ну, как бы, классно, но немножко разные вещи.

**Вадим.**
Ну вот у меня есть такой пример.
У нас на сайте, не знаю, есть 2-3 темы цветовые.
Сейчас чтобы иметь 2-3 темы на сайте нам нужно иметь 2-3 идентичных файла, больших файла, в которых написан CSS, в которых все цвета захардкожены, все их модификации захардкожены.
Три файла!
Когда переменные можно будет использовать динамически мы можем иметь один файл, а JS-ом просто выставлять на нужный элемент изменения переменной или подгружать другой CSS, в котором эта переменная изменена, допустим, и на основе этого файла, как шаблона,  динамически изменять тему сайта в зависимости от прокинутого цвета.
А внутри этого CSS - изначального CSS темы - уже там цветовыми функциями как угодно изменять, модифицировать и использовать на основе цвета. То есть, один файл против трёх файлов.
То есть, мы идём к динамическому использованию, переменному, как в JS.
Ведь мы в JS не объявляем переменные, нам потом транспайлер проходится и прописывает все значения, иначе это было бы, ну нереально.
JS бы так не работал просто.

**Оля.**
Три файла не нужны.
Делается класс внутри одного файла.
Класс на `<html>`, который переключает тебе темы.
Конечно, я согласна, резонно, что кода будет больше.
И когда CSS-переменные войдут уже в нашу жизнь плотно, конечно, всё будет лучше с точки зрения той же оптимизации, о которой мы говорили чуть ранее.
Нет, всё хорошо, просто пока немножко преждевременно.

**Вадим.**
Ну да, мы как обычно мечтатели здесь и хотим чтобы всё случилось раньше.
Но почему эти статьи ценны?
Потому что мы заранее начинаем понимать и продумывать, а не когда уже всё появится, а мы уже настолько привыкли к препроцессорам что нам и не нужно.
Ну, в общем, давайте, раз уж мы тут занимаемся образованием и новостями, не бояться фантазировать.
Ну и к моему слову про архитектурный подход: Серджио Гомес продолжил писать про кастомные свойства на этой неделе и написал статью, что [кастомные свойства это ваш новый API](https://sgom.es/posts/2017-02-17-css-custom-properties-as-your-api/ "CSS Custom Properties as your API").
Он здесь предлагает задуматься о том, что CSS теперь можно использовать не как инструкцию, в которой уже всё готово, её нужно подключить и уже на уровне HTML всё менять.
Ведь можно использовать CSS как шаблон, в который потом прокинуть переменную, и он приводит хороший пример, когда у вас, допустим, подгружается библиотека с сетками, в которой не обозначено количество колонок.
Или обозначено, но вы хотите его переопределить, соответственно, вы создаёте переменную `my-grid-columns-2` и у вас layout на этой странице двухколоночный.
А загрузили всего один файл CSS, и в HTML ничего менять не нужно, просто можете там стилем задать количество колонок на уровне вот этого.
Ведь можно переменную задавать в каждом блоке, то есть у вас на уровне `<body>` 2 колонки, а на следующем уровне, где вы переопределили эту переменную, тот же самый класс, один и тот же класс, допустим, `columns`, станет трёхколоночным, потому что на его уровне вы поменяли переменную.
То есть, удивительные вещи которые позволят нам, в итоге, разгрузить HTML от количества классов, которые мы в виде модификаторов расставляем, и задавать там конкретные переменные, и это очень-очень круто.
В общем, Серджио продолжает, с нетерпением ждём новых статей, потому что он очень классно разбирает кастомные свойства.

<!-- TODO: В работе
## 36:16 Make great again

## 45:28 Новый HTML-заголовок

## 59:36 Нервный опенсорс

## 01:14:00 W3C против WHATWG
-->