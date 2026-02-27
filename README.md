# 🛡️ Defensive Security & DFIR Portfolio

![Status](https://img.shields.io/badge/Status-Active_Project-success)
![Focus](https://img.shields.io/badge/Focus-Blue_Team_%7C_DFIR_%7C_Threat_Intel-blue)
![Goal](https://img.shields.io/badge/Goal-30+_Labs-orange)

Bienvenido a mi repositorio técnico de investigaciones forenses y respuesta a incidentes. 

Como estudiante de Ingeniería de Ciberseguridad (7mo ciclo, Universidad Nacional de Ingeniería - UNI) preparándome para el sector corporativo, este repositorio funciona como un **laboratorio vivo y en constante evolución**. Aquí documento mis prácticas, resoluciones y metodologías aplicadas a escenarios de ciberataques realistas, con el objetivo de desarrollar una sólida memoria muscular en operaciones de Blue Team.

## 📌 Sobre este proyecto y los Writeups
A diferencia de un repositorio estático, este es un proyecto en desarrollo. Las documentaciones proporcionan soluciones técnicas paso a paso. A medida que avanzo en mi formación analítica, la estructura de los reportes irá evolucionando desde guías técnicas básicas hacia resúmenes ejecutivos formales.

La dificultad de cada investigación refleja la calificación oficial de la plataforma de origen:
* 🟢 **Fácil:** Fundamentos de herramientas y extracción básica de artefactos.
* 🟡 **Medio:** Análisis profundo, ofuscación y correlación de múltiples eventos.
* 🔴 **Difícil:** Escenarios APT, caza de amenazas avanzada e ingeniería inversa.

## 📑 Tabla de Investigaciones

Los casos están divididos por disciplinas forenses, siguiendo los estándares de la industria.

### 🌐 Network Forensics
Investigación de tráfico de red, análisis de PCAPs y detección de exfiltración de datos.

| Escenario | Documento | Plataforma | Dificultad | Habilidades Demostradas (Tags) |
| :--- | :---: | :---: | :---: | :--- |
| **PacketMaze** | [PDF](./writeups/PacketMaze_Writeup.pdf) | CyberDefenders | 🟢 Fácil | `Wireshark` `FTP/HTTP Analysis` `Data Extraction` |
| **Tomcat Takeover** | [PDF](./writeups/TomcatTakeover_Writeup.pdf) | CyberDefenders | 🟡 Medio | `Web Shells` `Encrypted Traffic` `Malware Staging` |

### 🕵️ Threat Intelligence & Malware Analysis
Extracción de Indicadores de Compromiso (IoCs) y análisis de comportamiento de artefactos maliciosos.

| Escenario | Documento | Plataforma | Dificultad | Habilidades Demostradas (Tags) |
| :--- | :---: | :---: | :---: | :--- |
| **IcedID** | [PDF](./writeups/IcedID_Writeup.pdf) | CyberDefenders | 🟡 Medio | `OSINT` `VirusTotal` `Malware Behavior` `IoC Extraction` |

*(Categorías de Endpoint Forensics y Memory Dump Analysis en construcción próximamente...)*

## 🛠️ Herramientas de Análisis (Stack Tecnológico)
Una muestra de las herramientas empleadas en la resolución de estos escenarios:

* **Análisis de Red:** Wireshark, NetworkMiner, Zeek.
* **Inteligencia de Amenazas:** VirusTotal, Any.Run, OSINT.
* **Entornos:** VirtualBox (Entornos aislados de análisis en Ubuntu Linux).

---
*Este repositorio se actualiza continuamente con nuevos escenarios, reportes y análisis técnicos.*
