# Решатель квадратных уравнений

Этот скрипт может **решить** квадратное уравнение и

на выходе дать **количесво** корней и **сами** корни.

В репозитории есть **тест** к нему.

# Как использовать

Загрузите на компьютер все файлы с помощью команды в **консоли**:
```python code
git clone (ссылка на репозиторий)
```
Импортируйте в свой код **функцию**:
```python code
from quadratic_equation import get_roots
```
Подставляете **аргументы**:
```python code
root1, root2 = get_roots(9, 8, 7)
```
# Как запустить тест

Скрипт требует для своей работы установленного интерпретатора Python версии 3.5

Запуск на Linux:

```bash
python tests.py # может понадобиться вызов python3 вместо python, зависит от настроек операционной системы
```

Запуск на Windows происходит аналогично.

# Цели проекта

Код создан в учебных целях. В рамках учебного курса по веб-разработке ― [DEVMAN.org](https://devman.org)
