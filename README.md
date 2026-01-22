# Reconocimiento de Placas Vehiculares mediante Procesamiento Digital de Imágenes

## Descripción
Este proyecto implementa un sistema básico de reconocimiento de placas vehiculares utilizando Python y la biblioteca OpenCV.  
El desarrollo se basa exclusivamente en técnicas clásicas de procesamiento digital de imágenes y visión por computadora, sin el uso de algoritmos de inteligencia artificial ni aprendizaje automático.

El sistema permite detectar la placa vehicular y realizar el reconocimiento de sus caracteres mediante métodos tradicionales de segmentación y análisis de imágenes.

---

## Contexto Académico
Este proyecto fue desarrollado como parte de la asignatura **Procesamiento Digital de Señales**, correspondiente al **cuarto ciclo** de la carrera de **Ingeniería en Telecomunicaciones**.

El objetivo académico del proyecto es aplicar los conceptos teóricos del procesamiento digital de señales e imágenes en un problema práctico de visión por computadora.

---

## Objetivo
Desarrollar un sistema básico de detección de placas vehiculares y reconocimiento de sus caracteres mediante técnicas tradicionales de procesamiento de imágenes, con fines académicos y formativos.

---

## Alcance del Proyecto
- Procesamiento de imágenes vehiculares.
- Detección y segmentación de placas.
- Segmentación de caracteres presentes en la placa.
- Reconocimiento básico de caracteres mediante técnicas clásicas.
- Uso exclusivo de métodos determinísticos de procesamiento digital de imágenes.

Este proyecto **no emplea** modelos de inteligencia artificial ni aprendizaje automático.

---

## Metodología / Funcionamiento
El sistema sigue las siguientes etapas:

1. Carga de la imagen de entrada.
2. Conversión de la imagen a escala de grises.
3. Aplicación de filtros para reducción de ruido.
4. Detección de bordes.
5. Operaciones morfológicas para resaltar la región de la placa.
6. Detección y selección de contornos candidatos a placa.
7. Segmentación de los caracteres de la placa.
8. Reconocimiento básico de caracteres mediante análisis de forma y tamaño.

---

## Implementación
La implementación del sistema se encuentra desarrollada en el siguiente notebook, donde se documenta paso a paso el proceso completo de detección y reconocimiento de placas vehiculares:

[02_DetectorPlacasCar.ipynb](02_DetectorPlacasCar.ipynb)

---

## Tecnologías Utilizadas
- Python  
- OpenCV  
- NumPy  
- Procesamiento Digital de Imágenes  
- Visión por Computadora Clásica  

---

## Requisitos del Sistema
- Python 3.8 o superior
- OpenCV
- NumPy
- Jupyter Notebook
- Sistema operativo Windows, Linux o macOS

---

## Instalación
Clonar el repositorio:

```bash
git clone https://github.com/jcurimilma/Procesamiento-de-imagenes-Reconocimiento-de-placas-vehiculares-.git

