# 🎯 Gestión de Hábitos - Full Stack App
Universidad Galileo
Tecnico en Desarrollo de Software
Programacion Avanzada

**Gestión de Hábitos** es una aplicación diseñada para ayudar a los usuarios a **crear, administrar y monitorear hábitos** de manera efectiva.  
Este repositorio contiene **tanto el frontend (Next.js) como el backend (Express.js con MongoDB)**.

---

## 🚀 **Tecnologías Utilizadas**
### **Frontend (Next.js + Redux)**
- **Next.js** (Framework basado en React)
- **TypeScript** (Tipado estático para mejor seguridad)
- **Tailwind CSS** (Estilos modernos y responsivos)
- **Redux Toolkit** (Manejo de estado global)
- **Fetch API** (Para la comunicación con el backend)

### **Backend (Express + MongoDB)**
- **Node.js + Express.js** (API RESTful)
- **MongoDB + Mongoose** (Base de datos NoSQL)
- **dotenv** (Gestión de variables de entorno)
- **Cors** (Permitir solicitudes entre frontend y backend)

---

## 📂 **Estructura del Proyecto**
gestionhabitos/ ├── frontend/ # Cliente - Next.js │ ├── app/ # Páginas y componentes │ ├── feature/habit/ # Estado global de hábitos │ ├── Redux/ # Configuración de Redux │ ├── public/ # Archivos estáticos │ ├── package.json # Dependencias │ ├── README.md # Documentación del frontend ├── backend/ # Servidor - Express.js │ ├── config/ # Configuración de la BD │ ├── modelo/ # Modelos de datos │ ├── routes/ # Endpoints de la API │ ├── bin/www # Servidor Express │ ├── package.json # Dependencias │ ├── README.md # Documentación del backend ├── .gitignore # Archivos ignorados por Git └── README.md # Este archivo de documentación general

---

## 🛠 **Requisitos Previos**
Antes de comenzar, asegúrate de tener instalado:

- **Node.js** (versión 18 o superior) ➜ [Descargar](https://nodejs.org/)
- **MongoDB** (Base de datos) ➜ [Descargar](https://www.mongodb.com/)
- **Git** (Para clonar el proyecto) ➜ [Descargar](https://git-scm.com/)

---

## 🚀 **Instalación y Configuración**

### **1️⃣ Clonar el Repositorio**
Ejecuta el siguiente comando en la terminal:

git clone https://github.com/jonalex2020/gestionhabitos.git
Luego, entra en la carpeta del proyecto:

cd gestionhabitos
⚡ Configuración del Backend
1️⃣ Ir a la carpeta del backend:

cd backend
2️⃣ Instalar dependencias:

npm install
3️⃣ Configurar variables de entorno (.env)
Crea un archivo .env en la carpeta backend/ y agrega:

MONGO_URI=mongodb+srv://jonalexmerida:%40L3x%40nd3rm3r1d408101986%C3%B1@cluster0.qgzox.mongodb.net/habitosApp?retryWrites=true&w=majority&appName=Cluster0
PORT=3000

📌 Pega este codigo con las credenciales reales.

4️⃣ Iniciar el backend:

npm start
📌 Esto iniciará el servidor en http://localhost:3000.

⚡ Configuración del Frontend
1️⃣ Ir a la carpeta del frontend:

cd ../frontend
2️⃣ Instalar dependencias:

npm install
3️⃣ Ejecutar el frontend:

npm run dev
📌 Esto iniciará el frontend en http://localhost:3001.

📡 Endpoints del Backend
El backend expone los siguientes endpoints:

Método	Endpoint	Descripción
GET	/habits	Obtiene todos los hábitos
POST	/habits	Crea un nuevo hábito
PUT	/habits/:id	Actualiza un hábito por ID
DELETE	/habits/:id	Elimina un hábito por ID
🎨 Interfaz de Usuario
La aplicación usa Tailwind CSS para los estilos.
Puedes personalizar el diseño modificando frontend/app/globals.css.
📦 Construcción y Despliegue
Backend
Para ejecutar en producción:

npm run build
npm start
Frontend
Para generar la versión optimizada:

npm run build
npm start
🛠 Comandos Útiles
Comando	Descripción
git pull origin main	Traer cambios desde GitHub
git add .	Agregar archivos al seguimiento
git commit -m "msg"	Guardar cambios en el historial
git push origin main	Subir cambios a GitHub
📜 Licencia
Este proyecto está bajo la licencia MIT.

🤝 Creador
Jonalex Mérida | GitHub

📄 8. Licencia

Este proyecto está bajo la licencia MIT. Puedes modificarlo y usarlo libremente. 😊
