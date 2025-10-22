# Web Automation Backend

<img src="https://img.icons8.com/color/48/000000/docker.png" alt="Docker" title="Docker"/> <img src="https://img.icons8.com/color/48/000000/python.png" alt="Python" title="Python"/> <img src="https://img.icons8.com/color/48/000000/postgreesql.png" alt="PostgreSQL" title="PostgreSQL"/> <img src="https://playwright.dev/img/playwright-logo.svg" width="48" alt="Playwright" title="Playwright"/> <img src="https://img.icons8.com/color/48/000000/api.png" alt="API REST" title="API REST"/>

## 📋 Descripción del Proyecto

Backend desarrollado en Python para automatizar la extracción de datos de páginas web utilizando **Playwright**. La aplicación extrae información relevante de productos y almacena los datos en una base de datos **PostgreSQL** de manera eficiente y escalable.

## 🎯 Características

- **Web Scraping**: Extracción de datos de múltiples sitios web
- **Almacenamiento**: Base de datos PostgreSQL para persistencia
- **Escalabilidad**: Arquitectura modular para agregar nuevos sitios
- **Containerizado**: Implementación con Docker para fácil despliegue
- **API REST**: Interfaz para interactuar con los datos extraídos


## 🛠️ Stack Tecnológico

| Tecnología | Función |
||-|
| **🐳 Docker** | Containerización y orquestación |
| **🐍 Python** | Lógica de backend y scraping |
| **🎭 Playwright** | Automatización y extracción web |
| **🐘 PostgreSQL** | Almacenamiento de datos |
| **🔗 FastAPI** | API REST para interfaz |


## 📊 Diagrama de Base de Datos

<p align="center">
  <img src="misc\db.png" width="600" alt="Diagrama de Base de Datos"/>
</p>


## 🌐 Sitios Web Soportados

[🛒 SauceDemo](https://www.saucedemo.com/)

[🧪 Practice Software Testing](https://practicesoftwaretesting.com/)

## 🚀 Instalación y Ejecución

Gracias a Docker, las pruebas pueden realizarse fácilmente siguiendo estos pasos:

1. Clonar el repositorio.
2. Modificar, si es necesario, el archivo *.env* con la configuración deseada.
3. Tener Docker instalado y ejecutándose.
4. Desde consola, levantar el proyecto con:

~~~
docker-compose up --build
~~~

5. Podremos acceder a la API desde http://localhost:8000

<br>

*`Proyecto desarrollado como parte de un challenge individual de scraping a páginas web`*
