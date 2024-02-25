# Нужно установить вирт окружение
в терминале прописываем :

python3 -m venv venv
# Далее её нужно активировать 
source venv/bin/activate (только Linux)

(только Windows) venv/Scripts/activate
# Далее скачиваем все зависимости
pip install -r requirements.txt
# Запускаем сервер (dev)
cd ii99

cd lyceum

python manage.py runserver 
