# Pruebas_APIs

Repositorio de prácticas para aprender a consumir APIs REST con Python.

## Requisitos

- Python 3.x
- Instalar dependencias:

pip install requests python-dotenv


## Scripts

- **Prueba1.py** - Primera toma de contacto con la librería `requests`. Consumo básico de la API de GitHub.
- **Prueba Dashboard.py** - Consumo de múltiples APIs públicas (DummyJSON, HTTPBin, GitHub) con menú interactivo.
- **Prueba post_Get.py** - Práctica de métodos POST y GET con DummyJSON.
- **Prueba_CDS.py** - Consumo de un servicio OData de SAP S/4HANA con autenticación Basic y filtros OData. Las credenciales se gestionan mediante variables de entorno (`.env`).

## Notas

- El archivo `.env` con las credenciales SAP no está incluido en el repositorio por seguridad.
- Para ejecutar `Prueba_CDS.py` es necesario crear un `.env` con las variables `SAP_USER` y `SAP_PASSWORD`.
