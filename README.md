# 🏋️‍♀️ FitLife Fideliza - MVP Frontend & Backend

Este repositorio contiene la arquitectura completa de la aplicación de escritorio para la gestión de lealtad en centros fitness, desarrollada para la Clase 11: Interfaces Gráficas, Eventos y Excepciones.

## 🏗️ Arquitectura del Proyecto
La aplicación implementa una estructura modular que separa la lógica visual de la gestión de datos:

* **Frontend/ (`app_fidelizacion.py`):** GUI construida con `Tkinter`. Utiliza `Pillow` para el procesamiento de identidad visual y un sistema de validación de entradas con `messagebox`.
* **Backend/ (`mercadeo.py` & `database.py`):** Capa lógica que automatiza el cálculo de bonos según la categoría del cliente (Bronce, Plata, Oro) y gestiona la persistencia de datos.
* **Base de Datos (`fitlife_fidelizacion.db`):** Motor `SQLite` para el almacenamiento de transacciones y beneficios.
* **Orquestador (`main.py`):** Punto de entrada que inicializa la base de datos y lanza la interfaz gráfica.

## 👥 Integrantes del Grupo
* **Maria Juliana** (Líder de Proyecto)
* **Mariana Carmona**

## 🚀 Instalación y Uso
1. Instalar dependencias necesarias: `pip install Pillow`.
2. Ejecutar la aplicación desde la raíz: `python main.py`.

---
*Proyecto académico para el Tercer Corte - Universidad de La Sabana (2026).*
