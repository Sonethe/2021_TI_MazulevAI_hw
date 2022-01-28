#Устанавливаем python и pip

1) python3 --version
    ### Если не установлен
    1.1 sudo apt install python3

2) pip3 --version
    ### Если не установлен
    2.1 sudo apt -y install python3-pip

#Создаём и настраиваем среду

1) python3 -m venv venv
2) source venv/bin/activate
3) pip install --upgrade pip
4) pip install -r requarements.txt

#Запускаем приложение

1) source venv/bin/activate
2) python manage.py makemigrations
3) python manage.py migrate
4) python manage.py runserver