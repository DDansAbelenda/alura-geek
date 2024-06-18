# Alura_Geek
Este proyecto es una aplicación web desarrollada como parte del desafío del curso de Front End de Alura Latam. El objetivo del desafío es medir las habilidades en HTML, CSS y JavaScript a través del desarrollo de una aplicación que permita listar, registrar y eliminar productos. Además, se utiliza JSON-Server para crear una API y desplegarla en Vercel.

## Funcionalidades

La aplicación incluye las siguientes funcionalidades:

1. **Listado de productos**: Mostrar una lista de productos con su nombre, precio y descripción.
2. **Registro de productos**: Permitir al usuario agregar nuevos productos a la lista.
3. **Eliminación de productos**: Permitir al usuario eliminar productos de la lista.

## Tecnologías Utilizadas

- **HTML**: Para la estructura de la aplicación.
- **CSS**: Para el diseño y la presentación visual.
- **JavaScript**: Para la lógica y la interactividad de la aplicación.
- **JSON-Server**: Para crear una API simulada.
- **Vercel**: Para desplegar la API y la aplicación web.

## Instrucciones de Instalación

Para ejecutar la aplicación en tu máquina local, sigue estos pasos:

1. Clona este repositorio en tu máquina local:
   ```bash
   git clone https://github.com/DDansAbelenda/challenge-one-alura-geek.git
   ```
2. Navega al directorio del proyecto:
   ```bash
   cd challenge-one-alura-geek
   ```
3. Instala las dependencias del proyecto:
   ```bash
   npm install
   ```
4. Inicia el servidor JSON-Server:
   ```bash
   npx json-server --watch db.json
   ```
5. Abre en tu navegador el `index.html` para ver la aplicación.

## Despliegue en Vercel

La API está desplegada en Vercel. Puedes acceder a la API en el siguiente enlace:

[Enlace a la API](https://challenge-one-alura-geek-fake-api.vercel.app/)

## Uso de la Aplicación

1. **Listado de productos**:
   - Al abrir la aplicación, verás una lista de productos ya existentes obtenidos desde la API.

2. **Registro de productos**:
   - Completa el formulario con el nombre, precio y descripción del producto.
   - Haz clic en el botón "Agregar Producto" para añadir el producto a la lista y a la API.

3. **Eliminación de productos**:
   - Cada producto en la lista tiene un botón "Eliminar".
   - Haz clic en el botón "Eliminar" para eliminar el producto correspondiente de la lista y de la API.

## Contribuciones

Las contribuciones son bienvenidas. Si deseas mejorar este proyecto, por favor sigue estos pasos:

1. Haz un fork de este repositorio.
2. Crea una nueva rama:
   ```bash
   git checkout -b feature/nueva-funcionalidad
   ```
3. Realiza tus cambios y commitea:
   ```bash
   git commit -m "Agrega nueva funcionalidad"
   ```
4. Empuja tus cambios a tu repositorio:
   ```bash
   git push origin feature/nueva-funcionalidad
   ```
5. Abre un Pull Request en GitHub.

