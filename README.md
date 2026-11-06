# Mi Primer Sitio

Proyecto inicial desarrollado con Django.

## Requisitos

- Python 3.14 o superior
- Git

## Instalación

Clona el repositorio y entra en la carpeta del proyecto:

```powershell
git clone https://github.com/josemiguelpinoj-source/Mi-Primer-Sitio.git
cd Mi-Primer-Sitio
```

Crea el entorno virtual:

```powershell
py -m venv venv
```

Activa el entorno virtual en PowerShell:

```powershell
.\venv\Scripts\Activate.ps1
```

Instala Django:

```powershell
python -m pip install django
```

## Ejecutar el proyecto

Inicia el servidor de desarrollo:

```powershell
python manage.py runserver
```

Abre [http://127.0.0.1:8000/](http://127.0.0.1:8000/) en el navegador.

## Estructura principal

- `manage.py`: herramienta de administración de Django.
- `config/`: configuración principal del proyecto.
- `Mi_Sitio/`: carpeta destinada a la aplicación del sitio.

## Licencia

Este proyecto es de carácter educativo.
