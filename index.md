---
layout: default
---
# CARLOS EDUARDO NOBOA GUERRERO

 [LinkedIn](https://www.linkedin.com/in/carlos-noboa-b72040369) | [GitHub](https://github.com/cenoboa0) | [Email](mailto:cenoboa2@gmail.com) | [WhatsApp](https://wa.me/34632976508)

---

### **PERFIL PROFESIONAL**
Ingeniero en Tecnologías de la Información especializado en **Ciberseguridad Ofensiva y Gestión de Proyectos**. Experiencia técnica en auditoría de redes, pentesting y respuesta ante incidentes, complementada con una visión estratégica en planificación y negociación certificada por instituciones globales. Becario de la OEA, enfocado en la protección de activos críticos y la optimización de infraestructuras IT.

---

### **EDUCACIÓN**

**Universidad Internacional de Valencia (VIU)** | *Valencia, España*
*Máster Universitario en Ciberseguridad* | 2026 – Presente
* **Distinción:** Becario de la Organización de los Estados Americanos (OEA).

**Universidad Técnica Particular de Loja (UTPL)** | *Ecuador*
*Grado en Ingeniería en Tecnologías de la Información*
* Título con validez internacional (Homologado en la Unión Europea).

---

### **CERTIFICACIONES PROFESIONALES**

**Ciberseguridad (Cisco Networking Academy)**
* **Ethical Hacker:** Especialización en seguridad ofensiva y defensa de activos.
* **Introduction to Cybersecurity:** Fundamentos de protección y respuesta ante incidentes.

**Gestión y Liderazgo Estratégico**
* **Project Management:** Inicio y Planificación de Proyectos (**University of California, Irvine**).
* **Excelencia Operativa:** Gestión de Proyectos (**Pontificia Universidad Católica de Chile**).
* **Negociación:** Estrategias y Habilidades Esenciales (**University of Michigan**).

---
### **PROYECTOS DESTACADOS**

#### [Auditoría de Seguridad Ofensiva – Warzone VIU: CTF de Aplicaciones Web](https://github.com/cenoboa0/Hacking-e-tico-/blob/main/WarZone_Carlos_Noboa.pdf)
*Investigador de Seguridad / Pentester – Máster en Ciberseguridad, VIU*
* **Escenario:** Evaluación de seguridad completa sobre la plataforma de entrenamiento CTF (*Capture the Flag*) de la Universidad Internacional de Valencia, compuesta por 9 laboratorios independientes que simulan vectores de ataque reales en aplicaciones web del dominio `viuciberseguridad.wsg127.com`.
* **Logros:** Resolución del 100% de los laboratorios asignados con captura de todas las banderas (*flags*) disponibles. Explotación exitosa de vulnerabilidades XSS mediante técnicas avanzadas de evasión de filtros (JSFuck, codificación hexadecimal/HTML, *nested payloads*); elusión de mecanismos de autenticación a través de manipulación de tipos de dato PHP y deserialización insegura de cookies en Base64; exfiltración automatizada de credenciales mediante *Boolean-Based Blind SQL Injection* con script Python a medida; y obtención de credenciales válidas mediante ataque de diccionario con THC Hydra sobre un formulario sin *rate limiting*.
* **Metodología:** Ciclo completo de pentesting web (Reconocimiento → Análisis de código fuente → Construcción de payload → Explotación → Documentación de evidencias), con trazabilidad total mediante interceptación y manipulación de tráfico HTTP en Burp Suite Repeater.
* **Stack:** Kali Linux, Burp Suite, Python (`requests`), THC Hydra, Firefox Developer Tools.

#### [Auditoría OSINT y Reconocimiento Pasivo: Identificación de Superficie de Ataque y Evasión Perimetral](https://github.com/cenoboa0/Hacking-e-tico-/blob/main/Hacking_Etico_Reconociemiento_Pasivo.pdf)
*Investigador de Seguridad / Pentester*
* **Escenario:** Fase de reconocimiento pasivo y modelado de amenazas sobre la infraestructura digital de una organización de comercio electrónico con presencia consolidada para identificar vectores de exposición sin generar alertas en los sistemas defensivos.
* **Logros:** Descubrimiento de una brecha estructural crítica por desvío del Web Application Firewall (Bypass de WAF), triangulación de la dirección IP física del servidor de origen en OVH y mapeo completo del stack tecnológico interno y la estructura organizacional mediante ingeniería social pasiva.
* **Metodología:** Aplicación del marco estructurado OSINT Framework, técnicas de enumeración pasiva de subdominios (Certificate Transparency logs), análisis de infraestructura DNS y fingerprinting tecnológico perimetral.
* **Stack:** Kali Linux, OWASP Amass, Whois, Dig, WhatWeb, HackerTarget, crt.sh.

  #### [Minería de Datos y Automatización en R: Análisis Estadístico de Incidentes de Seguridad SSH](https://github.com/cenoboa0/Monitorizacio-n-y-data-mining/blob/main/Data%20Mining_Carlos_Noboa.pdf)
*Investigador de Seguridad / Científico de Datos de Red*
* **Escenario:** Automatización de un entorno de trabajo reproducible y desarrollo de scripts en RStudio para la ingesta, manipulación y análisis estadístico exploratorio masivo de registros de acceso SSH (`ssh_login_attempts-v2.csv`) con el fin de modelar vectores de amenazas.
* **Logros:** Procesamiento y limpieza de datos crudos de red para identificar el volumen neto de atacantes únicos y cuentas comprometidas, estructurando un ranquin jerárquico descendente de incidentes por dirección IP e implementando programación funcional vectorizada para optimizar auditorías de seguridad.
* **Metodología:** Aplicación del ciclo de vida de la ciencia de datos (Ingesta local, Validación de tipado abstracto, Filtrado multivariable en estructuras complejas y Programación funcional vectorizada en CPU de un solo bloque).
* **Stack:** R, RStudio, Tidyverse (Base R), Data.Frames, Listas Heterogéneas.

#### [Auditoría de Seguridad SMB en Entorno Linux: Enumeración de Usuarios y Evaluación de Accesos No Autenticados](https://github.com/cenoboa0/EthicalHacking-Lab-Enum4linux.git)
*Investigador de Seguridad / Pentester*
* **Escenario:** Auditoría completa de un servidor Linux (Debian) con servicios SMB expuestos en un entorno simulado de Halo.
* **Logros:** Identificación de vulnerabilidades de "Null Sessions" y enumeración de usuarios reales mediante **RID Cycling**.
* **Metodología:** Aplicación del ciclo de vida del Pentesting (Reconocimiento, Enumeración, Explotación y Reporte técnico).
* **Stack:** Kali Linux, Nmap, Enum4linux, SMBClient.
  
#### [Identificación de Credenciales Expuestas mediante Análisis de Archivos de Respaldo Públicamente Accesibles](https://github.com/cenoboa0/Hacking-e-tico-/blob/main/An%C3%A1lisis%20de%20vulnerabilidades%20web/1.%20Lab%20Source%20Code%20Disclosure%20via%20Backup%20Files.md)
*Investigador de Vulnerabilidades Web / Information Disclosure*
* **Escenario:** Identificación y explotación de un archivo de respaldo expuesto públicamente (ProductTemplate.java.bak) en un servidor web de producción.
* **Logros:** Credenciales de conexión hardcodeadas para una base de datos PostgreSQL, extraídas del método readObject() del código fuente filtrado.
* **Metodología:** Reconocimiento pasivo mediante robots.txt → enumeración de directorios (Directory Listing) → análisis estático de código fuente → exfiltración de credenciales.
* **Stack:** Burp Suite · Firefox · Kali Linux · PortSwigger Web Security Academy
  
#### [Planificación y Definición del Alcance de una Auditoría de Seguridad para Plataforma E-commerce](https://github.com/cenoboa0/NexusPlaza-Cyber-Audit-Scoping-and-Rules-of-Engagement)
*Auditor de Seguridad / GRC*
* **Escenario:** Planificación estratégica y técnica de una auditoría de seguridad externa para una plataforma e-commerce.
* **Logros:** Definición de activos críticos, establecimiento de Reglas de Compromiso (RoE) y protocolos de comunicación ética.
* **Metodología:** Análisis de superficie de ataque (Reconocimiento) y cumplimiento normativo para auditorías de caja negra.
* **Stack:** Nmap, GitHub, Frameworks de Auditoría Ética.


---

### **COMPETENCIAS TÉCNICAS (TECH STACK)**

* **Sistemas Operativos:** Kali Linux, Linux (Debian/Ubuntu), Windows Server.
* **Herramientas de Auditoría & Pentesting:** Nmap, Burp Suite, Enum4linux, SMBClient, Metasploit, Wireshark, Firefox Developer Tools.
* **OSINT & Reconocimiento:** OWASP Amass, OSINT Framework, Certificate Transparency Logs (crt.sh), Dig (DNS diagnostics), Whois, HackerTarget, WhatWeb (Fingerprinting perimetral).
* **Ciencia de Datos & Data Mining (Seguridad):** Lenguaje R, RStudio, Análisis estadístico exploratorio de logs de acceso (SSH/Syslog), Programación funcional vectorizada, Data.Frames y manipulación de estructuras complejas.
* **Gestión de Proyectos, GRC & Liderazgo:** Planificación estratégica de auditorías de caja negra, definición de Activos Críticos, redacción de Reglas de Compromiso (RoE), protocolos de comunicación ética, metodologías ágiles, control de versiones (GitHub) y liderazgo técnico.
* **Habilidades Blandas:** Negociación estratégica para la definición del alcance, comunicación asertiva en reportes técnicos y ejecutivos, resolución analítica de incidentes y modelado asimétrico de amenazas.
---

### **CONTACTO**
* ✉️ **Email:** cenoboa2@gmail.com
* 🔗 **LinkedIn:** [carlos-noboa-b72040369](https://www.linkedin.com/in/carlos-noboa-b72040369)
