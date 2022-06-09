# PageAnalyzerNET

[![.NET](https://github.com/dbulyk/PageAnalyzerNET/actions/workflows/dotnet.yml/badge.svg)](https://github.com/dbulyk/PageAnalyzerNET/actions/workflows/dotnet.yml)

## Описание

Данный проект позволяет проверять веб страницы на мимнимальную SEO-пригодногость, за счет проверки наличия тегов h1, title и description. В качестве базы данных используется PostgreSQL, имеются скрипты миграции для создания структуры бд.

## Функциональность:

### Главная

На главной странице можно добавить сайт для последующей проверки. Вставлять можно url любой длины и типа, программа автоматически обрежет ссылку до хоста и домена.

### Сайты

Здесь отображаются все добавленные сайты с датой и статусом последней проверки. По нажатию на ссылку открывается страница с отображением данных проверки: статус ответа, title, h1, description, дата и время последней проверки. При клике на кнопку "Запустить проверку", собственно, запускается сама проверка.

## Используемые технологии
C#, .NET Core, Entity Framework.



