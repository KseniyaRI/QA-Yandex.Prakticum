# QA-Yandex.Prakticum
Материалы с обучения на курсе ["Инженер по тестированию плюс"](https://practicum.yandex.ru/qa-engineer-plus/)

В [YouTrack](https://r1995kg.youtrack.cloud/projects) расположены все заведенные баг-репорты с указанием ожидаемого и фактического результата, последовательностью шагов до ошибки, окружением и подтверждающими скриншотам и скринкастами. Всего указано 4 учебных проекта, внутри которых найденные ошибки разделены по логическим блокам.

Чек-листы некоторых проверок представлены на скриншотах, так как из-за особенностей доступа только кураторам обучения, нет возможности предоставить доступ к TMS. 

[Папка "Яндекс Прилавок"](https://github.com/KseniyaRI/QA-Yandex.Prakticum/tree/main/%D0%AF%D0%BD%D0%B4%D0%B5%D0%BA%D1%81%20%D0%9F%D1%80%D0%B8%D0%BB%D0%B0%D0%B2%D0%BE%D0%BA) (веб-приложение)
1. В проекте "Яндекс Прилавок" тестировалось API функциональности продуктовой корзины с помощью Postman, необходимые URL располагались в Apidoc тестового стенда. Использованы запросы GET, POST, PUT и DELETE.
2. Чек-лист с проверками и ссылками на каждую найденную ошибку - https://docs.google.com/spreadsheets/d/1j7DV8_AukeHYS-cP9Yr4EsGLNIiRO9Kya7yEQzT5aiU/edit?usp=sharing.
3. Коллекции проверок из Postman выгружены в формате JSON - https://drive.google.com/file/d/1e0J7Hhn-TN_Yi3QPQbtD15GG-8LJR4dF/view?usp=sharing, https://drive.google.com/file/d/1tXFrr1UUY6kDsAZUpugxA87hlG9vnJM8/view?usp=sharing, https://drive.google.com/file/d/12HEsCR9grRbN9P2rNZM6U-9PhFa0UfFm/view?usp=sharing.
4. Все найденные баги были заведены в YouTrack - https://r1995kg.youtrack.cloud/projects/676f1cad-93c3-4b2c-8cc8-a8d517d381be.


[Папка "Яндекс Метро"](https://github.com/KseniyaRI/QA-Yandex.Prakticum/tree/main/%D0%AF%D0%BD%D0%B4%D0%B5%D0%BA%D1%81%20%D0%9C%D0%B5%D1%82%D1%80%D0%BE) (мобильное приложение)
1. В проекте "Яндекс Метро" был составлен чек-лист для регрессионного тестирования мобильного приложения после обновления до новой версии. Всего по составленному чек-листу было проведено 40 проверок, выявлено 4 бага. Чек-лист проверок представлен на скриншотах "Регресс_1 и Регресс_2".
2. Все требования, затронутые изменениями были покрыты тест-кейсами (скриншоты "Тест-кейсы - Яндекс Метро"), при составлении проверок применялись такие техники тест-дизайна как Попарное тестирование и Таблица принятия решений - https://docs.google.com/spreadsheets/d/1dXFxuU2rec05kcbhDJFXAfinZUp-dJy5bYdwlGsiTnQ/edit?usp=sharing.
3. Тестирование проводилось в эмуляторе Android Studio. 
4. Найденные баги заведены в YouTrack - https://r1995kg.youtrack.cloud/projects/331b501d-f8ad-4b4e-92e9-d05f82f0b169.


[Папка "Яндекс Маршруты"](https://github.com/KseniyaRI/QA-Yandex.Prakticum/tree/main/%D0%AF%D0%BD%D0%B4%D0%B5%D0%BA%D1%81%20%D0%9C%D0%B0%D1%80%D1%88%D1%80%D1%83%D1%82%D1%8B) (веб-приложение - тестировалось в двух разных окружениях - браузеры Яндекс и Firefox)
1. Для проекта "Яндекс Маршруты" была составлена mindmap карта для блоков интерфейс и логика функциональности приложения - https://drive.google.com/file/d/1fIhbkR6V8rc_xDE-rVmb36VBYKCDuwiQ/view?usp=sharing.
2. На проекте было проведено тестирование формы добавления водительских прав и форма добавления банковской карты. Скриншот со списком проверок называется "Формы".
3. Также на проекте проводилось тестирование полей ввода для поиска маршрута и тестирование полей ввода добавления прав с помощью такой техники тест-дизайна как классы эквивалентности и граничные значения (таблицы с необходимыми проверками и ссылками на найденные баг-репорты - https://docs.google.com/spreadsheets/d/1LDbdL2XcH9D1pbrZg0n9W0bEVaKKVTCdPSw0QzRyPN8/edit#gid=2010888140 и https://docs.google.com/spreadsheets/d/15P5_vcTkf3VP5R00ZWiiQlIR2ACk4TwOlWrewkwSAPc/edit?usp=sharing).
4. С помощью техники тест-дизайна - диаграмма связей и переходов (https://drive.google.com/file/d/1yu-kEcty0Kgo9Ap1OspPtVYVkEVO65se/view?usp=sharing) - был составлен чек-лист для проверки функциональности "Каршеринг" - скриншот называется "Каршеринг".
5. И была протестирована новая функциональность "Аэротакси" на фронтеде с помощью Charles, ссылка на папку со скриншотами из DevTools и Charles - https://drive.google.com/drive/folders/1gbUmTBeuJwxAwOcbb7Z63T5QyP-xTl8R?usp=sharing. В частности, для новой функциональности была подготовлена только фронтенд часть, необходимо было перехватить ответ бекенда и подставить новый вид транспорта (Аэротакси), чтобы проверить его отображение в приложении и необходимые расчета стоимости.
6. Найденные баги заведены в YouTrack - https://r1995kg.youtrack.cloud/projects/641c3ba2-a531-4318-90ec-f18bc713c6a5.
