# Lab01 - Configuración de Entorno y Estructura Base

## Descripción

Este laboratorio tiene como objetivo configurar un entorno de desarrollo en Python utilizando un entorno virtual, una estructura de proyecto clara y herramientas básicas de automatización. Forma parte del curso **Desarrollo de Software**.

## Objetivos

- Configurar un entorno virtual en Python.
- Estructurar correctamente un proyecto de laboratorio.
- Gestionar dependencias con ´requirements.txt´
- Automatizar la ejecución usando un ´Makefile´
- Versionar el proyecto con Git.

## Estructura del proyecto

lab01/
|-- README.md
|-- requirements.txt
|-- Makefile
|-- src/
| |-- main.py
|-- .venv/

## Requisitos

- Python 3.10+
- Git
- WSL (Ubuntu)
- Make

## Ejecución

1. Activar el entorno virtual:
```bash
source .venv/bin/activate
```

2. Ejecutar el laboratorio:
```bash
make run
```

## Conceptos aplicados

- Entornos virtuales en python
- Gestión de dependencias
- Automatización de tareas
- Buenas prácticas de estructura de proyectos.
