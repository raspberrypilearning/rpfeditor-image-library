Стартовий файл містить бібліотеку корисних зображень.

Натисни на значок «Галерея зображень».

![Квадратна іконка із зображенням гір та сонця.](images/view-gallery.png)

Прокрути бібліотеку зображень і занотуй назву зображення, яке ти хочеш використати на своїй сторінці.

![Показано бібліотеку зображень із файлом love.png.](images/editorimage-gallery.png)

Додай це зображення до секції `<main></main>` у файлі `index.html`, щоб воно зʼявилося на твоїй вебсторінці.

--- code ---
---
language: html
filename: index.html
line_numbers: true
line_number_start: 32
line_highlights: 35
---

<!-- Між тегами main розміщуємо основний вміст сторінки -->
<main>
  Lorem ipsum dolor sit amet. 
  <img src="love.png" alt="Опис зображення">
   
</main>

--- /code ---