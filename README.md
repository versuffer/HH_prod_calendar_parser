# HH_prod_calendar_parser
This script parses production calendar from HeadHunter (hh.ru/calendar)

## Output example
```
{
    datetime.date(2023, 1, 1): 'Выходной',
    datetime.date(2023, 1, 2): 'Выходной',
    datetime.date(2023, 1, 3): 'Выходной',
    datetime.date(2023, 1, 4): 'Выходной',
    datetime.date(2023, 1, 5): 'Выходной',
    datetime.date(2023, 1, 6): 'Выходной',
    datetime.date(2023, 1, 7): 'Выходной',
    datetime.date(2023, 1, 8): 'Выходной',
    datetime.date(2023, 1, 9): 'Рабочий день',
    datetime.date(2023, 1, 10): 'Рабочий день',
       ...
    datetime.date(2023, 2, 19): 'Выходной',
    datetime.date(2023, 2, 20): 'Рабочий день',
    datetime.date(2023, 2, 21): 'Рабочий день',
    datetime.date(2023, 2, 22): 'Сокращённый день',
    datetime.date(2023, 2, 23): 'Выходной',
    datetime.date(2023, 2, 24): 'Выходной',
       ...
    datetime.date(2023, 12, 31): 'Выходной'
 }
```