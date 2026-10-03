---
description: >-
  «Plasmo Voice» — это мод для голосового чата с системой позиционирования.
  Именно его мы используем для общения на сервере и прослушивания уникальных
  музыкальных пластинок.
icon: microphone-lines
layout:
  width: default
  title:
    visible: true
  description:
    visible: true
  tableOfContents:
    visible: true
  outline:
    visible: true
  pagination:
    visible: false
  metadata:
    visible: true
  tags:
    visible: true
  actions:
    visible: true
  anchors:
    visible: true
---

# Установка Plasmo Voice

{% hint style="warning" icon="comment-pen" %}
На данной странице будет приведен пример установки мода с использованием сайта [modrinth.com](https://modrinth.com/), но на других сайтах процесс аналогичен. Мы рекомендуем использовать только проверенные сайты, такие как: [curseforge.com](https://www.curseforge.com/minecraft) и [modrinth.com](https://modrinth.com)
{% endhint %}

## Загрузчик модов

Для работы модов могут требоваться различные загрузчики. На данный момент их существует огромное количество, но мы рассмотрим только два самых популярных: [**Fabric**](https://fabricmc.net/) и [**Forge**](https://files.minecraftforge.net). Выбор загрузчика зависит только от вас. Рекомендуем [**Fabric**](https://fabricmc.net/), так как моды для него обновляются и появляются гораздо быстрее.

После выбора загрузчика переходим на сайт создателей и скачиваем установщик на интересующую нас версию игры. Это может быть файл формата <mark style="color:orange;">`.exe`</mark> или <mark style="color:orange;">`.jar`</mark>. Открываем файл и производим установку клиентской версии.



<figure><img src="../../.gitbook/assets/Screenshot 2024-08-10 162534.png" alt=""><figcaption><p>Пример на fabric-installer.exe</p></figcaption></figure>

По завершению установки выбираем в лаунчере профиль запуска, соответствующий вашему загрузчику. В официальном лаунчере он находится в разделе «установки» или в нижнем левом углу на главной странице Minecraft. Все лаунчеры отличаются визуально, но подобное меню есть в каждом.

<figure><img src="../../.gitbook/assets/Screenshot 2024-08-10 163232.png" alt=""><figcaption></figcaption></figure>

### Скачивание модов

Переходим на сайт с [**модом**](https://modrinth.com/plugin/plasmo-voice). В фильтрах выбираем нужный загрузчик модов. Затем выставляем интересующую нас версию игры. Появляется мод для выбранного загрузчика под нужную версию игры, переходим на его страницу.

<figure><img src="../../.gitbook/assets/Screenshot 2024-08-10 135341.png" alt=""><figcaption><p>Выбираем загрузчик модов</p></figcaption></figure>

<figure><img src="../../.gitbook/assets/Screenshot 2024-08-10 135404.png" alt=""><figcaption><p>Выбираем версию игры</p></figcaption></figure>

<figure><img src="../../.gitbook/assets/Screenshot 2024-08-10 164907.png" alt=""><figcaption><p>Переходим на страницу версии мода</p></figcaption></figure>

### Зависимости модов

Открыв мод нужной версии, мы увидим раздел **Dependencies/Зависимости.**&#x20;

Обратите внимание на этот раздел, в нём указаны моды или библиотеки, без которых данный мод не будет работать. В нашем случае это [**Fabric API**](https://modrinth.com/mod/fabric-api/versions). Загрузку производим по такому же принципу.

<figure><img src="../../.gitbook/assets/Screenshot 2024-08-10 135436.png" alt=""><figcaption></figcaption></figure>

### Установка модов

Переносим загруженные моды в папку <mark style="color:orange;">`mods`</mark>. Быстрее всего перейти в неё можно, нажав на иконку «папки» в вашем лаунчере, если она есть. \
\
Либо используйте самый универсальный способ: в поисковой строке Windows, используя Win+S, введите <mark style="color:orange;">`%appdata%`</mark> — это откроет путь к месту, где есть папка <mark style="color:orange;">`.minecraft`</mark>, именно в ней хранится ваша игра и папка <mark style="color:orange;">`mods`</mark>.

<figure><img src="../../.gitbook/assets/image (422).png" alt=""><figcaption></figcaption></figure>

<figure><img src="../../.gitbook/assets/image (423).png" alt=""><figcaption></figcaption></figure>

<figure><img src="../../.gitbook/assets/image (424).png" alt=""><figcaption></figcaption></figure>

### Управление Plasmo Voice

После установки модов в нужную папку и запуска игры с необходимым профилем загрузчика модов, голосовой чат должен начать работать в игре. По умолчанию его можно настроить, нажав кнопку **V**. Посмотреть или изменить другие кнопки можно в настройках управления модом.&#x20;

{% hint style="warning" icon="comment-pen" %}
Для более детальной и удобной настройки модов рекомендуем использовать мод [modmenu](https://modrinth.com/mod/modmenu/versions)!
{% endhint %}
