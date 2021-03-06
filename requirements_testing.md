# Тестирование требований

Любой процесс начинается с требований, так и процесс разработки начинается с требований. Без документации, идеи и требований мы не можем приступить к работе и реализовать то, что хочет получить бизнес и пользователь.
Уровни требований 

Существует три основных уровня требований:
**Бизнес требования**
 **пользовательские требования**
**продуктные требования**

# Бизнес требования 
Это что-то, что необходимо нашему бизнесу, т.е. цель, ради которой создается наш продукт, для чего, какая польза и как получить с этого продукта прибыль. К примеру, у бизнеса есть цель создать некий сайт, который будет промоутить их продукцию. Это их основное бизнес требование.  
# Пользовательские требования
Дальше мы переходим на уровень пользовательских требований. Т.е., понятно, что этот сайт не будет существовать без пользователей, которые будут его использовать. Поэтому уровень пользовательских требований покрывает задачи, которые пользователь может выполнять с помощью продукта. Например, регистрироваться, общаться, искать информацию о продукте. Т.е. всё, что может выполнять наш пользователь. 
# Продуктные требования
Уровень продуктных требований - это то, как это все будет реализовано в нашем продукте с точки зрения разработки, учитывая контекст бизнес требований и контекст пользовательских требований. Он разделяется на функциональные требования (что наша система должна делать) и нефункциональные требования (как наша система должна это делать). Эти понятия взаимосвязаны с функциональным и нефункциональным тестированием.

**Пути выявления требований**

# Интервью
мы можем побеседовать с нашим заказчиком, бизнесом, либо пользователями, какой-то фокус группой, которая будет работать с нашим продуктом и узнать у них, что они хотят видеть в нем, узнать все эти требования.

# Наблюдение
Дальше, к примеру, уже существует какой-то продукт, который используется в той компании, которая заказала наши услуги, и мы пытаемся разработать какую-то новую версию этого продукта, более лучшую, поэтому мы можем понаблюдать за работой пользователей в этом продукте и выяснить, что их интересует, что бы они хотели улучшить в их продукте.

# Самостоятельное описание
 мы не знаем, как работает наш продукт, нет некоторых прототипов, тогда мы можем включить здравый смысл и самостоятельно описать эти требования, учитывая, например фазу интервью и наблюдение и написать их.

# Прототипирование
Если у нас, к примеру, есть некий сайт и мы разрабатываем конкурента этому сайту, то мы можем на него перейти и посмотреть, как он работает, как на нём реализованы те или иные функции, и также прописать их в наших требованиях.  

**Свойства требований**

# Завершённость 
Требование должно содержать всю информацию, необходимую для разработчиков, тестировщиков, либо других людей, которые будут с ним работать. Т.е. мы должны проверить то, что есть вся информация в этом требовании и мы не должны отвлекаться и переходить на другие требования, которые у нас есть в этой системе.

# Непротиворечивость
 К примеру, у вас есть некие картинки в вашем требовании, или mockup, шаблоны, которые будут реализованы в продукте в рамках этой функциональность, и есть текст, к примеру, exception’s критерии, которые есть у нас в user story (user story - это, по сути, критерии приёмки, т.е. те критерии, которые определяют, что наше требование реализовано в данной функциональности). И, к примеру, эта картинка, этот mockup не соответствует этому тексту, который написан в требовании. Вот это и значит, что данные в этом требовании противоречат между собой. То же касается различных таблиц. Либо же если мы знаем, что в каком-то требовании написано одно, а в другом требовании прописано совсем другое, возникает противоречие, такого быть не должно. Мы должны написать нашему бизнес-аналитику и сказать о том, что данное требование противоречит.

# Корректность 
 Требование должно четко указывать на то, что должно выполнять приложение. Не должно быть каких-то двусмысленных слов, т.е. система должна отрабатывать корректно. Мы должны ввести валидные данные. Мы должны четко понимать, какие именно данные мы должны ввести, если это валидные данные, и должно быть чётко прописано, что это буквы, либо же это цифры, либо же это десятичные дроби, либо же это спецсимвол, либо и то и другое. Всё это должно быть корректно прописано.

# Недвусмысленность 
Мы должны четко понимать, что в этом требовании у нас написано. К примеру, два человека смотрят на шестерку с двух сторон, один человек видит шестерку, а второй человек видит девятку, такого быть не должно. Мы должны все работать в одном информационном поле, в одном контексте.

# Проверяемость 
Требование должно быть однозначно проверенным на предмет того, выполняется оно или нет. Если вы понимаете, что вы не сможете это никак проверить, т.е. нет таких инструментов, тулов, то такое требование не нужно прописывать. Нужно обязательно сказать об этом бизнес-аналитику, либо продукт оунеру и придумать, как другим способом можно реализовать ту или иную функциональность. Есть такое определение “озолочение”. Если мы хотим реализовать в нашем продукте какую-то фичу, которая очень долго будет реализовываться и стоит очень больших денег, т.е. мы должны потратить как своё время, так и время разработчиков, также купить какую-то очень дорогую тулу, которая позволяет нам описать эту функциональность, тогда такое требование мы должны проверить на то, что действительно - необходима ли нам эта фича, соизмеримы ли затраченные силы с тем, что мы в итоге получим.

# Модифицируемость 
 Набор наших требований должен быть таким, чтобы его можно было легко модифицировать, при этом не изменяя требования в других местах. Очень хорошо, когда в требованиях нет ссылок на другие требования, мы должны стараться этого избегать. Мы должны проверять требования на то, что мы это требование в дальнейшем можем изменить так, чтобы оно не повлияло сильно на систему, и чтобы это изменение провести в максимально короткие сроки и с минимальными потерями.

# Прослеживаемость 
Наши требования должны быть прослеживаемыми, т.е. там должны быть, к примеру id у этого требования. Это требование обязательно должно быть взаимосвязано с другими требованиями, если всё-таки линки у нас есть, хотя это не особо рекомендуется использовать. Либо же, к примеру, мы можем привязать к этому требованию наш баг-репорт. Может быть это не сильно связано с этим требованием и прослеживаемостью, но вообще прослеживаемость всех артефактов в нашей системе должна быть обязательна. Также еще сюда можно отнести проранжированность, к примеру, если мы приоритезируем наши какие-то требования, что оно должно быть выполнено самым первым. Например, заказчику вот-вот прямо сейчас нужно, чтобы это требование было реализовано, тогда мы выполняем его первым. Т.е. проранжированность также сюда можно отнести.

Что мы можем первоначально сделать с нашими требованиями? 
Написать тест-кейсы
Написать тест-кейсы на требования, если мы не можем этого сделать, то возвращаемся к свойству требований “проверяемость”.
Задать вопрос
Мы можем задать вопрос нашему заказчику или аналитику, задаем уточняющие вопросы по нашему требованию или говорим , какое требование нужно переделать.

# Нарисовать схему
Есть интеллект-карты, такие, как наши презентации, mindmap. Берём наше большущее требование, разбиваем его на какие-то маленькие функциональности и каждую функциональность разбиваем еще на более мелкие. Тогда мы более четко понимаем вообще, что у нас прописано в требованиях, как мы можем с ними работать. А есть use-cases - это так называемые варианты использования, которые описывают все действия, которые наш пользователь может произвести, и реакцию системы на эти действия.

# Use-cases
У нас есть так называемые актеры, которые выполняют наши действия. Т.е. в данном случае у нас представлена система для написания каких-то квизов, и у нас есть администратор и студент. Дальше прописаны наши функциональности, которые мы реализовываем. Всё, что можно произвести внутри этого блока создания наших квизов. Администратор может логиниться в систему, управлять нашими квизами, добавлять их, удалять, апдейтить и т.д. Студент - регистрироваться, логиниться и т.д.

# User story 
User story - это, по сути, критерии приёмки, т.е. те критерии, которые определяют, что наше требование реализовано в данной функциональности.У нас есть описание нашей user story, что мы хотим получить в рамках этой функциональности. Как она пишется? Сначала мы пишем следующую фразу: “как участник конференции, как пользователь, я хочу иметь возможность регистрироваться онлайн для того, чтобы регистрироваться быстро и снизить количество бумажной работы”. Здесь есть три логических блока. Т.е., как пользователь, я хочу получить такую функциональность, которая позволяла бы мне сделать следующее. Дальше у нас прописан acceptance criteria - это критерии приемки. То, что у нас должно быть реализовано в нашем требовании в нашей user story для того, чтобы мы в дальнейшем смогли сказать, что ваша функциональность реализована. Что делает тестировщик? Он получает эту юзер стори и должен придумать тест-кейсы для каждого statement, который прописан в acceptance criteria для того, чтобы убедиться, что да, действительно, функциональность реализована правильно и все работает корректно. Т.е. мы берем каждый этот statement и проверяем его. Этим занимаются аналитики и продукт оунеры, т.е. написанием самих требований, поэтому наша задача проревьюить, протестировать сами требования на предмет того, что они соответствуют как свойствам хорошего требования, так и в принципе здравого смысла. 

# UI-mockup
Это шаблон для мобильного приложения, т.е. мы здесь подробно расписываем как выглядит каждая кнопка, какие поля есть в нем, что мы должны вводить, какие навигационные сообщения у нас выскакивают, т.е. этим занимается больше UI-дизайнер. Чаще всего шаблоны уже появляются после того, когда написаны требования, но также, к примеру, если заказчик проявит, скажем так, свою инициативу, и он хочет, чтобы действительно всё выглядело так, то он может предоставить уже разработанные шаблоны. Это может выглядеть просто в виде некой схемы, к примеру, там просто прописаны все блоки которые, у нас должны быть в нашем приложении и для каждого блока прописано, что должно быть на каждой из этих страниц, т.е. и такой вариант написания требований может быть. Иногда вообще это может быть просто клочок бумаги, на котором прописано, что я хочу получить то-то, то-то и то-то, просто как-то высокоуровнево, без каких-то уточнений на эту тему.

# Спецификации
Это такие документы, в которых тоже прописаны наши требования. Их написанием уже занимаются непосредственно бизнес-аналитики. Спецификациями проверяем точно так же. Мы находим требования, мы проверяем эти требования внутри спецификации согласно свойствам хорошего требования и выносим вердикт для того, чтобы в дальнейшем смогли это поправить и наше требование соответствовало всем необходимым свойствам.
