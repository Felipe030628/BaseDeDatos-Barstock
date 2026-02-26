# BaseDeDatos-Barstock
Archivos Actualizados de todo el proyecto Barstock
📌 Sistema de Gestión para Bar – Base de Datos (NetBeans + MySQL)

Este proyecto corresponde al desarrollo de la base de datos y su integración mediante JDBC en NetBeans, para un sistema de gestión de un bar.

El sistema permite administrar la información relacionada con pedidos, pagos, usuarios, productos y control de inventario, implementando operaciones CRUD completas desde Java hacia MySQL.

🗄️ Base de Datos

La base de datos fue desarrollada en MySQL con el nombre:

barstock


Incluye las siguientes tablas principales:

Usuarios

Tipos de Documentos

Productos

Categorías

Movimientos de Stock

Pedido Cabecera

Seguimiento de Pedido

Pagos

Métodos de Pago

Mesas

Cada tabla está correctamente relacionada mediante claves primarias y foráneas para garantizar integridad referencial.

💻 Tecnologías Utilizadas

Java (POO)

JDBC

MySQL

NetBeans

Patrón DAO (Data Access Object)

⚙️ Funcionalidades Implementadas

✔ Insertar registros
✔ Consultar registros por ID
✔ Actualizar información
✔ Eliminar registros
✔ Conexión a base de datos mediante JDBC

Cada entidad cuenta con su respectiva clase modelo y su clase DAO para manejar la persistencia de datos.

🏗️ Arquitectura

El proyecto está organizado bajo una estructura tipo MVC:

modelo → Clases que representan las entidades

Controlador → Clases DAO con la lógica de acceso a datos

Vista → Clases de prueba para ejecutar las operaciones

🎯 Objetivo del Proyecto

Desarrollar un sistema estructurado y escalable que permita la gestión eficiente de un bar, aplicando buenas prácticas de Programación Orientada a Objetos y conexión a bases de datos relacionales.
