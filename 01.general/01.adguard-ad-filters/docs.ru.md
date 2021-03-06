---
title: 'Рекламные фильтры AdGuard'
taxonomy:
    category:
        - docs
visible: true
---

*   [Введение](#introduction)
*   [Политика фильтров AdGuard](#policy)
*   [Участвовать в развитии фильтров AdGuard](#contribute)
*   [Фильтры AdGuard](#filters)

<a name="introduction"></a>
## Введение

This article is about filters that we create to be used in AdGuard and other ad blocking software (e.g. uBlock Origin). Every filter represents a set of rules in text format which are used by AdGuard apps and programs to filter advertising and privacy-threatening content (such as banners, pop-ups, trackers etc.). Rules specific for a particular Internet segment (German filter, Russian filter etc.), or serving a specific purpose (Social media filter, Tracking Protection filter etc.) are combined into one list — filter — and can be enabled/disabled all at once.

<a name="policy"></a>
## Политика фильтров AdGuard

Наша политика фильтров доступна [здесь](https://kb.adguard.com/ru/general/adguard-filter-policy).

<a name="contribute"></a>
## Участвовать в развитии фильтров AdGuard

Нам крайне повезло иметь вокруг себя сообщество, которое не только любит AdGuard, но и непосредственно поддерживает нас. Большое количество людей становятся волонтёрами и самыми различными способами помогают улучшить AdGuard для себя и всех остальных. Вы тоже можете помочь! Мы, в свою очередь, счастливы вознаградить наиболее активных членов сообщества. Так что же можно сделать? 

### Сообщать о проблемах

Мы полагаемся на сообщество в вопросе обратной связи по нашим фильтрам. Таким образом мы можем быть уверены, что наши фильтры всегда релевантны, и мы эффективно их обновляем. Чтобы сообщить о проблеме (незаблокированная реклама, ложное срабатывание), используйте этот [веб-инструмент](https://agrd.io/report).

### Предложить правило фильтрации

В нашем [репозитории фильтров на GitHub](https://github.com/AdguardTeam/AdguardFilters/issues) вы найдёте большое количество открытых задач. Каждая из них относится к проблеме на каком-либо сайте — пропущенная реклама, ложное срабатывание и т.д. — выбирайте любую и предлагайте в комментариях новые правила для фильтров. Инженеры фильтров AdGuard рассмотрят ваше предложение и добавят правило в фильтры, если оно окажется корректным.

Здесь вы можете найти [официальную документацию](https://kb.adguard.com/ru/general/how-to-create-your-own-ad-filters) по синтаксису правил фильтрации AdGuard. Вам потребуется ознакомиться с ней перед тем, как вы сможете создавать собственные правила фильтрации. 

### Другие способы помочь

У нас есть [специальная страница](https://adguard.com/contribute.html), на которой вы можете узнать больше о способах поучаствовать в развитии AdGuard.


<a name="filters"></a>

* **Базовый фильтр AdGuard** — убирает рекламу с сайтов на английском языке. Изначально основан на фильтре [EasyList](https://easylist.to) и доработан нами исходя из жалоб и пожеланий пользователей. [Посмотреть правила](https://filters.adtidy.org/extension/chromium/filters/2.txt)
* **Фильтр счетчиков и системы аналитики** — содержит наиболее полный список различных интернет-счётчиков и систем интернет-аналитики. Используйте его, чтобы избежать слежки за вашими действиями онлайн. [Посмотреть правила](https://filters.adtidy.org/extension/chromium/filters/3.txt)
* **Фильтр виджетов социальных сетей** — скрывает многочисленные кнопки «Мне нравится», «Поделиться» и подобные им интеграции с социальными сетями на популярных сайтах.
[Посмотреть правила](https://filters.adtidy.org/extension/chromium/filters/4.txt)
* **Фильтр раздражителей** — блокирует раздражающие элементы веб-сайтов, включая уведомления об использовании cookies, всплывающие сообщения внутри страниц и сторонние виджеты, не имеющие отношения к функциональности сайтов (но исключая виджеты и кнопки социальных сетей. Основан на фильтре Fanboy Annoyances List, но не дублирует его. [Посмотреть правила](https://filters.adtidy.org/extension/chromium/filters/14.txt)
* **Фильтр полезной рекламы** — разблокирует рекламу, которая может быть полезна пользователям. Подробнее об этом фильтре можете узнать на [его странице](https://kb.adguard.com/ru/general/search-ads-and-self-promotion). [Посмотреть правила](https://filters.adtidy.org/extension/chromium/filters/10.txt)
* **Русский фильтр** — убирает рекламу с сайтов на русском языке. Изначально за основу был взят фильтр [RU AdList](https://code.google.com/p/ruadlist/). В дальнейшем фильтр развивался самостоятельно, и на данный момент пересечений с RU AdList практически не осталось. [Посмотреть правила](https://filters.adtidy.org/extension/chromium/filters/1.txt)
* **Немецкий фильтр** — убирает рекламу с сайтов на немецком языке. Изначально основан на фильтре [EasyList Germany](https://easylist.adblockplus.org/) и доработан нами исходя из жалоб и сообщений пользователей. [Посмотреть правила](https://filters.adtidy.org/extension/chromium/filters/6.txt)
* **Французский фильтр** — убирает рекламу с сайтов на французском языке. Изначально основан на фильтре [Liste FR](https://forums.lanik.us/viewforum.php?f=91) и доработан нами исходя из жалоб и сообщений пользователей. [Посмотреть правила](https://filters.adtidy.org/extension/chromium/filters/16.txt)
* **Японский фильтр** — убирает рекламу с сайтов на японском языке. Изначально основан на фильтре [Fanboy’s Japanese](https://www.fanboy.co.nz/fanboy-japanese.txt) и доработан нами исходя из жалоб и сообщений пользователей. [Посмотреть правила](https://filters.adtidy.org/extension/chromium/filters/7.txt)
* **Голландский фильтр** — убирает рекламу с сайтов на голландском языке. Изначально основан на фильтре [EasyList Dutch](https://easylist.adblockplus.org/) и доработан нами исходя из жалоб и сообщений пользователей. [Посмотреть правила](https://filters.adtidy.org/extension/chromium/filters/8.txt)
* **Испано-португальский фильтр** — убирает рекламу с сайтов на испанском и португальском языках. Изначально основан на фильтре [Fanboy’s Spanish/Portuguese](https://www.fanboy.co.nz/fanboy-espanol.txt) и доработан нами исходя из жалоб и сообщений пользователей. [Посмотреть правила](https://filters.adtidy.org/extension/chromium/filters/9.txt)
* **Турецкий фильтр** — убирает рекламу с сайтов на турецком языке. Разрабатывается нами исходя из жалоб и сообщений пользователей. [Посмотреть правила](https://filters.adtidy.org/extension/chromium/filters/13.txt)
* **Китайский фильтр** — убирает рекламу с сайтов на китайском языке. Изначально основан на фильтре [EasyList China](http://abpchina.org/forum/forum.php) и доработан нами исходя из жалоб и сообщений пользователей. [Посмотреть правила](https://filters.adtidy.org/extension/chromium/filters/224.txt)
* **Экспериментальный фильтр** — предназначен для проверки некоторых новых правил фильтрации, которые потенциально могут вызывать конфликты или ломать работу сайтов. В случае успешной проверки правила из Экспериментального фильтра добавляются в основные фильтры. [Посмотреть правила](https://filters.adtidy.org/extension/chromium/filters/5.txt)
* **Фильтр мобильной рекламы** — блокирует рекламу на мобильных устройствах. Содержит все известные нам рекламные сети. [Посмотреть правила](https://filters.adtidy.org/extension/chromium/filters/11.txt)
* **DNS фильтр** — составлен из нескольких фильтров (Базовый фильтр AdGuard, Фильтр социальных сетей, Фильтр счетчиков и систем аналитики, Фильтр мобильной рекламы, EasyList и EasyPrivacy), и специально упрощён для лучшей совместимости с блокировкой рекламы на уровне DNS. Этот фильтр используется серверами AdGuard DNS для блокировки рекламы и трекинга. Узнать больше о блокировке на уровне DNS можно на [этой странице](https://adguard.com/ru/adguard-dns/overview.html). [Посмотреть правила](https://adguardteam.github.io/AdGuardSDNSFilter/Filters/filter.txt)