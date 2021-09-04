# docstrings2pdf
* Версия: 0.3
## Описание
* Данное приложение переводит docstrings в PDF формат. Может работать со всем модулем, классом, методом класса или функцией. 
## Требования
* Python3 и выше
* Modules: ast, fpdf
## Состав
* Консольная версия: main.py
* Пример для использования: example.py 
* Пример выходного файла: example.pdf
## Структура
* Config file: config.py
* docstringsParser.py: Содержит класс, реализующий парсеры Модуля, Класса и Функции
* pdfConverter.py: Класс, создающий и форматирующий PDF (пока не с нуля)
## Консольная версия
* Справка по запуску: main.py -h
* Пример запуска: python main.py -i "example.Human"

(c) rZb.K 2018.
