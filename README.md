# Решатель квадратных уравнений

Программа решает квадртные уравнения с действительными числами

# Как использовать

Для использования программы необходимо импортировать модуль **from quadratic_equation import get_roots**.
Функция **get_roots** принимает на вход три действительных числа, которые являются коэффициентами квадратного уравнения.
Пример использования, **get_roots(1, -2, 3)** на выходе получим объект класса **tuple, (1.0, 1.0)**
  # импорт модуля в ваш код
  from quadratic_equation import get_roots
  
  # Использование функции
  get_roots(1, -2, 3)
  
  # Пример выходных данных
  (1.0, None)
  

# Как запустить

Скрипт требует для своей работы установленного интерпретатора Python версии 3.5

Запуск на Linux:

```bash
python tests.py # может понадобиться вызов python3 вместо python, зависит от настроек операционной системы
```

Запуск на Windows происходит аналогично.

# Цели проекта

Код создан в учебных целях. В рамках учебного курса по веб-разработке ― [DEVMAN.org](https://devman.org)
