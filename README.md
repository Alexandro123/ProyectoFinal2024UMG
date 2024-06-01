# Proyecto Final 2024 - API de Tarjetas de Crédito

Este proyecto es una API desarrollada como parte del Proyecto Final 2024 para un sistema bancario de tarjetas de crédito. La API está construida utilizando Java 17 y Spring Boot, y proporciona funcionalidades esenciales como pagos, consumos, consultas de saldos, fechas de corte, estados de cuenta y detalles de la tarjeta.

## Requisitos previos

- Java Development Kit (JDK) 17
- Maven
- MySQL

## Configuración

1. Clona este repositorio: `git clone https://github.com/tu-usuario/proyecto-final-2024.git`
2. Navega al directorio del proyecto: `cd proyecto-final-2024`
3. Configura las variables de entorno necesarias, como las credenciales de la base de datos.
4. Compila el proyecto: `mvn clean install`
5. Ejecuta la aplicación: `java -jar target/proyecto-final-2024.jar`

## Configuración de la base de datos

- URL de conexión: `viaduct.proxy.railway.net`
- Nombre de la base de datos: `railway`
- Usuario: `root`
- Contraseña: `CBARFiRXhTMwCozsPUPuNBtUjgkZAqGJ`
- Puerto: `37127`

## Despliegue

La API está desplegada en Railway y se puede acceder a través de la siguiente URL:

- URL de la API: `https://lucid-dream-production.up.railway.app`

## Endpoints de la API

- `POST /api/pagos`: Permite realizar pagos a la tarjeta de crédito.
- `POST /api/consumos`: Registra consumos realizados con la tarjeta de crédito.
- `GET /api/saldos`: Proporciona el saldo actual, saldo disponible y saldo al corte.
- `GET /api/fechas-corte`: Obtiene la fecha de corte próxima y pasada.
- `GET /api/estados-cuenta`: Genera y proporciona el estado de cuenta para una fecha de corte específica.
- `GET /api/detalles-tarjeta`: Proporciona detalles de la tarjeta.
- ...

## Contribución

1. Haz un fork de este repositorio.
2. Crea una rama con tu nueva funcionalidad: `git checkout -b mi-nueva-funcionalidad`
3. Realiza los cambios y commitea: `git commit -am 'Agrega nueva funcionalidad'`
4. Haz push a la rama: `git push origin mi-nueva-funcionalidad`
5. Envía una pull request.

## Contacto

- Nombre: [Tu nombre]
- Correo electrónico: [Tu correo electrónico]
- GitHub: [Tu usuario de GitHub]
