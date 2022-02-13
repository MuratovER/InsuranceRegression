# Проект InsuranceRegression
Программа для предсказания рассходов страховой компании на будущие месяца учитывая статистику предыдущих лет


## Требования для начала работы

- Python 3.10.2, pip, git
- Базза данных формата insdb.db


## Начало работы с проектом

### Клонирования проекта
```
git clone https://github.com/MuratovER/InsuranceRegression.git
```

### Проверка наличия Python
```
python3 --version
```

## Virtual environment (venv)
Обязательное условие для работы с Python проектами это виртуальная среда для избежания конфликта зависимостей.

#### Cоздание venv
Windows
```
python -m venv venv
```

#### Запуск
Windows
```
venv\scripts\activate
```

Linux
```
source venv/bin/activate
```

Название venv в начале командной строки говорит о том, что вирутальная среда активирована
(venv) C:\ts>


### Установка зависимостей проекта
```
pip install -r requirements.txt
```

## Запуск 

(venv) PS C:\InsuranceRegression> python main.py

## База данных

### Требования к базе данных
В базе данных должна быть таблица expenses в которой должны быть 3 колонки id(id элемента) d1(Дата формата DD:MM:YYYY) insurance(Расходы)



## Структура проекта


**model.py**

> Типовой источник информации о ваших данных. Он содержит основные поля и поведение данных, которые вы храните.

**logic.py**

> Вся логика проекта производящая рассчёт линейной регресии.


