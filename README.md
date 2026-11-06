<div align="center">

<img src="./assets/terminal.svg" alt="Terminal: whoami → Cristian Martinez, Full Stack Developer" width="100%"/>

# Hola, soy Cristian Martinez

**Full Stack Developer** · React / Next.js · Node.js · Spring Boot<br/>
📍 Buenos Aires, Argentina · 🌎 Abierto a oportunidades remotas

<a href="mailto:eze.cmartinez@gmail.com"><img src="https://img.shields.io/badge/Email-eze.cmartinez%40gmail.com-D14836?style=flat&logo=gmail&logoColor=white"/></a>
<a href="https://doi.org/10.3847/2515-5172/ada615"><img src="https://img.shields.io/badge/Publicación-AAS%20Research%20Notes-1f6feb?style=flat&logo=readthedocs&logoColor=white"/></a>

</div>

---

## 🧭 Del hardware al software

Llegué al software desde el hardware. Este es el recorrido:

```mermaid
timeline
    title Mi camino en la tecnología
    Hardware : Microcontroladores en C y assembler
    Automatización : Desarrollador certificado Crestron : Salas para Prisma, Mercado Libre y directorios bancarios
    Frontend : React · React Native · Expo
    Emprendimiento : Co-fundador de Bubbletic (cooperativa tecnológica)
    Full Stack enterprise : Fintech con arquitectura distribuida : Next.js → BFF → microservicios
    Hoy : IA aplicada (MCP, agentes) : Spec-Driven Development : Licenciatura en Informática (UNAHUR)
```

---

## 🚪 Elegí tu camino

<details>
<summary><b>👔 Soy recruiter: dame el resumen en 30 segundos</b></summary>
<br/>

- **Perfil:** Full Stack Developer con más de 5 años de experiencia, con fuerte peso en frontend y en crecimiento constante en backend y arquitectura.
- **Experiencia más fuerte:** plataforma fintech distribuida, en un ecosistema de ~5 equipos.
- **Busco:** rol full stack, remoto, en relación de dependencia.
- **Diferencial:** vengo del hardware y la automatización, así que entiendo los sistemas de punta a punta.
- **Extra:** co-autor de una nota de investigación publicada por la American Astronomical Society.

</details>

<details>
<summary><b>💻 Soy dev: mostrame la arquitectura y el código</b></summary>
<br/>

### Experiencia destacada: Full Stack Developer en Nera (fintech)

```mermaid
flowchart LR
    U([Usuario]) --> F["Frontend<br/>Next.js<br/>CSP · Auth0 MFA · Amplitude"]
    F --> B["BFF<br/>Node / Express"]
    B --> M1["Microservicio<br/>Spring Boot"]
    B --> M2["Microservicio<br/>Spring Boot"]
    M1 --> SQL[("Base de datos SQL")]
    M2 --> NOSQL[("Base de datos NoSQL")]
    F -. assets .-> S[("AWS S3 + CloudFront")]
```

- Implementé **Content Security Policy (CSP)** en el frontend como respuesta a una auditoría de seguridad bancaria.
- Integré **MFA con Auth0** en el flujo de autenticación.
- Integré métricas de producto con **Amplitude**.
- Desarrollé cambios **end-to-end** atravesando base de datos → microservicio → BFF → frontend.
- Trabajé con persistencia en bases de datos **SQL y NoSQL** desde los microservicios.
- Trabajé con **AWS S3 + CloudFront**, deploy con **nullplatform** y **CI/CD en GitHub**.

### Proyectos

| Proyecto | Descripción | Stack |
|---|---|---|
| **tool-init** | CLI zero-dependency para scaffolding de proyectos con un sistema de orquestación de cuatro roles. | Node.js (ESM) |
| **Racing MCP Server** | Servidor MCP que expone datos de Racing Club a asistentes de IA. | Node.js · MCP |
| **Domótica con IA** | App propia para controlar luces, relés, infrarrojos y Google Home con lenguaje natural. | IoT · IA |
| **La Granja de Atahualpa** | Juego desarrollado en equipo (Cyberobjeto) con Wollok Game, en el paradigma de objetos. | Wollok |
| **Websockets Chat** | Chat web en tiempo real. | React · Express · Socket.io |

</details>

<details>
<summary><b>🔭 Soy curioso: contame del exoplaneta</b></summary>
<br/>

**A Neptune-size Planet Candidate in a 2.77 days Orbit Around TYC 8996-1013-1**<br/>
*Research Notes of the AAS* · Enero 2025 · [DOI 10.3847/2515-5172/ada615](https://doi.org/10.3847/2515-5172/ada615)

Analizamos datos del satélite **TESS** con Python (Astropy, Lightkurve, Juliet). La idea es simple: cuando un planeta pasa delante de su estrella, el brillo que medimos baja un poquito. Ese "pozo" en la curva de luz, repetido cada 2,77 días, delata a un candidato del tamaño de Neptuno.

</details>

---

## 🛠️ Stack

**Frontend**<br/>
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat&logo=react&logoColor=61DAFB)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat&logo=nextdotjs&logoColor=white)
![React Native](https://img.shields.io/badge/React_Native-20232A?style=flat&logo=react&logoColor=61DAFB)
![Expo](https://img.shields.io/badge/Expo-000020?style=flat&logo=expo&logoColor=white)

**Backend**<br/>
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=flat&logo=express&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat&logo=springboot&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat&logo=openjdk&logoColor=white)

**Datos**<br/>
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat&logo=mongodb&logoColor=white)

**Cloud, DevOps y herramientas**<br/>
![AWS S3](https://img.shields.io/badge/AWS_S3-569A31?style=flat&logo=amazons3&logoColor=white)
![CloudFront](https://img.shields.io/badge/CloudFront-8C4FFF?style=flat&logo=amazonaws&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat&logo=githubactions&logoColor=white)
![Auth0](https://img.shields.io/badge/Auth0-EB5424?style=flat&logo=auth0&logoColor=white)
![Amplitude](https://img.shields.io/badge/Amplitude-1E61F0?style=flat&logo=amplitude&logoColor=white)

---

## ⚡ Ahora mismo

- 🏗️ Profundizando en arquitectura de software y backend para ser un full stack cada vez más completo.
- 🤖 Construyendo herramientas con IA aplicada (MCP, agentes).
- 🎓 Avanzando en la Licenciatura en Informática (UNAHUR).
