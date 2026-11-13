# Привет, я Фатыхова Рената 👋

**QA Engineer · автоматизация на Java**

Пишу автотесты для Web, REST API и мобильных приложений.
В проектах использую Page Objects, модели данных, Allure-отчёты и запуск в Jenkins.
Здесь собраны мои дипломные проекты QA.GURU и примеры ручного тестирования.

[![Telegram](https://img.shields.io/badge/Telegram-@renata__fatykhov-26A5E4?logo=telegram&logoColor=white)](https://t.me/renata_fatykhov)

## Стек

![Java](https://img.shields.io/badge/Java-ED8B00?logo=openjdk&logoColor=white)
![Gradle](https://img.shields.io/badge/Gradle-02303A?logo=gradle&logoColor=white)
![JUnit 5](https://img.shields.io/badge/JUnit_5-25A162?logo=junit5&logoColor=white)
![Selenide](https://img.shields.io/badge/Selenide-43B02A?logo=selenium&logoColor=white)
![REST Assured](https://img.shields.io/badge/REST_Assured-167D46)
![Appium](https://img.shields.io/badge/Appium-662D91?logo=appium&logoColor=white)
![Allure](https://img.shields.io/badge/Allure_Report-FF6B35)
![Jenkins](https://img.shields.io/badge/Jenkins-D24939?logo=jenkins&logoColor=white)
![Selenoid](https://img.shields.io/badge/Selenoid-2496ED?logo=docker&logoColor=white)
![BrowserStack](https://img.shields.io/badge/BrowserStack-F7B500)
![Git](https://img.shields.io/badge/Git-F05032?logo=git&logoColor=white)

## Дипломные проекты

### 🌐 Web · Tutu.ru

[Код и README](https://github.com/RenataFatykhov/tutu) · [Jenkins](https://jenkins.qa.guru/job/tutu/)

UI smoke-тесты туристического сервиса: главная страница, форма поиска,
шапка, футер, справочная, путеводитель и раздел поездов.

- Selenide + JUnit 5, действия и проверки вынесены в Page Object.
- Локальный Chrome и удалённый запуск в Selenoid.
- Allure со скриншотами, HTML страницы и видео удалённых запусков.
- Примеры отчётов Jenkins, Allure TestOps и Telegram — в README.

### 🔌 API + UI · Book Club

[Код и README · ветка ui_api](https://github.com/RenataFatykhov/book-club-tests/tree/ui_api) · [Jenkins](https://jenkins.qa.guru/job/api_ui_java_book_club_tests/)

Регистрация и авторизация, профиль, книжные клубы и отзывы: **31 API-сценарий и 7 UI-сценариев**.

- REST Assured, модели запросов и ответов на Java records, Request/Response Specs.
- Проверка JSON Schema и Allure listener с собственными HTML-шаблонами.
- Создание пользователя и клуба через API для UI-тестов; авторизация через localStorage.
- Page Objects и отдельные команды запуска API/UI-наборов.

### 📱 Mobile · Wikipedia

[Код и README](https://github.com/RenataFatykhov/mobile_tests_local_and_remote)

Android-тесты onboarding, поиска и открытия статьи в Wikipedia.
Дополнительно — iOS smoke-тест приложения UI Elements в BrowserStack.

- Appium + Selenide + JUnit 5, Screen Objects и конфигурация OWNER.
- Запуск на эмуляторе, реальном Android-устройстве и в BrowserStack.
- Allure-шаги, скриншоты и XML; видео для облачных сессий.

## Ручное тестирование

Тест-кейсы с предусловиями, шагами и ожидаемыми результатами дополняют автотесты.

| Продукт | Документация |
| --- | --- |
| Tutu.ru | [Навигация, поиск и форма входа](docs/tutu-manual-test-cases.md) |
| Book Club | [Регистрация, профиль, клубы и отзывы](docs/book-club-manual-test-cases.md) |
| Wikipedia Android | [Onboarding, поиск и работа приложения](docs/wikipedia-manual-test-cases.md) |

## Связаться со мной

Telegram: [@renata_fatykhov](https://t.me/renata_fatykhov)
