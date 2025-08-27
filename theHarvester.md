# 🌐 theHarvester

**theHarvester** es una herramienta de código abierto incluida en Kali Linux que sirve para **recolectar información pública (OSINT) sobre correos electrónicos, subdominios, hosts y direcciones IP** de un dominio específico, utilizando motores de búsqueda, redes sociales y otras fuentes abiertas.  

---

## Funcionalidades principales

- Descubrir **dominios, subdominios y servidores** de una organización.  
- Obtener **correos electrónicos públicos** asociados a un dominio.  
- Recolectar **puertos abiertos, tIPs y hostnames** para auditorías de seguridad.  
- Realizar pruebas de **footprinting y reconocimiento** en el marco de un pentest.  

---

## 💻 Instalación en Linux / Kali Linux

En Kali Linux viene **preinstalado**, pero si necesitas instalarlo manualmente:  

```bash
sudo apt update && sudo apt install theharvester -y

Verificar instalación:

theHarvester -h

▶️ Uso Básico

    Buscar correos y subdominios en un dominio con Google:

theHarvester -d microsoft.com -b google -l 200

    Usar todas las fuentes disponibles y guardar en HTML:

theHarvester -d tesla.com -b all -l 500 -f tesla_report.html

    Brute force de subdominios con diccionario:

theHarvester -d openai.com -b bing -c

⚙️ Parámetros Principales
Para saber todos los posibles parámetros de theHarvester hay que usar:
theHarvester -h

Parámetro	Descripción
-d <dominio>	Dominio objetivo (ej: tesla.com)
-b <fuente>	Fuente de datos (google, bing, yahoo, linkedin, crtsh, all)
-l <número>	Límite de resultados (ej: -l 300)
-s <número>	Offset o inicio de resultados (paginación)
-f <archivo>	Exporta resultados a HTML/XML (ej: -f reporte.html)
-v	Modo verbose (más información en consola)
-c	DNS bruteforce con diccionario de subdominios
-n	No resuelve hostnames a IP
-t	Expansión TLD (prueba .net, .org, .es, etc.)
-e <dns>	Define servidores DNS específicos


✅ Resumen

    Función principal: Recolectar información OSINT de un dominio (emails, subdominios, hosts, IPs).

    Instalación: En Kali ya viene incluido; si no, instalar con apt install.

    Uso: Ejecutar theHarvester con el dominio y fuente de datos.

    Utilidad: Muy valioso en pentesting, auditorías de seguridad y reconocimiento previo a ataques.


theHarvester es una herramienta clave en la fase de recolección de información de un pentester o investigador OSINT.

