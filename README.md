<div align="center">
  <img src="assets/hero.svg" width="100%" alt="John Casana — AI Developer e Ingeniero Electrónico"/>
  <br/>
  <img src="https://readme-typing-svg.demolab.com?font=Inter&weight=500&size=19&duration=3200&pause=1100&color=D9B45A&center=true&vCenter=true&width=640&height=40&lines=Dise%C3%B1o+sistemas+inteligentes+que+aprenden%2C+se+adaptan+y+act%C3%BAan.;Agentes+%C2%B7+RAG+%C2%B7+Automatizaci%C3%B3n;De+la+electr%C3%B3nica+a+la+nube." alt="tagline"/>
  <br/>
  <a href="https://www.linkedin.com/in/johncasana/"><img src="https://img.shields.io/badge/LinkedIn-johncasana-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="mailto:johncasana83@gmail.com"><img src="https://img.shields.io/badge/Gmail-johncasana83-EA4335?style=flat-square&logo=gmail&logoColor=white" alt="Gmail"/></a>
</div>

<img src="assets/divider.svg" width="100%" alt=""/>

## Sobre mí

Soy ingeniero electrónico egresado de la **Universidad Nacional de Ingeniería (UNI)**, del quinto superior de mi promoción, y desarrollador enfocado en **IA generativa**.

Me interesa diseñar sistemas que combinan modelos de lenguaje, bases vectoriales y agentes para automatizar procesos y apoyar decisiones con datos. Vengo de la electrónica, así que disfruto entender un sistema de punta a punta: desde el diseño de una PCB hasta una API desplegada en la nube.

- **Ubicación:** Lima, Perú
- **Formación:** Ingeniería Electrónica, UNI
- **Idiomas:** español e inglés

<img src="assets/divider.svg" width="100%" alt=""/>

## Habilidades

<div align="center">
  <img src="assets/radar.svg" width="680" alt="Radar de habilidades"/>
  <br/>
  <sub>Hexágono inspirado en el gráfico de Nen. Los niveles son una referencia, no una medición.</sub>
</div>

<br/>

| Área | Herramientas y conceptos |
| :-- | :-- |
| **GenAI y RAG** | Gemini, Vertex AI, embeddings, chunking, bases vectoriales (Qdrant, Pinecone, Supabase), Hugging Face |
| **Agentes y automatización** | Model Context Protocol (MCP), n8n, Copilot Studio, Dialogflow, watsonx Assistant, Power Automate, Power Apps |
| **Backend y APIs** | Python, FastAPI, TypeScript, Node.js, webhooks, streaming SSE, pytest |
| **Datos y ML** | SQL y PL/SQL, PySpark, pandas, NumPy, matplotlib, Power BI, TensorFlow, deep learning, NLP |
| **Cloud y DevOps** | GCP (Cloud Run, Firestore, Cloud Tasks), AWS (Glue, S3), Azure DevOps, Docker, Terraform, Git |
| **Frontend y electrónica** | Angular, HTML, CSS y JavaScript, diseño y fabricación de PCB |

<div align="center">
  <img src="https://skillicons.dev/icons?i=py,fastapi,ts,js,nodejs,angular,tensorflow,pandas,numpy,docker,terraform,gcp,aws,azure,supabase,git,github&theme=dark&perline=17" alt="stack"/>
</div>

<img src="assets/divider.svg" width="100%" alt=""/>

## Proyectos

### Loma · Chatbot RAG para una ONG de ecoturismo

Asistente conversacional que atiende consultas por **WhatsApp** y desde un **widget web** embebible, respondiendo con información de los propios documentos de la organización.

- **Pipeline RAG:** ingesta de PDFs, URLs y texto, división en fragmentos de 500 palabras con solape, embeddings con Gemini y búsqueda en Qdrant.
- **Umbral de similitud:** si no hay contexto suficiente, no inventa una respuesta y deriva la conversación a una persona.
- **WhatsApp asíncrono:** el webhook responde al instante y el procesamiento pasa por Cloud Tasks, para respetar el límite de tiempo de Meta.
- **Leads y CRM:** sesiones en Firestore, puntaje de intención y sincronización de contactos con HubSpot.
- **Widget propio:** JavaScript puro, sin dependencias, con respuestas en streaming (SSE) y pantalla completa en móvil.
- **Calidad y despliegue:** panel de administración, tests con pytest sin llamadas reales a APIs y despliegue en Cloud Run con Docker.

<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python"/>
<img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" alt="FastAPI"/>
<img src="https://img.shields.io/badge/Gemini-8E75B2?style=flat-square&logo=googlegemini&logoColor=white" alt="Gemini"/>
<img src="https://img.shields.io/badge/Qdrant-DC244C?style=flat-square&logo=qdrant&logoColor=white" alt="Qdrant"/>
<img src="https://img.shields.io/badge/Firestore-FFA000?style=flat-square&logo=firebase&logoColor=white" alt="Firestore"/>
<img src="https://img.shields.io/badge/Cloud%20Run-4285F4?style=flat-square&logo=googlecloud&logoColor=white" alt="Cloud Run"/>
<img src="https://img.shields.io/badge/WhatsApp-25D366?style=flat-square&logo=whatsapp&logoColor=white" alt="WhatsApp"/>
<img src="https://img.shields.io/badge/HubSpot-FF7A59?style=flat-square&logo=hubspot&logoColor=white" alt="HubSpot"/>

### Otros proyectos

<table>
  <tr>
    <td width="50%" valign="top">
      <b>RAG para documentos legales</b><br/>
      Pipeline completo: web scraping, estrategias de chunking y embeddings con Vertex AI, ajustado para maximizar la precisión de las respuestas.<br/>
      <sub>Vertex AI · Python · scraping</sub>
    </td>
    <td width="50%" valign="top">
      <b>AEO Tracker</b><br/>
      Aplicación full-stack que mide y audita la presencia e impacto de marcas en distintos motores de IA generativa.<br/>
      <sub>FastAPI · Angular · GCP</sub>
    </td>
  </tr>
  <tr>
    <td valign="top">
      <b>Agentes en Copilot Studio</b><br/>
      Chatbots corporativos con herramientas (tools) personalizadas e IA generativa integrada.<br/>
      <sub>Copilot Studio · Power Platform</sub>
    </td>
    <td valign="top">
      <b>ETL en AWS</b><br/>
      Servicios AWS Glue y S3 desplegados con Docker y Terraform para ejecutar procesos ETL de datos en local.<br/>
      <sub>AWS Glue · S3 · Docker · Terraform</sub>
    </td>
  </tr>
  <tr>
    <td valign="top">
      <b>Servidor MCP</b><br/>
      Práctica con el SDK de Model Context Protocol: servidor en TypeScript con herramientas tipadas con Zod, como una consulta de clima vía Open-Meteo.<br/>
      <sub>TypeScript · MCP SDK · Zod</sub>
    </td>
    <td valign="top">
      <b>Visualización de datos</b><br/>
      Scripts que comparan indicadores entre periodos y generan gráficos listos para reportes.<br/>
      <sub>Python · matplotlib · NumPy</sub>
    </td>
  </tr>
</table>

<img src="assets/divider.svg" width="100%" alt=""/>

## Licencias y certificaciones

| Área | Certificación | Emisor | Año |
| :-- | :-- | :-- | :-: |
| **IA y ML** | Macroentrenamiento de Inteligencia Artificial (Python, ML, DL, NLP) | UNAM | 2025 |
| | Fundamentals of Deep Learning | NVIDIA | 2025 |
| | Machine Learning Engineer (Git, Docker, MLOps, GCP) | IEEE CIS UNI | 2024 |
| | n8n: agentes de IA, RAG y bases vectoriales | Udemy | 2025 |
| **Automatización** | Microsoft Copilot Studio | Udemy | 2025 |
| | Microsoft Copilot 365 | Udemy | 2025 |
| | Microsoft Power Apps | Udemy | 2025 |
| | Microsoft Power Automate | Udemy | 2025 |
| **Cloud y DevOps** | GCP Digital Leader | Udemy | 2025 |
| | AWS Cloud Practitioner Essentials | AWS | 2025 |
| | Azure DevOps | Udemy | 2025 |
| | Curso profesional de Git | Código Facilito | 2024 |
| **Datos y programación** | Curso profesional de Python | Código Facilito | 2024 |
| | Análisis de datos con Python (NumPy y pandas) | Código Facilito | 2024 |
| | SQL (Intermediate) | HackerRank | 2025 |
| | Excel y Power BI | Cámara de Comercio Exterior | 2024 |
| **Electrónica e idiomas** | Diseño y fabricación de PCB | CTIC UNI | 2023 |
| | Examen de suficiencia de inglés | UNI | 2022 |

<img src="assets/divider.svg" width="100%" alt=""/>

## Contacto

<a href="https://www.linkedin.com/in/johncasana/"><img src="https://img.shields.io/badge/LinkedIn-johncasana-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
<a href="mailto:johncasana83@gmail.com"><img src="https://img.shields.io/badge/Gmail-johncasana83-EA4335?style=flat-square&logo=gmail&logoColor=white" alt="Gmail"/></a>

<div align="center">
  <img src="assets/footer.svg" width="100%" alt="Nos vemos en el próximo examen."/>
</div>
