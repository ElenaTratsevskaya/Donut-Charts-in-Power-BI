# Donut-Charts-in-Power-BI
Transforming Donut Charts in Power BI from Power BI Masterclass

</br></br>
<div id="header" align="center">
<img src="https://user-images.githubusercontent.com/71708626/110930907-702e6d80-8308-11eb-8b03-9c4ad447bcf8.png" title="powerBI" width="60" height="60"/>&nbsp;
<img src="https://avatars.mds.yandex.net/i?id=0306d580613d24b96d174bd747f0550cde2a5d3b-12620487-images-thumbs&n=13" title="Medium" width="242" height="60"/>&nbsp;
</div></br></br>

Визуализация выполнена на основе статьи [medium.com](https://medium.com/microsoft-power-bi/from-boring-to-brilliant-transforming-donut-charts-in-power-bi-chap-1-0f00c3a571d6) <br> 
опубликованной в [Power BI Masterclass](https://www.linkedin.com/company/microsoft-power-bi-masterclass/posts/?feedView=all) <br><br> 

Кольцевая как и Круговая диаграмма имеет широкие возможности настройки. Можно менять угол поворота, управлять размером кружка отверстия, это помимо цветовых настроек и положения меток. Большой диапазон по выводу данных, главное сама процент посчитает. Если ввести абсолютные значения, то не надо делать меры. <br> <br> 

*Стандартная кольцевая диаграмма* <br> 
![Для VC-1](https://github.com/user-attachments/assets/2e74c746-b781-450b-9fbf-d21ec5acd823) <br><br>

Статья "From Boring to Brilliant: Transforming Donut Charts in Power BI: Chap -1" в Power BI Masterclass рассказывает о творческом подходе к привычному виджету.<br> 

✴️ Идея выглядит простой:<br> 
копи-паст построенной диаграммы > уменьшение размера каждой следующей и настройка цвета секций в ней > создание карточек вместо меток данных. <br> 

*Трансформированная кольцевая диаграмма*<br> 
![Для VC-2](https://github.com/user-attachments/assets/82c54e2c-8efb-412b-8f93-9281b930d1d2)<br> 

Итак!<br>
✅ Неожиданно.<br>
✅ Вместо меток данных крупно выведены карточки с показателями. Иные возможности управления читаемостью.<br><br>

▶️ Я отказалась от условных обозначений, т.к. цвет черты в карточке эту опцию выполняет, на мой взгляд. Минус ещё один элемент в конструкции.<br>
▶️ Не соблюдала одинаковую толщину колец, как рекомендует автор, умышленно. Так возникает эффект перспективы, уходящей к центру.<br>
▶️ Добавила карточки с % показателями, всё-таки назначение круговой диаграммы показывать именно доли.<br><br>

🔻 Трудоёмко, особенно построение колец.<br>
🔻 Критично по количеству выводимых параметров. В статье 4, так и рекомендует автор. У меня 5, по-моему, это предел. А вот в стандартных виджетах можно до 7.<br><br>

✴️ В любом случае новые возможности известного инструмента. <br>

Для трансформации использована круговая диаграмма из проекта, опубликованного здесь ранее <br> 
[DA-Power-BI-project_Financial-analysis-with-forecast-construction-](https://github.com/ElenaTratsevskaya/DA-Power-BI-project_Financial-analysis-with-forecast-construction-) 
<br> <br> 
Файл pbix прикрепляю.



