# Trabajo Práctico Integrador - Sistema de Gestión de Países

## Descripción

Aplicación de consola desarrollada en Python para la gestión de información de países utilizando archivos CSV como almacenamiento persistente.

El sistema permite administrar datos de distintos países, incluyendo nombre, población, superficie y continente.

## Funcionalidades

### Gestión de países
- Listar todos los países registrados.
- Agregar nuevos países.
- Actualizar población o superficie de un país existente.
- Validación de datos ingresados por el usuario.

### Búsquedas
- Búsqueda por coincidencia exacta.
- Búsqueda por coincidencia parcial.

### Filtros
- Filtrar por continente.
- Filtrar por rango de población.
- Filtrar por rango de superficie.

### Ordenamiento
- Ordenar por nombre.
- Ordenar por población.
- Ordenar por superficie.
- Orden ascendente o descendente.

### Estadísticas
- País con mayor población.
- País con menor población.
- Promedio de población.
- Promedio de superficie.
- Cantidad de países por continente.
- Total de países registrados.

### Persistencia de datos
- Lectura de datos desde archivo CSV.
- Guardado automático de cambios en archivo CSV.
- Creación automática del archivo si no existe.

## Tecnologías utilizadas

- Python 3
- Módulo `csv`
- Módulo `os`
- Programación estructurada

## Estructura de datos

Cada país contiene los siguientes campos:

| Campo | Tipo |
|---------|---------|
| nombre | Texto |
| poblacion | Entero |
| superficie | Entero |
| continente | Texto |

## Archivo de almacenamiento

El sistema utiliza el archivo:

```text
paises.csv
```

Formato:

```csv
nombre,poblacion,superficie,continente
Argentina,45376763,2780400,America
Brasil,213993437,8515767,America
```

## Ejecución

Ejecutar desde la terminal:

```bash
python tpi_paises.py
```

## Autores
Nicolas Sancholuz
Agustín Fernández

## Institución

Universidad Tecnológica Nacional (UTN)
Tecnicatura Universitaria en Programación
