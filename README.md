# 🚀 Especialista TI (IBM) | Junior SecOps & SIEM | Docker 
![Profile Views](https://komarev.com/ghpvc/?username=defensa29-svg&color=blue&style=flat-square)

<img width="2240" height="2380" alt="combinado-ivan-ajenjomorales" src="https://github.com/user-attachments/assets/9d369e9a-7ade-4574-8ec5-ef845c77ba1a" />


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

<img width="1920" height="1280" alt="image_20260926_004346-uso-etico-y-con-permiso-mejor-en-el-medio-icluye-mi-nombre-herramientas-clave" src="https://github.com/user-attachments/assets/0df23a59-ad52-4115-9dbe-f798aed560d1" />

---
### 💻 Pila tecnológica

**Seguridad y Redes**
![XSOAR](https://img.shields.io/badge/PALOALTO-XSOAR-FF6A00?style=for-the-badge&logo=paloaltonetworks&logoColor=white)
![CISCO](https://img.shields.io/badge/CISCO-SECURITY-1BA0D7?style=for-the-badge&logo=cisco&logoColor=white)
![Wireshark](https://img.shields.io/badge/WIRESHARK-ANALYSIS-1679A7?style=for-the-badge&logo=wireshark&logoColor=white)
![Trivy](https://img.shields.io/badge/TRIVY-HARDENING-C71B26?style=for-the-badge&logo=aqua&logoColor=white)

**Sistemas y Automatización**
![Docker](https://img.shields.io/badge/DOCKER-SWARM-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Ubuntu](https://img.shields.io/badge/LINUX-UBUNTU-E95420?style=for-the-badge&logo=ubuntu&logoColor=white)
![Bash](https://img.shields.io/badge/BASH-SCRIPTS-4EAA25?style=for-the-badge&logo=gnubash&logoColor=white)
![PowerShell](https://img.shields.io/badge/POWERSHELL-HARDEN-5391FE?style=for-the-badge&logo=powershell&logoColor=white)
![Windows](https://img.shields.io/badge/WINDOWS-HARDENING-0078D4?style=for-the-badge&logo=windows11&logoColor=white)
![Python](https://img.shields.io/badge/PYTHON-AUTOMATION-FFC300?style=for-the-badge&logo=python&logoColor=black)

### Resumen del laboratorio actual
**Equipo-azul-laboratorio-sociedad-l1-l2:** Laboratorio de parcheo y endurecimiento para SOC L1/L2. 

Validación de ciclo de vida de parches en Ubuntu y Windows, deshabilitado de SMBv1 y cierre de puertos (vsftpd/21) con UFW.

**Autor:** Iván Ajenjo Morales | L1/L2 ITIL SecOps | Licencia MIT
