## 1. Dzmitry Melnikov
## 2. Contact Info:
* email: dmitry.melni@gmail.com
* [Telegram](https://tlgg.ru/@lAvarisel)
* [GitHub](https://github.com/lAvarisel)
## 3. Summary
    I want to start my career as a front-end developer by making it my main profession. I am ready to quickly learn, grow, so that over time it is possible to become a team leader.
## 4. Skills
* HTML
* CSS
* JS
* C#
* Pug, Less, Sass
* Git
* БЭМ
## 5. Code examples
[github](https://github.com/lAvarisel/mimusic.github.io/blob/master/src/blocks/page-news/page-news.pug)
```
    mixin page-news(text, mods)
    -
        var allMods = '';
            if(typeof(mods) !== 'undefined' && mods) {
            var modsList = mods.split(',');
            for (var i = 0; i < modsList.length; i++) {
                allMods = allMods + ' page-news--' + modsList[i].trim();
            }
        }
    section.page-news(class=allMods)&attributes(attributes)
        .page-news__inner
        block

    mixin page-news-sliderItem(data, mod)
    -
        let thisItemClass = 'page-news__sliderItem';
        let thisItemId = 'page-news__sliderItem_' + data.id;
        if(mod === 'active') {
            thisItemClass += '  page-news__sliderItem--active';
        }
    div(class=thisItemClass id= thisItemId)
        span.page-news__prefix= data.prefix
        h2.page-news__title= data.title
        img.page-news__rectangle(src=data.rectangle, alt='decorate')
        span.page-news__date= data.date
        p.page-news__content= data.content
        +btn('BUY TICKETS', 'page-news__btn')

    mixin page-news-item(data, mod)
    -
        let thisItemClass = 'page-news__item';
        let thisItemId = 'page-news__item_' + data.id;
        if(mod === 'active') {
            thisItemClass += '  page-news__item--active';
        }
    li(class= thisItemClass id=thisItemId)
        span.page-news__itemDate= data.date
        h2.page-news__itemTitle= data.title
        p.page-news__itemContent= data.content
        +btn('BUY TICKETS', 'page-news__btn')(class = 'page-news__btn_mobile')
```
## 6. Experience
* 2 years of work on a [project](https://github.com/lAvarisel) as a consultant
## 7. Education
* Belarusian National Technical University
* IT-Academy (HTML, CSS, JS)
## 8. English
    A2