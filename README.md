# Current-news
### Ссылка на Colab https://colab.research.google.com/drive/1ix7Aae_OcYoiOqwGw3dXEEEZehHIqgUl?usp=sharing  
#### Видео URL https://drive.google.com/file/d/1HeLj35yTpL0HJXU5hvUDdKbZk5EAQhFQ/view?usp=share_link 
#### Описание:
  Мой проект представляет из себя парсинг новостного сайта 'https://news.mail.ru/. Так как я учусь на маркетинге, то такой навык будет весьма полезен, так как мы часто проводим анализ вторичной информации, выгружаем ее в excel таблицы и обрабатываем необходимым образом. 
  В данном парсере мы извлекаем информацию по новостным статьям в общую таблицу (дата фрейм), а именно берем название источника, например МК (московский комсомолец), время выпуска новости, заголовок и ссылку на первоисточник (если такая имеется). Так как новостные блоки имеют одинаковые коды, то мы можем использовать цикл для пополнения списков. 
  Также добавлена функция сортировки для создания таблицы в эксель, сортировка новостей по новизне, то есть вперед будут выдвигаться самые свежие новости, также добавлена функция поиска слов, фраз среди новостей. При каждом запуске информация в дата фрейм обновляется.
  Такой парсинг весьма удобен для анализа сайтов, поиска определенной информации (с помощью функции поиск), поиск статистики .
