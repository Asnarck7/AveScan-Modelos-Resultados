<div align="center">

<img src="logo/Logo-AveScan.jpeg" alt="Logo AveScan" width="220"/>

# 🐦 AveScan

### Identificación automática de aves del departamento del Tolima mediante aprendizaje profundo

<p>
  <strong>Proyecto de investigación y desarrollo</strong>
</p>

<p>
  Aplicación móvil para la identificación automática de especies de aves mediante modelos de aprendizaje profundo.
</p>

</div>

---

## 📌 Sobre el proyecto

**AveScan** es una aplicación móvil desarrollada para apoyar la identificación automática de aves del departamento del Tolima mediante técnicas de **aprendizaje profundo y visión por computador**.

El proyecto integra un modelo basado en la arquitectura **MobileViT**, entrenado y evaluado sobre un conjunto de **545 especies**, y posteriormente preparado para su utilización en dispositivos móviles mediante formatos compatibles con el despliegue de modelos de aprendizaje automático.

Este repositorio contiene los principales materiales técnicos y resultados obtenidos durante el desarrollo del proyecto.

---

## 🎯 Objetivo

Desarrollar una aplicación móvil capaz de realizar la identificación automática de especies de aves mediante aprendizaje profundo, facilitando el reconocimiento de la biodiversidad presente en el departamento del Tolima.

---

## 🧠 Modelo de aprendizaje profundo

El modelo final seleccionado corresponde a **MobileViT**, arquitectura que combina características de redes convolucionales con mecanismos basados en Transformers.

### Características principales

| Característica         | Descripción          |
| ---------------------- | -------------------- |
| 🧠 Arquitectura        | MobileViT            |
| 🐦 Clases              | 545 especies         |
| 📱 Orientación         | Despliegue móvil     |
| 🔄 Evaluación          | Fase 3 + TTA         |
| 🔥 Explicabilidad      | Grad-CAM             |
| 📦 Formato móvil       | TensorFlow Lite      |
| 💻 Framework principal | PyTorch / TensorFlow |

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
│       ├── labels.txt
│       ├── mobilevit_fase3_final_float16.tflite
│       ├── mobilevit_fase3_final_float32.tflite
│       ├── mobilevit_fase3_mejor.pt
│       ├── mobilevit_final.onnx
│       └── comparacion_tamano.png
│
├── 📊 resultados/
│   └── RESULTADOS_FASE3_TTA.zip
│
├── 🔥 gradcam/
│   └── GradCAM_545_especies.zip
│
└── 📘 manual/
    └── Manual_de_Usuario_AveScan.pdf
```

---

## 📓 Notebooks

Los notebooks contienen diferentes etapas del proceso de entrenamiento y experimentación:

* **MobileNetV2:** entrenamiento del modelo padre utilizado como referencia.
* **MobileViT:** entrenamiento y ajuste del modelo final seleccionado.

Los notebooks permiten consultar el proceso experimental utilizado durante el desarrollo del proyecto.

---

## 🧠 Modelos entrenados

Se incluyen los principales formatos generados durante el proceso de entrenamiento y exportación del modelo MobileViT:

* `.pt` → modelo nativo en PyTorch.
* `.onnx` → formato de intercambio.
* `.tflite` → formatos destinados al despliegue móvil.
* `labels.txt` → etiquetas correspondientes a las 545 clases.

---

## 📊 Resultados

La carpeta `resultados` contiene los resultados completos correspondientes a la **Fase 3 + Test-Time Augmentation (TTA)**.

Incluye:

* Matrices de confusión.
* Comparación entre Fase 2 y Fase 3 + TTA.
* Desempeño por especie.
* Comparación entre modelo padre e hijo.
* Progreso de las fases de entrenamiento.
* Top 15 de especies con mayor mejora.
* Archivos de resultados en formatos CSV y Excel.

---

## 🔥 Explicabilidad mediante Grad-CAM

Se incluyen las visualizaciones generadas mediante **Grad-CAM**, utilizadas para analizar las regiones de las imágenes que reciben mayor atención por parte del modelo durante la clasificación.

El conjunto completo contiene visualizaciones correspondientes a las **545 especies evaluadas**.

---

## 📱 Aplicación móvil

La aplicación móvil AveScan fue desarrollada como parte del proyecto para permitir la identificación de aves mediante dispositivos Android.

El código fuente de la aplicación y el archivo APK se encuentran en el repositorio desarrollado conjuntamente por los integrantes del proyecto.

> El repositorio actual se centra principalmente en los modelos, experimentación, resultados y material técnico del componente de aprendizaje profundo.

---

## ☁️ Material complementario

Debido al tamaño de algunos archivos y conjuntos de datos utilizados durante el proyecto, determinados materiales se mantienen en almacenamiento externo.

Entre ellos se encuentra el conjunto de datos completo y otros archivos de gran tamaño utilizados durante el proceso experimental.

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
