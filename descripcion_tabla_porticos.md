# Tabla porticos

Este archivo contiene la tabla principal del sistema de pórticos de Mirich.

## Archivo principal
- porticos.csv

## Descripción
Cada fila representa un pórtico.

Este archivo contiene el inventario de pórticos del sistema.

Columnas principales:
- id: identificador interno
- portico: nombre del pórtico
- ubicacion: dirección o referencia
- municipio_id: id del municipio relacionado
- localidad: localidad del pórtico
- camaras: arreglo con nombres de cámaras
- ip_camara: arreglo con IPs de cámaras
- ip_raspi: IP de la raspberry
- activo: estado operativo
- geolocalizacion: coordenadas (lat, lon)
- licencia: licencia asociada
- credenciales_raspi: contiene usario y contraseña del webserver y supervisor
- credenciales_camaras: usuario admin y la contraseña de la camra

# valor id de Municipio relacionado
1 = Pilar
2 = Santa fe
3 = Rosario
4 = Cordoba
5 = Mendoza
6 = Sanjuan


## Alcance
Las respuestas deben salir exclusivamente de estos archivos.
Si un dato no está presente o no puede inferirse claramente, debe indicarse.
