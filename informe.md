# Práctica Servidor Web con Docker y Nginx

## 1. Contenedores servidor web

**Despliegue de Servidores Web en Contenedores Docker usando Nginx**

## 2. Tiempo de duración

**2 hroas**

## 3. Fundamentos

## ¿Qué es Docker y cómo funciona?

Según el repositorio de Red Hat, **Docker** es la tecnología de organización en contenedores que posibilita la creación y el uso de los contenedores de Linux®.

La tecnología Docker utiliza el kernel de Linux y sus funciones, como los **grupos de control** y los **espacios de nombre**, para dividir los procesos y ejecutarlos de manera independiente.  
El propósito de los contenedores es ejecutar varios procesos y aplicaciones por separado para que se pueda aprovechar mejor la infraestructura y, al mismo tiempo, conservar la seguridad que se obtendría con los sistemas individuales.

---

## ¿Qué son los contenedores?

Las herramientas de los contenedores, como Docker, proporcionan un **modelo de implementación basado en imágenes**.  
Esto permite compartir fácilmente una aplicación o un conjunto de servicios, con todas las dependencias en varios entornos.

Docker también **automatiza la implementación** de las aplicaciones (o los conjuntos de procesos que las constituyen) en el entorno de contenedores.

---

## ¿Qué es Nginx?

**Nginx**, pronunciado como “engine-ex”, es un **servidor web de código abierto** que, desde su éxito inicial como servidor web, ahora también es usado como:
- Proxy inverso
- Caché de HTTP
- Balanceador de carga

### Algunas características comunes de Nginx incluyen:
- Proxy inverso con caché
- Soporte para IPv6
- Balanceo de carga
- Soporte FastCGI con almacenamiento en caché
- Websockets
- Manejo de archivos estáticos, archivos de índice y auto indexación
- TLS / SSL con SNI

---

## ¿Qué es una imagen en contenedores?

Una **imagen de contenedor** es como una *plantilla* o *receta* que contiene todo lo necesario para ejecutar una aplicación.

> Piénsalo así: si el contenedor es la "casa", la imagen es el "plano de construcción".

### Esta imagen incluye:
- El código de la aplicación.
- Las dependencias (librerías, frameworks).
- Herramientas mínimas del sistema operativo.
- Archivos de configuración.

## 4. Conocimientos previos

- Comandos básicos de Linux.
- Manejo de navegador web.
- Conceptos básicos de virtualización.
- Conocimientos sobre contenedores Docker.
- Edición de archivos HTML.

## 5. Objetivos a alcanzar

- Implementar contenedores con Nginx.
- Manipular archivos de configuración dentro de contenedores.
- Personalizar páginas web mediante la edición de archivos HTML dentro de Nginx.
- Validar la visualización correcta desde un navegador.

## 6. Equipo necesario

- Computador con sistema operativo **Windows/Linux/MacOS**.
- Cuenta en **Docker Play** o instalación local de Docker.
- Docker versión **XX.XX.XX** (colocar la versión instalada).
- Conexión a Internet.
- Editor de texto (por ejemplo: Visual Studio Code o Nano).

## 7. Material de apoyo

- [Documentación oficial de Docker](https://docs.docker.com/)
- [Guía de la asignatura](#) *(coloca enlace si tienes)*
- [Cheat Sheet de comandos Linux](https://education.github.com/git-cheat-sheet-education.pdf)
- Documentación de Nginx.

## 8. Procedimiento

## Paso 1 
# Instalación de docker 
  
 ![Texto alternativo](https://github.com/Edissonfierro/docker1/blob/main/1.jpg)

  ![Texto alternativo](https://github.com/Edissonfierro/docker1/blob/main/2.jpg)

## Paso 2 
# Creación de contenedores
 ![Texto alternativo](https://github.com/Edissonfierro/docker1/blob/main/3.jpg)


## PAso 3 Copiar el archivo html

![Texto alternativo](https://github.com/Edissonfierro/docker1/blob/main/4.jpg)

## PAso 4 Editar los archivos con nano 

![Texto alternativo](https://github.com/Edissonfierro/docker1/blob/main/5.jpg)
![Texto alternativo](https://github.com/Edissonfierro/docker1/blob/main/6.jpg)

  ## 9. Resultados esperados

##Local host 8089
![Texto alternativo](https://github.com/Edissonfierro/docker1/blob/main/7.jpg)
##Local host 8090

![Texto alternativo](https://github.com/Edissonfierro/docker1/blob/main/8.jpg)

##Evidencia de los contenedores 

![Texto alternativo](https://github.com/Edissonfierro/docker1/blob/main/9.jpg)


## 10. Bibliografía

Red Hat. (n.d.). *What is Docker?*. Red Hat. Recuperado el 12 de abril de 2025, de https://www.redhat.com/es/topics/containers/what-is-docker

Kinsta. (n.d.). *¿Qué es Nginx?*. Kinsta. Recuperado el 12 de abril de 2025, de https://kinsta.com/es/base-de-conocimiento/que-es-nginx/

