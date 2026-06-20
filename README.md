# Análisis de una empresa de telecomunicaciones

Introducción:

Soy analista de datos en ConnectaTel, una empresa de telecomunicaciones con operaciones en México y Colombia.

Mi equipo debe entregar un reporte para entender cómo los clientes usan realmente los servicios móviles (llamadas y mensajes).

El objetivo de la empresa es identificar patrones de uso, detectar comportamientos atípicos y comprender qué segmentos de clientes muestran necesidades diferenciadas, con el fin de optimizar la oferta comercial y mejorar la experiencia del usuario.

Para ello, trabajare con tres fuentes de datos:

plans.csv: los planes actuales (precio, minutos incluidos, GB incluidos, costo por extra).

users_latam.csv: información de clientes: edad, ciudad, fecha de registro, plan contratado.

usage.csv: el detalle de uso real: llamadas (duración) y mensajes (longitud).

Mi misión será explorar, limpiar y analizar estas bases de datos para construir una visión clara, confiable y accionable sobre el comportamiento de uso de los clientes y cómo varía entre diferentes grupos de usuarios.

## 📂 Contenido del repositorio

- `Project_ConnectaTel.ipynb`
  → Notebook principal con limpieza, EDA, distribuciones, outliers y conclusiones.

## ▶ Cómo abrir el notebook en Google Colab

Haz clic en el siguiente botón:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Alezgo-ui/Project_ConnectaTel/blob/main/Project_ConnectaTel.ipynb)

O:

1. Abre el archivo `.ipynb` en GitHub
2. Haz clic en **Open in Colab**

## 📘 Cómo reproducir el análisis

1. Abre `Project_ConnectaTel.ipynb`
2. Ejecuta las celdas en orden
3. El notebook carga automáticamente el dataset desde `/data/` o desde un enlace público (según corresponda)

## 🧠 Objetivo del análisis

- Integrar y limpiar bases de datos provenientes de tres fuentes distintas.
- Aplicar técnicas de validación, estandarización de tipos de datos y detección de valores inconsistentes.
- Construir un perfil estadístico del uso (llamadas y mensajes) por cliente y por segmentos demográficos.
- Detectar outliers y comportamientos atípicos mediante métodos estadísticos y visuales.
- Crear segmentaciones de clientes basadas en edad, país y comportamiento de uso.
- Visualizar diferencias entre segmentos y extraer insights comerciales relevantes.
