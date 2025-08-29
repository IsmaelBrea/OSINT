# Herramientas OSINT
OSINT (Open Source Intelligence) es la práctica de recopilar información pública y legalmente accesible de internet y otras fuentes abiertas para análisis, investigaciones o seguridad informática. Es legal porque no implica hackeo, todo proviene de sitios webs públicos, motores de búsqueda, archivos filtrados o expuestos o redes sociales abiertas entre otras cosas.

En este repositorio veremos una **colección de herramientas** (Linux y webs) para la recolección de inteligencia de código abierto (OSINT), enfocadas en obtener información pública de diversas fuentes en línea para investigaciones y análisis de seguridad. 

Para aprender a usar la mayoría de estas herramientas Linux, podemos utilizar el parámetro -h o --help con el comando correspondiente, lo que nos mostrará todos los parámetros disponibles y su descripción: 
**comando -h**


---


---

## Principales usos de OSINT

### 1. Correos electrónicos
- Comprobar en qué páginas está registrado un correo electrónico: **Holehe, Hunt, HudsonRock**  
- Saber qué datos están expuestos en Internet: **EmailChecker** ([emailchecker.enriqueite.com](https://emailchecker.enriqueite.com)), **Have I Been Pwned** ([haveibeenpwned.com](https://haveibeenpwned.com))  

### 2. Redes sociales
- Buscar en qué redes sociales se encuentra un nombre de usuario: **Sherlock, Maigret, Toutatis**  

### 3. Dominios y sitios web
- Recolección de información pública a partir de un dominio: **TheHarvester, Whois, DNSDumpster** ([dnsdumpster.com](https://dnsdumpster.com))  

### 4. Direcciones IP
- Obtener información específica de una IP: **GhostTrack, GeoRecon, ISMALICIOUS**  

### 5. Números de teléfono
- Obtener información a partir de números de teléfono: **Ignorant**, etc.  

### 6. Dispositivos y servicios expuestos
- Explorar dispositivos conectados a Internet y servicios expuestos: **Shodan.io**  

### 7. Imágenes y rostros
- Búsqueda y verificación de rostros en Internet: **PimEyes**  

---

## Herramientas OSINT

### A. Para correos electrónicos
1. **Holehe**: Script de línea de comandos que verifica si un correo o nombre de usuario está registrado en múltiples servicios web.  
2. **EmailChecker**: Web que muestra qué datos han sido expuestos en filtraciones de correo.  
3. **Have I Been Pwned**: Web que permite comprobar si una cuenta ha sido comprometida en brechas de seguridad conocidas.  

### B. Para redes sociales
4. **Sherlock**: Script que busca cuentas de usuario en varias redes sociales usando un nombre de usuario específico.  

### C. Para dominios y sitios web
5. **TheHarvester** (preinstalada en Kali Linux): herramienta que recolecta emails, subdominios y hosts de un dominio u organización usando fuentes OSINT.  
6. **DNSDumpster**: Web que muestra de forma clara los registros DNS de un dominio, incluyendo IPs, servidores de correo y subdominios.  

### D. Para IPs
7. **GhostTrack, GeoRecon, Who.is, ISMALICIOUS**: Herramientas para obtener información geográfica, de servicios y metadatos de direcciones IP.  

### E. Para números de teléfono
8. **Ignorant**:  Permite verificar si un número de teléfono está asociado con cuentas en distintas plataformas.

### F. Para dispositivos y servicios expuestos
9. **Shodan.io**: Motor de búsqueda de dispositivos conectados a Internet, mostrando IPs, puertos abiertos, servicios activos y metadatos.  

### G. Para imágenes y rostros
10. **PimEyes**: Web que permite buscar rostros en Internet mediante reconocimiento facial, mostrando dónde ha aparecido una persona en fotos públicas.  


