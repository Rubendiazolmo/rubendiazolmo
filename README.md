# Rubén Díaz Olmo

> Industrial automation tech · building at the IT/OT boundary · Valencia, Spain

Técnico de automatización industrial con +4 años en entornos OT — PLC, HMI, SCADA multimarca —
evolucionando hacia desarrollo de software industrial, integración IT/OT y sistemas de datos.
Construyo herramientas que eliminan trabajo manual y conectan el mundo de planta con el mundo IT.
Automatizo antes de repetir.

---

## Stack

| OT | Lenguajes | Data & Observabilidad | IA aplicada | Infra |
|---|---|---|---|---|
| Siemens TIA Portal / Step7 | Python | InfluxDB · Telegraf | Claude (Anthropic API) | Docker |
| Omron · Rockwell · Schneider | C# | Grafana | Ollama · Mistral · Qwen | Linux · Windows |
| WinCC · ASEM · Indusoft | Go | SQLite | Embeddings + RAG | Tailscale |
| Modbus TCP/RTU · Profinet | REST APIs | ChromaDB | Telegram Bots | Homelab |

---

## Proyectos en entorno profesional

**Sistema de alarmas industriales por Telegram**
`Python` `WinCC` `ASEM` `Telegram Bot API`
Integración con varios sistemas SCADA/HMI para notificación automática de alarmas a grupos de usuarios. Arquitectura desacoplada que no interfiere con el sistema de control. Desplegado en entornos reales de producción.

**Pipeline de documentación técnica con LLM**
`Python` `C#` `Claude API` `REST API` `SQLite`
Procesamiento batch de logs de campo con Claude para generar documentación técnica estructurada. Persistencia intermedia en JSON para auditoría y reprocesado. Publicación automática en wiki interna vía API REST. Implementación dual en Python y C# con base de datos compartida.

**Sistema de registros industriales**
`Telegraf` `InfluxDB` `Grafana` `Docker`
Sustitución de una solución basada en hardware con limitaciones técnicas por un stack moderno contenerizado. Mejora drástica en tiempos de consulta de datos históricos y visualización en tiempo real adaptada a necesidades reales de planta.

**Acceso remoto seguro a entornos OT**
`Tailscale` `Guacamole` `VNC` `Linux`
Solución de acceso remoto a sistemas industriales sin exposición directa a internet. Permite intervención técnica remota sobre PLCs, HMIs y PCs de planta desde cualquier ubicación de forma segura.

---

## Proyectos personales

**Sistema RAG para mantenimiento industrial**
`Python` `Ollama` `ChromaDB` `Telegram Bot API`
Base de conocimiento construida sobre histórico de averías. Embeddings locales con Ollama y ChromaDB para búsqueda semántica. Bot de consulta vía Telegram con control de calidad mediante umbrales de similitud. Sin dependencia cloud.

**MFA para HMI industrial**
`Go` `ESP32` `Modbus` `TOTP`
Autenticación de doble factor para HMIs industriales usando TOTP. Implementación con ESP32 vía Modbus y variante en Go para HMIs en PC. Sincronización de hora entre dispositivos. Seguridad OT sin depender de servicios externos.

**Time tracker con reporting automático**
`Python` `SQLite` `Ollama`
Registro local de tiempo por proyecto con exportación a CSV. Generación automática de reportes mediante LLM local. Herramienta interna para seguimiento de trabajo real sin fricción.

**Sistema de captura de conocimiento técnico** *(en desarrollo)*
Herramienta para registrar problemas, soluciones y decisiones técnicas del trabajo diario. Base de conocimiento compartida para evitar pérdida de contexto y reducir repetición de errores en equipos técnicos.

---

## Hacia dónde evoluciono

- Desarrollo de software industrial — herramientas que viven en planta y resuelven problemas reales
- Sistemas de datos y telemetría — del sensor a la visualización, sin intermediarios innecesarios
- Integración IT/OT — conectar lo que lleva años desconectado
- IoT y edge computing — procesamiento donde se generan los datos
- IA aplicada a entornos industriales — no como buzzword, sino como herramienta concreta

---

[rubendiazolmo.github.io](https://rubendiazolmo.github.io) · rubendiazolmo@outlook.com
