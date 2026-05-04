# 🚀 Laboratorio 03 - Configuración de Repositorio con Git (Trabajo Colaborativo)

![curso](https://img.shields.io/badge/curso-Pruebas_y_Aseguramiento-blue?style=for-the-badge) ![estado](https://img.shields.io/badge/estado-Completado_y_Entregado-brightgreen?style=for-the-badge)

## 👨‍💻 Datos del Estudiante

* **Nombre:** Yordi Ajeo Atao Huaman
* **Curso:** Pruebas y Aseguramiento de Calidad
* **Código:** 27222121

## 🎯 Objetivo del Laboratorio

Dominar el flujo de trabajo en equipo utilizando un repositorio remoto compartido. Esto implica aplicar las mejores prácticas de control de versiones, resolución de conflictos y colaboración descentralizada a través de Git y GitHub.

## 🛠️ Stack de Herramientas

* **Control de Versiones:** Git
* **Plataforma:** GitHub
* **Editor de Código:** Visual Studio Code
* **Terminal:** Windows Terminal / Git Bash

---

## ⚙️ Flujo de Trabajo Realizado

1. **Verificación del entorno:** Se comprobó la correcta instalación de Git en el sistema local.
2. **Configuración de credenciales:** Se establecieron el nombre de usuario y correo electrónico a nivel global para firmar los commits.
3. **Acceso al repositorio:** Se obtuvo la URL del repositorio remoto administrado por el equipo.
4. **Clonación:** Se descargó el proyecto a la máquina local utilizando el comando `git clone`.
5. **Navegación:** Se ingresó al directorio raíz del proyecto desde la terminal.
6. **Monitoreo:** Se verificó el estado actual de la rama y los archivos con `git status`.
7. **Modificación:** Se crearon y editaron los archivos correspondientes a la asignación.
8. **Staging:** Se prepararon los cambios para ser guardados utilizando `git add`.
9. **Commit:** Se encapsularon los cambios locales con un mensaje claro y descriptivo.
10. **Push:** Se sincronizó el trabajo enviándolo al repositorio remoto para ponerlo a disposición del equipo.

---

## 💻 Comandos Clave Utilizados

A continuación, el registro de los comandos ejecutados en la terminal para completar la integración:
```bash
# 1. Comprobar la versión instalada
git --version

# 2. Configurar la identidad del desarrollador
git config --global user.name "Yordi Ajeo Atao Huaman"
git config --global user.email "yordi.atao.27@unsch.edu.pe"

# 3. Traer el repositorio del compañero a local
git clone [https://github.com/Zeth-21/PROYECTO_01.git](https://github.com/Zeth-21/PROYECTO_01.git)

# 4. Acceder a la carpeta del proyecto
cd PROYECTO_01

# 5. Revisar si hay archivos modificados o sin seguimiento
git status

# 6. Añadir todos los cambios al área de preparación (staging)
git add .

# 7. Crear el commit con un mensaje descriptivo
git commit -m "docs: agrega archivo markdown con mis datos de estudiante"

# 8. Subir los cambios al repositorio remoto (rama principal)
git push origin main