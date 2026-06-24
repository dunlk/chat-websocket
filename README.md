# ChatWorld

Aplicación de chat en tiempo real desarrollada con React, TypeScript, FastAPI y WebSockets.

## Características

- Registro de usuarios
- Inicio de sesión con JWT
- Creación de salas de chat
- Mensajería en tiempo real mediante WebSockets
- Gestión de perfiles
- Persistencia de mensajes
- Interfaz responsive

## Tecnologías

### Frontend

- React
- TypeScript
- Tailwind CSS
- React Router DOM
- Zustand

### Backend

- FastAPI
- SQLAlchemy
- PostgreSQL
- WebSockets
- JWT
- Bcrypt

## Instalación

### Backend

```bash
cd backend

python -m venv venv

source venv/bin/activate

pip install -r requirements.txt

uvicorn app.main:app --reload
```
### Frontenv
```bash
cd frontend

npm install

npm run dev
```
