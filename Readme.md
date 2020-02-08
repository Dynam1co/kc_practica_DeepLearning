# Práctica Deep Learning - BootCamp Big Data & Machine Learning

Este es el repositorio que contiene los archivos necesarios para realizar la práctica de la asignatura de Deep Learning del Bootcamp Big Data y Machine Learning IV cursado en KeepCoding en 2019-2020.

## Objetivo

El objetivo es predecir el precio de la vivienda en la ciudad de Madrid a partir de un dataset de apartamentos de Airbnb conseguido mediante técnicas de scraping. La predicción se hará tendiendo en cuenta tanto datos numéricos como imágenes.

Se ha usado un dataset con datos reales pero reducido, con 14780 observaciones ya que lo importante en este caso no es el resultado, si no el procedimiento.

## Dataset 

El dataset no está incluido en el proyecto para no ocupar un espacio innecesario y agilizar tiempos. Puede descargarse de [esta url](https://public.opendatasoft.com/explore/dataset/airbnb-listings/export/?disjunctive.host_verifications&disjunctive.amenities&disjunctive.features&q=Madrid&dataChart=eyJxdWVyaWVzIjpbeyJjaGFydHMiOlt7InR5cGUiOiJjb2x1bW4iLCJmdW5jIjoiQ09VTlQiLCJ5QXhpcyI6Imhvc3RfbGlzdGluZ3NfY291bnQiLCJzY2llbnRpZmljRGlzcGxheSI6dHJ1ZSwiY29sb3IiOiJyYW5nZS1jdXN0b20ifV0sInhBeGlzIjoiY2l0eSIsIm1heHBvaW50cyI6IiIsInRpbWVzY2FsZSI6IiIsInNvcnQiOiIiLCJzZXJpZXNCcmVha2Rvd24iOiJyb29tX3R5cGUiLCJjb25maWciOnsiZGF0YXNldCI6ImFpcmJuYi1saXN0aW5ncyIsIm9wdGlvbnMiOnsiZGlzanVuY3RpdmUuaG9zdF92ZXJpZmljYXRpb25zIjp0cnVlLCJkaXNqdW5jdGl2ZS5hbWVuaXRpZXMiOnRydWUsImRpc2p1bmN0aXZlLmZlYXR1cmVzIjp0cnVlfX19XSwidGltZXNjYWxlIjoiIiwiZGlzcGxheUxlZ2VuZCI6dHJ1ZSwiYWxpZ25Nb250aCI6dHJ1ZX0%3D&location=16,41.38377,2.15774&basemap=jawg.streets)

## Resolución del problema

La resolución de la práctica se ha hecho en Python usando varios notebooks de Jupyter donde en cada uno se explica todo el procedimiento paso a paso.

### 1. Descargar imágenes de los apartamentos
Las imágenes quedarán guardadas en la carpeta **img** por el volumen de datos que hay, las imágenes no están incluidas en el repositorio GitHub

[Descarga de imágenes](descargaImagenes.ipynb)