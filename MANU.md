# 📘 Laboratorio 03 - Configuración de Repositorio con Git (Repositorio Compartido)

![Curso](https://img.shields.io/badge/curso-Pruebas%20y%20Aseguramiento-blue)
![Estado](https://img.shields.io/badge/estado-Entregado-green)

---

## 👥 Datos del Estudiante

- **Nombre:** Manuel Elias Yahve Ore Huasaja  
- **Curso:** Pruebas y Aseguramiento de Calidad  
- **Código:** 27220506  

---

## 📄 Descripción del Estudiante

### 🎯 Objetivo del laboratorio
Trabajar con un repositorio remoto compartido utilizando Git, aplicando control de versiones y colaboración en equipo mediante GitHub.

### 🛠 Herramientas utilizadas
- Git  
- GitHub  
- Terminal (Linux / Git Bash)  

---

## ⚙️ Pasos realizados

1. Se verificó la instalación de Git en el sistema.
2. Se configuró la identidad del usuario (nombre y correo).
3. Se accedió a un repositorio remoto compartido (propiedad de otro usuario).
4. Se clonó el repositorio utilizando `git clone`.
5. Se ingresó a la carpeta del proyecto.
6. Se verificó el estado del repositorio con `git status`.
7. Se realizaron cambios en los archivos del proyecto (por ejemplo: README).
8. Se agregaron los cambios con `git add`.
9. Se realizó un commit con un mensaje descriptivo.
10. Se enviaron los cambios al repositorio remoto con `git push`.

---

## 💻 Comandos utilizados en Git (OBLIGATORIO)

```bash
# Verificar instalación de Git
git --version

# Configurar usuario
git config --global user.name "Manuel Elias Yahve Ore Huasaja"
git config --global user.email "manuel.ore.27@unsch.edu.pe"

# Clonar repositorio de otro usuario (repositorio compartido)
git clone https://github.com/Zeth-21/Proyecto_01.git

# Entrar al proyecto
cd mi-primer-proyecto

# Ver estado del repositorio
git status

# Agregar cambios realizados
git add .

# Crear commit
git commit -m "mensaje"

#como estoy trabajadno en mi rama "feature/nombre-funcion", mando para que se junte con el main

# Subir cambios al repositorio del usuario principal
git push origin feature/nombre-funcion