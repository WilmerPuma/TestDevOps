# Documentación del Proyecto
##  Infraestructura como Código (IaC) con Terraform

 se incluye los archivos necesarios para definir la infraestructura de AWS utilizando Terraform.
-	main.tf: Este archivo define los recursos de AWS que necesitamos para nuestro entorno, como una instancia EC2 y un grupo de seguridad.

##### Configuración de Contenedores con Docker

En la carpeta PruebasDevOps/, encontrarás los archivos relacionados con la configuración de contenedores utilizando Docker.
- Dockerfile.backend: Este archivo Dockerfile define cómo construir la imagen del contenedor para nuestro backend Node.js. Instala las dependencias y configura el entorno para ejecutar la aplicación.
- Docker-compose.yml: El archivo docker-compose.yml orquesta los contenedores necesarios para ejecutar la aplicación completa, incluyendo el backend y la base de datos MongoDB.

##### Pipeline CI/CD con GitHub Actions
En la carpeta. github/workflows/, hemos incluido el flujo de trabajo de GitHub Actions para el pipeline CI/CD.

-	ci-cd.yml: Este archivo YAML define las acciones que se deben realizar en cada etapa del pipeline, incluyendo la instalación de dependencias, ejecución de pruebas, construcción y despliegue de contenedores en AWS.

