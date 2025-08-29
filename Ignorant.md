# 📱 Ignorant

**Ignorant** es una herramienta de línea de comandos que permite **verificar si un número de teléfono está asociado con cuentas en plataformas como Instagram, Snapchat o Amazon**.  
Se usa principalmente con fines de **seguridad informática y análisis OSINT (Open Source Intelligence)**, para comprobar la exposición de números de teléfono y obtener información pública vinculada a ellos. Con esta herramienta se pueden rastrear posibles cuentas asociadas a un número, identificar perfiles falsos o analizar riesgos de seguridad.

---

## Funcionalidades principales

- Verificación de **números de teléfono** en múltiples servicios web.  
- Obtención de información de cuentas asociadas al número.  
- Compatible con varios servicios populares.  
- Generación de **informes en consola** para análisis rápido.  

---

## Requisitos previos

Para usar Ignorant necesitas:

- **Python 3.7 o superior**.  
- Acceso a una terminal o consola (Linux, macOS, Windows con WSL o CMD/Powershell).  
- **Git** si quieres clonar el repositorio oficial.  

---

## Instalación en Linux / Kali Linux

### Opción 1: Instalar con `pip` desde GitHub (recomendado)

```bash
pip3 install --user git+https://github.com/megadose/ignorant.git
```

Asegurarse de que el PATH incluye la carpeta de binarios de usuario

```bash
export PATH=$PATH:~/.local/bin
```

### Opción 2: Clonar el repositorio actual

```bash
git clone https://github.com/megadose/ignorant.git
cd ignorant/
python3 setup.py install --user
export PATH=$PATH:~/.local/bin
```

## Uso básico
**-h o --help: muestra ayuda con todas las opciones disponibles**

ignorant prefijo numero

Ejemplo:
ignorant 34 646464646

## Cómo interpretarlo

    Exists: la cuenta está registrada en ese servicio.

    Not Exists: la cuenta no está registrada en ese servicio.

    Unknown: no se pudo verificar, generalmente por problemas de red o cambios en la API del servicio.

## Consejos y buenas prácticas

        No abuses del escaneo masivo de números, puede bloquear tu IP.

        Actualiza Ignorant regularmente, ya que los servicios web cambian sus métodos de verificación.

        Usa un entorno virtual de Python (venv) para mantener el sistema limpio.
        
        Combínalo con otras herramientas OSINT para un análisis más completo.


