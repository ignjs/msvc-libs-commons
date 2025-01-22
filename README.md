# libs-msvc-commons

Proyecto de demostración para Spring Boot que excluye la configuración automática de la fuente de datos.

## Descripción

Este proyecto proporciona una base común para microservicios en Spring Boot, excluyendo la configuración automática de la fuente de datos. Es útil para proyectos que no requieren una base de datos o que manejan la configuración de la base de datos de manera manual.

## Requisitos

- Java 21
- Maven 3.6.3 o superior

## Instalación

1. Clona el repositorio:
    ```sh
    git clone <URL_DEL_REPOSITORIO>
    ```
2. Navega al directorio del proyecto:
    ```sh
    cd libs-msvc-commons
    ```
3. Compila el proyecto con Maven:
    ```sh
    mvn clean install
    ```

## Uso

Para ejecutar la aplicación, usa el siguiente comando:
```sh
mvn spring-boot:run
```

## Integración en otros proyectos

Para integrar libs-msvc-commons en otros proyectos, sigue estos pasos:
1. Añade la dependencia en el archivo pom.xml de tu proyecto:
```xml
<dependency>
    <groupId>com.ign.libs.msvc.commons</groupId>
    <artifactId>libs-msvc-commons</artifactId>
    <version>0.0.1-SNAPSHOT</version>
</dependency>
```

2. Asegúrate de que tu proyecto esté configurado para usar el repositorio donde se encuentra libs-msvc-commons.
