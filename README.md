<div align="center">

<img src="logo/Logo-AveScan.jpeg" alt="AveScan" width="180">

# 🐦 AveScan

### Identificación automática de aves del departamento del Tolima mediante aprendizaje profundo

**Material complementario del proyecto de investigación**

Modelos de aprendizaje profundo · Experimentación · Evaluación · Explicabilidad

</div>

---

## 📌 Sobre el proyecto

**AveScan** es una aplicación móvil desarrollada para apoyar la identificación automática de especies de aves del departamento del Tolima mediante técnicas de **aprendizaje profundo y visión por computador**.

El proyecto integra un modelo basado en la arquitectura **MobileViT**, entrenado y evaluado para la clasificación de **545 especies de aves**, y posteriormente preparado para su utilización en dispositivos móviles mediante formatos compatibles con TensorFlow Lite.

Este repositorio contiene el material técnico y experimental asociado al desarrollo del componente de aprendizaje profundo del proyecto.

---

## 🎯 Objetivo

Desarrollar una aplicación móvil capaz de realizar la identificación automática de especies de aves mediante aprendizaje profundo, contribuyendo al reconocimiento y consulta de la biodiversidad presente en el departamento del Tolima.

---

## 🧠 Modelo final

El modelo seleccionado para el proyecto corresponde a **MobileViT**, una arquitectura orientada a dispositivos con recursos limitados que combina características de redes convolucionales con mecanismos basados en Transformers.

### Características principales

| Característica | Información |
|---|---|
| 🧠 Arquitectura | MobileViT |
| 🐦 Número de clases | 545 especies |
| 📱 Orientación | Despliegue móvil |
| 🔄 Evaluación | Fase 3 + TTA |
| 🔥 Explicabilidad | Grad-CAM |
| 📦 Formatos móviles | TensorFlow Lite |
| 💻 Frameworks | PyTorch / TensorFlow |

---

## 📂 Contenido del repositorio

```text
AveScan-Modelos-Resultados/
│
├── 📄 README.md
│
├── 🖼️ logo/
│   └── Logo-AveScan.jpeg
│
├── 📓 notebooks/
│   ├── Mobilenetv2.ipynb
│   └── MobileViT.ipynb
│
├── 🧠 modelos/
│   └── mobilevit_fase3/
│       ├── comparacion_tamano.png
│       ├── labels.txt
│       ├── mobilevit_fase3_final_float16.tflite
│       ├── mobilevit_fase3_final_float32.tflite
│       ├── mobilevit_fase3_mejor.pt
│       └── mobilevit_final.onnx
│
├── 📊 resultados/
│   └── RESULTADOS_FASE3_TTA.zip
│
└── 📘 manual/
    └── Manual de Usuario - AveScan.pdf
