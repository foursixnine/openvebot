# openvebot
Bot para telegram para obtener los enlaces a los grupos de la OpenVe a traves de inline commands, el mismo hace uso del archivo readme.md y a traves de web scrapping se procesan los enlaces.

## Requisitos

* Python > 3.*
* beautifulsoup4
* [python-telegram-bot](https://github.com/python-telegram-bot/python-telegram-bot)

## Instalacion

* `pip install -r requirements.txt`

## Configuración

Ejecutar el bot pasando como parametro el token generado por @botfather en telegram, se debe habilitar la opcion de bot inline.
Una vez hecho esto, solo es necesario ejecutar el archivo bot.py

> python bot.py "TOKEN"

## ToDo
- [x] Procesar inline-querys de tipo Articulo.
- [x] Devolver nombre, enlace y admins del grupo en el query result.
- [x] Busqueda simple por el nombre.
- [ ] Actualizar a la nueva version del repositorio
- [x] Corregir `Bad Request: RESULTS_TOO_MUCH` al estar el query vacio

> Producido porque son muchos grupos y el maximo a enviar por peticion son 50.

- [ ] Mejorar la busqueda.

>Se requeriria cambiar la estrutura del repo actual, para poder tener maneras de categorizar mejor los grupos y mejorar de esta manera la busqueda.

