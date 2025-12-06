# 🎓 TutorConnect

![Django](https://img.shields.io/badge/Django-4.0+-092E20?style=for-the-badge&logo=django&logoColor=white) ![Python](https://img.shields.io/badge/Python-3.8+-3776AB?style=for-the-badge&logo=python&logoColor=white)

Plataforma web desarrollada en Django para conectar tutores con estudiantes. (Aquí puedes expandir explicando si usa autenticación, roles de usuario, etc.)

## 🚀 Instalación Local

Sigue estos pasos para ejecutar el proyecto en tu máquina:

1.  **Clonar el repositorio**
    ```bash
    git clone [https://github.com/HaroldToribio/TutorConnect.git](https://github.com/HaroldToribio/TutorConnect.git)
    cd TutorConnect
    ```

2.  **Crear entorno virtual**
    ```bash
    python -m venv venv
    # Windows:
    .\venv\Scripts\activate
    # Mac/Linux:
    source venv/bin/activate
    ```

3.  **Instalar dependencias**
    ```bash
    pip install -r requirements.txt
    ```

4.  **Migrar base de datos**
    ```bash
    python manage.py migrate
    ```

5.  **Crear superusuario (Opcional)**
    ```bash
    python manage.py createsuperuser
    ```

6.  **Correr el servidor**
    ```bash
    python manage.py runserver
    ```

## 🔑 Credenciales de Prueba (Demo)
* **Admin User:** admin
* **Password:** (Pon aquí la contraseña genérica si es segura, ej: Admin1234)

## 📂 Estructura del Proyecto
* `MiApp/`: Lógica principal de la aplicación.
* `ProyectoFinal/`: Configuración global (settings, urls).
* `templates/`: Archivos HTML.