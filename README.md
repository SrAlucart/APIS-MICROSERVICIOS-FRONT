# 🧩 Microservicios API

Este proyecto demuestra una **arquitectura basada en microservicios** construida con un **API Gateway** que centraliza la comunicación entre servicios independientes, como el **Servicio de Usuarios** y el **Servicio de Productos**, junto con un **Frontend desarrollado en React**.  
Esta versión incluye **integración completa del frontend**, **mejoras en la configuración de los servicios** y varias **optimizaciones orientadas a la escalabilidad y mantenibilidad**.

---

## 🚀 Tecnologías Principales

- **Node.js** (API Gateway)
- **Express.js**
- **MySQL / MariaDB**
- **React + Vite**
- **TailwindCSS**
- **Docker (opcional)**

---

## 🧱 Estructura del Proyecto
├── api-gateway/ # Gateway central que enruta las solicitudes a los microservicios
├── products-service/ # Gestiona las operaciones relacionadas con productos
├── users-service/ # Administra la autenticación y los datos de los usuarios
└── Frontend/ # Frontend en React + Vite que consume la API del gateway

---

## ⚙️ Instalación y Configuración

### 1. Clonar el repositorio
```bash
git clone https://github.com/SrAlucart/APIS-MICROSERVICIOS-FRONT.git
cd APIS-MICROSERVICIOS-FRONT
```
### 2. Configurar las bases de datos
#### MySQL / MariaDB (Servicio de Usuarios)
Crea una base de datos llamada `node_mvc` (o el nombre que prefieras, asegurándote de actualizar el archivo `.env` en consecuencia).

```sql
CREATE DATABASE node_mvc;
```
#### MongoDB (Servicio de Productos)
Asegúrate de tener MongoDB instalado y en ejecución. Crea una base de datos
llamada `productos_db` (o el nombre que prefieras, asegurándote de actualizar el archivo `.env` en consecuencia).
``` 
```
### 📦 Instalar dependencias

Ejecuta el siguiente comando dentro de cada carpeta (api-gateway, users-service, products-service y Frontend/Frontend):
```bash
npm install
``` 
## ▶️ Ejecución de los servicios

🧠 API Gateway
```bash
cd api-gateway
node index.js
# Disponible en: http://localhost:3000
```   
## 👤 Servicio de Usuarios
```bash
cd users-service
node index.js
# Disponible en: http://localhost:3001
``` 
## 📦 Servicio de Productos
```bash
cd products-service
node index.js
# Disponible en: http://localhost:3002
``` 
## 💻 Frontend
```bash
cd Frontend/Frontend
npm run dev
# El frontend se ejecutará en: http://localhost:5173
``` 
