## Descripción del proyecto

Como su nombre lo indica, "**Task App**" es una aplicación web de tareas realizada con el framework **Django**. La misma permite **crear**, **mostrar**, **editar** y **eliminar** tareas.

**Características del proyecto**:

- Registro e inicio de sesión de usuarios.
- Autenticación de usuarios.
- Crear tareas.
- Ver tareas.
- Editar tareas.
- Eliminar tareas.

## Ejecución del proyecto

Para ejecutar este proyecto deberá tener instalado **Python** en su ordenador. Lo primero que haremos será descargar el proyecto y abrirlo en nuestro editor de preferencia. Si bien no es obligatorio, es recomendable crear un **entorno virtual** para almacenar las dependencias de sus proyectos por separado.

Para instalar un **entorno virtual**, ejecute el siguiente comando:

```
pip install virtualenv
```

Si su sistema operativo es **Windows**, abra el **"Símbolo del sistema"** y ejecute el siguiente comando:

```
source env/Scripts/activate
```

Si su sistema operativo es **Linux** o **Mac**, abra la **"Terminal"** y ejecute:

```
source env/bin/activate
```

A continuación, instale las dependencias del proyecto con:

```
pip install -r requeriments.txt
```

Ya casi está listo, ahora solo resta ejecutar el proyecto con el siguiente comando:

```
python manage.py runserver
```
