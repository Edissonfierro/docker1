# Práctica Servidor Web con Docker y Nginx

## 1. Contenedores servidor web

**Despliegue de Servidores Web en Contenedores Docker usando Nginx**

## 2. Tiempo de duración

**2 hroas**

## 3. Fundamentos

Docker es una plataforma que permite crear, desplegar y ejecutar aplicaciones 
mediante contenedores. Un contenedor es una unidad estándar de software que 
empaqueta el código y todas sus dependencias para que la aplicación se ejecute 
de manera rápida y confiable en cualquier entorno.

Nginx es un servidor web ligero, de alto rendimiento, que también funciona como 
proxy inverso, equilibrador de carga, y más. Su eficiencia lo ha posicionado como 
uno de los servidores más populares a nivel mundial.

Esta práctica combina Docker y Nginx para demostrar cómo levantar múltiples 
servidores web dentro de contenedores, facilitando la portabilidad, escalabilidad y 
eficiencia del desarrollo.

**Imagen 1-1: Arquitectura de Docker y contenedores Nginx**

![Arquitectura de Docker](https://www.docker.com/wp-content/uploads/2022/03/what-is-docker-1024x576.png)

**Imagen 1-2: Funcionamiento de Nginx**

![Funcionamiento de Nginx](https://miro.medium.com/max/1400/1*kgLHLsRYZ8XZ37DT0F8Ovg.png)

Docker simplifica la administración de servidores web, permitiendo el despliegue de múltiples instancias de Nginx en contenedores independientes que funcionan de manera simultánea en un mismo sistema anfitrión.

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

**Paso 1:** Crear el primer contenedor Nginx llamado nginx1 exponiendo el puerto 8089.
```bash
docker run -d --name nginx1 -p 8089:80 nginx
