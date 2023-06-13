# Maturity matrix. Матрица зрелости

Maturity matrix. Матрица зрелости – прозрачный процесс аудита и реаудита систем компании с использованием:
1. Практик гибкой разработки.
2. Культуры DevOps.
3. Современных подходов к автоматизации.
4. Современных инструментов CI/CD.

В данном репозитории описан пример внедрения процесса аудита и реаудита систем для их дальнейшего развития.
Подробнее читайте в статье на habr - https://habr.com/ru/articles/727568/

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


Copyright (c) 2022 - 2023 Krylov Alexandr.
License autor by Krylov Alexandr type cc.
Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
