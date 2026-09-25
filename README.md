# 🚀 Especialista TI (IBM) | Junior SecOps & SIEM | Docker 
![Profile Views](https://komarev.com/ghpvc/?username=defensa29-svg&color=blue&style=flat-square)

<img width="1400" height="788" alt="bbefa799786133 5efa9bf3d1b49" src="https://github.com/user-attachments/assets/2a2b3be3-f079-4fca-b5a9-9bccaac99b0e" />



### 🔥 Sobre mí - Profesional de Soporte Técnico y SecOps

Profesional de Soporte Técnico y SecOps enfocado en mercado IT, con sólida formación práctica y certificaciones oficiales en ciberseguridad, automatización y gestión de incidencias L1/L2.

Fundamentos de Docker y SecOps demostrados de forma continua en mis laboratorios y publicaciones de esta red.

**🔹 CERTIFICACIONES Y COMPETENCIAS CLAVE:**

🛡️ **Palo Alto Networks:** SecOps, arquitectura SOAR (Cortex XSOAR), gestión de amenazas (TIM) y aislamiento de endpoints (XDR/XSIAM).
🎯 **Hacking Ético & IA:** Certificado en "Hacker ético" y "Cazador de amenazas de IA".
🌐 **Cisco Systems:** Redes, ciberseguridad, análisis de amenazas, controles y seguridad perimetral.
💻 **IBM SkillsBuild:** TI avanzada (DHCP/IP, cloud, APIs), ciberseguridad y datos.
🤖 **Anthropic:** Claude 101 y Claude Code (Automatización, prompts y auditorías con RAG).
🏛️ **Fundación Carlos Slim:** Técnico en Sistemas Informáticos, Seguridad Perimetral, Análisis de Riesgos e Investigación Digital.
🔑 **Microsoft:** Identidades, accesos y gobernanza con Microsoft Entra ID.

**⚙️ CAPACIDADES TÉCNICAS Y OPERATIVAS:**

🐳 **Seguridad en Contenedores:** Bastionado (hardening) de entornos Docker e implementación de soluciones defensivas (Trivy, Falco) y despliegue automatizado de infraestructuras de alta disponibilidad, auto-reparación (Self-healing) y actualizaciones progresivas en caliente (Rolling Updates) con Docker Swarm.
📡 **Auditoría de Redes:** Análisis profundo de tráfico y protocolos con Wireshark para detección de anomalías.
🤖 **Automatización:** Desarrollo de scripts propios (.bat / .reg / .sh / .ps1) para optimización de sistemas y laboratorios de pruebas.
🎧 **Soporte, Helpdesk y SLAs:** Configuración e incidencias en Windows (95 a 11). Titulación Oficial SEXPE: Empleado de Información al Cliente homologada, con competencias en soporte omnicanal, Helpdesk, cumplimiento de SLAs, aplicación de RGPD y gestión de Knowledge Base.

---

### 🗺️ RUTA EN CIBERSEGURIDAD - Mi Roadmap

> No se trata de aprender todo, sino de construir una base sólida y seguir avanzando paso a paso.

**1. REDES:** TCP/IP, DNS, HTTP/HTTPS, Subnetting, Firewall/VPN, Puertos y servicios
**2. LINUX / WINDOWS:** Usuarios y permisos, Procesos y servicios, Logs, Bash/PowerShell
**3. ACTIVE DIRECTORY:** Usuarios y grupos, Políticas (GPO), Permisos, Kerberos/LDAP, Windows Server
**4. FUNDAMENTOS DE SEGURIDAD:** Amenazas y vulnerabilidades, Autenticación/Autorización, Criptografía básica, Hardening, Gestión de incidentes
**5. PYTHON:** Automatización, Análisis de datos, Peticiones HTTP, Scripts de seguridad
**6. LABORATORIOS:** Wireshark, Análisis de logs, Máquinas vulnerables, Proyectos prácticos, GitHub -> **Aquí están mis labs**

---

### 🛠️ HERRAMIENTAS CLAVE PARA PRUEBAS CONTROLADAS

> Pentesting y análisis de seguridad en entornos autorizados | Uso ético y con permiso

#### 01 - Kali Linux [DISTRO]
Distribución orientada a pentesting y auditoría. **Uso Blue Team:** La uso como base para mis labs, pero desde defensa para validar que mis hardening funcionan.
`Comando defensivo: lynis audit system`

#### 02 - Nmap [RECON]
Descubre hosts, puertos y servicios en red. **Uso Blue Team:** Inventario defensivo, no ataque. Ver qué tengo abierto yo.
```bash
nmap -sV -sC 127.0.0.1
ss -tuln
```

#### 03 - Burp Suite [WEB]
Analiza y prueba la seguridad de aplicaciones web. **Uso Blue Team:** Intercepto mi propia web de laboratorio para encontrar cabeceras inseguras.
`Uso: Proxy -> Intercept -> Repeater para validar parches`

#### 04 - Metasploit [EXPLOIT]
Framework para validar y simular explotación. **Uso Blue Team:** Solo para validar que mi parche cerró la vulnerabilidad en mi VM autorizada.

#### 05 - Wireshark [TRÁFICO]
Inspecciona tráfico y protocolos en tiempo real. **Uso Blue Team:** Mi herramienta principal SOC L1. Detecto SMBv1, DNS anómalo, intentos de exfiltración.
```bash
tshark -i eth0 -Y "smb.cmd == 0x72" # Detectar SMBv1
```

#### 06 - OWASP ZAP [VULNS]
Escáner web útil para detectar fallos comunes. **Uso Blue Team:** Escaneo automático de mis labs web antes de publicar.

**FLUJO DE TRABAJO BLUE TEAM:**
`Reconocimiento (Entiende el entorno) -> Análisis (Identifica riesgos) -> Validación (Confirma hallazgos)`

> Las herramientas no sustituyen la metodología ni la autorización. Aprender, practicar y reportar de forma responsable.
> <img width="800" height="998" alt="1789915370346" src="https://github.com/user-attachments/assets/11345c9f-1ae7-4a91-afef-f0810bba3d48" />
---

### 💻 Pila tecnológica

**Seguridad & Redes**
![PaloAlto](https://img.shields.io/badge/PaloAlto-XSOAR-orange?style=for-the-badge)
![Cisco](https://img.shields.io/badge/Cisco-Security-blue?style=for-the-badge)
![Wireshark](https://img.shields.io/badge/Wireshark-Analysis-1679A7?style=for-the-badge)
![Trivy](https://img.shields.io/badge/Trivy-Hardening-red?style=for-the-badge)

**Sistemas**
![Docker](https://img.shields.io/badge/Docker-Swarm-2496ED?style=for-the-badge&logo=docker)
![Linux](https://img.shields.io/badge/Linux-Ubuntu-E95420?style=for-the-badge&logo=ubuntu)
![Bash](https://img.shields.io/badge/Bash-Scripts-black?style=for-the-badge&logo=gnu-bash)
![PowerShell](https://img.shields.io/badge/PowerShell-Harden-blue?style=for-the-badge&logo=powershell)

---
### Resumen del laboratorio actual
**equipo-azul-laboratorio-sociedad-l1-l2:** Laboratorio de parcheo y endurecimiento para SOC L1/L2. Validación de ciclo de vida de parches en Ubuntu y Windows, deshabilitado de SMBv1 y cierre de puertos (vsftpd/21) con UFW.

**Autor:** Iván Ajenjo Morales | defensa29-svg | L1/L2 ITIL SecOps | Licencia MIT
