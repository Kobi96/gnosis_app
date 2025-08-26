# 📚 Gnosis

**Gnosis** es una aplicación web para registrar, organizar y explorar libros.  
El objetivo es brindar a los usuarios una biblioteca digital personal donde puedan:
- Añadir libros leídos o por leer
- Llevar un registro del progreso de lectura
- Consultar estadísticas de hábitos de lectura

---

## 🚀 Tecnologías principales
- **Frontend:** React + TypeScript
- **Backend:** Express + TypeScript
- **Base de datos:** MongoDB
- **Infraestructura:** Node.js, Docker (opcional), despliegue en Render/Vercel

---

## 📂 Estructura del proyecto
gnosis_app/
├── client/ # Frontend (React + TS)
├── server/ # Backend (Express + TS)
└── README.md
---

## ⚡ Instalación y ejecución
1. Clonar el repositorio:
   ```bash
   git clone https://github.com/<tu-usuario>/gnosis_app.git
   cd gnosis_app
2. Instalar dependencias en el servidor:
cd server
npm install
3. Instalar dependencias en el cliente:
cd ../client
npm install
4. Levantar backend en modo dev:
cd ../server
npm run dev
5. Levantar frontend:
cd ../client
npm start

🌐 Deploy

Frontend: Vercel / Netlify

Backend: Render / Railway

Los enlaces de producción se agregarán próximamente.

✨ Estado del proyecto

Actualmente en fase inicial de desarrollo (Semana 1/10):
✔️ Configuración del stack base (React, Express, MongoDB)
✔️ Deploy inicial vacío

🛠 Próximos pasos

Definir modelo de datos de libros en MongoDB

Implementar endpoints iniciales (CRUD de libros)

Integrar frontend con backend

📜 Licencia

Este proyecto se distribuye bajo licencia MIT.


