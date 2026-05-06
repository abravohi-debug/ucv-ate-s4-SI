# Lab 4 - API de Procesamiento de Imágenes con FastAPI y OpenCV

## Descripción

Este proyecto desarrolla una API para el procesamiento de imágenes utilizando **FastAPI**, **OpenCV** y **Programación Orientada a Objetos (POO)**.

La API permite recibir imágenes, aplicar detección de bordes mediante el algoritmo **Canny** y devolver resultados estructurados en formato JSON.

## Objetivo

Construir una API que procese imágenes aplicando detección de bordes y devuelva resultados estructurados.

##  Tecnologías utilizadas
- Python 3.10
- FastAPI
- Uvicorn
- OpenCV
- NumPy
- Poetry
- Pytest

## Estructura del proyecto

UCV-ATE-S4-SI/
│
├── .vscode/
│   └── settings.json
│
├── lab4_api_cv/
│   │
│   ├── .pytest_cache/
│   ├── .venv/
│   │
│   ├── data/
│   │   ├── imagen_prueba.jpg
│   │   └── WhatsApp Image ....
│   │
│   ├── src/
│   │   └── lab4_api_cv/
│   │       │
│   │       ├── api/
│   │       │   ├── __init__.py
│   │       │   └── main.py
│   │       │
│   │       ├── services/
│   │       │   ├── __init__.py
│   │       │   └── image_service.py
│   │       │
│   │       └── __init__.py
│   │
│   ├── py/
│   │
│   ├── tests/
│   │   └── test_api.py
│   │
│   ├── poetry.lock
│   ├── pyproject.toml
│   └── pyproject.toml
│
├── .gitignore
├── LICENSE
└── README.md
