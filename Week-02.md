# A02: Приводим страницу в порядок

Приводим нашу веб-страницу в более приемлемый вид, а также публикуем изменения на сервер.

Когда: 30 августа 2015, 18:30 по Новосибирску.

Видео: [скачать в полном качестве](http://media.sunday-school.ru/SundaySchool-02-800p.mp4) или [смотреть на YouTube](http://www.youtube.com/watch?v=vPccLdv3IkU).


## Содержимое занятия 02

### Публикация изменений на наш сервер

Вам нужно:

1. Закоммитить изменения в Git, используя, например, приложение GitHub.
2. Сделать Sync (или Push), чтобы залить изменения на сервера GitHub.
3. Перейти по специальной ссылке, чтобы скопировать сайт с серверов GitHub на наш сервер:

    * http://sunday-school.ru/webhook/deploy/irina/minion
    * http://sunday-school.ru/webhook/deploy/sasha/site
    * http://sunday-school.ru/webhook/deploy/andreyo/toys
    * http://sunday-school.ru/webhook/deploy/school/www

Сами сайты:

* «Воскресная школа»: http://sunday-school.ru/
* «Минион», Ирина К.: http://minion.irina.sunday-school.ru/
* «Блог», Саша Т.: http://sasha.sunday-school.ru/
* «Toys4kids», Андрей О.: http://toys.andreyo.sunday-school.ru/


### Добавление видео с YouTube

Копируем кусок HTML из раздела Share → Embed. Размеры видео можно поставить произвольные.


### Меняем оформление

Темы для Boostrap:

* [Bootswatch](http://bootswatch.com/), рекомендуемый источник бесплатных простых тем.

    Отсюда нужно скачать `bootstrap.min.css` и заменить им соответствующий файл в проекте.

* [Bootstrap Live Customizer](http://bootstrap-live-customizer.com/), настройка тем вручную.

    Для этого нужно взять `variables.less` из любой темы, где он есть (в частности, с Bootswatch), вставить в сайт, потом поменять любые переменные.

    В итоге оттуда мы скачиваем `theme.min.css`, которую добавляем к проекту.

* [StartBootstrap](http://startbootstrap.com/), более сложные бесплатные темы.

    После скачивания темы нужно полностью заменить у себя все файлы Bootstrap на новые.

* [WrapBootstrap](https://wrapbootstrap.com/), платные темы.

    После покупки обращайтесь за инструкциями.

Подбор цветов:

* [Adobe Color](https://color.adobe.com/)


### Ручное изменение стилей

Вам могут пригодиться справочники на webref.ru:

* [Справочник стилей CSS](https://webref.ru/css)
* [Справочник тегов HTML](https://webref.ru/html)
* [Bootstrap — модульные сетки](https://webref.ru/layout/bootstrap/grid) и ее [адаптация для разных размеров экрана](https://webref.ru/layout/bootstrap/responsive)
* [Bootstrap — стили](https://webref.ru/layout/bootstrap/css)
* [Bootstrap — меню, вкладки и др. компоненты](https://webref.ru/layout/bootstrap/component)
