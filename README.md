Тестовое задание, цель которого проверить уровень владения и освоения WordPress.
====

# Введение

Это очень простая задача. И все инструкции о том как это делать тоже присутствуют.

Цель задания - не столько проверить уровень знаний, сколько понять уровень стремления получить знания.

Для ее решения достаточно технического склада ума и настойчивости.

Вопросы можно и даже очень нужно задавать. Для этого есть специальный раздел https://github.com/systemo-biz/test/issues

Вы можете не решить задачу, но если мы увидим что вы умеете формулировать свои мысли и задавать вопросы - вы наш человек.

Если вы очень умны, но боитесь задавать вопросы (стесняетесь показаться глупым или просто не способны формулировать свои мысли в письменном виде) - то можно даже не пытаться. Даже если вы легко решите эту задачу, то не умение задавать вопросы - преградит ваш путь к развитию.

Готовы? Тогда вперед :) Смелость и любопытство вам в помощь! Ну и конечно мы ждем вопросы, на которые постараемся оперативно отвечать :)


# Задача
Сделать каталог фильмов и вывести по ним данные.

# Требования

# 1. База и модель

1.1. Ставим чистый WordPress на бесплатный хостинг типа http://www.hostinger.ru/ или https://www.openshift.com/

1.2. Поставить тему Unite http://wordpress.org/themes/unite (она несет на борту Bootstrap 3)

1.3. Сделать для темы дочку http://wpmag.ru/2013/dochernie-temy-wordpress/

1.4. Добавить новый тип записи Фильмы для создания базы фильмов. Можно использовать расширение CPT UI http://wordpress.org/plugins/custom-post-type-ui/

1.5. К фильмам добавляем таксономии: Жанры, Страны, Год и Актеры. Чтобы классифицировать фильмы по жанрам и др условиям. Можно использовать тоже расширение что в п.1.4

1.6. Добавляем 2 текстовых поля к типу поста Фильмы: Стоимость сеанса и Дата выхода в прокат. Лучше использовать расширение ACF http://wordpress.org/plugins/advanced-custom-fields/

1.7. Забить базу рыбой на 5-7 фильмов, разных жанров, стран, стоимости и т д - чтобы убедиться что наполнение работает

# 2. Представление

У нас есть данные которые мы храним на сайте. Но нам надо их как то показать людям :)

2.1. У каждого фильма после описания выводим "Страну" и "Жанр", а также "Стоимость" и "Дату выхода". Сделать это можно двумя методами, через правку шаблона дочерней темы и через хуки.

2.2. На странице отдельного фильма выводим через хук. http://wpcraft.ru/dobavlyaem-informatsiyu-o-zapisi-na-sajte-bez-pravki-shablona-cherez-huk-the_content-wordpress/

2.3.  На странице списка фильмов выводим через создание и правку шаблона. Нужно создать шаблон архива типа записи в дочерней теме. Подсказка тут http://truemisha.ru/blog/wordpress/template-hierarchy.html

# 3. Bootstrap

Bootstrap - это просто. Это самый короткий путь к тому чтобы понять как верстать грамотные и пуленепробиваемые сайты.
Вводная есть тут http://wpcraft.ru/kak-verstat-sovremennye-sajty-tratya-minimum-vremeni-bystro-obuchayas-srazu-krossbrauzerno-i-adaptivno-ili-kak-pravilno-ispolzovat-bootstrap/

3.1. Сделайте вывод 4-х блоков данных в форме сетки 2х2

3.2. Стоимость и дату оформите как label + иконку

3.3. К Жанру и Стране просто добавьте иконку.

3.4. Можете добавить оформления элементами Bootstrap на свой вкус. Если хотите нас поразить своим чувством эстетики :)
