Группа 12:

Зайцев Антон
Зайцев Александр
Чурилов Алексей

Work№4 Работа с облаком.
Для справки:
Программу можно запустить через uvicorn.
Программа реализована на FastAPI.
Модель генерирует текст на английском языке по изображению, т.е решает задачу формата Image-to-Text.
Модель принимает на вход изображения типа: https://.....jpg.
Модель подключается через библиотеку transformes, вес модели 900+ mb.

Короткая памятка по применению:
1) обновляем систему
  sudo apt-get update
  sudo apt-get dist-upgrade
  sudo reboot (перезагружаем)
2) создаем директорию
  mkdir python_venv
3) устанавлиаем библиотеку для виртуального окружения
  sudo apt install python3.10-venv
4) устанавливаем python как python3
  sudo apt install python-is-python3 
5) устанавливаем виртуальное python окружение
  сd python_venv
  python -m venv fort
6) активируем окружение
  source fort/bin/activate
4) клонирую репозиторий
  git clone https://github.com/m6129/four.git
5) заходим в клонированный каталог
  сd four
6) устанавливаем pip
  sudo apt install python3-pip
7) устанавливаем requirements
    pip install -r requirements.txt
8) запускаем uvicorn main:app --host=0.0.0.0
9) заходим через браузер http://158.160.17.242:8000/ или http://158.160.17.242:8000/docs
