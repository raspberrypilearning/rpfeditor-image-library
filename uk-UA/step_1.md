Стартовий файл містить бібліотеку корисних зображень.

Натисни на значок «Галерея зображень».

![A square shaped icon with a mountain scene and the sun show in the icon.](images/view-gallery.png)

Прокрути бібліотеку зображень і занотуй назву зображення, яке ти хочеш використати на своїй сторінці.

![The image library with love.png file shown.](images/editorimage-gallery.png)

Додай це зображення до секції `<main></main>` у файлі `index.html`, щоб воно зʼявилося на твоїй вебсторінці.

## --- code ---

language: html
filename: index.html
line_numbers: true
line_number_start: 32
line_highlights: 35
--------------------------------------------------------

```
<!-- The main content for the webpage goes between the main tags -->
<main>
  Lorem ipsum dolor sit amet. 
  <img src="love.png" alt="Description of the image.">
   
</main>
```

\--- /code ---