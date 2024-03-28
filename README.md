# Documentación del Proyecto
##  Infraestructura como Código (IaC) con Terraform

En la carpeta terraform/, hemos incluido los archivos necesarios para definir la infraestructura de AWS utilizando Terraform.
•	main.tf: Este archivo define los recursos de AWS que necesitamos para nuestro entorno, como una instancia EC2 y un grupo de seguridad.

**Configuración de Contenedores con Docker**
En la carpeta docker/, encontrarás los archivos relacionados con la configuración de contenedores utilizando Docker.
•	Dockerfile.backend: Este archivo Dockerfile define cómo construir la imagen del contenedor para nuestro backend Node.js. Instala las dependencias y configura el entorno para ejecutar la aplicación.
•	docker-compose.yml: El archivo docker-compose.yml orquesta los contenedores necesarios para ejecutar la aplicación completa, incluyendo el backend y la base de datos MongoDB.

**Pipeline CI/CD con GitHub Actions**
En la carpeta. github/workflows/, hemos incluido el flujo de trabajo de GitHub Actions para el pipeline CI/CD.

•	ci-cd.yml: Este archivo YAML define las acciones que se deben realizar en cada etapa del pipeline, incluyendo la instalación de dependencias, ejecución de pruebas, construcción y despliegue de contenedores en AWS.

**Explicación de Componentes
Terraform**
Terraform se utiliza para definir nuestra infraestructura como código, lo que nos permite gestionarla de manera automatizada y reproducible. En el archivo main.tf, especificamos los recursos de AWS necesarios para nuestro entorno de aplicación.
**Docker**
Docker se utiliza para contenerizar nuestra aplicación, lo que garantiza la portabilidad y consistencia del entorno de ejecución. Hemos creado un Dockerfile para el backend de nuestra aplicación Node.js, donde instalamos las dependencias y configuramos el entorno de ejecución. El archivo docker-compose.yml orquesta los contenedores necesarios para ejecutar la aplicación completa.
**GitHub Actions**
GitHub Actions se utiliza para automatizar nuestro pipeline de integración y entrega continua (CI/CD). En el archivo ci-cd.yml, definimos los pasos necesarios para clonar el repositorio, instalar dependencias, ejecutar pruebas, construir imágenes de Docker y desplegar la aplicación en AWS.
