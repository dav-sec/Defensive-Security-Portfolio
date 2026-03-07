# Defensive Security & DFIR Portfolio

![Status](https://img.shields.io/badge/Status-Active_Project-success)
![Focus](https://img.shields.io/badge/Focus-Blue_Team_%7C_DFIR_%7C_Threat_Intel-blue)
![Goal](https://img.shields.io/badge/Goal-30+_Labs-orange)

Bienvenido a mi repositorio técnico de investigaciones forenses y respuesta a incidentes. 

Como estudiante de Ingeniería de Ciberseguridad preparándome para el sector corporativo, este repositorio funciona como un **laboratorio vivo y en constante evolución**. Aquí documento mis prácticas, resoluciones y metodologías aplicadas a escenarios de ciberataques realistas, con el objetivo de desarrollar una sólida memoria muscular en operaciones de Blue Team.

## Sobre este proyecto y los Writeups
A diferencia de un repositorio estático, este es un proyecto en desarrollo. Las documentaciones proporcionan soluciones técnicas paso a paso. A medida que avanzo en mi formación analítica, la estructura de los reportes irá evolucionando desde guías técnicas básicas hacia resúmenes ejecutivos formales.

La dificultad de cada investigación refleja la calificación oficial de la plataforma de origen:
* 🟢 **Easy**
* 🟡 **Medium**
* 🔴 **Hard**

## Tabla de Investigaciones

Los casos están divididos por disciplinas forenses, siguiendo los estándares de la industria.

### Network Forensics
Investigación de tráfico de red, análisis de PCAPs y detección de exfiltración de datos.

| Escenario | Documento | Plataforma | Dificultad | Herramientas |
| :--- | :---: | :---: | :---: | :--- |
| **PacketMaze** | [PDF](https://github.com/dav-sec/Defensive-Security-Portfolio/blob/main/Writeups/CyberDefenders/Medium/PacketMaze/PacketMaze_CyberDefenders.pdf) | CyberDefenders | 🟡 Medium | `Wireshark` |
| **Tomcat Takeover** | [PDF](https://github.com/dav-sec/Defensive-Security-Portfolio/blob/main/Writeups/CyberDefenders/Easy/Tomcat%20Takeover/Tomcat%20Takeover_CyberDefenders.pdf) | CyberDefenders | 🟢 Easy | `Wireshark` `NetworkMiner` |
| **Lockdown** | [PDF](https://github.com/dav-sec/Defensive-Security-Portfolio/blob/main/Writeups/CyberDefenders/Easy/Lockdown/Lockdown_CyberDefenders.pdf) | CyberDefenders | 🟢 Easy | `Wireshark` `Volatility 3` `flare-floss` `Detect It Easy (DIE)` `VirusTotal` `Tria.ge` |
| **BlueSky Ransomware** | [PDF](https://github.com/dav-sec/Defensive-Security-Portfolio/blob/main/Writeups/CyberDefenders/Medium/BlueSky%20Ransomware/BlueSky%20Ransomware_CyberDefenders.pdf) | CyberDefenders | 🟡 Medium | `Wireshark` `NetworkMiner` `Event Log Explorer` `Any.run` `VirusTotal` |
| **OpenWire** | [PDF](https://github.com/dav-sec/Defensive-Security-Portfolio/blob/main/Writeups/CyberDefenders/Medium/OpenWire/OpenWire_CyberDefenders.pdf) | CyberDefenders | 🟡 Medium | `Wireshark` `NetworkMiner` |
| **HawkEye** | [PDF](https://github.com/dav-sec/Defensive-Security-Portfolio/blob/main/Writeups/CyberDefenders/Medium/HawkEye/HawkEye_CyberDefenders.pdf) | CyberDefenders | 🟡 Medium | `Wireshark` `NetworkMiner` `MaxMind Geo IP` `QuickHash` `CyberChef` |
| **NukeTheBrowser** | [PDF](https://github.com/dav-sec/Defensive-Security-Portfolio/blob/main/Writeups/CyberDefenders/Hard/NukeTheBrowser/NukeTheBrowser_CyberDefenders.pdf) | CyberDefenders | 🔴 Hard | `Wireshark` `NetworkMiner` `SpiderMonkey` `QuickHash` `CyberChef` `Scdbg` `Detect It Easy (DIE)` |
| **EscapeRoom** | [PDF](https://github.com/dav-sec/Defensive-Security-Portfolio/blob/main/Writeups/CyberDefenders/Medium/EscapeRoom/EscapeRoom_CyberDefenders.pdf) | CyberDefenders | 🟡 Medium | `Wireshark` `NetworkMiner` `Zui` `QuickHash` `CyberChef` `Hashcat` `VirusTotal` `IDA` `Radare2` |

### Threat Intelligence
Extracción de Indicadores de Compromiso (IoCs) y análisis de comportamiento de artefactos maliciosos.

| Escenario | Documento | Plataforma | Dificultad | Habilidades Demostradas (Tags) |
| :--- | :---: | :---: | :---: | :--- |
| **IcedID** | [PDF](https://github.com/dav-sec/Defensive-Security-Portfolio/blob/main/Writeups/CyberDefenders/Easy/IcedID/IcedID_CyberDefenders.pdf) | CyberDefenders | 🟢 Easy | `VirusTotal` `Malpedia` `Tria.ge` |

*(Categorías en construcción próximamente...)*


## Herramientas Utilizadas

Algunas de las herramientas utilizadas en estas resoluciones incluyen:

| Categoría | Nombre de la Herramienta | Enlace |
| :--- | :--- | :--- |
| **Análisis de Red y Paquetes** | Wireshark | https://www.wireshark.org/ |
| | NetworkMiner | https://www.netresec.com/?page=NetworkMiner |
| **Análisis de Memoria (Memory Forensics)** | Volatility 3 | https://github.com/volatilityfoundation/volatility3 |
| **Análisis de Logs y Eventos del Sistema** | Event Log Explorer | https://eventlogxp.com/ |
| **Ingeniería Inversa y Análisis Estático** | Detect It Easy (DIE) | https://github.com/horsicq/Detect-It-Easy |
| | FLARE FLOSS | https://github.com/mandiant/flare-floss |
| | Scdbg | https://github.com/BestProjects/scdbg |
| **Inteligencia de Amenazas y Malware** | VirusTotal | https://www.virustotal.com/ |
| | Malpedia | https://malpedia.caad.fkie.fraunhofer.de/ |
| | Tria.ge | https://tria.ge/ |
| | Any.run | https://any.run/ |
| **Desofuscación y Procesamiento de Datos** | CyberChef | https://gchq.github.io/CyberChef/ |
| | QuickHash | https://www.quickhash-gui.org/ |
| | SpiderMonkey | https://spidermonkey.dev/ |
| **Inteligencia de Red y Geolocalización** | MaxMind Geo IP | https://www.maxmind.com/ |

---
*Este repositorio se actualiza continuamente con nuevos escenarios, reportes y análisis técnicos.*
