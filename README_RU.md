DevOpsHQ — это небольшой проект с инструментарием для DevOps-разработчиков 
===========================================================================
This is welcome page of the DevOpsHQ project. You can see english documentation [here](https://devopshq.github.io).


***Содержание:***
- [Цели сообщества](#Introduction)
- [Ссылки на наши проекты](#Links)
- [О нас в Интернете](#About)
- [Контакты](#Contacts)


# Цели сообщества <a name="Introduction"></a>

Всем привет! [DevOpsHQ](https://github.com/devopshq) — это небольшой проект нескольких DevOps-разработчиков, где мы выкладываем инструменты, которыми пользуемся в нашей повседневной работе. Все инструменты под MIT-лицензией. Будем очень рады, если вы захотите поддержать нас своими коммитами! Контрибьютером может стать любой желающий :)

По любым вопросам можно обратиться к админам проекта: [Alexander Pazdnikov](https://github.com/apazdnikov), [Timur Gilmullin](https://github.com/Tim55667757) и [Aleksey Burov](https://github.com/orgs/devopshq/people/allburov). 

**Наша глобальная цель.** Сформировать открытые готовые решения для управления полным циклом процесса разработки, тестирования и смежных процессов, а также доставки, развёртывания и лицензирования продуктов:
1. Объединить в единую систему связанные знания о различных сборочных и деплойных методологиях, а также лучшие практики по доставке и развёртыванию программных продуктов.
2. Описать технологическую схему и реализовать инструменты для поставки продуктов: начиная от коммита строчки кода разработчиком, до разворачивания готового продукта на инфраструктуре заказчика.
3. Объединить в законченную систему различные решения в области Continuous Integration и Continuous Delivery, предлагаемые различными компаниями-разработчиками программного обеспечения и индивидуальными разработчиками. 
4. Объединить различные компании и разработчиков вокруг готового открытого продукта и системы с полными функциями управления разработкой.

**Главная нефункциональная цель.** Возможность развития инструментария и его использования каждым предприятием или человеком без любых ограничений, в том числе без патентных ограничений.


# Ссылки на наши проекты <a name="Links"></a>

***Опубликованные инструменты:***

**[ExampleProject](https://devopshq.github.io/ExampleProject/)** — это пример простого типового проекта в собществе DevOpsHQ с базовой функциональностью. Документация содержит в себе примеры и рекомендации для самостоятельной организации сборки любого нового проекта в сообществе DevOpsHQ. Сам проект имеет типовую структуру и сборку в Travis CI. Фактически, достаточно скопировать этот проект, заменить некоторые настройки и новый проект в сообществе готов к использованию!

**[CrossPM](http://devopshq.github.io/crosspm/)** — универсальный пакетный менеджер.

**[vspheretools](http://devopshq.github.io/vspheretools/)** — инструмент для управления виртуальными машинами на vSphere.

**[YouTrack Python 3 Client Library](https://devopshq.github.io/youtrack/)** — Python-клиент для работы с API YouTrack.

**[TFS API Python client](https://devopshq.github.io/tfs/)** — Python-клиент для работы с API Team Foundation Server от Microsoft.

**[A Python client for Artifactory](https://devopshq.github.io/artifactory/)** — Python-клиент для работы с API хранилища бинарных данных Artifactory.

**[FuzzyClassificator](https://devopshq.github.io/FuzzyClassificator/)** — нейро-нечёткий классификатор данных.

**[FuzzyRoutines](https://github.com/devopshq/FuzzyRoutines/)** — библиотека на python для работы с нечёткими шкалами, нечёткой логикой и нечёткими множествами.

**[FunnyTestPage](https://github.com/devopshq/FunnyTestPage)** — простой тест: сможете ли вы стать тестировщиком интерфейсов?

***Готовятся к публикации:***

**CrossBuilder** — система организации кросс-платформенных сборок Build As a Code, наподобие Travis CI, но независящая от используемой CI-системы (TeamCity, Jenkins, GitLab CI, Travis CI и прочих). 

**ChangelogBuilder** — генератор релиз-нотов с описанием изменений по продукту, который получает и агрегирует данные из различных трекеров (TFS, YouTrack, GitLab, JIRA и прочих). 

**pyteamcity** — свой доработанный python-клиент для работы с API TeamCity.

**MSI SDK** — SDK для создания msi.-пакетов и deb.-пакетов для инсталляторов продуктов.

**SupplyLab** — это Continuous Delivery система (GUS + FLUS + LicenseLab) для доставки продуктов, их обновлений и лицензий до инфраструктуры заказчика.

**pytest-testrail** — плагин для pytest, который умеет пушить результаты тестов в testrail.


# О нас в Интернете <a name="About"></a>

***Почитать про нас можно тут:***

- "[Личный опыт: как выглядит наша система Continuous Integration](https://habrahabr.ru/company/pt/blog/313616/)" (статья на Хабре)
- "[Миссия выполнима: как развить DevOps в компании со множеством проектов](https://habrahabr.ru/company/pt/blog/310584/)" (статья на Хабре)
- "[DevOps в современных ИТ уже давно выделился в самостоятельную инженерную дисциплину﻿](http://samag.ru/archive/article/3543)" (интервью в Системном администраторе)
- "[Автоматизация процессов разработки: как мы в Positive Technologies внедряли идеи DevOps](https://habrahabr.ru/company/pt/blog/343884/)" (статья на Хабре)

***Посмотреть на наши решения можно тут:***

- [Op!DevOps! 2016](https://www.youtube.com/playlist?list=PLEl1NAXHTFNxcKRN09VQThNbQ33neUyfn) — митап Op!DevOps! прошёл 7 октября 2016 г. в Москве. На нём в формате фаст-трека были озвучены проблемы в области автоматизации разработки и тестирования, а также предложены методы и средства их решения. 
    - "[Сообщество DevOpsHQ идеология и инструменты](https://www.youtube.com/watch?v=BeIeaeVVRbc&index=16&t=0s&list=PLEl1NAXHTFNxcKRN09VQThNbQ33neUyfn)" — анонс открытого сообщества Open DevOps Community. 
- [Op!DevOps! 2017](https://www.youtube.com/playlist?list=PLEl1NAXHTFNyUW3toSkHLL4Jl1cw4vWkc) — митап Op!DevOps! 2017 прошёл 21 октября в московском офисе компании Positive Technologies. Мы провели приятный субботний вечер и в узком, почти семейном кругу, обсудили проблемы автоматизации, которые удалось решить нашей DevOps-команде за прошедший год. Кроме того, мы рассмотрели некоторые технологии и инструменты, поделились планами развития DevOps. 
    - "[Развитие сообщества Open DevOps Community](https://www.youtube.com/watch?v=fYjV-eZlvVA&t=46s&list=PLEl1NAXHTFNyUW3toSkHLL4Jl1cw4vWkc&index=8)" — рассказали о развитии сообщества Open DevOps Community, показали опубликованные проекты за 2017 год, поделились планами развития сообщества. 


# Контакты <a name="Contacts"></a>

- По организационным вопросам можно обратиться к [Timur Gilmullin](https://github.com/Tim55667757): [tim55667757@gmail.com](mailto:tim55667757@gmail.com)   
- Наш телеграмм-канал: [https://telegram.me/devopshq](https://telegram.me/devopshq)
    - Немного [наших стикеров](https://telegram.me/addstickers/opdevops) для телеграмма :)
