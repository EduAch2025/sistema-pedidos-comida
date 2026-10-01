# Sistema de pedidos de comida local

## Descripción

Proyecto inicial de Ingeniería de Software orientado al desarrollo de un sistema web para gestionar pedidos de comida local.

## Caso práctico

Una startup de Cusco desea desarrollar un sistema web para gestionar pedidos de comida local. El equipo necesita organizar el código fuente desde el inicio mediante un sistema de control de versiones.

## Objetivo inicial

Preparar el entorno de trabajo y crear la base del repositorio para que el proyecto pueda desarrollarse de manera organizada, manteniendo un historial de sus cambios.

## Alcance actual

En esta primera etapa se realizaron las siguientes actividades:

- Instalación y verificación de Git.
- Configuración del usuario de Git.
- Creación de la carpeta del proyecto.
- Inicialización del repositorio local.
- Creación del archivo `README.md`.
- Creación del primer commit.
- Conexión del repositorio local con GitHub.
- Publicación de la rama principal en el repositorio remoto.

## Configuración inicial

### Verificación de Git

```bash
git --version
```

Versión utilizada durante la configuración:

```text
git version 2.54.0.windows.1
```

### Configuración del usuario

```bash
git config --global user.name "EduAch2025"
git config --global user.email "231862@unsaac.edu.pe"
```

### Creación e inicialización del proyecto

```bash
mkdir sistema-pedidos-comida
cd sistema-pedidos-comida
git init
```

### Primer versionamiento

```bash
git add .
git commit -m "Primer commit"
git branch -M main
```

### Conexión con GitHub

```bash
git remote add origin https://github.com/EduAch2025/sistema-pedidos-comida.git
git push -u origin main
```

## Tecnologías y herramientas

- Git 2.54.0 para el control de versiones.
- GitHub para alojar el repositorio remoto.
- PowerShell como terminal de trabajo en Windows.

## Repositorio

[Repositorio en GitHub](https://github.com/EduAch2025/sistema-pedidos-comida)

## Estado del proyecto

Configuración inicial completada. El desarrollo funcional del sistema se realizará en las siguientes etapas del laboratorio.
