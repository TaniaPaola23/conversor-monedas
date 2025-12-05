# 💰 Conversor de Monedas - Challenge Java

![Java](https://img.shields.io/badge/Java-21-orange) ![Maven](https://img.shields.io/badge/Maven-Project-blue) ![Status](https://img.shields.io/badge/Status-En%20Desarrollo-green)

Bienvenido al repositorio oficial de nuestro proyecto final. Esta es una aplicación de consola en Java que realiza conversiones de divisas en tiempo real consumiendo una API externa y registrando el historial de consultas.

## 🚀 Características del Proyecto

- **Conversión en Tiempo Real:** Consumo de la [ExchangeRate-API](https://www.exchangerate-api.com/) para obtener tasas actualizadas.
- **Interfaz de Consola:** Menú interactivo y fácil de usar.
- **Historial de Consultas:** Generación automática de archivos JSON con las últimas conversiones realizadas.
- **Arquitectura Limpia:** Separación de responsabilidades (Modelo, Servicio, Vista).

## 🛠️ Tecnologías Utilizadas

- **Java 21:** Lenguaje principal (uso de `Records`, `HttpClient`).
- **Maven:** Gestión de dependencias.
- **Gson:** Librería de Google para serialización/deserialización de JSON.
- **Visual Studio Code:** Entorno de desarrollo recomendado.
- **Git & GitHub:** Control de versiones y trabajo colaborativo.

## 📋 Pre-requisitos

Antes de empezar, asegúrate de tener instalado:
1.  **Java JDK 21**: [Descargar aquí](https://adoptium.net/).
2.  **Visual Studio Code** con el "Extension Pack for Java".
3.  Una **API Key** gratuita de ExchangeRate-API.

## 🔧 Instalación y Ejecución

Sigue estos pasos para correr el proyecto en tu máquina local:

1.  **Clonar el repositorio:**
    ```bash
    git clone [https://github.com/TaniaPaola23/conversor-monedas.git](https://github.com/TaniaPaola23/conversor-monedas.git)
    ```

2.  **Abrir en VS Code:**
    Abre la carpeta del proyecto. Espera a que cargue la configuración de Maven (puede tardar unos segundos la primera vez).

3.  **Configurar la API Key:**
    *Ve a la clase `ConsultaMoneda.java` (o donde definan la conexión) y reemplaza la variable de la API Key con tu propia clave.*

4.  **Ejecutar:**
    Busca el archivo `src/main/java/com/conversor/Principal.java` y dale clic a **Run**.

## 👥 Equipo de Desarrollo (Squad)

Este proyecto es desarrollado bajo la metodología Scrum por 6 integrantes 

## 📂 Estructura del Proyecto

```text
src/main/java/com/conversor/
├── model/       # Records (Moneda.java)
├── service/     # Lógica de conexión a API y cálculos
├── ui/          # Menús e interacción con usuario
├── utils/       # Validaciones y herramientas
└── Principal.java  # Punto de entrada (Main)