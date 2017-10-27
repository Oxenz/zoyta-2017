# zoyta-2017

***
##### Коротко о главном
`Responsive design maket together with flexible gulp config + desktop first + preprocessorCSS + git + Flexbox + BEM-nameing + svg-sprites`
***   

## Сборка :checkered_flag: 

Используем комманды `gulp dev` / `gulp build`   

---

Проект состоит из index.html

1. Раскладка страницы выполнена целиком на Flexbox
2. Без сбоев работает кроссбраузерно в (all Chromium engine), FF, IE+11, Edge
3. Проект можно удобно масштабировать, благодаря удачному применению BEM и грамотной организации классов, для svg графики подготовлена эффективная экосистема наследования и зависимостей лежащие в папке`stylus/global/`
4. Валидация HTML и CSS соблюдена, испытания велись на [w3c](https://validator.w3.org/nu/ 'Перейти в этом окне')
5. Ключевые особенности формирующие zoyta
	* Используется 3 типа шрифтов в 2-ух форматах .woff .woff2
	* Применяется семантическая разметка с соблюдением современных стандартов и правильным БЭМ именованием классов, папок, файлов.
	* Используется базовая стилизация по средствам CSS сложно стилизуемых `<select>`
	* Отдельное внимание стоит уделить веб графики — SVG, все иконки в векторе, построены на symbols-SVG-спрайте который подключается как внешний (#external) файл, это дает возможность создание неограниченного количества слепков нужных иконок и управлением стилями через CSS, но для работы в любимом всеми IE используется библиотека svg4everybody, если нужно обойтись без JS нужно использовать другой способ  #fragment identifiers связанный с встраиванием в тело html символьного спрайта с последующим обращением к нему через `<use>` thx SaraSoueidan :thumbsup:
	* Normalize.css лучше Reset.css все файлы .css правильно минифицированны

![maket-desktop](https://github.com/Oxenz/zoyta-2017/blob/master/img/pre/index-desktop-zoyta-2017.jpg "Макет главной страницы index.html")
![maket-mobile](https://github.com/Oxenz/zoyta-2017/blob/master/img/pre/index-mob-zoyta-2017.png "Макет главной страницы index.html")
![maket-tablet](https://github.com/Oxenz/zoyta-2017/blob/master/img/pre/index-tablet-zoyta-2017.png "Макет главной страницы index.html")
