# Proyecto mBot 2 - Navegación Autónoma
**Centro Educativo:** IES José Isbert  
**Fecha:** 19 de marzo de 2026

## Descripción del Proyecto
Este repositorio contiene el código y la documentación técnica para el robot mBot 2 de Makeblock Education. El objetivo principal es la implementación de un sistema de navegación que permita al robot seguir una trayectoria y gestionar obstáculos de manera autónoma.

## Funciones del Software
El programa desarrollado integra las siguientes capacidades:
* **Seguimiento de línea:** El software procesa las lecturas del Sensor Quad RGB para realizar correcciones en la dirección y asegurar que el robot se mantenga sobre la línea de la pista.
* **Gestión de obstáculos:** Mediante el Sensor Ultrasónico 2.0, el código monitoriza la distancia frontal en tiempo real. Al detectar un objeto por debajo del umbral de seguridad, el sistema ejecuta una rutina de parada automática.

## Relación Software-Hardware
* **Entrada (Input):** El programa captura y digitaliza los datos provenientes de los sensores de luz (RGB) y de distancia (ultrasonidos).
* **Procesamiento:** La placa CyberPi actúa como unidad central, ejecutando la lógica de control y toma de decisiones.
* **Salida (Output):** El software regula la potencia y rotación de los motores con encoders, permitiendo desplazamientos y giros de alta precisión.

## Código Ético
Declaramos que la totalidad de este proyecto ha sido realizada por los 5 estudiantes integrantes del equipo del IES José Isbert. La participación del tutor se ha limitado a la orientación pedagógica, sin intervenir en la programación ni en la resolución técnica de los desafíos.
