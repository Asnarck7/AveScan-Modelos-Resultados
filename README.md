<div align="center">

<img src="logo/Logo-AveScan.jpeg" alt="Logo AveScan" width="220"/>

# 🐦 AveScan

### Identificación automática de aves del departamento del Tolima mediante aprendizaje profundo

<p>
  <strong>Material complementario del proyecto de investigación</strong>
</p>

<p>
  Modelos de aprendizaje profundo · Experimentación · Evaluación · Explicabilidad
</p>

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

| Característica      | Información          |
| ------------------- | -------------------- |
| 🧠 Arquitectura     | MobileViT            |
| 🐦 Número de clases | 545 especies         |
| 📱 Orientación      | Despliegue móvil     |
| 🔄 Evaluación       | Fase 3 + TTA         |
| 🔥 Explicabilidad   | Grad-CAM             |
| 📦 Formatos móviles | TensorFlow Lite      |
| 💻 Frameworks       | PyTorch / TensorFlow |

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
```

---

## 📓 Notebooks de experimentación

Se incluyen los principales notebooks utilizados durante el proceso de desarrollo y experimentación:

### MobileNetV2

`Mobilenetv2.ipynb`

Utilizado para el entrenamiento del modelo padre y como referencia para el desarrollo posterior del modelo final.

### MobileViT

`MobileViT.ipynb`

Utilizado para el entrenamiento, ajuste y evaluación del modelo final seleccionado para el proyecto.

---

## 🧠 Modelos entrenados

La carpeta `modelos` contiene los principales formatos generados durante el entrenamiento y exportación del modelo MobileViT:

* **PyTorch (`.pt`)** — modelo entrenado en su formato nativo.
* **ONNX (`.onnx`)** — formato de intercambio para modelos de aprendizaje automático.
* **TensorFlow Lite (`.tflite`)** — formatos destinados al despliegue del modelo en dispositivos móviles.
* **`labels.txt`** — archivo con las etiquetas correspondientes a las 545 clases.
* **`comparacion_tamano.png`** — comparación del tamaño de los formatos generados.

---

## 📊 Resultados de evaluación

La carpeta `resultados` contiene los resultados correspondientes a la **Fase 3 + Test-Time Augmentation (TTA)**.

El archivo incluye:

* Siete matrices de confusión generadas por bloques.
* Comparación entre Fase 2 y Fase 3 + TTA.
* Desempeño por especie.
* Comparación final entre el modelo padre e hijo.
* Gráficas de progreso.
* Top 15 de especies con mayor mejora.
* Resultados en formatos CSV y Excel.

---

## 🔥 Explicabilidad mediante Grad-CAM

El proyecto incorpora **Grad-CAM** como técnica de explicabilidad para analizar las regiones de las imágenes que tienen mayor influencia en las predicciones realizadas por el modelo.

Las visualizaciones correspondientes a las especies evaluadas se encuentran dentro del material complementario almacenado externamente.

---

## 📱 Aplicación móvil

El desarrollo de la aplicación móvil AveScan y su archivo APK se encuentran en el repositorio desarrollado conjuntamente por los integrantes del proyecto.

👉 **Repositorio de la aplicación móvil:**
[AndresVasqu3z/aves-tolima](https://github.com/AndresVasqu3z/aves-tolima)

Este repositorio se mantiene independiente del presente repositorio, que está orientado principalmente al componente de **aprendizaje profundo, modelos, experimentación y resultados**.

---

## ☁️ Material complementario

Debido al tamaño de algunos archivos generados durante el proceso experimental, determinados materiales se encuentran almacenados externamente.

### 📦 Incluye

* Modelos entrenados de la Fase 3.
* Conjunto de datos y material experimental.
* Visualizaciones Grad-CAM y otros archivos complementarios.

👉 **[Acceder al material complementario en Google Drive](https://drive.google.com/drive/folders/1byUO8WokUW7XQ7aetZ6Z-FEei2Z1_cgO?usp=sharing)**

---

## 🛠️ Tecnologías utilizadas

<div align="center">

`Python` · `PyTorch` · `TensorFlow` · `TensorFlow Lite` · `MobileViT` · `Jupyter Notebook` · `Grad-CAM` · `Flutter`

</div>

---

## 👥 Proyecto

**AveScan — Desarrollo de una aplicación móvil para la identificación automática de aves del departamento del Tolima mediante aprendizaje profundo.**

**Año:** 2026

**Institución:** Universidad Cooperativa de Colombia

**Programa:** Ingeniería de Sistemas

---

<div align="center">

### 🐦 AveScan

**Tecnología aplicada al reconocimiento de la biodiversidad del Tolima.**

</div>
