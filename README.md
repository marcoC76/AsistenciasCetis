## Sistema de Asistencia con Escaner QR 

Este repositorio contiene el código fuente para un sistema de asistencia simple que utiliza un escáner de códigos QR para registrar la presencia de los estudiantes. 

**Características:**

* **Escáner QR:** Implementa un escáner QR que detecta códigos QR desde la cámara del dispositivo.
* **Registro de asistencia:**  El escáner envía la información del código QR a una hoja de cálculo de Google para registrar la asistencia.
* **Interfaz de usuario:** Un diseño sencillo y fácil de usar para facilitar el registro.
* **Configuración flexible:** Se puede personalizar la configuración mediante un archivo JSON para definir la URL de la hoja de cálculo, colores de la interfaz, etc.

**Uso:**

1. **Configuración:** 
    * Crea un archivo `config.json` con las siguientes propiedades:
        * **googleSheetsLinks:** Un objeto que contiene las URLs de las hojas de cálculo para cada materia.
        * **interfaceColors:** Un objeto que contiene los colores de la interfaz (primario, secundario, texto).
        * **subjects:** Un arreglo que contiene las materias disponibles.
    * Introduce la ID de tu hoja de cálculo de Google en la URL correspondiente.
2. **Despliegue:** 
    *  Abre el archivo `index.html` en un navegador web.
    *  Asegúrate de tener habilitada la cámara de tu dispositivo.
3. **Escaneado:**
    *  Haz clic en el botón "Leer QR".
    *  Apunta la cámara al código QR de asistencia.
    *  El sistema registrará la asistencia en la hoja de cálculo de Google.

**Requisitos:**

* Un navegador web compatible con HTML5 y Javascript.
* Una cuenta de Google para utilizar las hojas de cálculo.
* Un escáner QR en el dispositivo.

**Tecnologías:**

* HTML5
* Javascript
* ZXing.js (librería de escaneo QR)
* Google Sheets

**Instalación:**

1. Clona este repositorio.
2. Abre `index.html` en un navegador.
3. Configura `config.json` con tus propios datos.

**Nota:**

* La seguridad de la información registrada depende de la configuración de tu hoja de cálculo de Google.
* Este proyecto es solo un ejemplo básico y puede necesitar ajustes para funcionar en diferentes entornos.

**Contribuciones:**

Las contribuciones son bienvenidas. Puedes crear una solicitud de extracción (pull request) para mejorar el código, agregar nuevas funciones o corregir errores.

**Licencia:**

Este proyecto está bajo la licencia MIT.


**Contacto:**

Si tienes alguna pregunta o comentario, por favor contacta al autor del proyecto.
