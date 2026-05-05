# Defensive Security & DFIR Portfolio

![Status](https://img.shields.io/badge/Status-Active_Project-success)
![Focus](https://img.shields.io/badge/Focus-Blue_Team_%7C_DFIR_%7C_Threat_Intel-blue)
![Goal](https://img.shields.io/badge/Goal-30+_Labs-orange)

Bienvenido a mi repositorio técnico de investigaciones forenses y respuesta a incidentes. 

Este repositorio funciona como un **laboratorio vivo y en constante evolución**. Aquí documento mis prácticas, resoluciones y metodologías aplicadas a escenarios de ciberataques realistas, con el objetivo de desarrollar una sólida memoria muscular en operaciones de Blue Team.

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
| **PacketMaze** | [PDF](https://github.com/dav-sec/Defensive-Security-Portfolio/blob/main/Writeups/CyberDefenders/Medium/PacketMaze/PacketMaze_CyberDefenders.pdf) | [CyberDefenders](https://cyberdefenders.org/blueteam-ctf-challenges/packetmaze/) | 🟡 Medium | `Wireshark` |
| **Tomcat Takeover** | [PDF](https://github.com/dav-sec/Defensive-Security-Portfolio/blob/main/Writeups/CyberDefenders/Easy/Tomcat%20Takeover/Tomcat%20Takeover_CyberDefenders.pdf) | [CyberDefenders](https://cyberdefenders.org/blueteam-ctf-challenges/tomcat-takeover/) | 🟢 Easy | `Wireshark` `NetworkMiner` |
| **Lockdown** | [PDF](https://github.com/dav-sec/Defensive-Security-Portfolio/blob/main/Writeups/CyberDefenders/Easy/Lockdown/Lockdown_CyberDefenders.pdf) | [CyberDefenders](https://cyberdefenders.org/blueteam-ctf-challenges/lockdown/) | 🟢 Easy | `Wireshark` `Volatility 3` `flare-floss` `Detect It Easy (DIE)` `VirusTotal` `Tria.ge` |
| **BlueSky Ransomware** | [PDF](https://github.com/dav-sec/Defensive-Security-Portfolio/blob/main/Writeups/CyberDefenders/Medium/BlueSky%20Ransomware/BlueSky%20Ransomware_CyberDefenders.pdf) | [CyberDefenders](https://cyberdefenders.org/blueteam-ctf-challenges/bluesky-ransomware/) | 🟡 Medium | `Wireshark` `NetworkMiner` `Event Log Explorer` `Any.run` `VirusTotal` |
| **OpenWire** | [PDF](https://github.com/dav-sec/Defensive-Security-Portfolio/blob/main/Writeups/CyberDefenders/Medium/OpenWire/OpenWire_CyberDefenders.pdf) | [CyberDefenders](https://cyberdefenders.org/blueteam-ctf-challenges/openwire/) | 🟡 Medium | `Wireshark` `NetworkMiner` |
| **HawkEye** | [PDF](https://github.com/dav-sec/Defensive-Security-Portfolio/blob/main/Writeups/CyberDefenders/Medium/HawkEye/HawkEye_CyberDefenders.pdf) | [CyberDefenders](https://cyberdefenders.org/blueteam-ctf-challenges/hawkeye/) | 🟡 Medium | `Wireshark` `NetworkMiner` `MaxMind Geo IP` `QuickHash` `CyberChef` |
| **NukeTheBrowser** | [PDF](https://github.com/dav-sec/Defensive-Security-Portfolio/blob/main/Writeups/CyberDefenders/Hard/NukeTheBrowser/NukeTheBrowser_CyberDefenders.pdf) | [CyberDefenders](https://cyberdefenders.org/blueteam-ctf-challenges/nukethebrowser/) | 🔴 Hard | `Wireshark` `NetworkMiner` `SpiderMonkey` `QuickHash` `CyberChef` `Scdbg` `Detect It Easy (DIE)` |
| **EscapeRoom** | [PDF](https://github.com/dav-sec/Defensive-Security-Portfolio/blob/main/Writeups/CyberDefenders/Medium/EscapeRoom/EscapeRoom_CyberDefenders.pdf) | [CyberDefenders](https://cyberdefenders.org/blueteam-ctf-challenges/escaperoom/) | 🟡 Medium | `Wireshark` `NetworkMiner` `Zui` `QuickHash` `CyberChef` `Hashcat` `VirusTotal` `IDA` `Radare2` |
| **XLMRat** | [PDF](https://github.com/dav-sec/Defensive-Security-Portfolio/blob/main/Writeups/CyberDefenders/Easy/XLMRat/XLMRat_CyberDefenders.pdf) | [CyberDefenders](https://cyberdefenders.org/blueteam-ctf-challenges/xlmrat/) | 🟢 Easy | `Wireshark` `Whois` `CyberChef` `VirusTotal` |
| **DanaBot** | [PDF](https://github.com/dav-sec/Defensive-Security-Portfolio/blob/main/Writeups/CyberDefenders/Easy/DanaBot/DanaBot_CyberDefenders.pdf) | [CyberDefenders](https://cyberdefenders.org/blueteam-ctf-challenges/danabot/) | 🟢 Easy | `Wireshark` `VirusTotal` `QuickHash` `Any.run` |
| **Web Investigation** | [PDF](https://github.com/dav-sec/Defensive-Security-Portfolio/blob/main/Writeups/CyberDefenders/Easy/Web%20Investigation/Web%20Investigation_CyberDefenders.pdf) | [CyberDefenders](https://cyberdefenders.org/blueteam-ctf-challenges/web-investigation/) | 🟢 Easy | `Wireshark` `Whois` `CyberChef` |
| **PsExec Hunt** | [PDF](https://github.com/dav-sec/Defensive-Security-Portfolio/blob/main/Writeups/CyberDefenders/Easy/PsExec%20Hunt/PsExec%20Hunt_CyberDefenders.pdf) | [CyberDefenders](https://cyberdefenders.org/blueteam-ctf-challenges/psexec-hunt/) | 🟢 Easy | `Wireshark` |
| **Acoustic** | [PDF](https://github.com/dav-sec/Defensive-Security-Portfolio/blob/main/Writeups/CyberDefenders/Medium/Acoustic/Acoustic_CyberDefenders.pdf) | [CyberDefenders](https://cyberdefenders.org/blueteam-ctf-challenges/acoustic/) | 🟡 Medium | `Wireshark` `NetworkMiner` |

### Threat Intelligence
Extracción de Indicadores de Compromiso (IoCs) y análisis de comportamiento de artefactos maliciosos.

| Escenario | Documento | Plataforma | Dificultad | Herramientas |
| :--- | :---: | :---: | :---: | :--- |
| **IcedID** | [PDF](https://github.com/dav-sec/Defensive-Security-Portfolio/blob/main/Writeups/CyberDefenders/Easy/IcedID/IcedID_CyberDefenders.pdf) | [CyberDefenders](https://cyberdefenders.org/blueteam-ctf-challenges/icedid/) | 🟢 Easy | `VirusTotal` `Malpedia` `Tria.ge` |
| **3CX Supply Chain** | [PDF](https://github.com/dav-sec/Defensive-Security-Portfolio/blob/main/Writeups/CyberDefenders/Easy/3CX%20Supply%20Chain/3CX%20Supply%20Chain_CyberDefenders.pdf) | [CyberDefenders](https://cyberdefenders.org/blueteam-ctf-challenges/3cx-supply-chain/) | 🟢 Easy | `VirusTotal` |
| **Intel101** | [PDF](https://github.com/dav-sec/Defensive-Security-Portfolio/blob/main/Writeups/CyberDefenders/Medium/Intel101/Intel101_CyberDefenders.pdf) | [CyberDefenders](https://cyberdefenders.org/blueteam-ctf-challenges/intel101/) | 🟡 Medium | `Whois` `Wayback Machine` `QuickHash` `Google Lens` |
| **Oski** | [PDF](https://github.com/dav-sec/Defensive-Security-Portfolio/blob/main/Writeups/CyberDefenders/Easy/Oski/Oski_CyberDefenders.pdf) | [CyberDefenders](https://cyberdefenders.org/blueteam-ctf-challenges/oski/) | 🟢 Easy | `VirusTotal` `Any.run` |
| **BRabbit** | [PDF](https://github.com/dav-sec/Defensive-Security-Portfolio/blob/main/Writeups/CyberDefenders/Medium/BRabbit/BRabbit_CyberDefenders.pdf) | [CyberDefenders](https://cyberdefenders.org/blueteam-ctf-challenges/brabbit/) | 🟡 Medium | `VirusTotal` `Any.run` `Email Header Analyzer` `Tria.ge` `IDA` `Malpedia` |
| **PhishStrike** | [PDF](https://github.com/dav-sec/Defensive-Security-Portfolio/blob/main/Writeups/CyberDefenders/Medium/PhishStrike/PhishStrike_CyberDefenders.pdf) | [CyberDefenders](https://cyberdefenders.org/blueteam-ctf-challenges/phishstrike/) | 🟡 Medium | `VirusTotal` `Any.run` `Email Header Analyzer` `Tria.ge` `URLHaus` `MalwareBazaar` `CyberChef` `VMRay` |

### Endpoint Forensics
Análisis de imágenes de disco, revisión de registros del sistema (logs) y reconstrucción de la actividad del usuario.

| Escenario | Documento | Plataforma | Dificultad | Herramientas |
| :--- | :---: | :---: | :---: | :--- |
| **Insider** | [PDF](https://github.com/dav-sec/Defensive-Security-Portfolio/blob/main/Writeups/CyberDefenders/Easy/Insider/Insider_CyberDefenders.pdf) | [CyberDefenders](https://cyberdefenders.org/blueteam-ctf-challenges/insider/) | 🟢 Easy | `FTK Imager` |
| **The Crime** | [PDF](https://github.com/dav-sec/Defensive-Security-Portfolio/blob/main/Writeups/CyberDefenders/Easy/The%20Crime/The%20Crime_CyberDefenders.pdf) | [CyberDefenders](https://cyberdefenders.org/blueteam-ctf-challenges/the-crime/) | 🟢 Easy | `ALEAPP` `DB Browser for SQLite` |
| **Silent Breach** | [PDF](https://github.com/dav-sec/Defensive-Security-Portfolio/blob/main/Writeups/CyberDefenders/Medium/Silent%20Breach/Silent%20Breach_CyberDefenders.pdf) | [CyberDefenders](https://cyberdefenders.org/blueteam-ctf-challenges/silent-breach/) | 🟡 Medium | `FTK Imager` `DB Browser for SQLite` `VirusTotal` `CyberChef` `Strings` |
| **LGDroid** | [PDF](https://github.com/dav-sec/Defensive-Security-Portfolio/blob/main/Writeups/CyberDefenders/Medium/LGDroid/LGDroid_CyberDefenders.pdf) | [CyberDefenders](https://cyberdefenders.org/blueteam-ctf-challenges/lgdroid/) | 🟡 Medium | `DB Browser for SQLite` `ssim-calculator` `Epoch Converter` `Strings` |
| **BlackEnergy** | [PDF](https://github.com/dav-sec/Defensive-Security-Portfolio/blob/main/Writeups/CyberDefenders/Medium/BlackEnergy/BlackEnergy_CyberDefenders.pdf) | [CyberDefenders](https://cyberdefenders.org/blueteam-ctf-challenges/blackenergy/) | 🟡 Medium | `Volatility 2` |

### Malware Analysis
Análisis de software malicioso para identificar su funcionamiento, comportamiento y propósito, incluyendo técnicas de evasión, persistencia y posibles impactos en el sistema.

| Escenario | Documento | Plataforma | Dificultad | Herramientas |
| :--- | :---: | :---: | :---: | :--- |
| **FakeGPT** | [PDF](https://github.com/dav-sec/Defensive-Security-Portfolio/blob/main/Writeups/CyberDefenders/Easy/FakeGPT/FakeGPT_CyberDefenders.pdf) | [CyberDefenders](https://cyberdefenders.org/blueteam-ctf-challenges/fakegpt/) | 🟢 Easy | `CRX Viewer` `CyberChef` |
| **GetPDF** | [PDF](https://github.com/dav-sec/Defensive-Security-Portfolio/blob/main/Writeups/CyberDefenders/Medium/GetPDF/GetPDF_CyberDefenders.pdf) | [CyberDefenders](https://cyberdefenders.org/blueteam-ctf-challenges/getpdf/) | 🟡 Medium | `Wireshark` `de4js` `QuickHash` `peepdf` `CyberChef` `scdbg` `VirusTotal` |
| **Obfuscated** | [PDF](https://github.com/dav-sec/Defensive-Security-Portfolio/blob/main/Writeups/CyberDefenders/Medium/Obfuscated/Obfuscated_CyberDefenders.pdf) | [CyberDefenders](https://cyberdefenders.org/blueteam-ctf-challenges/obfuscated/) | 🟡 Medium | `QuickHash` `Oledump` `Olevba` `Any.run` `de4js` `CyberChef` |
| **Emprisa Maldoc** | [PDF](https://github.com/dav-sec/Defensive-Security-Portfolio/blob/main/Writeups/CyberDefenders/Medium/Emprisa%20Maldoc/Emprisa%20Maldoc_CyberDefenders.pdf) | [CyberDefenders](https://cyberdefenders.org/blueteam-ctf-challenges/emprisa-maldoc/) | 🟡 Medium | `VirusTotal` `rtfdump` `Any.run` `CyberChef` `scdbg` |
| **RotaJakiro** | [PDF](https://github.com/dav-sec/Defensive-Security-Portfolio/blob/main/Writeups/CyberDefenders/Hard/RotaJakiro/RotaJakiro_CyberDefenders.pdf) | [CyberDefenders](https://cyberdefenders.org/blueteam-ctf-challenges/rotajakiro/) | 🔴 Hard | `QuickHash` `readelf` `Ghidra` `strace` `Wireshark` |
| **RE101** | [PDF](https://github.com/dav-sec/Defensive-Security-Portfolio/blob/main/Writeups/CyberDefenders/Medium/RE101/RE101_CyberDefenders.pdf) | [CyberDefenders](https://cyberdefenders.org/blueteam-ctf-challenges/re101/) | 🟡 Medium | `IDA` `CyberChef` `zipdetails` `strings` `Hexed.it` |

*(Categorías en construcción próximamente...)*


## Herramientas Utilizadas

Algunas de las herramientas utilizadas en estas resoluciones incluyen:

| Categoría | Nombre de la Herramienta | Enlace |
| :--- | :--- | :--- |
| **Análisis de Tráfico de Red** | Wireshark | https://www.wireshark.org/ |
| | NetworkMiner | https://www.netresec.com/?page=NetworkMiner |
| | Zui | https://zui.brimdata.io/ |
| **Forense Digital y Análisis de Artefactos** | Volatility 3 | https://github.com/volatilityfoundation/volatility3 |
| | Volatility 2 | https://github.com/volatilityfoundation/volatility.git |
| | Event Log Explorer | https://eventlogxp.com/ |
| | FTK Imager | https://accessdata.com/product-download/ftk-imager-version-4-5 |
| | ALEAPP | https://github.com/abrignoni/ALEAPP |
| | DB Browser for SQLite | https://sqlitebrowser.org/ |
| | zipdetails | https://github.com/pmqs/zipdetails |
| **Ingeniería Inversa y Análisis de Malware** | Detect It Easy (DIE) | https://github.com/horsicq/Detect-It-Easy |
| | FLARE FLOSS | https://github.com/mandiant/flare-floss |
| | Scdbg | https://github.com/BestProjects/scdbg |
| | IDA | https://hex-rays.com/ida-free/ |
| | Radare2 | https://github.com/radareorg/radare2 |
| | Ghidra | https://ghidra-sre.org/ |
| | readelf | https://man7.org/linux/man-pages/man1/readelf.1.html |
| | strace | https://strace.io/ |
| | SpiderMonkey | https://spidermonkey.dev/ |
| | Strings | https://learn.microsoft.com/en-us/sysinternals/downloads/strings |
| | CRX Viewer | https://robwu.nl/crxviewer/ |
| | de4js | https://thanhle.io.vn/de4js/ |
| | peepdf | https://github.com/jesparza/peepdf |
| | oledump | https://github.com/DidierStevens/DidierStevensSuite/blob/master/oledump.py |
| | olevba | https://github.com/decalage2/oletools/wiki/olevba |
| | rtfdump | https://github.com/DidierStevens/DidierStevensSuite/blob/master/rtfdump.py |
| | Hexed.it | https://hexed.it/ |
| **Procesamiento y Análisis de Datos** | CyberChef | https://gchq.github.io/CyberChef/ |
| | QuickHash | https://www.quickhash-gui.org/ |
| | Hashcat | https://hashcat.net/hashcat/ |
| | Epoch Converter | https://www.epochconverter.com/ |
| **Análisis Multimedia y Evidencia Visual** | SSIM Calculator | https://github.com/asanka-code/ssim-calculator.git |
| **Inteligencia de Amenazas (Threat Intelligence / OSINT)** | VirusTotal | https://www.virustotal.com/ |
| | Malpedia | https://malpedia.caad.fkie.fraunhofer.de/ |
| | Tria.ge | https://tria.ge/ |
| | Any.run | https://any.run/ |
| | VMRay | https://www.vmray.com/ |
| | URLhaus | https://urlhaus.abuse.ch/ |
| | MalwareBazaar | https://bazaar.abuse.ch/ |
| | MaxMind Geo IP | https://www.maxmind.com/ |
| | Wayback Machine | https://archive.org/web/ |
| | Google Lens | https://lens.google/ |
| | Whois | https://lookup.icann.org/es/lookup |
| | Email Header Analyzer | https://mxtoolbox.com/EmailHeaders.aspx |

---
*Este repositorio se actualiza continuamente con nuevos escenarios, reportes y análisis técnicos.*
