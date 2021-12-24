# Python Django Proyecto Final Blog
Proyecto Final del Informatorio
----
LINEAMIENTOS DEL PROYECTO FINAL
----
- **Objetivo**
**Diseñar y desarrollar un blog con tecnología _DJANGO_ y abarcando la mayor cantidad de temas visto en el curso.**

1. **Modalidad**
  - El trabajo final deberá ser desarrollado en forma grupal.
  - Durante la semana del 06 de Diciembre, cada profe indicará los grupos organizados en función a niveles de experiencia/conocimiento adquirido.
  - Desde la semana que se comience a utilizar la herramienta DJANGO, los encuentros serán obligatorios, debiendo participar al menos una persona por equipo.
  - Durante la semana del 20 de Diciembre, cada trabajo debe poder ser accedido desde repositorios GIT, cuya URL se subirá en la tarea correspondiente dentro del aula virtual.

2. Además, cada grupo deberá subir un video a Youtube, con una duración de no más de 3', presentando:
  - Nombre del Blog
  - Integrantes del grupo
  - Mostrando las ventajas de su producto

### ¿QUÉ OBJETIVO DEBE TENER EL BLOG DESARROLLADO?

**El Blog que desarrollen debe permitir la difusión, visibilización y debate sobre iniciativas que contribuyan al cumplimiento de los 17 Objetivos de Desarrollo Sostenible (17 ODS) incluidos en la Agenda 2030 de la ONU.**

### ¿QUÉ SON LOS 17 ODS?

Los Objetivos de Desarrollo Sostenible, también conocidos como Objetivos Mundiales, se adoptaron por todos los Estados Miembros en 2015 como un llamado universal para poner fin a la pobreza, proteger el planeta y garantizar que todas las personas gocen de paz y prosperidad para 2030.

Los 17 ODS están integrados, ya que reconocen que las intervenciones en un área afectarán los resultados de otras y que el desarrollo debe equilibrar la sostenibilidad medio ambiental, económica y social.

Siguiendo la promesa de no dejar a nadie atrás, los países se han comprometido a acelerar el progreso para aquellos más atrasados. Es por esto que los ODS han sido diseñados para traer al mundo varios “ceros” que cambien la vida, lo que incluye pobreza cero, hambre cero, SIDA cero y discriminación cero contra las mujeres y niñas.

Todo el mundo es necesario para alcanzar estos objetivos ambiciosos. Se necesita la creatividad, el conocimiento, la tecnología y los recursos financieros de toda la sociedad para conseguir los ODS en cada contexto.

### ¿QUÉ FUNCIONALIDADES MÍNIMAS DEBE CONTENER?

1. La aplicación debe permitir:

- El acceso de diversos perfiles (admin, writer, reader, etc)
- Cargar un nuevo post, eliminar post publicados a usuario admin
- Comentar post a usuarios tipo writer
- Login a usuario tipo admin y writer
- Filtrar post por fecha, categoría de post y comentarios recibidos

The models for this site are as shown below:

![Django Blog Models](./blog/static/images/teatro_vera.jpg)


For more information see the associated [MDN assessment page](https://developer.mozilla.org/en-US/docs/Learn/Server-side/Django/django_assessment_blog).


## Comandos para levantar el proyecto

To get this project up and running locally on your computer:
1. Set up the [Python development environment](https://developer.mozilla.org/en-US/docs/Learn/Server-side/Django/development_environment).
   We recommend using a Python virtual environment.
1. Assuming you have Python setup, run the following commands (if you're on Windows you may use `py` or `py -3` instead of `python3` to start Python):
   ```
   pip3 install -r requirements.txt
   python3 manage.py makemigrations
   python3 manage.py migrate
   python3 manage.py collectstatic
   python3 manage.py test # Run the standard tests. These should all pass.
   python3 manage.py createsuperuser # Create a superuser
   python3 manage.py runserver
   ```
1. Open a browser to `http://127.0.0.1:8000/admin/` to open the admin site
1. Create a few test objects of each type.
1. Open tab to `http://127.0.0.1:8000` to see the main site, with your new objects.
