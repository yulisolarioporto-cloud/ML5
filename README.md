# Proyectos de Clasificación con Inteligencia Artificial

Dos ejercicios prácticos que utilizan **p5.js** para la interfaz visual y **ml5.js** para ejecutar modelos de Inteligencia Artificial directamente en el navegador.

---

##  Descripción de los Ejercicios

### Ejercicio 01: Reconocimiento de Imágenes Estáticas (MobileNet)
Este script permite analizar imágenes de forma dinámica sin necesidad de modificar el código fuente para cambiar la ruta de los archivos.
* **Cómo funciona:** El usuario elige un animal desde un menú desplegable (`<select>`). La página carga la imagen en el lienzo al instante, la procesa con el modelo pre-entrenado **MobileNet** y muestra el nombre del objeto junto con su porcentaje de confianza directamente sobre la foto.

### Ejercicio 02: Scanner de Objetos con Barras (Teachable Machine)
Este script utiliza la cámara web en tiempo real para clasificar objetos mediante un modelo personalizado.
* **Cómo funciona:** El modelo fue entrenado previamente con **5 objetos específicos**. Al iniciar la cámara, el lienzo muestra el video en vivo y genera automáticamente 5 barras de progreso de diferentes colores. Estas barras aumentan o disminuyen su tamaño en tiempo real para mostrar el nivel de confianza de la IA por cada uno de los objetos entrenados.

---

##  Requisitos para Ejecución

1. **Servidor Local:** Es obligatorio usar un servidor local (como la extensión *Live Server* de Visual Studio Code o el módulo de Python) debido a las restricciones de seguridad de los navegadores al cargar modelos e imágenes.
2. **Conexión a Internet:** Se requiere conexión para cargar las librerías de p5.js y ml5.js desde sus respectivos enlaces externos (CDNs).
