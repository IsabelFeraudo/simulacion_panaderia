# SIMULACION: TRABAJO PRACTICO FINAL
Trabajo práctico Final para la materia Simulación, Ingeniería en Sistemas UTN FRC

## Instalación/Despliegue en Windows
1. Descargue el repositorio
5. Instale docker https://docs.docker.com/desktop/install/windows-install/
6. Ir a la carpeta del proyecto 
7. Construir la imágen con el archivo Dockerfile
8. Levantar la imágen con docker-compose o con docker run
9. Acceder a la página con 127.0.0.1:8000

10. ## Instalación/Despliegue en Linux
- posicionarse en carpeta
- python3 -m venv venv
- source venv/bin/activate
- clonar el repositorio
- entrar en la carpeta del repositorio (cd)
- pip install -r requirements.txt
- moverse a la carpeta donde se encuentra el archivo manage.py
- python manage.py runserver
- abrir navegador y colocar en el navegador localhost:8000
