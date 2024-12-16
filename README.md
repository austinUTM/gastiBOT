# gastiBOT

# Proyecto del Bot de Telegram

Este proyecto utiliza **Aiogram** para crear un bot de Telegram que gestiona las finanzas personales.

## Requisitos

- **Conda** (para gestionar el entorno y las dependencias).
- **Python 3.9** o superior (definido en el archivo `environment.yml`).

## Instalación

Sigue estos pasos para configurar el entorno de Conda y ejecutar el proyecto:

### 1. Clonar el repositorio

Primero, clona este repositorio a tu máquina local. Ejecuta el siguiente comando en tu terminal:

```bash
git clone https://github.com/austinUTM/gastiBOT.git

cd tu_repositorio
```

### 2. Crea el hambiente

```bash
conda env create -f environment.yml
```

### 3. Configura tu entorno de desarrollo

## NOTA:
Para crear o actualizar el archivo **environment.yml** ejecuta el siguiente comando:
```bash
conda env export --no-builds > environment.yml
```