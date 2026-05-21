# DistribOrder
### Sistema Distribuido de Gestión de Pedidos Tolerante a Fallos

DistribOrder es una aplicación web distribuida diseñada para la gestión de pedidos en tiempo real, implementando principios de tolerancia a fallos, balanceo de carga y arquitectura moderna basada en microservicios.

El proyecto fue desarrollado como solución académica universitaria utilizando tecnologías modernas como React, FastAPI, Supabase, Docker y Nginx, acompañado de una interfaz profesional inspirada en plataformas como Vercel y Supabase.

---

# Vista General

DistribOrder permite registrar, visualizar y administrar pedidos mediante un sistema distribuido con arquitectura cliente-servidor.

El sistema cuenta con:
- Frontend moderno e interactivo.
- Backend robusto desarrollado con FastAPI.
- Persistencia de datos en Supabase.
- Balanceador de carga con Nginx.
- Contenedores Docker para despliegue.
- Tolerancia a fallos y manejo distribuido.

---

# Características Principales

- Gestión de pedidos en tiempo real.
- Arquitectura distribuida tolerante a fallos.
- Backend desarrollado con FastAPI.
- Frontend moderno construido con React + Vite.
- Base de datos en Supabase.
- Balanceador de carga con Nginx.
- Contenedorización mediante Docker.
- Interfaz moderna, responsiva y profesional.
- Simulación de nodos de atención.
- Actualización dinámica de estados de pedidos.

---

# Arquitectura del Proyecto

```bash
Proyecto Fernando/
│
├── backend/              # API FastAPI
├── frontend/             # Aplicación React
├── load_balancer/        # Configuración Nginx
├── docs/                 # Documentación del proyecto
├── docker-compose.yml
└── README.md
```

---

# Tecnologías Utilizadas

## Frontend
- React
- Vite
- Vanilla CSS
- JavaScript ES6+

## Backend
- FastAPI
- Python 3.12
- Uvicorn

## Base de Datos
- Supabase

## Infraestructura
- Docker
- Docker Compose
- Nginx

---

# Instalación del Proyecto

## 1. Clonar el repositorio

```bash
git clone https://github.com/TU-USUARIO/distriborder-system.git
```

---

## 2. Entrar al proyecto

```bash
cd distriborder-system
```

---

# Configuración del Backend

## Entrar a la carpeta backend

```bash
cd backend
```

## Instalar dependencias

```bash
pip install -r requirements.txt
```

## Ejecutar servidor

```bash
python -m uvicorn main:app --reload --port 8001
```

Servidor disponible en:

```bash
http://127.0.0.1:8001
```

---

# Configuración del Frontend

## Entrar a la carpeta frontend

```bash
cd frontend
```

## Instalar dependencias

```bash
npm install
```

## Ejecutar frontend

```bash
npm run dev
```

Frontend disponible en:

```bash
http://localhost:3000
```

---

# Variables de Entorno

Crear un archivo `.env` dentro de la carpeta backend:

```env
SUPABASE_URL=tu_url
SUPABASE_KEY=tu_api_key
```

---

# Docker

## Ejecutar todo el sistema

```bash
docker-compose up --build
```

---

# Funcionalidades del Sistema

## Registro de Pedidos

Permite registrar nuevos pedidos indicando:
- Nombre del cliente
- Producto
- Cantidad
- Dirección de envío

---

## Gestión de Estados

Los pedidos pueden cambiar entre:
- Pendiente
- En Proceso
- Enviado
- Entregado

---

## Tolerancia a Fallos

El sistema implementa mecanismos de resiliencia para garantizar disponibilidad ante fallos parciales.

---

## Balanceador de Carga

Nginx distribuye solicitudes entre servicios simulando una arquitectura distribuida real.

---

# Diseño de Interfaz

La interfaz fue diseñada bajo principios modernos de UX/UI:

- Diseño oscuro profesional.
- Glassmorphism sutil.
- Layout responsive.
- Inputs minimalistas.
- Tarjetas modernas.
- Transiciones suaves.
- Dashboard inspirado en plataformas empresariales modernas.

---

# Pruebas Implementadas

## Pruebas Unitarias
- Validación de endpoints.
- Registro correcto de pedidos.
- Cambio de estados.

## Pruebas de Integración
- Comunicación frontend-backend.
- Conexión con Supabase.
- Persistencia de datos.

## Pruebas de Fallo
- Simulación de desconexión de base de datos.
- Verificación de estabilidad del sistema.

---

# Objetivos Académicos

Este proyecto fue desarrollado con fines educativos para demostrar:

- Arquitectura distribuida.
- Tolerancia a fallos.
- Comunicación cliente-servidor.
- Desarrollo Full Stack moderno.
- Uso de contenedores Docker.
- Balanceo de carga.
- Integración con servicios cloud.
- Desarrollo de interfaces modernas.

---

# Estado del Proyecto

Proyecto académico funcional y estable.

---

# Capturas del Sistema

Agregar aquí:
- Dashboard principal.
- Registro de pedidos.
- Gestión de estados.
- Evidencias de pruebas.
- Arquitectura Docker.

---

# Autores

Proyecto desarrollado por estudiantes universitarios como práctica académica de Sistemas Distribuidos y Computación Ubicua.

---

# Licencia

Proyecto académico de uso educativo.
