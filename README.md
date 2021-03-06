# Знаете ли вы ООП?

Тема объектно-ориентированного программирования на протяжении многих лет \(десятилетий?\) является предметом жарких споров. Хорошо порывшись в интернете, можно найти десятки разных толкований, многие из которых утверждают взаимоисключающие вещи. Даже если вы попробуете задать вопрос "что такое ооп" десяти разным разработчикам, то, скорее всего, получите 10 разных ответов. Да, местами они будут похожи, но никто не даст формальных определений и в деталях все будет отличаться. Иногда, от людей уставших спорить, можно услышать "ООП у каждого свое", что в какой-то степени является правдой.

На неокрепшие умы такая ситуация влияет крайне отрицательно. Думаю не ошибусь если скажу что большинство людей, которые только начинают учить программирование на высокоуровневых языках, узнают про ооп раньше, чем запускают свою первую программу. Дальше в игру вступает сломанный телефон и в головах образуется каша.

Каждый год на популярных сайтах появляются статьи в стиле "вот что такое настоящее ооп" и рядом с ними "почему ооп не работает" или "я не понимаю ооп". Погуглите: "why oop is bad".

Попробуйте критически взглянуть на эту ситуацию. Как такое возможно? Почему настолько ужасная ситуация сложилась именно вокруг ООП? Почему никто не разоблачает автоматное, реактивное или функциональное программирование?

В этой книге я постараюсь максимально полно ответить на все вопросы, развенчать мифы, отделить мух от котлет, подвести формальную базу под интуитивные (и не очень) понятия. На протяжении всего повествования, я буду приводить примеры на совершенно разных языках: ruby, java, erlang, JavaScript, smalltalk, haskell, clojure и других. Основным языком повествования, при этом, я, все же, выбрал JavaScript в силу его широчайшей распространенности с одной стороны и удобством представления изучаемых концепций с другой.

### Структура книги

#### Первая часть

Чем ооп не является

#### Вторая часть

Вперед в прошлое

#### Третья часть

Чем ООП является

#### Четвертая часть

Паттерны

### На кого рассчитана книга

Книга рассчитана на тех кто уже, так или иначе, знаком с фразой "полиморфизм, наследование, инкапсуляция". Особенно она полезна тем кто уже активно программирует и хочет систематизировать свои знания. Новичкам я советую смотреть по ситуации. Там где имеет смысл, я буду кратко раскрывать понятия или давать соответствующие ссылки для самостоятельной подготовки к уровню материала.

### Авторский опыт

С 2007 года, я успел поработать в компаниях начиная от кровавого энтерпрайза и заканчивая небольшими стартапами, попутно, не раз, меняя стек разработки. За это время прошел путь от разработчик до технического директора, основал и развил несколько филиалов компаний, очно вырастил сотню разработчиков в рамках созданного центра обучения, создал и закрыл несколько аутсорс компаний и, в конце концов, вместе с Рахимом создал новый хекслет.

Во многом именно хекслет стал толчком к написанию этой книги.

### Дисклеймер

То что вы видите прямо сейчас - это черновик. Подразумевается итеративное развитие контента, поэтому в начале будет больше похож на сборник рандомных мыслей. Прошу понять и простить. Конструктивный фидбек (подкрепленный доказательной базой из компьютерных наук) всячески приветствуется. 

Общение по книге происходит здесь: http://slack-ru.hexlet.io в канале #computer_science


