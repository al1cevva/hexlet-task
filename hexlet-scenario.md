# Тестовый сценарий тестирования страницы поиска вакансий

##### Таблица 1. Тест-кейсы для тестирования списковой формы вакансий

| ID  | Название теста | Шаги воспроизведения | Ожидаемый результат |
| ------------- | ------------- | --- | --- |
| 1 | Список вакансий  | --- | --- |
| 1.1 | Отображение списка вакансий на странице | 1. Перейти к странице https://ibs.ru/career/jobs/ | Отображается страница вакансий. Число вакансий в заголовке соответствует числу вакансий над списком вакансий. Справа от фильтров отображается список вакансий. |
| 1.2 | Навигация по списку вакансий | 1. Перейти к странице https://ibs.ru/career/jobs/ <br> 2. Под списком вакансий перейти на любую другую страницу с вакансиями, например, 4. <br> 3. Вернуться на 1-ую страницу вакансий.  |1. Отображается страница со списком вакансий. <br> 2. Отображается другая страница вакансий в зависимости от выбранной. Под списком вакансий подсвечена цифра выбранной страницы. <br> 3. Отображается первая изначальная страница с вакансиями. |
| 1.3 | Переход к вакансии из списка вакансий | 1. Перейти к странице https://ibs.ru/career/jobs/ <br> 2. На списковой форме выбрать любую вакансию и нажать на нее. <br> 3. Нажать на кнопку возврата на предыдущую страницу в браузере. | 1. Отображается страница со списком вакансий. <br> 2.Отображается страница вакансии. Заголовок и ключевые слова вакансии соответствует заголовку и ключевым словам вакансии на списковой форме. <br> 3. Отображается список вакансий на той же странице, с которой была выбрана вакансия. |
| 2 | Работа фильтров  | --- | --- |
| 2.1 | Отображение фильтров на странице  | 1. Перейти к странице https://ibs.ru/career/jobs/ 2. Раскрыть свёрнутые фильтры. | 1. Отображается страница с вакансиями. Слева от списка вакансий расположены фильтры. Фильтры Опыт и Формат работы раскрыты. Около фильтров отображается кол-во соответствующих вакансий. Фильтры Направление, Город, Технологии свёрнуты. Снизу расположены дополнительные фильтры Срочные вакансии и Вакансии с обучением. <br> 2. Скрытые фильтры развернуты. Около фильтров отображается кол-во соответствующих вакансий. Фильтры с кол-вом вакансий (0) окрашены в серый цвет и не могут быть выбраны.|
| 2.2 | Выставление фильтров  | 1. Перейти к странице https://ibs.ru/career/jobs/ <br> 2. Выбрать несколько фильтров. <br> 3. Нажать на кнопку Сбросить. |1. Отображается страница со списком вакансий. <br> 2. Около заголовка Фильтр отображается кол-во выбранных фильтров. На списковой форме вакансий изменилось кол-во вакансий в соответствии с выбором. <br> 3. Фильтры сброшены, на списковой форме отображаются все вакансии. |
| 2.3 | Связь фильтров и ключевых слов | 1. Перейти к странице https://ibs.ru/career/jobs/ <br> 2. Проставить фильтр, который соответствует одному из ключевых слов над списком вакансий, например, Удаленно. <br> 3. Нажать на другое ключевое слово, которое соответствует одному из фильтро, например, Тестирование. <br> 4. Нажать на кнопку Сбросить. | 1. Отображается страница со списком вакансий. <br> 2. Соответствующее ключевое слово теперь выделено. Отображаются соответствующие вакансии. <br> 3. В списке фильтров отмечен соответствующий фильтр. Список вакансий обновлен. <br> 4. Фильтры и ключевые слова сброшены, на списковой форме отображаются все вакансии. |
| 3 | Поиск вакансий  | --- | --- |
| 3.1 | Ручной поиск вакансий  | 1. Перейти к странице https://ibs.ru/career/jobs/ <br> 2. В поле Поиск начать вводить  | --- |
| 3.1 | Ручной поиск вакансий  | --- | --- |
| 4 | Адаптивность  | --- | --- |
| 5 | Нажатие на иконку сайта  | --- | --- |