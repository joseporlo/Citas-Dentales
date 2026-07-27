# Sistema de Administracion Dental (Dentixx / GPS)

Este proyecto es un ecosistema integral disenado para la administracion y gestion de clinicas odontologicas. Permite centralizar los historiales clinicos, agendar citas y mantener un control estricto de los pacientes y los tratamientos medicos.

## Estructura del Proyecto

- BaseDentixxOficial.sql: Archivo principal con el modelado y definicion completa de la base de datos relacional. Garantiza la integridad referencial de los historiales clinicos.
- Dentixx/: Directorio principal de la aplicacion, segmentado en modulos para mayor escalabilidad.
  - MODULO1 a MODULO4: Diferentes componentes y logica de negocio del sistema (por ejemplo: Citas, Expedientes, Inventario, Reportes).
  - api/: Endpoints y controladores para la comunicacion y el flujo de datos.
  - config/: Configuraciones del sistema y conexion segura a la base de datos.
  - assets/ y uploads/: Recursos estaticos y almacenamiento de archivos subidos por los usuarios.

## Caracteristicas Principales

- Modelado Relacional: Diseno de base de datos robusto para garantizar la persistencia e integridad de la informacion medica sensible.
- Arquitectura Modular: Codigo segmentado en directorios independientes para facilitar el mantenimiento y desarrollo colaborativo.
- API Integrada: Flujo de informacion optimizado a traves de una estructura de API interna.

## Instalacion y Configuracion

1. Importar el archivo BaseDentixxOficial.sql en el gestor de base de datos local (MySQL/SQL Server).
2. Localizar el directorio config/ y actualizar las credenciales de acceso a la base de datos.
3. Montar la aplicacion en el servidor web local correspondiente.
