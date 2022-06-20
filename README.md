# Neurolap
Creadora intelectual: Dra. Ninoska Ocampo

Realizado con el apoyo de Andrea Arana, Karol Argote

Versión del proyecto hecho usando Django y PostgreSQL

Desarrolladores de esta versión:

* Luis Carvajal

* Alberto Flores

* Bruno Bustos

* Miguel Barrionuevo

* Wilson Zenteno

Para hacerlo correr en una terminal:

python manage.py runserver

Instrucciones para la BDD con PostgreSQL:

1. Para que les pueda correr en sus computadoras lo que deben hacer es crear una base de datos en Postgres con el nombre "neurolap"
2. Luego en el Visual se van a la parte de settings.py, al sector de DATABASE y donde dice PASSWORD ponen la contraseña de su Postgres
3. Abren Terminal y primero 
python manage.py createsuperuser (les pedira el nombre, correo, y password) podria poner un root-root, admin-admin; algo facil
luego python manage.py makemigrations
y python manage.py migrate (En uno de estos dos puntos les saldra como un error en la terminal que les dara dos opciones... solo ponen 1 y luego None.. Como unas 5 veces deben hacer  esos dos pasos. Esto es por los foreing keys y eso)
Actualizan el Postgres y ya deberian de estar las tablas.

y ya pueden acceder a la base de datos y hacer el CRUD desde el administrador de django http://127.0.0.1:8000/admin
