# 📜 Obtención de Nombres de Funciones PHP con Electron

¡Bienvenido! 🎉 Esta aplicación, creada con [Electron](https://www.electronjs.org/), te permite obtener fácilmente los nombres de todas las funciones en un archivo PHP. Esto es muy útil para refactorizar tu código sin necesidad de hacer scroll, copiar y pegar. 🚀

## 🌟 Características

- **Carga de archivos PHP**: Selecciona cualquier archivo PHP desde tu ordenador.
- **Extracción de funciones**: Obtén una lista de todas las funciones definidas en el archivo PHP.
- **Visualización clara**: Las funciones se muestran en una lista fácil de leer.

## 🛠️ Instalación

Sigue estos pasos para instalar y ejecutar la aplicación en tu máquina:

1. **Clona el repositorio**:

    ```bash
    git clone https://github.com/tuusuario/tu-repositorio.git
    ```

2. **Navega al directorio del proyecto**:

    ```bash
    cd tu-repositorio
    ```

3. **Instala las dependencias**:

    ```bash
    npm install
    ```

## 🚀 Ejecución

Una vez que hayas instalado todas las dependencias, puedes iniciar la aplicación con el siguiente comando:

```bash
npm start
```

## 📄 Descripción de Archivos
**index.html**
Este archivo contiene la interfaz de usuario para cargar archivos PHP y mostrar los nombres de las funciones. Incluye un formulario para seleccionar un archivo PHP y un script para procesar el archivo y extraer los nombres de las funciones.

**main.js**
Este archivo configura la ventana principal de la aplicación Electron. Se encarga de cargar el archivo HTML y de gestionar la ventana de la aplicación, asegurando que la interfaz se muestre correctamente y que la caché del navegador esté deshabilitada.

## 💻 Contribución

¡Las contribuciones son bienvenidas! Si tienes alguna idea para mejorar esta aplicación, siéntete libre de abrir un issue o enviar un pull request.

## 📜 Licencia

Este proyecto está bajo la Licencia MIT.
