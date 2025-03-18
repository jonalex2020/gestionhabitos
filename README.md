# 🎯 Gestión de Hábitos - Frontend
Universidad Galileo
Tecnico en Desarrollo de Software
Programacion Avanzada

Este es el **frontend** de la aplicación **Gestión de Hábitos**, desarrollado con **Next.js** y **Redux Toolkit**.  
Permite visualizar, crear y administrar hábitos de manera sencilla.

## 🚀 Tecnologías Utilizadas

- **Next.js** (Framework de React para SSR y SSG)
- **TypeScript** (Tipado estático para mayor seguridad)
- **Tailwind CSS** (Estilos modernos y responsivos)
- **Redux Toolkit** (Manejo de estado global)
- **Fetch API** (Consumo de la API del backend en Express)

---

## 📂 **Estructura del Proyecto**

frontend/ 
├── app/ # Contenedor principal de la app │ 
├── layout.tsx # Layout global │ 
├── page.tsx # Página principal │ 
├── habits.tsx # Componente para mostrar hábitos │ 
├── StoreProvider.tsx # Proveedor de Redux │ 
├── globals.css # Estilos generales 
├── feature/habit/ # Módulo de hábitos │ 
├── habitSlice.ts # Estado y acciones de Redux │ 
├── habitApi.ts # Función para llamar a la API 
├── Redux/ # Configuración de Redux │ 
├── store.ts # Configuración de la store global 
├── public/ # Archivos públicos ├── .gitignore # Archivos ignorados por Git 
├── package.json # Dependencias del proyecto └── tsconfig.json # Configuración de TypeScript

---

## 🎯 **Requisitos Previos**

Antes de empezar, asegúrate de tener instalado:

- **Node.js** (versión 18 o superior) ➜ [Descargar](https://nodejs.org/)
- **Git** (para clonar el proyecto) ➜ [Descargar](https://git-scm.com/)

---

## ⚡ **Instalación y Configuración**

1️⃣ **Clonar el repositorio**:


git clone https://github.com/jonalex2020/gestionhabitos.git
2️⃣ Ingresar al directorio del frontend:


cd gestionhabitos/frontend
3️⃣ Instalar dependencias:


npm install
🚀 Ejecutar el Proyecto en Desarrollo
Para iniciar el frontend en modo desarrollo, usa:


npm run dev
🔹 Por defecto, la aplicación estará disponible en:
👉 http://localhost:3001

🔗 Conectar con el Backend
El frontend se comunica con el backend Express.js en el puerto 3000.
Si el backend no está corriendo, inicia su servidor primero:


cd ../backend
npm start
🔹 Asegúrate de que las variables de entorno están configuradas correctamente.

🎨 Diseño y UI
El frontend usa Tailwind CSS para los estilos.
Si deseas personalizar el diseño, modifica los archivos en:


frontend/app/globals.css
📡 Consumo de API (Endpoints)
El frontend se comunica con los siguientes endpoints:

Método	Endpoint	Descripción
GET	/habits	Obtiene todos los hábitos
POST	/habits	Crea un nuevo hábito
PUT	/habits/:id	Actualiza un hábito por ID
DELETE	/habits/:id	Elimina un hábito por ID
📦 Construir para Producción
Para generar una versión optimizada del proyecto, usa:

npm run build
Esto generará la carpeta .next con los archivos listos para producción.

🛠 Comandos Útiles

Comando	Descripción
npm install	Instala dependencias
npm run dev	Inicia el servidor en desarrollo
npm run build	Genera la versión de producción
npm run start	Inicia la aplicación en producción

📜 Licencia
Este proyecto está bajo la licencia MIT. Puedes modificarlo y usarlo libremente. 😊

🤝 Creador
Jonalex Mérida | GitHub

