# План
## Перечень автоматизируемых сценариев
Задача: Запись на обучение профессии "Тестировщик ПО"

Предусловие:

Три способа попасть на форму записи:
1. Пролистать всю странцу профессии до формы записи
2. Нажать на кнопку "Записаться" в верхнем блоке страницы сайта 
3. Нажать на кнопку "Записаться" в первом блоке страницы профессии


Способы попасть на страницу профессии
1. Через меню "Каталог курсов"=>Выбор из списка слева раздел "Программирование"=> выбор в столбце Для начинающих строку "Тестировщик ПО"
2. Через раздел "Направления обучения=>Программирование=>Тестировщик ПО"  на главной странице https://netology.ru
3. Через раздел "Обучение" в подвале сайта https://netology.ru =>Программирование=>Тестировщик ПО"

Тест кейсы
1. Заполнить Имя=> Анна
Заполнить номер телефона=> +7927303-19-91
Нажать на кнопку "Записаться"
Ожидаемый результат:После нажатия кнопки записаться появляется окно уведомления, что заявка на обучение принята
2. Заполнить Имя=>
Заполнить номер телефона=>
Нажать на кнопку "Записаться"
Ожидаемый результат:после нажатия на кнопку Записаться происходит пролистывание страницы профессии до низа на блок формы записи.
3. Заполнить Имя=>пустое поле
Заполнить номер телефона=>пустое поле
Нажать на кнопку "Записаться"
Ожидаемый результат:после нажатия на кнопку Записаться строки с пустыми полями подсвечиваются красным и пользователь видит сообщение "Обязательное поле"
4. Заполнить Имя=>пустое поле
Заполнить номер телефона=>+7927303-19-91
Нажать на кнопку "Записаться"
Ожидаемый результат:после нажатия на кнопку Записаться строка с пустым полем подсвечивается красным и пользователь видит сообщение "Обязательное поле"
5. Заполнить Имя=> Анна
Заполнить номер телефона=>пустое поле
Нажать на кнопку "Записаться"
Ожидаемый результат:после нажатия на кнопку Записаться строка с пустым полем подсвечивается красным и пользователь видит сообщение "Обязательное поле"
6. Заполнить Имя=> А
Заполнить номер телефона=>+7927303-19-91
Ожидаемый результат:строка с именем подсвечивается красным и и пользователь видит сообщение "Должно быть не короче 2 символов"
7. Заполнить Имя=> Анна
Заполнить номер телефона=>0
Ожидаемый результат:строка с номером телефона подсвечивается красным и пользователь видит сообщение "Номер в формате +9 (999) 999-99-99"
8. Заполнить Имя=> Анна
Заполнить номер телефона=>89273031991
Ожидаемый результат:строка с номером телефона подсвечивается красным и пользователь видит сообщение "Номер в формате +9 (999) 999-99-99"
## Перечень используемых инструментов с обоснованием выбора
1. IDEA в качестве среды разработки
2. Java как язык программирования
3. Gradle для автоматизации сборки
4. JUnit5 наиболее используемая среда для тестирования Java
5. Selenide фреймворк для автоматизации тестирования,быстро и просто 
6. Allure отчетность
7. Docker Compose создания тестового окружения
8. mySQL для проверки тестовых данных, вставки, обновления и удаления значений тестовых данных в базе данных
9. Сucumber для описания сценарий
## Перечень необходимых разрешений/данных/доступов
1. Разрешение на выполнение автоматизированного тестирования сайта
2. Доступ к базе данных
3. Доступ к API
4. Тестовый стенд для тестирования записи тестовых пользователей
5. Тестовые данные пользователей (номера телефонов)
6. Если тестирование на проде, то тестовые аккаунты для отправки запросов
## Перечень и описание возможных рисков при автоматизации
1. При изменении в интерфейсе/представлении блоков платформы, автотесты нужно будет переписывать
2. Если тестирование на проде, сложность подготовки тестовых номеров телефонов( или их ограниченное количество)
3. Если тестирование на проде, дополнительная нагрузка для сервиса 
## Перечень необходимых специалистов для автоматизации
1. Тестировщик со знанием Java и принципов автоматизации
2. Разработчик среды для получения необходимых доступов/разрешений
## Интервальная оценка с учётом рисков (в часах)
35ч(5 рабочих дней по 1 на каждый сценарий) 
