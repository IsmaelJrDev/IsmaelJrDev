<div align="center">
  <img src="src/Banner_Ismael_Jr_Cuerpo_Largo_2_Recortada.png" alt="Ismael Bibiano - Banner"/>
</div>

<div align="center">

# Ismael Bibiano Martínez

**Desarrollador Backend | Microservicios y Sistemas Distribuidos**

Ingeniería en Sistemas Computacionales, TESJI (9.° semestre) · Jilotepec, México

[Portfolio](https://ismaelbibianodev.vercel.app/) · [LinkedIn](https://www.linkedin.com/in/ismael-bibiano-martinez-b6472230a) · [ismaelbibiano.dev@gmail.com](mailto:ismaelbibiano.dev@gmail.com)

</div>

---

## Perfil

Desarrollador backend enfocado en diseñar e implementar arquitecturas distribuidas de punta a punta: modelado de servicios y APIs, mensajería entre componentes, replicación de datos y despliegue de la infraestructura donde corren.

- Experiencia construyendo sistemas de microservicios sobre **hardware físico real** (nodos en LAN, dispositivos IoT), no solo en entornos simulados.
- Sistema propio **en producción**: POS con más de 2,000 productos, del cual soy el único responsable de base de datos, backend y frontend.
- Enfoque en decisiones documentadas (ADR), contratos explícitos (Protobuf, OpenAPI) y validación previa al despliegue (pruebas unitarias y de carga).

**Disponible para residencia profesional.**

---

## Proyectos

### Sistema C5: Alertas Ciudadanas de Emergencia

Pipeline de eventos en tiempo real sobre hardware físico.

- 5 microservicios (Recepción, Geolocalización, Clasificación, Notificaciones, Historial) comunicados con **Redis Streams** y **gRPC** con contratos Protobuf.
- Flujo completo: dispositivos **ESP32** publican alertas por **MQTT** (broker Mosquitto), un Ingestion Service las vuelca al bus de eventos y se persisten en **PostgreSQL** con replicación primary-replica.
- **Nginx** como load balancer y dashboard en **React + Leaflet** con actualizaciones por WebSocket.
- Decisiones arquitectónicas documentadas mediante ADR.

`Node.js` `Python` `gRPC` `MQTT` `Redis Streams` `PostgreSQL` `React` `Leaflet` `Nginx` `ESP32`

---

### Sistema POS D-MART (en producción)

Punto de venta en uso real con más de 2,000 productos, desarrollado desde cero.

- Automatiza inventario, registro de ventas, control de caja y reportes diarios.
- **Reducción del 30 % en los tiempos de cobro y cierre de caja.**
- Responsable único de base de datos, backend y frontend.

`Python` `MySQL` `JavaScript` `TailwindCSS`

---

### [DocFlow: Gestión Documental Distribuida con IA](https://github.com/IsmaelJrDev/DocsFlow)

Pipeline de IA 100 % offline sobre 3 nodos físicos en LAN.

- Tres modelos **Ollama** en máquinas separadas: Llama3 (análisis), Mistral (resumen) y Phi3 (clasificación).
- OCR con pdf2image y pytesseract.
- **MongoDB Replica Set** de 3 nodos con failover automático.
- **Nginx** como API gateway unificado y Auth Service con JWT.

`Node.js` `FastAPI` `Ollama` `MongoDB` `Docker` `Nginx` `JWT`

---

### [PinBoard: Microservicios estilo Pinterest](https://github.com/IsmaelJrDev/PinBoard-Backend/tree/develop)

Patrón Database-per-Service con clústeres de replicación.

- 5 microservicios independientes con bases de datos aisladas.
- Clúster PostgreSQL primary-replica (Sequelize) y MongoDB Replica Set para servicios de contenido.
- Auth Service con JWT y documentación Swagger/OpenAPI.
- Nginx como reverse proxy y orquestación con Docker Compose.

`Node.js` `Docker` `PostgreSQL` `MongoDB` `Nginx` `JWT` `Swagger`

---

### Plataforma SaaS de Control Escolar

Microservicios con pruebas de carga previas al despliegue.

- Endpoints REST en TypeScript para el módulo de Alumnos.
- Diseño del modelo relacional en PostgreSQL.
- Pruebas unitarias con Jest y pruebas de carga con K6 para validar estabilidad.
- Docker Compose y API Gateway.

`TypeScript` `PostgreSQL` `Docker` `Jest` `K6`

---

### Proyectos de investigación (Machine Learning)

| Proyecto | Descripción | Stack |
|---|---|---|
| [API Detección de Malware](https://github.com/IsmaelJrDev/API_RandomForest.git) | Clasificación de tráfico de red con Random Forest: preprocesamiento, extracción de características y endpoints REST. | Python, Django, MongoDB, Scikit-learn |
| [API Detección de Cáncer de Piel](https://github.com/IsmaelJrDev/API_Skin_Cancer.git) | Clasificación de imágenes dermatológicas con ML y endpoints REST para diagnóstico preliminar. | Python, Django, Scikit-learn |
| [API Transformación de Imágenes](https://github.com/IsmaelJrDev/API_Transformacion_Imagenes.git) | Rotación, traslación, cizallamiento y detección de bordes (filtro Sobel) mediante álgebra lineal. | Python, Flask, NumPy, Pillow |

---

## Habilidades

| Área | Tecnologías |
|---|---|
| Lenguajes y backend | Node.js, TypeScript, JavaScript, Python, FastAPI, Express |
| Sistemas distribuidos y mensajería | gRPC (Protobuf), Redis Streams, MQTT (Mosquitto) |
| Bases de datos | PostgreSQL, MongoDB, MySQL, MariaDB, Redis |
| Infraestructura y DevOps | Docker, Docker Compose, Nginx, Linux, Git, AWS |
| IoT | ESP32 |
| Frontend | React, TailwindCSS |
| Testing | Jest, K6 |

---

## Estadísticas de GitHub

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=IsmaelJrDev&show_icons=true&theme=github_dark&hide_border=true&include_all_commits=true&count_private=true" alt="GitHub Stats"/>

<img src="https://github-readme-stats.vercel.app/api/top-langs?username=IsmaelJrDev&layout=compact&theme=github_dark&hide_border=true" alt="Top Languages"/>

</div>
