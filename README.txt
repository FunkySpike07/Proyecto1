Verifica que tengas el entorno virtual activado (.venv)
    Si no lo tienes ejecuta en el bash:

        py -3 -m venv .venv

    Ahora se mostrara (.venv) debajo de la linea de comandos
(Si no lo hace prueba abriendo un nuevo bash)

Verifica que tengas Django instalado en el proyecto (o de manera global en su caso)
    Si no lo tiene ejecuta en el bash (omite si Django esta de manera global):

        python -m pip install --upgrade pip
        python -m pip install django
    
    Ahora ve a View > Command Palette > Python > Python (.venv)

Ejecuta el programa escribiendo
    python manage.py runserver

Cambia o agrega nuevas urls al archivo "prueba.txt"
Edita la apariencia de las interfaces desde la carpeta "Plantillas"
Codifica la logica de programacion desde "views.py"
Agrega nuevas direcciones desde "urls.py"