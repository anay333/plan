# План
## Перечень автоматизируемых сценариев
Задача: Запись на обучение профессии "Тестировщик ПО"
1. Пролистать всю странцу профессии до формы записи=>заполнить Имя=>заполнить номер телефона=> нажать на кнопку Записаться
2. Нажатием кнопоки "Записаться" в верхнем инфоблоке на странице профессии через меню "Каталог курсов"=>Выбор из списка слева раздел "Программирование"=> выбор в столбце Для начинающих строку "Тестировщик ПО"
3. Нажатием кнопоки "Записаться" в форме записи на странице профессии через меню "Каталог курсов"
4. Нажатием кнопоки "Записаться" в верхнем инфоблоке через раздел "Направления обучения=>Программирование=>Тестировщик ПО"  на главной странице https://netology.ru
5. Нажатием кнопоки "Записаться" в форме записи через раздел "Направления обучения=>Программирование=>Тестировщик ПО"  на главной странице https://netology.ru
## Перечень используемых инструментов с обоснованием выбора
1. Gradle для автоматизации сборки
2. JUnit5 наиболее используемая среда для тестирования Java
3. Selenide фреймворк для автоматизации тестирования,быстро и просто 
4. Allure отчетность
## Перечень необходимых разрешений/данных/доступов
1. Тестовый стенд для тестирования записи тестовых пользователей
2. Тестовые данные пользователей (номера телефонов)
3. Если тестирование на проде, то тестовые аккаунты для отправки запросов
## Перечень и описание возможных рисков при автоматизации
1. При изменении в интерфейсе/представлении блоков платформы, автотесты нужно будет переписывать
2. Если тестирование на проде, сложность подготовки тестовых номеров телефонов( или их ограниченное количество)
3. Если тестирование на проде, дополнительная нагрузка для сервиса 
## Перечень необходимых специалистов для автоматизации
1. Тестировщик со знанием Java и принципов автоматизации
2. Разработчик среды для получения необходимых доступов/разрешений
## Интервальная оценка с учётом рисков (в часах)
140ч(4 рабочие недели)
