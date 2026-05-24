# Larry Yoffre

**Full Stack Developer · AI Systems Integration** Granada, España | Remoto — Híbrido  
[Portafolio](https://www.larryyoffre.com) · [LinkedIn](https://www.linkedin.com/in/larry-yoffre-9b45102bb) · [Email](mailto:lyyos.info@gmail.com)

---

## De un vistazo

Vengo de la industria de la **maquinaria pesada**, un entorno implacable donde un error operativo cuesta miles de euros en cuestión de segundos. De ahí importé mi ética de trabajo hacia el software: **disciplina estricta, alta responsabilidad ante sistemas complejos y un método sistemático de estudio.**

Como desarrollador, actúo como el Arquitecto y Controlador Técnico de mis sistemas a través de un flujo estructurado de ingeniería inversa:

1. **Diseño de Invariantes:** Antes del desarrollo, itero con múltiples modelos para blindar un plan canónico con reglas de negocio, contratos técnicos y principios de seguridad no negociables.
2. **Andamiaje Automatizado:** Con las fronteras claras, utilizo IA para levantar infraestructuras complejas y estructuras de código avanzadas rápidamente.
3. **Auditoría Inversa:** Mi verdadero trabajo comienza aquí. Realizo verificaciones funcionales y desgloso el software en registros estructurados por fases para auditar, leer y comprender a fondo el 100% de la lógica interna del sistema.


## 🏗️ Proyectos Destacados

### 🧠 NEXUS-AI — Self-Healing Content Pipeline
Plataforma SaaS que transforma contenido web estático en una entidad evolutiva, trend-aware y auto-regenerativa mediante agentes, embeddings, cosine similarity y GitOps.
* **Estado Actual:** v2.3.0 — Pipeline completo funcional con autenticación real, rate limiting y deploy seguro. AI Provider activo: VertexGeminiHybridProvider.
* **Módulos del Pipeline:**
  * **Trend Hunter:** Ingesta de señales de mercado, clustering de micro-intenciones, auditoría semántica y detección de gaps mediante cosine similarity.
  * **Semantic Alignment:** Personas sintéticas como jueces vectoriales, centroide objetivo (V_target), generación LLM con bucle de autocorrección (ΔS), ancla de marca (V_b ≥ 0.85).
  * **GitOps Deploy:** Generación de variantes de contenido (A/B/C), deploy atómico vía GitHub API → CI/CD, ciclo self-healing configurable.
* **Arquitectura Multi-proveedor AI:** Cadena de selección Hybrid (Vertex+Gemini) > Vertex > Gemini > OpenAI > Mock, con fallback automático y modo demo sin credenciales.
* **Seguridad:** NextAuth.js v5 con JWT, protección SSRF en scraping de URLs, firma HMAC-SHA256 para payloads de deploy y allowlist de repositorios.
* **Base de Datos Vectorial:** PostgreSQL + pgvector con soporte para embeddings de hasta 3072 dimensiones (Matryoshka).
* **Transparencia y Calidad:** Commits convencionales, hooks pre-commit (Husky) con typecheck, lint y format. Mock fallback universal para desarrollo sin servicios externos.
* **Stack:** Next.js 16 (App Router), TypeScript, Tailwind CSS, Zustand, Drizzle ORM, PostgreSQL, pgvector, Vertex AI, Gemini API, OpenAI, Cheerio, Docker, NextAuth.js.


* [Ver Repositorio](https://github.com/lys-developre/nexus-ai)
  
    🥇 **Proyecto Ganador Sandbox** · Hackathon GenAI Arena por *SIDN Digital Thinking*.
--- 



### 🌐 larryyoffre.com — 3D WebGL Production Portfolio
Mi ventana al mundo optimizada para rendimiento, fluidez de fotogramas y Core Web Vitals.
* **Core Técnico:** Implementación nativa y optimización de gráficos tridimensionales interactivos directamente en el navegador sin penalizar la experiencia ni los tiempos de carga del usuario.
* **Stack:** Three.js, React Three Fiber, Tailwind CSS, UX Performance.
* [Visitar Web](https://www.larryyoffre.com)
  

---

## ⚙️ Mi Flujo de Trabajo (Scaffold & Reverse Audit)

Mi fortaleza radica en la gestión de la complejidad técnica a través de un enfoque documental y un análisis de trazabilidad inverso:


[ 1. Scaffold con IA ] ➔ [ 2. Revisión Funcional Inicial ] ➔ [ 3. Documentación por Fases ] ➔ [ 4. Comprensión Profunda ]
Andamiaje Rápido: Utilizo herramientas avanzadas para levantar la arquitectura conceptual, esquemas y configuraciones iniciales del sistema.

Validación Superficial: Compruebo que el flujo básico y los endpoints cumplan operativamente con los requisitos iniciales.

Análisis por Fases: Desgloso el código generado en registros detallados de arquitectura y control de calidad (desde las bases del monorepo hasta la seguridad perimetral y observabilidad).

Asimilación e Iteración: Utilizo estos documentos para leer, auditar y absorber las líneas de código a nivel avanzado. Esto me permite mapear desviaciones (code-vs-policy drifts) y corregir errores de consistencia de manera iterativa.

## 🛠️ Stack Tecnológico
Producción (Listo para aportar valor)
Frontend: Next.js, React, TypeScript, Tailwind CSS, shadcn/ui, next-intl.

Backend & DB: Node.js, RESTful APIs, Better Auth, PostgreSQL, Prisma, Drizzle ORM.

Escalando (Workflows diarios / En desarrollo activo)
Backend : PHP, Laravel.

Tooling & DevOps: Docker, Git, Turborepo, pnpm, Vitest, Biome, CI/CD (GitHub Actions).

AI Ecosystem: Vercel AI SDK, OpenAI/Gemini/Vertex AI/Bedrock APIs.

## 📈 Executive Summary 

Full Stack Developer focused on distributed systems and AI infrastructure integration, based in Granada, Spain.

Coming from a heavy machinery operations background, I apply strict operational discipline and accountability to software architectures. My development flow leverages AI generation tools for rapid architecture scaffolding, immediately followed by a rigorous, document-driven reverse audit process to ensure complete systems comprehension.

Highlighted Project: NEXUS-AI (Self-Healing Content Pipeline)
Core Systems: Three-module pipeline (Trend Hunter → Semantic Alignment → GitOps Deploy) that transforms static web content into evolving, trend-aware entities. Multi-provider AI chain (Hybrid Vertex+Gemini > Vertex > Gemini > OpenAI > Mock) with automatic fallback. Vector database with pgvector for cosine similarity gap detection, V_target centroid, and ΔS self-correction loop.

Engineering Transparency: v2.3.0 — fully operational pipeline with real auth, rate limiting, and secure HMAC-signed deploys. Mock fallback at every layer for development without credentials. Conventional commits, pre-commit hooks, and source-available license for portfolio evaluation.

Core Stack
Next.js, TypeScript, Node.js, PostgreSQL, Better Auth, PHP/Laravel.
