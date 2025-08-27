# 🕵️‍♂️ Sherlock:

**Sherlock** es una herramienta de código abierto escrita en Python que sirve para **buscar un nombre de usuario en cientos de redes sociales** y plataformas públicas, facilitando tareas de **OSINT (Open Source Intelligence)**.  
Sirve básicamente para saber dónde está registrado tu nombre de usuario.

---

## Funcionalidades principales

- Identificar si un nombre de usuario está registrado en diferentes redes sociales.
- Recolectar información pública de perfiles en línea.
- Ayuda en auditorías de seguridad, investigaciones OSINT o vigilancia digital.

---

##  Instalación en Linux / Kali Linux (método recomendado)

1. **Actualizar el sistema** (opcional):
```bash
sudo apt update && sudo apt upgrade -y

    Verificar Python 3 y pip (Kali ya lo incluye):

python3 --version
pip3 --version

    Clonar el repositorio de Sherlock:

git clone https://github.com/sherlock-project/sherlock.git
cd sherlock

    Instalar Sherlock y dependencias usando pip:

python3 -m pip install --user .

    Agregar scripts de usuario al PATH (si no se reconoce el comando sherlock):

export PATH=$HOME/.local/bin:$PATH

    Para hacerlo permanente:

echo 'export PATH=$HOME/.local/bin:$PATH' >> ~/.bashrc
source ~/.bashrc
```
    ✅ No usar sudo apt install sherlock, ya que en Kali rolling falla por dependencias rotas (python3-stem).

▶️ Uso Básico

Buscar un usuario:
    sherlock usuario123

Guardar resultados en CSV:
    sherlock usuario123 --csv

Usar Tor para anonimato:
        sherlock usuario123 --tor

 Buscar múltiples usuarios a la vez:
    sherlock usuario123 usuario456

Buscar desde un archivo de usuarios:   
    sherlock -l lista_usuarios.txt    

✅ Resumen

    Función principal: Localizar perfiles públicos de un usuario en redes sociales.

    Instalación segura en Kali: Clonar el repositorio y usar pip install --user ..

    Uso: Ejecutar el comando sherlock con el nombre de usuario, con opciones para exportar o usar Tor.


Sherlock es muy útil para investigadores, analistas de seguridad y profesionales de OSINT que necesiten mapear la presencia digital de personas o marcas.



