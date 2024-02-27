# Maturity matrix. Матрица зрелости

Maturity matrix. Матрица зрелости – прозрачный процесс аудита и реаудита систем компании с использованием:
1. Практик Agile разработки.
2. Культуры DevOps.
3. Современных подходов к автоматизации.
4. Современных инструментов CI/CD.

В данном репозитории описан пример внедрения процесса аудита и реаудита систем для их дальнейшего развития.
Подробнее читайте в статье на habr - 

# Деление на целевые и не целевые системы
Важно заметить и добавить, что Ваши системы, при внедрении процесса, рано или поздно поделятся на целевые и нет.
Где целевые - те системы, внедрение и развитие которых планируется сроком не менее 3-5 лет
Не целевые - те системы, которые в ближайшие перспективы не будут развиваться с последующем выводом из эксплуатации.

# Набор метрик, на основе которых можно замерять эффективность разработки в проектах

Название практики|Название метрики
---------|------------
Модульное тестирование| % покрытия модульными тестами
CI/CD |время на сборку при непрерывной интеграции
CI/CD |% успешных сборок непрерывной интеграции
CI/CD |время на поставку 
CI/CD |% успешных поставок 
Методология тестирования | время на прохождение смок тестов
Методология тестирования |время на прохождение регресс тестов
Методология тестирования |% автоматизации тестовых сценариев
Методология тестирования |% ложных срабатываний у автотестов
Методология тестирования |% пропущенных дефектов в интеграционные среды
Методология тестирования |% успешно пройденных тестов
Инфраструктура | время на подготовку нового окружения
