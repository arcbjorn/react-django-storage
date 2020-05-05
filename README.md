# Simple Storage Set-Up (React, Django & REST APIs)

### 1. Clone repository

```sh
git clone https://github.com/arcbjorn/react-django-storage
```

### 2. Activate Virtual Environment

```sh
cd react-django-storage
source venv/bin/activate
```

### 3. Make Default Migrations & Start the server

```sh
python manage.py migrate
python manage.py runserver
```

<details>
 <summary>Don’t forget that you need to create a superuser account, if you'd like to access the django admin: [http://127.0.0.1:8000/admin](http://127.0.0.1:8000/admin)</summary>

```
(venv) $ python manage.py createsuperuser
Username: myusername
Email address: username@gmail.com
Password: 
Password (again): 
Superuser created successfully.
```

</details>

### 4. Install NPM Dependencies & Run the React App

```sh
cd react-django-storage/storagefront
npm install
npm run dev
```

App on the port:
[http://127.0.0.1:8000/](http://127.0.0.1:8000/).

API to populate DB: 
[http://127.0.0.1:8000/api/user](http://127.0.0.1:8000/api/user).
