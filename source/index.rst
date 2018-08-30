Блокчейн-платформа для пострения цифровых экосистем
===================================================

.. raw:: html

   <iframe width="560" height="315" src="https://www.youtube.com/embed/0yFkO963Wjc?rel=0&amp;showinfo=0" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>
   <br>
   <br>
   <br>


О документации
--------------

Документация содержит описание |platform| — блокчейн-платформы для построения цифровых экосистем.

Документация содержит актуальное описания функциональности платформы и постоянно обновляется при внесении исправлений и добавлении новых опций.


История DayLight, eGaaS, Apla и Genesis
---------------------------------------

|platform| основан на коде блокчейна криптовалюты DCoin, созданной в 2011 году основателем проекта. 


DayLight
^^^^^^^^

Работы по созданию текущей версии платформы начались в начале 2016 года в рамках проекта **DayLight**. 

Усилиями работы нескольких программистов к осени 2016 года были реализованы основные протоколы сети, создан легкий клиент, разработана концепция контрактов и выпущены начальные версии языков программирования контрактов и  шаблонизатора. 


eGaaS
^^^^^

Поскольку платформа исходно разрабатывалась для реализации проектов в области e-Government, то было принято решение о смене названия проекта на **eGaaS** (*Electronic Government as a Service*). 

В начале весны была запущена тестовая сеть и на ее базе до и осени 2017 года был выполнено несколько проектов в статусе proof-of-concept для ОАЭ, Индии, Люксембурга (регистрация бизнеса, управление контрактами, земельный реестр, цепочка поставок, регистрация автомобилей и др.). 


Apla
^^^^

Летом 2017 года командой проекта было принято решение создать на базе платформы публичную блокчейн-сеть с юридической поддержкой аккаунтов (не останавливая работу над пилотами в сфере e-Government). Для нового проекта было выбрано название **Apla** (по-гречески "просто").

Обрели свои имена и программный клиент — *Molis*, а также языки программирования контрактов — *Simvolio* и шаблонизатора — *Protypo*. 

В это же время была запущена процедура рефакторинга исходного кода: был полностью переписан программный клиент (на базе библиотеки JavaScript React),  сделана новая версия REST API v2, существенно переработаны языки *Simvolio* и *Protypo*, разработан и реализован функционал выделенных экосистем, начата работа над визуальным конструктором страниц и проведены некоторые другие изменения и дополнения. 


Genesis
^^^^^^^

К концу 2017 года стало очевидно, что платформа может вступись в конкурентную борьбу и с существующими полностью публичными сетями типа Ethereum, NEO и др. Таким образом сформировался еще одни проект на основе кода платформы — **Genesis**, который запускается без проведения ICO с распределением токенов среди программистов — пользователей GitHub.



Contents
========

.. toctree::
   :maxdepth: 2

Contents
========

.. toctree::
   :maxdepth: 2
   :caption: Обзор

   concepts/about-the-platform.rst
   concepts/faq.rst
   concepts/thesaurus.rst


.. toctree::
   :maxdepth: 2
   :caption: Руководство

   introduction/script.rst
   introduction/templates2.rst
   introduction/appexample.rst
   introduction/vm.rst
   introduction/install.rst


.. toctree::
   :maxdepth: 2
   :caption: Справочная информация

   reference/api2.rst
   reference/update_client.rst
   reference/desync_monitor.rst


.. toctree::
   :maxdepth: 2
   :caption: Дополнительно


   introduction/mobile.rst
   introduction/contractsignatures.rst


.. todolist::