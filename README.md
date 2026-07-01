# Ismael Bibiano Martínez

**Ingeniero en Sistemas Computacionales · Desarrollador Backend · Microservicios & Sistemas Distribuidos**

Estudiante de 8° semestre en TESJI (TecNM). Me especializo en backend, arquitecturas de microservicios y sistemas distribuidos. Trabajo con hardware físico real — nodos LAN, ESP32, brokers MQTT — no solo entornos simulados en la nube.

[![Portfolio](https://img.shields.io/badge/Portfolio-ismaelbibianodev.vercel.app-black?style=flat-square&logo=vercel&logoColor=white)](https://ismaelbibianodev.vercel.app/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Ismael_Bibiano-0077B5?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ismael-bibiano-martinez-b6472230a)
[![Gmail](https://img.shields.io/badge/Gmail-ismaelbibiano.dev-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:ismaelbibiano.dev@gmail.com)

---

## Stack

**Backend**
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white)

**Sistemas Distribuidos & Mensajería**
![gRPC](https://img.shields.io/badge/gRPC-4285F4?style=flat-square&logo=google&logoColor=white)
![Redis](https://img.shields.io/badge/Redis_Streams-DC382D?style=flat-square&logo=redis&logoColor=white)
![MQTT](https://img.shields.io/badge/MQTT-Mosquitto-660066?style=flat-square&logo=eclipsemosquitto&logoColor=white)

**Bases de Datos**
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=flat-square&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![MariaDB](https://img.shields.io/badge/MariaDB-003545?style=flat-square&logo=mariadb&logoColor=white)

**Infraestructura**
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white)

**IoT**
![ESP32](https://img.shields.io/badge/ESP32-000000?style=flat-square&logo=espressif&logoColor=white)

**Frontend**
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![TailwindCSS](https://img.shields.io/badge/TailwindCSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)

---

## Proyectos

### Sistemas Distribuidos & Microservicios

| Proyecto | Descripción | Stack | Estado |
|---|---|---|---|
| **Sistema C5 — Alertas Ciudadanas** | Pipeline de eventos en tiempo real: ESP32 → MQTT → Redis Streams → 5 microservicios → PostgreSQL. Comunicación inter-servicio con gRPC (Protobuf). Replicación primary-replica, Nginx como load balancer, dashboard React + Leaflet. Decisiones documentadas con ADR. | `Node.js` `Python` `gRPC` `MQTT` `Redis Streams` `PostgreSQL` `React` `Nginx` | ✅ Completado |
| [**DocFlow**](https://github.com/IsmaelJrDev/DocsFlow) | Plataforma distribuida de gestión documental con pipeline de IA 100% offline. Tres modelos Ollama (Llama3, Mistral, Phi3) en nodos físicos separados. OCR, resumen automático y clasificación por prioridad. MongoDB Replica Set de 3 nodos. | `Node.js` `FastAPI` `Ollama` `MongoDB` `Docker` `Nginx` `JWT` | ✅ Completado |
| [**PinBoard**](https://github.com/IsmaelJrDev/PinBoard-Backend/tree/develop) | 5 microservicios independientes con Database-per-Service pattern. Clúster PostgreSQL primary-replica, MongoDB Replica Set, JWT + Swagger, Nginx como reverse proxy. | `Node.js` `Docker` `PostgreSQL` `MongoDB` `Nginx` `JWT` | ✅ Completado |
| **Plataforma de Control Escolar** | SaaS académico con microservicios, endpoints REST en TypeScript, modelo relacional con PostgreSQL, pruebas unitarias con Jest y de carga con K6. | `TypeScript` `Docker` `PostgreSQL` `Jest` `K6` | ✅ Completado |

### Producción

| Proyecto | Descripción | Stack | Estado |
|---|---|---|---|
| **Sistema POS — D-MART** | Punto de venta para tienda con 2,000+ productos. Automatiza inventario, ventas y reportes diarios. Reducción del 30% en tiempos de cobro y cierre de caja. Actualmente en uso real. | `Python` `MySQL` `TailwindCSS` `JavaScript` | 🟢 Producción |

### Investigación & ML

| Proyecto | Descripción | Stack |
|---|---|---|
| [**API Detección de Malware**](https://github.com/IsmaelJrDev/API_RandomForest.git) | Clasificación de tráfico de red con Random Forest. Preprocesamiento, extracción de características y endpoints REST. | `Python` `Django` `MongoDB` `Scikit-learn` |
| [**API Detección de Cáncer de Piel**](https://github.com/IsmaelJrDev/API_Skin_Cancer.git) | Clasificación de imágenes dermatológicas. Endpoints REST para diagnóstico preliminar. | `Python` `Scikit-learn` `Django` |
| [**API Transformación de Imágenes**](https://github.com/IsmaelJrDev/API_Transformacion_Imagenes.git) | Rotación, traslación, cizallamiento y detección de bordes (Filtro Sobel) mediante álgebra lineal. | `Python` `Flask` `NumPy` `Pillow` |

---

## Principios de Ingeniería

```
· SOLID                          · CAP Theorem awareness
· Clean Code                     · Consistencia eventual vs. fuerte
· Eight Fallacies of             · Database-per-Service pattern
  Distributed Computing          · ADR (Architecture Decision Records)
· Zero Trust Security            · Git Flow + Conventional Commits
```

---

## GitHub Stats

<div align="center">
<img src="https://github-readme-streak-stats.herokuapp.com?user=IsmaelJrDev&theme=github-dark-blue&hide_border=true&border_radius=4" alt="GitHub Streak"/>
<br/>
<img src="https://github-readme-stats.vercel.app/api?username=IsmaelJrDev&show_icons=true&theme=github_dark&hide_border=true&include_all_commits=true&count_private=true" alt="GitHub Stats"/>
<br/>
<img src="https://github-readme-stats.vercel.app/api/top-langs?username=IsmaelJrDev&layout=compact&theme=github_dark&hide_border=true" alt="Top Languages"/>
</div>

---

<div align="center">
<sub>Construyendo en serio · Jilotepec, México</sub>
</div>
