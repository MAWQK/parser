Проект предоставляет:
- Получение актуальных курсов валют с официального API ЦБ РФ
- Сохранение данных с timestamp в CSV-файл
- Интеграцию с Google Диском для хранения истории

 Технологии
- Python 3
- Библиотеки: `requests`, `csv`, `datetime`
- Google Colab Integration
- API: [ЦБ РФ](https://www.cbr-xml-daily.ru/)

Быстрый старт

Вариант 1: Запуск в Google Colab
1. Нажмите кнопку "Open in Colab" выше
2. Подключите ваш Google Диск при запросе
3. Выполните все ячейки ноутбука

Вариант 2: Локальный запуск
```bash
git clone https://github.com/ваш_username/ваш_репозиторий.git
cd ваш_репозиторий
pip install requests
python ваш_скрипт.py
