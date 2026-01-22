# Reconocimiento de Placas Vehiculares con OpenCV

## Descripción
Este proyecto implementa un sistema básico de reconocimiento de placas vehiculares desarrollado en Python utilizando la biblioteca OpenCV.  
El sistema se basa exclusivamente en técnicas clásicas de procesamiento digital de imágenes y visión por computadora, sin emplear algoritmos de inteligencia artificial ni aprendizaje automático.

El objetivo principal es detectar y segmentar la región de la placa vehicular a partir de imágenes, con fines académicos y de aprendizaje.

---

## Objetivo
Desarrollar un sistema básico de detección de placas vehiculares mediante técnicas tradicionales de procesamiento de imágenes, permitiendo comprender el funcionamiento y las limitaciones de los métodos clásicos de visión por computadora.

---

## Alcance del Proyecto
- Procesamiento de imágenes vehiculares.
- Detección y segmentación de placas.
- Aplicación de técnicas determinísticas de visión por computadora.
- Uso con imágenes estáticas para fines académicos.

Este proyecto **no incluye** reconocimiento de caracteres (OCR) ni modelos basados en inteligencia artificial.

---

## Metodología / Funcionamiento
El sistema sigue las siguientes etapas:

1. Carga de la imagen de entrada.
2. Conversión de la imagen a escala de grises.
3. Aplicación de filtros para reducción de ruido.
4. Detección de bordes.
5. Aplicación de operaciones morfológicas.
6. Detección de contornos.
7. Selección de regiones candidatas a placas según criterios geométricos.

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
- Sistema operativo Windows, Linux o macOS

---
