# XR Interaction Challenge

## Datos del Estudiante y Curso
* **Apellidos y Nombres:** [Barrera Rivas, Kirt Antonio]
* **Código de Estudiante:** [0009-0003-8499-7177]
* **Curso:** Laboratorio de Realidad Extendida (XR) para Videojuegos
* **Docente:** Victor Alejandro Arroyo Castro

---

## Descripción del Proyecto
Pequeña experiencia interactiva desarrollada en Unity (URP) orientada a un entorno de entrenamiento XR. Integra la configuración básica de XR Origin, manipulación física de objetos mediante XR Interaction Toolkit, interacción por rayo a distancia y mecánicas de locomoción por teletransporte.

---

## Funcionalidades Implementadas
1. **Configuración XR:** Entorno configurado con Universal Render Pipeline (URP) y XR Interaction Toolkit con soporte para simulación/HMD.
2. **Escenario 3D:** Sala delimitada con piso, iluminación direccional y elementos 3D primitivos que conforman el área de pruebas.
3. **Manipulación de Objetos (XR Grab):** Dos objetos interactivos con físicas completas (`Rigidbody` y `XR Grab Interactable`) manipulables directamente por el usuario.
4. **Interacción a Distancia (Ray Interactor):** Botón/objeto interactivo a distancia mediante rayo (`XR Simple Interactable`) que activa y desactiva la iluminación de la sala.
5. **Reto Libre (Locomoción):** Sistema de teletransporte configurado mediante `Teleportation Area` en la superficie del suelo.

---

## Controles / Instrucciones
* **Grip (Agarre):** Sujetar y soltar los objetos manipulables en la mesa.
* **Ray / Trigger (Gatillo):** Apuntar al interruptor a distancia para encender/apagar la luz del escenario.
* **Teletransporte:** Apuntar con el rayo hacia el piso y soltar/presionar para desplazarse por la sala.
*(Si se prueba con XR Device Simulator: usar teclas de movimiento de cámara y clic derecho/izquierdo según mapeo estándar).*

---

## Tecnologías y Paquetes Utilizados
* Unity (Versión utilizada, ej. 2022.3 LTS)
* Universal Render Pipeline (URP)
* XR Interaction Toolkit
* XR Plugin Management / OpenXR

---

## Evidencias
* **Enlace al video demostrativo (máx. 1 minuto):** [Inserta aquí tu enlace de YouTube / Drive público]

### Capturas de Pantalla

#### 1. Vista General del Escenario
(Captura.png)

#### 2. Configuración XR y Componentes en el Inspector
![Configuración Inspector](ruta/a/tu/captura2.png)

#### 3. Interacción en Funcionamiento
![Interacción Funcionando](ruta/a/tu/captura3.png)
