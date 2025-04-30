# 🚀 Mi Proyecto de Django 

Este es mi primera proyecto de django realizado en Tecsup, laboratorio 7

## 📋 Descripción general

La estructura de mi proyecto de django es el siguiente:

"src" : Directorio de codigo principal 

"config" : Configuracion de Proyecto 

"core" : Aplicacion principal 

"venv" : Entorno virtual (No registrado en git)

## ✨ Caracteristicas

Estrucutura de Django limpio y ordenado 

Separacion de la confisuracion y codigo de la aplicacion

Listo para utilizar frameworks fronted 

Interfaz de admin para gestion de contenido 

## 🔧 Intalacion 

1. Clona el repositorio 

2. Crea y activa el entorno virtual:
   ```bash
   python -m venv venv
   venv\Scripts\activate

3. Intalacion de las dependencias:
    ```bash
    cd src
    pip install -r requirements.txt

4. Aplica Miagraciones:
    ```bash
    python manage.py migrate

5. Crear el superusuario:
    ```bash
    python3 manage.py createsuperuser

## 🚀 Running the Project

Para la ejecucion del proyecto se realiza los siguientes comandos.

      cd src
      python manage.py runserver
    
acceso al sitio web en http://127.0.0.1:8000/ y al admin en http://127.0.0.1:8000/admin/
