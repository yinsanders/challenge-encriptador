# Proyecto de Encriptación y Desencriptación de Texto

Este proyecto es una aplicación web que permite encriptar y desencriptar texto utilizando JavaScript. La encriptación se realiza mediante el reemplazo de ciertas vocales por cadenas de texto específicas. La aplicación proporciona una interfaz de usuario interactiva que permite ingresar texto, encriptarlo, desencriptarlo y copiar el resultado al portapapeles.

## Tabla de Contenidos

- [Características](#características)
- [Tecnologías Utilizadas](#tecnologías-utilizadas)
- [Estructura del Proyecto](#estructura-del-proyecto)
- [Cómo Usar](#cómo-usar)
- [Cómo Ejecutar el Proyecto](#cómo-ejecutar-el-proyecto)
- [Lógica de Encriptación](#lógica-de-encriptación)
- [Contribuciones](#contribuciones)
- [Licencia](#licencia)

## Características

- **Encriptación de Texto:** Convierte el texto ingresado en un formato encriptado reemplazando las vocales con cadenas de texto específicas.
- **Desencriptación de Texto:** Restaura el texto encriptado a su forma original.
- **Copiar al Portapapeles:** Permite copiar el texto encriptado o desencriptado al portapapeles con un solo clic.
- **Interfaz de Usuario Reactiva:** Actualiza la interfaz de usuario para reflejar el estado actual de la aplicación.

## Tecnologías Utilizadas

- **HTML5:** Estructura del contenido de la página.
- **CSS3:** Estilización de la interfaz de usuario.
- **JavaScript (ES6):** Lógica de encriptación y desencriptación.

## Estructura del Proyecto

/proyecto-encriptacion
│
├── index.html         # Página principal de la aplicación
├── styles.css         # Estilos de la aplicación
└── main.js            # Lógica de la aplicación

## Cómo Usar

1. **Abrir la aplicación:** Navegar a la página web donde se encuentra hospedada la aplicación.

2. **Ingresar texto:** Escribe o pega el texto que deseas encriptar en el área de texto proporcionada.

3. **Encriptar texto:** Haz clic en el botón "Encriptar" para convertir el texto a su forma encriptada.

4. **Desencriptar texto:** Haz clic en el botón "Desencriptar" para restaurar el texto a su forma original.

5. **Copiar texto:** Usa el botón "Copiar" para guardar el texto final en el portapapeles.

## Cómo Ejecutar el Proyecto

1. **Clonar el repositorio:**

   ```bash
   git clone https://github.com/yinsanders/proyecto-encriptacion.git

2. **Abrir el archivo index.html:**

Navegar hasta el directorio del proyecto y abrir index.html en tu navegador web preferido.

## Lógica de Encriptación

La encriptación y desencriptación se basan en el siguiente mapeo de caracteres:

Vocal	Reemplazo
e	    enter
o	    ober
i	    imes
a	    ai
u	    ufat

## Contribuciones

Si deseas contribuir a este proyecto, sigue estos pasos:

1. **Haz un fork del repositorio.**

2. **Crea una rama para tu característica (git checkout -b nueva-característica).**

3. **Realiza tus cambios y haz commit (git commit -m 'Agrega nueva característica').**

4. **Haz push a la rama (git push origin nueva-característica).**

5. **Abre un Pull Request.**

## Licencia

Este proyecto está bajo Licencia.