### Swagger presentation

## Мозговой штурм

1. Сделать заготовку микросервиса во время презентации, по пути рассказывая, что происходит.
2. Как пример взять какую-нибудь функцию, требующую вынесения в микросервис. Например, stock service. Надо будет уточнить, какие методы и какие данные используются там, и сделать версию в Swagger. Пока использовать базовые get/post
3. Необходимо написать уже готовый yaml-файл, объяснить его структуру.
4. На основе файла сгенерировать документацию с помощью Swagger UI, клиент для JavaScript и Clojure, а также заготовку сервера на NodeJS.
5. Разобраться как это все сделать на Swagger Hub. Стоит ли все делать там, чтобы потом еще и запустить API.
6. Посмотреть, как AWS работает со Swagger.


UI, Editor, CodeGen, Validator

Преимущества Swagger Hub:
- Интеграция с GitHub
- Интеграция с Amazon

Недостатки:
- Платность
- Внутри компании лучше пользоваться своими инструментами

## План презентации

### Слайды "What is Swagger" - 10 min

1. What is swagger? YAML/JSON file
2. Swagger ecosystem: UI, Editor, CodeGen, Validator, Swagger Hub
3. Additional Swagger tools by community: Mock APIs, language integrations, annotations parsing

### Описание синтаксиса YAML-файла - 5 min

### Генерация документации, клиента, сервера - 10 min

Использовать инструменты на компьютере

### Swagger Hub + Amazon AWS Lambda - 30 min

1. Создать проект на Swagger Hub
2. Скопировать YAML-файл
3. Интегрировать с AWS Lambda
    - подготовить роли и ключи
