# 👋 Hola, soy Yordi

### Full Stack Developer · Arquitecto de Soluciones · Backend · Datos · Cloud · Seguridad

Construyo soluciones full stack, sistemas backend, APIs, herramientas ETL, dashboards, automatizaciones y arquitecturas cloud seguras. Me gusta convertir procesos complejos en software útil, escalable y mantenible, conectando arquitectura, datos, frontend, backend, seguridad y automatización.

---

## 🚀 Perfil profesional

```txt
Full Stack Developer | Backend & Solution Architect | Cloud Security | APIs | ETL | Data | Automation
```

- Desarrollo aplicaciones full stack con enfoque en arquitectura limpia.
- Diseño APIs, servicios backend, integraciones y procesos de datos.
- Construyo herramientas internas, dashboards y automatizaciones.
- Trabajo con bases de datos, validación de información y migraciones.
- Diseño soluciones cloud con foco en seguridad, trazabilidad y operación.
- Automatizo procesos de remediación de vulnerabilidades en ambientes serverless.
- Me enfoco en soluciones prácticas, escalables, mantenibles y seguras.

---

## 🧠 Áreas principales

```mermaid
mindmap
  root((Full Stack & Arquitectura))
    Frontend
      React
      Angular
      Tailwind
      Dashboards
      UI Técnica
    Backend
      Java
      Spring Boot
      Python
      Flask
      REST APIs
      Integraciones
    Datos
      SQL
      ETL
      Migraciones
      Validación
      Reportes
    Cloud & DevOps
      AWS
      Serverless
      Docker
      GitHub Actions
      CI/CD
      Automatización
    Seguridad
      Remediación CVE
      Vulnerability Management
      IaC Security
      Security Hub
      Inspector
      Wiz
    Arquitectura
      Diseño de Soluciones
      Sistemas Escalables
      Herramientas Internas
      Procesos Visuales
```

---

## 🛠️ Tecnologías

### Lenguajes y Backend

![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white)
![REST API](https://img.shields.io/badge/REST_API-005571?style=for-the-badge&logo=fastapi&logoColor=white)

### Frontend

![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Angular](https://img.shields.io/badge/Angular-DD0031?style=for-the-badge&logo=angular&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwindcss&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)

### Datos, Cloud, Seguridad y DevOps

![SQL](https://img.shields.io/badge/SQL-336791?style=for-the-badge&logo=postgresql&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-005C84?style=for-the-badge&logo=mysql&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white)
![AWS Lambda](https://img.shields.io/badge/AWS_Lambda-FF9900?style=for-the-badge&logo=awslambda&logoColor=white)
![CloudFormation](https://img.shields.io/badge/CloudFormation-FF4F8B?style=for-the-badge&logo=amazonaws&logoColor=white)
![AWS SAM](https://img.shields.io/badge/AWS_SAM-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white)
![Security Hub](https://img.shields.io/badge/Security_Hub-527FFF?style=for-the-badge&logo=amazonaws&logoColor=white)
![AWS Inspector](https://img.shields.io/badge/AWS_Inspector-7AA116?style=for-the-badge&logo=amazonaws&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

---

## 🔐 Seguridad Cloud y Remediación de Vulnerabilidades

He trabajado en la remediación de vulnerabilidades sobre arquitecturas serverless en AWS, aplicando procesos controlados para ambientes separados de desarrollo, validación y producción, sin exponer información sensible de cuentas, clientes o proyectos.

### Experiencia destacada

- Remediación de vulnerabilidades en arquitecturas **serverless** con múltiples funciones AWS Lambda.
- Gestión de dependencias en **Python Lambda Layers** y paquetes Java empaquetados como **fat JAR / uber JAR**.
- Actualización centralizada de layers para corregir vulnerabilidades en varias funciones con bajo impacto operativo.
- Aplicación de overlays controlados en paquetes Java para reemplazar librerías vulnerables sin recompilar todo el proyecto.
- Automatización de builds y despliegues usando **Docker**, **AWS CLI**, **CloudFormation**, **SAM** y scripts PowerShell.
- Validación previa de identidad y ambiente antes de ejecutar cambios en infraestructura cloud.
- Generación de respaldos antes de modificar paquetes desplegados.
- Documentación de evidencias para auditoría: CVE, versión vulnerable, versión corregida, alcance, resultado y trazabilidad.

### Herramientas y prácticas

```txt
AWS Lambda · CloudFormation · AWS SAM · Docker · Python Layers · Java 21 · PowerShell · AWS CLI · Wiz · AWS Inspector · Security Hub
```

### Enfoque de remediación

```mermaid
flowchart LR
    A[Detección de vulnerabilidad] --> B[Análisis de dependencia afectada]
    B --> C{Tipo de runtime}
    C -->|Python| D[Actualizar Lambda Layer]
    C -->|Java| E[Overlay o recompilación]
    D --> F[Build reproducible con Docker]
    E --> G[Backup del paquete original]
    F --> H[Deploy controlado por ambiente]
    G --> H
    H --> I[Validación y trazabilidad]
```

### Resultados técnicos

- Gestión de remediaciones sobre decenas de funciones serverless.
- Corrección de vulnerabilidades críticas, altas y medias en dependencias de backend.
- Reducción del tiempo de remediación mediante automatización y layers reutilizables.
- Separación segura de ambientes y ejecución controlada por perfiles/permisos.
- Estrategia de rollback mediante versionado de layers y backups de paquetes.

---

## 📊 GitHub Stats

![Yordi's GitHub stats](https://github-readme-stats.vercel.app/api?username=ygaleote&show_icons=true&theme=tokyonight&hide_border=true&count_private=true)

![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=ygaleote&layout=compact&theme=tokyonight&hide_border=true)

![GitHub Streak](https://streak-stats.demolab.com?user=ygaleote&theme=tokyonight&hide_border=true)

---

## 📈 Actividad

![Yordi's GitHub activity graph](https://github-readme-activity-graph.vercel.app/graph?username=ygaleote&theme=tokyo-night&hide_border=true)

---

## 🧩 Cómo pienso el software

> Construyo soluciones prácticas, limpias, escalables y seguras para resolver problemas reales con tecnología.

Para mí, buen software no es solo código: es arquitectura, datos, experiencia de usuario, seguridad, automatización, despliegue y contexto de negocio trabajando juntos.

---

## 🎯 Enfoque actual

- Arquitectura full stack
- APIs y microservicios
- Automatización de procesos
- Plataformas ETL
- Dashboards y analítica
- Cloud con AWS
- Seguridad cloud y remediación de vulnerabilidades
- Infraestructura como código
- Herramientas internas
- DevOps y CI/CD
