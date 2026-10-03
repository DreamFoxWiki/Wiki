---
icon: square-terminal
layout:
  width: default
  title:
    visible: true
  description:
    visible: false
  tableOfContents:
    visible: true
  outline:
    visible: true
  pagination:
    visible: true
  metadata:
    visible: true
  tags:
    visible: true
  actions:
    visible: true
  anchors:
    visible: true
---

# Команды

{% hint style="info" %}
На этой странице собраны команды, доступные всем игрокам.\
Почти все команды начинаются с префикса "**/"**, их необходимо вводить в чат[^1] <img src="../../.gitbook/assets/image (524).png" alt="" data-size="line">
{% endhint %}

### Команды общения <img src="../../.gitbook/assets/image (419).png" alt="" data-size="line">

<table><thead><tr><th width="218"></th><th></th></tr></thead><tbody><tr><td><mark style="color:orange;"><strong>!текст</strong></mark></td><td>Отправляет текст в глобальный чат</td></tr><tr><td><a data-footnote-ref href="#user-content-fn-2"><mark style="color:orange;"><strong>текст</strong></mark></a></td><td>Отправляет текст в локальный чат с ограниченным радиусом действия</td></tr><tr><td><a data-footnote-ref href="#user-content-fn-3"><mark style="color:orange;"><strong>/t</strong></mark><strong> , </strong><mark style="color:orange;"><strong>/m</strong></mark></a></td><td>Отправляет личное сообщение другому игроку</td></tr><tr><td><a data-footnote-ref href="#user-content-fn-4"><mark style="color:orange;"><strong>/do</strong></mark></a></td><td>Описание действий от третьего лица</td></tr><tr><td><a data-footnote-ref href="#user-content-fn-5"><mark style="color:orange;"><strong>/try</strong></mark> </a></td><td>Выполняет действие с вероятностью 50/50, то есть <mark style="color:green;">(Успешно)</mark>, или <mark style="color:red;">(Неуспешно)</mark></td></tr></tbody></table>

### Команды действия <img src="../../.gitbook/assets/image (420).png" alt="" data-size="line">

<table><thead><tr><th width="221"></th><th></th></tr></thead><tbody><tr><td><mark style="color:orange;"><strong>/coin</strong></mark></td><td>Подбрасывает монетку, выпадает «Орёл» или «Решка»</td></tr><tr><td><mark style="color:orange;"><strong>/afk</strong></mark></td><td>Включает/выключает состояние AFK. На нашем сервере состояние AFK помогает <a data-footnote-ref href="#user-content-fn-6">пропустить ночь</a></td></tr><tr><td><mark style="color:orange;"><strong>/lay</strong></mark> </td><td>Переводит игрока в положение лёжа. В данном положении игрок считается лежащим на кровати.</td></tr><tr><td><a data-footnote-ref href="#user-content-fn-7"><mark style="color:orange;"><strong>/ползать</strong></mark></a></td><td>Переводит игрока в положение ползания. Так же в это положение можно перейти смотря себе под ноги, нажимая дважды Shift.</td></tr><tr><td><mark style="color:orange;"><strong>/sit</strong></mark></td><td>Переводит игрока в положение сидя</td></tr><tr><td><a data-footnote-ref href="#user-content-fn-8"><mark style="color:orange;"><strong>/spin</strong></mark></a></td><td>Игрок начинает кружиться на месте, сопровождается визуальными эффектами</td></tr><tr><td><mark style="color:orange;"><strong>{pos}</strong></mark></td><td>Поделиться координатами в чате</td></tr><tr><td><mark style="color:orange;"><strong>{i}</strong></mark></td><td>Отправляет в чат ссылку на предмет, который вы удерживаете в руке</td></tr><tr><td><a data-footnote-ref href="#user-content-fn-9"><mark style="color:orange;"><strong>[Кнопка]</strong></mark></a><mark style="color:orange;"><strong>{...}</strong></mark></td><td>В чате появляется кнопка, при нажатии на которую открывается скрытый текст с ссылкой (предмет, координаты, текст и т.д). Важно, чтобы между кнопкой и действием в {} скобках не было пробела.</td></tr><tr><td><mark style="color:orange;"><strong>/disc burn</strong></mark></td><td>Записывает кастомную музыку на пластинку. <a href="kastomnaya-muzyka.md">Подробнее</a></td></tr><tr><td><mark style="color:orange;"><strong>/алхимия</strong></mark></td><td>Команда плагина для смешивания зелий. <a href="alkhimiya.md">Подробнее</a></td></tr><tr><td><mark style="color:orange;"><strong>/art</strong></mark></td><td>Команда плагина для рисования картин. <a href="arty-i-kak-ikh-delat.md">Подробнее</a></td></tr><tr><td><mark style="color:orange;"><strong>/автовход</strong></mark></td><td>Привязка своей лицензии к серверу. Если есть лицензия, то сервер становится для вас лично лицензионным. </td></tr></tbody></table>

### Косметические команды <img src="../../.gitbook/assets/image (525).png" alt="" data-size="line">

<table><thead><tr><th width="221"></th><th></th></tr></thead><tbody><tr><td><a data-footnote-ref href="#user-content-fn-10"><mark style="color:orange;"><strong>/шляпа</strong></mark></a></td><td>Надевает предмет, находящийся в руке, на голову</td></tr><tr><td><mark style="color:orange;"><strong>/skin</strong></mark></td><td>Устанавливает скин. <a href="../../tekh.-chast/ustanovki/ustanovka-skina.md">Подробнее</a></td></tr></tbody></table>

### Команды для отключения функций <img src="../../.gitbook/assets/image (526).png" alt="" data-size="line">

<table><thead><tr><th width="221"></th><th></th></tr></thead><tbody><tr><td><a data-footnote-ref href="#user-content-fn-11"><mark style="color:orange;"><strong>/msgtoggle</strong></mark></a></td><td>Включает / отключает возможность получения личных сообщений</td></tr><tr><td><mark style="color:orange;"><strong>/отключитьфантомов</strong></mark></td><td>Отключает спавн фантомов для вашего персонажа</td></tr><tr><td><mark style="color:orange;"><strong>/sit toggle</strong></mark></td><td>Отключает возможность садиться на блоки через ПКМ</td></tr><tr><td><mark style="color:orange;"><strong>/sit playertoggle</strong></mark></td><td>Отключает возможность садиться на голову игрока через ПКМ</td></tr></tbody></table>

[^1]: Открывается нажатием клавиши T (англ.)

[^2]: Если ваше сообщение никто не увидит, об этом будет уведомление в чате

[^3]: <mark style="color:orange;">Пример:</mark> **/m** puppy (ник игрока) у тебя сегодня такой забавный скин

[^4]: _/do Погладил пушистую кошечку мурлышку по голове._&#x3164;ㅤㅤㅤㅤㅤ<mark style="color:orange;">Результат:</mark> **\*puppy** (ник игрока) погладил пушистую кошечку мурлышку по голове

[^5]: <mark style="color:orange;">Пример:</mark> **/try** попытался чмокнуть большую кошку в носик.ㅤㅤㅤㅤ<mark style="color:orange;">Результат:</mark> **\* puppy** попытался чмокнуть большую кошку в носик <mark style="color:red;">**(Неуспешно)**</mark> _\*видимо убежала\*_

[^6]: Оно не засчитывает вас как спящего, но не учитывает как бодровствующего, тем самым сокращая кол-во людей необходимых для пропуска ночи. Также, даже если Вы уже лежите в кровати/находитесь в аду или краю, то прописывание /afk всё равно поможет скипнуть ночь.

[^7]: ![](<../../.gitbook/assets/fox-bellyflop (2).png>)

[^8]: ![](<../../.gitbook/assets/spin-fox (1).gif>)

[^9]: Пример: <mark style="color:orange;">\[Нажми на меня]</mark>{/art preview Raiden}\
    \
    ![](<../../.gitbook/assets/image (410).png>)

[^10]: Так же предмет можно просто переместить в слот головы в инвентаре персонажа

[^11]: Игрок с ником [Schmierrohrlinge](../../istoriya-servera/legendy-proekta.md#schmierrohrlinge) пишет вам непристойности про сыр в ЛС? Просто отключите получения личных сообщений
