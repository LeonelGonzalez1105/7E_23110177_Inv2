# Arquitectura de Sistemas Expertos

Este repositorio contiene el desglose y análisis de la arquitectura funcional de un **Sistema Experto (SE)**, desarrollado como parte de la formación en Ingeniería Mecatrónica.

##  Introducción
Un Sistema Experto es una rama de la Inteligencia Artificial diseñada para emular el razonamiento de un especialista humano en un dominio específico para resolver problemas complejos y tomar decisiones.

##  Componentes de la Arquitectura

### 1. Componente Humana e Interacción
* **Experto Humano e Ingeniero del Conocimiento:** Colaboración para traducir el conocimiento especializado a un lenguaje lógico.
* **Interfaz de Usuario:** El enlace que permite la comunicación fluida entre el sistema y el usuario final.
* **Subsistema de Explicación:** Justifica el razonamiento y las conclusiones alcanzadas por el motor de inferencia.

### 2. Gestión del Conocimiento
* **Base de Conocimiento:** Almacena reglas de validez general ($IF-THEN$).
* **Base de Hechos (Memoria de Trabajo):** Contiene los datos temporales y específicos de la situación actual.
* **Control de Coherencia:** Garantiza que no existan contradicciones dentro de la base de conocimiento.

### 3. El Motor de Inferencia
Es el "corazón" del sistema. Su función es aplicar el conocimiento a los datos para generar conclusiones, ya sea mediante lógica determinista o probabilística (manejo de incertidumbre).

### 4. Ciclo de Aprendizaje y Ejecución
* **Subsistema de Aprendizaje:** Permite la mejora del sistema mediante el ajuste de parámetros o la inclusión de nuevas reglas estructurales.
* **Ejecución de Órdenes:** Permite al sistema realizar acciones físicas o lógicas (ej. abrir una válvula o detener un proceso).

---

## 📊 Diagrama de Bloques
A continuación se presenta la representación gráfica de la interacción entre los módulos:

![Diagrama de Arquitectura de Sistemas Expertos](./image_09363a.png)

---

## 👨‍💻 Autor
* **Leonel González** - *Estudiante de Ingeniería Mecatrónica*
* **Institución:** CETI
