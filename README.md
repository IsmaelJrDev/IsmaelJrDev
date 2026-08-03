<div align="center">
  <img src="src/Banner_Ismael_Jr_Cuerpo_Largo_2_Recortada.png" alt="Ismael Bibiano — Banner"/>
</div>

<div align="center">

# Ismael Bibiano Martínez

**Desarrollador Backend · Microservicios & Sistemas Distribuidos**
**Ingeniero en Sistemas Computacionales — TESJI (8° Semestre)**

<br/>

[![Portfolio](https://img.shields.io/badge/Portfolio-ismaelbibianodev.vercel.app-000000?style=for-the-badge&logo=vercel&logoColor=white)](https://ismaelbibianodev.vercel.app/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Ismael_Bibiano-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ismael-bibiano-martinez-b6472230a)
[![Gmail](https://img.shields.io/badge/Gmail-ismaelbibiano.dev-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:ismaelbibiano.dev@gmail.com)

</div>

---

Diseño e implemento arquitecturas backend: desde el modelado de servicios y APIs hasta la infraestructura donde corren. Me especializo en sistemas distribuidos y microservicios sobre hardware físico real.

---

## 🧰 Stack Técnico

**Backend**

![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white)

**Sistemas Distribuidos & Mensajería**

![gRPC](https://img.shields.io/badge/gRPC-4285F4?style=flat-square&logo=google&logoColor=white)
![Redis Streams](https://img.shields.io/badge/Redis_Streams-DC382D?style=flat-square&logo=redis&logoColor=white)
![MQTT](https://img.shields.io/badge/MQTT_Mosquitto-660066?style=flat-square&logo=eclipsemosquitto&logoColor=white)

**IoT**

![ESP32](https://img.shields.io/badge/ESP32-E7352C?style=flat-square&logo=espressif&logoColor=white)

**Bases de Datos**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=flat-square&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![MariaDB](https://img.shields.io/badge/MariaDB-003545?style=flat-square&logo=mariadb&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)

**Infraestructura & DevOps**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white)

**Frontend**

![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![TailwindCSS](https://img.shields.io/badge/TailwindCSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)

---

## 🚀 Proyectos Destacados

### 🔴 Sistema C5 — Alertas Ciudadanas de Emergencia
> Pipeline de eventos en tiempo real sobre hardware físico

**5 microservicios** (Recepción · Geolocalización · Clasificación · Notificaciones · Historial) conectados mediante Redis Streams y gRPC con contratos Protobuf. Dispositivos ESP32 publican alertas vía MQTT → broker Mosquitto → Ingestion Service → bus de eventos → PostgreSQL con replicación primary-replica. Nginx como load balancer. Dashboard React + Leaflet con WebSocket. Decisiones arquitectónicas documentadas en ADR.

`Node.js` · `Python` · `gRPC` · `MQTT` · `Redis Streams` · `PostgreSQL` · `React` · `Leaflet` · `Nginx` · `ESP32`

---

### 🟣 [DocFlow — Gestión Documental Distribuida con IA](https://github.com/IsmaelJrDev/DocsFlow)
> Pipeline de IA 100% offline sobre 3 nodos físicos LAN

Tres modelos Ollama distintos (Llama3 → análisis · Mistral → resumen · Phi3 → clasificación) corriendo en máquinas físicas separadas. OCR con pdf2image y pytesseract. MongoDB Replica Set de 3 nodos con failover automático. Nginx como API gateway unificado. Auth Service con JWT.

`Node.js` · `FastAPI` · `Ollama` · `MongoDB` · `Docker` · `Nginx` · `JWT`

---

### 🔵 [PinBoard — Microservicios Estilo Pinterest](https://github.com/IsmaelJrDev/PinBoard-Backend/tree/develop)
> Database-per-Service pattern con clústeres de replicación

5 microservicios independientes con bases de datos aisladas. Clúster PostgreSQL primary-replica (Sequelize) + MongoDB Replica Set para servicios de contenido. Auth Service completo con JWT y Swagger/OpenAPI. Nginx como reverse proxy. Orquestación con Docker Compose.

`Node.js` · `Docker` · `PostgreSQL` · `MongoDB` · `Nginx` · `JWT` · `Swagger`

---

### 🟠 Plataforma SaaS de Control Escolar
> Microservicios con testing de carga pre-despliegue

Endpoints REST en TypeScript para módulo de Alumnos. Diseño del modelo relacional con PostgreSQL. Pruebas unitarias con Jest y pruebas de carga con K6 para validar estabilidad antes del despliegue. Orquestación con Docker Compose y API Gateway.

`TypeScript` · `PostgreSQL` · `Docker` · `Jest` · `K6`

---

### 🟢 Sistema POS — D-MART *(Producción)*
> Sistema en uso real con 2,000+ productos

Punto de venta desarrollado desde cero. Automatiza inventario, registra ventas, controla caja y genera reportes diarios. **Reducción del 30% en tiempos de cobro y cierre de caja.** Único responsable de base de datos, backend y frontend.

`Python` · `MySQL` · `TailwindCSS` · `JavaScript`

---

## 🔬 Proyectos de Investigación

<table>
  <tr>
    <td>
      <a href="https://github.com/IsmaelJrDev/API_RandomForest.git"><strong>API Detección de Malware</strong></a><br/>
      Clasificación de tráfico de red con Random Forest. Pipeline: preprocesamiento → extracción de características → endpoints REST.<br/>
      <sub>Python · Django · MongoDB · Scikit-learn</sub>
    </td>
    <td>
      <a href="https://github.com/IsmaelJrDev/API_Skin_Cancer.git"><strong>API Detección de Cáncer de Piel</strong></a><br/>
      Clasificación de imágenes dermatológicas con ML. Endpoints REST para diagnóstico preliminar.<br/>
      <sub>Python · Scikit-learn · Django</sub>
    </td>
    <td>
      <a href="https://github.com/IsmaelJrDev/API_Transformacion_Imagenes.git"><strong>API Transformación de Imágenes</strong></a><br/>
      Rotación, traslación, cizallamiento y detección de bordes con Filtro Sobel mediante álgebra lineal.<br/>
      <sub>Python · Flask · NumPy · Pillow</sub>
    </td>
  </tr>
</table>

---

## 📊 GitHub Stats

<div align="center">

<img src="https://github-readme-streak-stats.herokuapp.com?user=IsmaelJrDev&theme=github-dark-blue&hide_border=true&border_radius=4" alt="GitHub Streak"/>

<img src="https://github-readme-stats.vercel.app/api?username=IsmaelJrDev&show_icons=true&theme=github_dark&hide_border=true&include_all_commits=true&count_private=true" alt="GitHub Stats"/>

<img src="https://github-readme-stats.vercel.app/api/top-langs?username=IsmaelJrDev&layout=compact&theme=github_dark&hide_border=true" alt="Top Languages"/>

</div>

---

<div align="center">
<sub>Jilotepec, México · Disponible para residencia profesional</sub>
</div>