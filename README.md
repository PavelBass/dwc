# Тестовое задание от DATADVANCE

В качестве решения задания была создана утилита dwc - DATADVANCE Words Calculator. Исходя из условия "we don't think that a candidate will take more than an hour to complete it", скрипт не был покрыт тестами.

Версия языка: __Python 3.6.2__

## Установка
Для тестирования работы утилиты рекомендуется создать виртуальное окружение:

```virtualenv -p python3.6 dwc_test```

и активировать его:

```source dwc_test/bin/activate```


Установка утилиты из репозитория:

```pip install git+https://github.com/PavelBass/dwc.git```

## Использование

Например:

`dwc shakespeare.txt -l 10` - статистика 10 самых популярных слов по файлу shakespeare.txt

`dwc shakespeare.txt` - вся статистика по файлу shakespeare.txt

`dwc --help` - помощь по использованию утилиты.
