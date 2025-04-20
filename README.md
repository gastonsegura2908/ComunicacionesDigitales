# Comunicación LoRa en Python – Análisis y Visualización de Datos

Este repositorio contiene un cuaderno Jupyter orientado al procesamiento, análisis y visualización de datos provenientes de una comunicación inalámbrica basada en tecnología **LoRa (Long Range Radio)**. El objetivo es interpretar y representar datos recibidos desde un nodo LoRa conectado a un microcontrolador o dispositivo embebido, permitiendo su posterior análisis.

## 📚 Contenido del repositorio

- `LoRa.ipynb`: cuaderno Jupyter que procesa los datos recibidos por puerto serie, interpreta tramas, extrae información de sensores y genera gráficos en tiempo real o sobre registros guardados.

## 🚀 Funcionalidades principales

- Lectura de datos vía **puerto serie** utilizando `pyserial`.
- Decodificación de tramas estructuradas provenientes de un nodo LoRa.
- Almacenamiento de datos recibidos en formato `.csv`.
- Visualización gráfica de:
  - Humedad y temperatura ambiente.
  - Humedad de suelo.
  - Estados del sistema (modo de operación, actividad de sensores, etc.).
- Control de errores en la recepción de datos (manejo de excepciones).
- Registro de tiempo de recepción.

## 📦 Requisitos

El cuaderno fue desarrollado en **Python 3** y requiere las siguientes bibliotecas:

```bash
pip install pyserial pandas matplotlib
