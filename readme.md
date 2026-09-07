# Hito Evaluativo - Gestión de Estacionamientos Particulares

Aplicación web interactiva desarrollada con **Streamlit** para el análisis y gestión de estacionamientos particulares.

---

## 📋 Requisitos del Sistema

- **Python:** `3.14.2` (o superior)
- **Gestor de paquetes:** `pip`

---

## 🚀 Instalación y Configuración

1. **Activar el entorno virtual (opcional pero recomendado):**
   ```bash
   # En Linux / macOS:
   source .venv/bin/activate

   # En Windows:
   .venv\Scripts\activate
   ```

2. **Instalar dependencias:**
   ```bash
   pip install -r requierments.txt
   ```
   *(o `pip install streamlit`)*

---

## ▶️ Ejecución de la Aplicación

Para iniciar el servidor de Streamlit y visualizar la aplicación en el navegador, ejecuta:

```bash
streamlit run main.py
```

O utilizando el módulo de Python:

```bash
python -m streamlit run main.py
```

> **Nota:** En GitHub Codespaces, al ejecutar el comando anterior se abrirá automáticamente una notificación para ver la aplicación en el puerto `8501`.

---

## 📁 Estructura del Proyecto

- `main.py`: Archivo principal y punto de entrada de la aplicación Streamlit.
- `Data/`: Carpeta que contiene los conjuntos de datos (`dataset_estacionamientos.csv`, `dataset_estacionamientos.xlsx`).
- `requierments.txt`: Lista de librerías y dependencias necesarias.
