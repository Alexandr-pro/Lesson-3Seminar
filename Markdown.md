Семинар №2

# Туториал по языку разметки Markdown

## Работа с заголовки


## Работа со списками

## Работа с изображения

бла-бла-бла воздушный шарик
Чтобы добавить изображения в Markdown, используйте следующую конструкцию:
["Альтернативныйтекст"] (https://cameralabs.org/media/camera/oktiabr/26/48_4ea61a0674caca148d0b75dedd3a29ef.jpg)



## Работа с таблицами

Для того чтобы, добавить таблицу в Markdown, нужно будет пойти на некоторые ухищрения. Воспользуемся разметкой GFM, пример:

First Header | Second Header
------------- | -------------
Content Cell | Content Cell
Content Cell | Content Cell
Для красоты можно и по бокам линии нарисовать:

| First Header | Second Header |
| ------------- | ------------- |
| Content Cell | Content Cell |
| Content Cell | Content Cell |
Можно управлять выравниванием столбцов при помощи
двоеточия.
| Left-Aligned | Center Aligned | Right Aligned |
|:------------- |:---------------:| -------------:|
| col 3 is | some wordy text | **$1600** |
| col 2 is | centered | $12 |
| zebra stripes | are neat | ~~$1~~ |
Внутри таблиц можно использовать ссылки, наклонный,
жирный или зачеркнутый текст.
Для всего остального есть обычный HTML. Воспользуйтесь тегом table:
```HTML
 <table><td><tr></tr></td></table>
 ```