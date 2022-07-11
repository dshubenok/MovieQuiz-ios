# quiz-ios
QuizApp - это приложение с квизами о фильмах из топ-250 рейтинга IMDb

## Ссылки

[Макет Figma](https://www.figma.com/file/l0IMG3Eys35fUrbvArtwsR/YP-Quiz?node-id=34%3A243)

[API IMDb](https://imdb-api.com/api#Top250Movies-header)

## Описание приложения

- Одностраничное приложение с квизами о фильмах из топ-250 рейтинга IMDb. Пользователь приложения последовательно отвечает на вопросы о рейтинге фильма. По итогам каждого раунда игры показывается статистика о количестве правильных ответов и лучших результатах пользователя. Цель игры - правильно ответить на все 10 вопросов раунда.

## Функциональные требования
- При запуске приложения показывается сплеш-скрин;
- После запуска приложения показывается экран вопроса с текстом вопроса, картинкой и двумя вариантами ответа, “да” и “нет”, только 1 из них правильный;
- Вопрос квиза составляется относительно IMDb рейтинга фильма по 10 бальной шкале, пример: "Рейтинг этого фильма больше 6?";
- Можно нажать на один из вариантов ответа на вопрос и получить отклик о том, правильный он или нет, при этом рамка фотографии поменяет цвет на соответствующий;
- После выбора ответа на вопрос автоматически появляется следующий вопрос;
- После завершения раунда из 10 вопросов появляется поп-ап со статистикой пользователя. А именно - результат текущего раунда, количество сыгранных раундов, рекорд с датой и средняя точность в процентах; 
- Пользователь может запустить новый раунд, нажав на кнопку "Сыграть еше раз".

## Технические требования 
- Приложение должно поддерживать устройства iPhone с iOS 13 или выше, предусмотрен только портретный режим. 

