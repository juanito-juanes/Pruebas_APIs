# Pruebas_APIs

Repositorio de prácticas para aprender a consumir APIs REST con Python.

## Requisitos

- Python 3.x
- Instalar dependencias:

pip install requests python-dotenv


## Scripts

- **Prueba_CDS.py** - Consumo de un servicio OData de SAP S/4HANA con autenticación Basic y filtros OData. Las credenciales se gestionan mediante variables de entorno (`.env`).

## Notas

- El archivo `.env` con las credenciales SAP no está incluido en el repositorio por seguridad.
- Para ejecutar `Prueba_CDS.py` es necesario crear un `.env` con las variables `SAP_USER` y `SAP_PASSWORD`.
