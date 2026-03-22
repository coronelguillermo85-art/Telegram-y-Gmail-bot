# 🤖 AI-Ops & Automation Ecosystem
### Desarrollado por Guillermo Coronel

Este repositorio centraliza mis desarrollos en **Automatización de Procesos (IPA)** y **Orquestación de Inteligencia Artificial**. Aquí demuestro cómo transformo tareas manuales en flujos de trabajo autónomos, escalables y eficientes, utilizando un stack moderno de herramientas No-Code y Low-Code.

---

## 🧠 Proyecto 1: AI-Job-Scout (Dify + Make + Telegram)
*Sistema de filtrado inteligente y scouting de oportunidades mediante IA.*

Este ecosistema utiliza Inteligencia Artificial para reducir el ruido informativo y priorizar vacantes de alto valor en tiempo real, permitiendo una respuesta inmediata ante oportunidades estratégicas.

### 🛠 Arquitectura del Agente (Dify.ai)
El corazón del sistema es un flujo de trabajo en **Dify** que procesa cada dato detectado:
- **Modelo:** Llama-3.1-8b-instant.
- **Lógica de Clasificación:** El agente evalúa títulos y descripciones bajo tres criterios:
  1. **Filtro de Relevancia:** Descarta automáticamente contenido que no sea una oferta laboral real (noticias, artículos, etc.).
  2. **Scoring de Perfil:** Asigna un *Match Score* (1-10) basado en mi stack técnico y experiencia previa.
  3. **Generación de Síntesis:** Extrae categorías clave y redacta una estrategia de contacto inicial.

### 🔄 Integración Sistémica (Make.com)
1. **Captura:** Monitoreo de feeds RSS y Scrapping vía peticiones **HTTP**.
2. **Inferencia:** Envío de datos a la API de Dify para procesamiento cognitivo.
3. **Delivery:** Notificación enriquecida a un **Bot de Telegram** personalizado.

---

## 📧 Proyecto 2: Mail-Ops Manager (Make + Google Sheets + Gmail)
*Sistema de centralización de avisos y gestión de Mesa de Ayuda.*

Este flujo representa mi capacidad para gestionar una **Mesa de Ayuda (Help Desk)** automatizada, transformando reportes técnicos en registros estructurados y acciones de comunicación automáticas.

### 🛠 Funcionamiento:
1. **Recepción de Datos:** Captura de avisos técnicos y reportes generados (incluyendo sugerencias de asistentes de IA).
2. **Centralización en Google Sheets:** Los datos se insertan automáticamente en una hoja de cálculo, garantizando la trazabilidad, el orden cronológico y el historial de cada incidencia.
3. **Validación y Despacho:** El sistema utiliza módulos **HTTP** para verificar información y dispara correos electrónicos automáticos vía **Gmail** a los destinatarios correspondientes.

### 📈 Impacto en Soporte N1/N2:
- **Eliminación del Error Humano:** 0% de pérdida de información en el traspaso manual de datos.
- **Optimización de Tiempos (SLA):** Procesamiento e inserción instantánea de reportes.
- **Auditoría:** Registro centralizado listo para análisis de métricas y mejora continua de procesos.

---

## 🛠 Stack Tecnológico
* **Orquestación:** Make.com, n8n.
* **Inteligencia Artificial:** Dify.ai (Llama 3.1).
* **Bases de Datos:** Google Sheets, Airtable.
* **Comunicaciones:** Telegram Bot API, Gmail API.
