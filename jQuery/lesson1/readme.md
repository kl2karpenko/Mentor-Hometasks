## DOM дерево

```javascript
  <div id="main">
    <nav class="navigation">
        <ul>
            <li><a href="#">Text 1</a></li>
            <li><a href="#">Text 2</a></li>
        </ul>
    </nav>

    <section id="sidebar">
        <p>Text etxtjbkb hgjvljh li lk kbkjhvhg</p>
        
        <div id="p">
            <span></span>
        </div>
        
        <ul>
            <li><input type="checkbox" id="ch_1"></li>
            <li><input type="checkbox" id="ch_2"></li>
        </ul>
    </section>
  </div>
```

## 1 task

Подключите jQuery, убедитесь в доступности объекта -библиотеки. Примечание: попробуйте подключение с разных CDN-хранилищ, и при помощи локального файла

#### Выведите в консоль:

1. Количество li на странице
2. Текст внутри первой ссылки на странице
3. Количество DOM узлов в блоке section
4. Значение id в блоке section
5. Значение класса в блоке nav

Откройте верстку http://codepen.io/htmllab/pen/NNaGOV

#### Выберите при помощи селекторов jQuery:

1. все HTML-элементы strong и окрасьте их в зеленый цвет
2. найдите все HTML-элементы em и добавьте им класс .selected
3. Найдите все элементы mark, которые находятся в div с классом row и задайте им класс .selected
4. Найдите все гиперссылки и удалите у них подчеркивания
5. Найдите все HTML-элементы, который содержат слово «Задания» и находятся в элементе с классом .container
6. Переключите элементы strong с классом some в состояние без этого класса, а тем элементам (strong), у которых небыло этого класса — добавьте.
7. среди набора элементов с классом .row удалите класс у второго элемента
8. прочитайте CSS-свойство color у второй гиперсылки в тексте

## 2 task

#### Выполните операции используя jQuery API:

1. Перезапишите текст во второй ссылке на странице на "Hello my friend"
2. Добавьте для блока навигации id="nav"
3. Закрасьте цвет текста в блоке #main в синий цвет
4. С помощью 1 селектора выберите все элементы, потом всем элементам сделайте цвет фона черным, а цвет текста - белым
5. Одной строчкой измените текст в 2 элементах сразу - в параграфе и в span который находиться внутри div#p на: "Text" 
6. Добавьте для элемента ch_1 свойство disabled=true
7. Элемент ch_2 сделайте полупрозрачным
8. Для чекбоксов добавьте атрибут value && name
9. Сделайте так чтобы первая ссылка на странице вела на главную страницу google.com
10. Добавьте атрибут title для всех ссылок на странице
11. Выведите есть ли у элемента section класс "red"

## 3 task

#### Поменяйте структуру DOM дерева используя jQuery API:

1. Все li внутри которых есть чекбоксы вынесите в верхий список внутри nav > ul
2. Удалите пустой списко ul
3. Перенесите параграф после блока div#p
4. В список ul добавьте в начал два элемента li внутри со ссылками на Википедию и на Megogo
5. Замените блок div#p на section#sectionMain
6. Оберните элемент #main в div#content

## 4 task

Дан инпуты. Переместите содержимое атрибута value в атрибут placeholder, а сам атрибут value удалите совсем.

## 5 task

Найдите все теги div, у которых в атрибуте class ровно 3 класса.

## 6 task

Дан элемент #test. Поменяйте этот элемент местами с его соседом снизу.

## 7 task

Представим себе, что атрибута placeholder не существует. Реализуйте свой placeholder (пусть его текст хранится в атрибуте data-placeholder).

Работа с data элементами в jQuery: https://api.jquery.com/data/

## 8 task

Все абзацы, внутри которых есть b, оберните в тег div

## 9 task

Найдите все абзацы p с классом .www, поставьте им в начало текст '!', затем добавьте к этим абзацам еще и заголовки h1-h6 и покрасьте эти абзацы и заголовки в красный цвет.

## 10 task

Дан элемент #test. Поставьте ему в начало текст непосредственного соседа сверху, а в конец - текст непосредственного соседа снизу.

## 11 task

Найдите все абзацы p с классом .www, покрасьте их в красный цвет. Затем выберите среди найденных абзацев первый и поставьте ему текст '!', затем выберите последний и ему поставьте текст '?'. Решите задачу одной цепочкой.

## 12 task

Найдите все абзацы p, у которых непосредственный родитель не div и оберните каждый из них в div class="www". 

## 13 task

Найдите все абзацы p, у которых есть атрибут class, и каждый из них оберните в div с теми же классами, как у найденного абзаца, а классы каждого абзаца удалите вместе с атрибутом class.

## 14 task

Найдите ol с #test и переставьте все li в нем в обратном порядке

## 15 task

Дан элемент #text. Найдите всех его соседей сверху и всех его соседей снизу и поменяйте их местами (то есть все, что стоит до элемента, должно стать после него и наоборот)

## 16 task

Получите все li на странице. Четные из полученных сделайте пустыми, а нечетные удалите.

## 17 task

Получите все li с классом .www, сделайте им красный цвет, затем найдите среди найденных те li, у которых есть класс .bbb и удалите их. Решите все одной цепочкой.

## 18 task

Найдите все абзацы p, у которых есть атрибут class, и каждый из них оберните в div с теми же классами, как у найденного абзаца, а классы каждого абзаца удалите вместе с атрибутом class.

## 19 task

Даны абзацы с числами. Поставьте каждому из них в конец число, которое в нем хранится, умноженное на его порядковый номер в наборе.
