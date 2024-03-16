# **Тема "Тестирование API" курс ЯндексПрактикум**

### Проект автоматизации тестирования API учебного сервиса "Яндекс.Самокат"

1. Ссылка на сайт: *https://qa-scooter.praktikum-services.ru/*
2. Документация API: *https://qa-scooter.praktikum-services.ru/docs/*
3. Основа для написания автотестов: *Pytest*, *Requests*, 
4. В автотестах используются: фикстуры *@pytest.fixture* и параметризация *@pytest.mark.parametrize*
5. Отчет о тестировании: *Allure*

**Установка Pytest:**
````
pip install pytest
````

**Установка Requests:**
````
pip install requests
````

**Установка Faker:**
````
pip install Faker
````

**Запуск автотестов:**
````
pytest -v
````

**Отчет о тестировании Allure:**
````
pip install allure-pytest
````
````
pytest tests --alluredir=allure_results
````
````
allure serve allure_results
````
