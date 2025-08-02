Django Month 5 Test

Учебный проект на Django, созданный в рамках Month 5.

---

 🚀 Как запустить проект

 🔧 Вариант 1: Без Docker (локально)

1. Клонируй репозиторий:
   ```bash
   git clone https://github.com/your-username/month5_project.git
   cd month5_project

2.Создай и активируй виртуальное окружение:

  python -m venv venv
  source venv/bin/activate

3.Установи зависимости:

pip install -r requirements.txt

4.Примени миграции:

python manage.py migrate

5.Запусти сервер:

python manage.py runserver


 Вариант 2: Через Docker
 Убедись, что установлен Docker и Docker Compose.

1.Собери и запусти контейнер:

docker-compose up --build

2.Запусти докер:

docker-compose up

3.Приложение будет доступно на:

"http://localhost:8000/"
















