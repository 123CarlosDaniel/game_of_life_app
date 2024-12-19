# El Juego de la Vida

Una implementación del famoso "Juego de la Vida" de John Conway, creada con tecnologías modernas para ofrecer una experiencia interactiva y visualmente atractiva. Esta aplicación utiliza una arquitectura full stack con tecnologías de frontend y backend escalables.

## Tecnologías utilizadas

### Frontend
- **Next.js**: Framework de React para aplicaciones web.
- **React.js**: Librería para construir interfaces de usuario.
- **TailwindCSS**: Framework de CSS para estilos rápidos y personalizados.
- **HTML Canvas**: Para renderizar la simulación del juego.
- **Auth.js v5**: Manejo de autenticación para usuarios.

### Backend
- **FastAPI**: Framework rápido para construir APIs en Python.
- **MySQL**: Base de datos relacional para almacenar información del juego y usuarios.
- **Procedimientos almacenados**: Lógica avanzada directamente en la base de datos para optimizar operaciones.

## Características principales

- Simulación interactiva del Juego de la Vida usando HTML Canvas.
- Autenticación de usuarios con Auth.js v5.
- Backend robusto en FastAPI para manejo de datos y operaciones.
- Base de datos eficiente con MySQL y procedimientos almacenados.
- Estilos personalizables y responsive con TailwindCSS.
- Experiencia fluida gracias a la integración de Next.js y React.js.

## Instalación

1. **Clonar el repositorio**
   ```bash
   git clone [<URL-del-repositorio>](https://github.com/123CarlosDaniel/online-editor.git)
   cd online-editor
   ```

2. **Configurar el entorno del frontend**
   - Navega a la carpeta `frontend`.
   - Instala las dependencias:
     ```bash
     npm install
     ```

3. **Configurar el entorno del backend**
   - Navega a la carpeta `backend`.
   - Instala las dependencias necesarias para Python:
     ```bash
     pip install -r requirements.txt
     ```

4. **Configurar la base de datos**
   - Crea una base de datos MySQL.
   - Ejecuta el script de inicialización proporcionado para crear las tablas y los procedimientos almacenados.

5. **Configurar variables de entorno**
   - Crea un archivo `.env` tanto para el frontend como para el backend.
   - Configura los detalles de conexión a la base de datos, claves secretas para autenticación, y otros parámetros necesarios.

6. **Ejecutar la aplicación**
   - Inicia el backend:
     ```bash
     uvicorn main:app --reload
     ```
   - Inicia el frontend:
     ```bash
     npm run dev
     ```

7. **Acceso a la aplicación**
   - Abre tu navegador en `http://localhost:3000`.

## Uso

- Los usuarios pueden registrarse e iniciar sesión para guardar configuraciones personalizadas del juego.
- La simulación permite pausar, reanudar y ajustar la velocidad de los ciclos del juego.
- El canvas es escalable y admite zoom para ver detalles de la simulación.

## Contribuciones

Contribuciones son bienvenidas. Por favor, sigue los pasos:

1. Realiza un fork del repositorio.
2. Crea una nueva rama para tu función:
   ```bash
   git checkout -b nueva-funcion
   ```
3. Realiza tus cambios y haz commit:
   ```bash
   git commit -m "Agregada nueva función"
   ```
4. Envía un pull request.

## Licencia

Este proyecto está licenciado bajo la [MIT License](LICENSE).

---
© 2024 - Proyecto "El Juego de la Vida"

