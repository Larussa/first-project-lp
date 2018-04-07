# THOMAS RHYTHM

#### Используемые в проекте технологии
* Библиотека JavaScript - jQuery (в том числе и Tabs) 
* Google maps - для подключения Google карты 
#### Плагины
* ***slick-slider*** - стилизация карусели
* ***slick-nav*** - стилизация мобильного меню
* ***show header on scroll*** - для прокрутки меню по всем страницам сайта
#### Шрифты и иконки
1. Font-Awesome - иконочный шрифт
2. Шрифты:
* Dosis : 300, 400
* Open Sans: 300, 400
#### Стандартные компоненты и классы
#### Компоненты
###### 1. Стилизируем заголовки:
```scss /* или css */
.title.title-white
.title.section-title 
.title.section-title-light 
.title-small
```
###### 2. Стандартные кнопки:
```scss /* или css */
.btn
.btn[disabled]
.btn.btn-default
.btn.btn-xs 
.romb-icon
.romb-icon.black-icon 
.romb-icon.white-icon 
.romb-icon.transparent-icon
```  
###### 3. Отступы между стандартными блоками:
```scss /* или css */
.default-section
.small-section
.container 
.container-fluid
```

###### 3. Стилизируем стандартную текстовую информацию:
```scss /* или css */
.text-default
``` 
##### Классы

###### 1. Выравнивание элементов по горизонтали и вертикали:
```scss /* или css */
.text-center
.text-right
.text-justify
.m-auto
```    
##### 2. Цвет для фона:
```scss /* или css */
.bg-black
.bg-grey
```
##### 3. Стилизируем ***табы***: 
* Табы в ***.default-section .services***
```scss /* или css */
#tabs
#tabs .tabs-nav li
#tabs .tabs-nav li span 
#tabs .tabs-nav .icon-title 
.tabs-nav .ui-state-active span 
#tabs .tabs-nav .icon 
#tabs .tabs-panel 
```
##### 3. Стилизируем ***Skills***  **.default-section .about-studio**:

```scss /* или css */
.team-item .team-item-skills
.team-item-skills p 
.title.section-title.skills-title 
.team-item .team-item-img:hover .team-item-skills
.skill-item span 
.skill-item
.progress-wrapp 
```
- для анимации скилов
```scss /* или css */
.progress-wrapp .progress 
.progress-wrapp .progress.branding 
.progress-wrapp .progress.design 
.progress-wrapp .progress.development
.progress-wrapp .progress.photography
.team-item .team-item-img:hover .block1 .branding 
.team-item .team-item-img:hover .block1 .design 
.team-item .team-item-img:hover .block1 .development 
```
##### 3. Стилизируем элементы формы:
```scss /* или css */
.form-control 
.textarea.form-control 
.form-control[disabled], 
.form-control.disabled 
.form-control.error 
.form-info 
.form-info .fa 
.form-info span 
```

##### 4. Стилизируем карусель
 ```scss /* или css */
.reviews-carousel .icon 
.reviews-carousel p
.reviews-carousel .review-author
.slick-dots
.slick-dots li
.slick-dots li button
.slick-dots li+li
.slick-dots li.slick-active 
.slick-arrow
.slick-arrow.slick-prev
.slick-arrow.slick-next
.slick-arrow.slick-next .carousel-button
.slick-arrow .carousel-button .fa 
.slick-arrow.slick-prev .carousel-button .fa
.slick-arrow.slick-next .carousel-button .fa
.slick-arrow .carousel-button
```    
    
##### Основные компоненты 
 
1. .header
 ```scss /* или css */
.header .logo 
.header .header-nav
.header .header-nav li 
.header .header-nav li+li 
.slicknav_menu 
```

2. .inner

 ```scss /* или css */
.inner::before 
.inner-content
.inner-content h1 
.inner-content span
.inner-icon 
```

3. .about-studio

 ```scss /* или css */ 
.about-studio .about-studio-text 
.about-studio .team-item 
.about-studio .team-item .team-item-info 
.about-studio .team-item .team-item-img
.team-item .team-item-skills
.team-item-skills p 
.title.section-title.skills-title
.skill-item span 
.skill-item 
.progress-wrapp 
.progress-wrapp .progress 

``` 

4. .about-studio

 ```scss /* или css */ 
#tabs 
#tabs .tabs-nav 
#tabs .tabs-nav .icon
#tabs .tabs-nav .icon-title
.tabs-nav .ui-state-active spa
```

5. .lets-talk

 ```scss /* или css */ 

.lets-talk-content 
.lets-talk-content p 
.lets-talk .lets-talk-img
``` 

6. .portfolio

 ```scss /* или css */ 
.default-section.portfolio
.text-portfolio 
#portfolio-tabs 
#portfolio-tabs .portfolio-tabs-nav
#portfolio-tabs .tabs-content .portfolio-item 
.tabs-content .portfolio-item img 

```

7. .why-choose-us
 ```scss /* или css */ 
.why-choose-us .why-choose-us-features 
.why-choose-us .title 
.why-choose-us .title-small
.icon-why-choose-as .icon 
```

7. .reviews
 ```scss /* или css */ 
.reviews-carousel 
.reviews-carousel .icon 
.reviews-carousel p 
.reviews-carousel .review-author 
.slick-dots 
.slick-arrow 
.slick-arrow.slick-next .carousel-button
.slick-arrow .carousel-button
```

8. .latest-news 
 ```scss /* или css */ 
.latest-news .title-link
.latest-news .news-item .news-item-info
.latest-news .news-item .news-item-date
.news-item .news-item-img
.latest-news .news-item .news-item-img img
.news-item .news-item-img, .news-item .news-item-img
.news-item .btn
```

9. .subscribe
 ```scss /* или css */ 
.subscribe form .form-control
.subscribe .form-info
```

10. .contacts
 ```scss /* или css */ 
.contact-item .contact-item-content 
.contact-items-wrapper
.contact-item-content span.contact-title
.contact-item-icon
.contact-item-content span.contact-data
.contact-item .contact-item-content span
.contact-form
.contact-form .form-col
.form-row 
.contact-form .form-info-submit
.contact-form .form-info
.contact-form .form-control+.form-control
```

11. #map
 ```scss /* или css */ 
#map
.map-container
.map-container .on-map-block
.map-container:hover .on-map-block
.map-container .on-map-block::before
.map-container .map-info 
.map-container .map-info .title.map-title
```

12. .footer
 ```scss /* или css */ 
.footer
.footer .footer-logo
.footer .footer-nav
.footer .footer-nav li
.footer .footer-nav li+li
.footer .footer-info .footer-copyright
.footer .footer-info .footer-date
.footer .footer-info span
```
##### Основные контрольные точки media-запросов

    @media (max-width: 1199px) - устройства c разрешением до 1199px
    @media (max-width: 991px) - устройства c разрешением до 991px
    @media (max-width: 767px) - устройства c разрешением до 767px
    @media (max-width: 599px) - мобильные устройства c разрешением до 599px
    @media (max-width: 479px) - мобильные устройства c разрешением до 479px
##### Структура папок и их содержание

Название папки  | Содержание папки
----------------|----------------------
css       |Стили к проекту
js       |Java Scripts, подключаемые к проекту
img   | Готовые картинки к проету
fonts       |Шрифты


* **Папка CSS** 

Название файла  | Содержание файла
----------------|----------------------
style.css       |Файл каскадной таблицы стилей, в который производится сбока необходимых стилей
grid.css       | Основные стили колонок сайта
et-line.css   | основные стили для иконок 
slicknav.css       | Основные стили slicknav меню
fontawesome.css | Стили иконочного шрифта
index.html      | Индексный файл для проверки вносимых изменений

* **Папка JS** 

Название файла  | Содержание файла
----------------|----------------------
google-maps.js       |Файл подключения карты Google
header-scroll.js       | Файл подключения скролинга хедера
init.js   | Файл инициализации плагинов
jquery.slicknav.min.js       | Файл подключения плагина slicknav меню
scroll-to.js | Файл подключения плагина slicknav в мобильной версии
