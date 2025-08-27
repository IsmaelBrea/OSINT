# Holehe: Guía completa

## ¿Qué es Holehe?

**Holehe** es una herramienta de línea de comandos que permite **verificar si un correo electrónico o nombre de usuario está registrado en múltiples servicios web** (como Gmail, Outlook, Instagram, Twitter, etc.).  
Se usa principalmente con fines de **seguridad informática y análisis OSINT (Open Source Intelligence)**, para comprobar la exposición de correos y usuarios en distintas plataformas.

> ⚠️ **Aviso legal:** Solo debes usar Holehe sobre cuentas propias o con permiso explícito. Usarlo sobre cuentas de terceros sin autorización puede ser ilegal.

---

## Funcionalidades principales

- Verificación de disponibilidad de **correos electrónicos**.
- Verificación de disponibilidad de **nombres de usuario**.
- Compatible con múltiples servicios web populares.
- Generación de **informes en consola**.

---

## Requisitos previos

Para usar Holehe necesitas:

- **Python 3.7 o superior**.
- Acceso a una terminal o consola (Linux, macOS, Windows con WSL o CMD/Powershell).
- **Git** si quieres clonar el repositorio oficial.

---

## Instalación

### Opción 1: Instalar con `pip` (recomendado)

```bash
pip install holehe

Esto instalará Holehe y todas las dependencias necesarias.

```

### Opción 2: Clonar el repositorio oficial
```bash
git clone https://github.com/megadose/holehe.git
cd holehe
pip install -r requirements.txt
```

## Uso básico
holehe <correo_o_usuario>


Opciones útiles

-h o --help: muestra ayuda con todas las opciones disponibles.

-t o --timeout <segundos>: define el tiempo máximo de espera por servicio.

--json: genera salida en formato JSON para análisis o scripts.

--no-colors: desactiva los colores en la salida (útil para redirección a archivos).



## Cómo interpretarlo

    Exists: la cuenta está registrada en ese servicio.

    Not Exists: la cuenta no está registrada en ese servicio.

    Unknown: no se pudo verificar, generalmente por problemas de red o cambios en la API del servicio.

## Consejos y buenas prácticas

No abuses del escaneo masivo de correos o usuarios, puede bloquear tu IP.

Actualiza Holehe regularmente, ya que los servicios web cambian sus métodos de verificación.

Usa un entorno virtual de Python (venv) para mantener el sistema limpio.


Combínalo con otras herramientas OSINT para análisis más completo.

