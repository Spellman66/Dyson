# 🌌 Dyson Swarm: Ultra-3D Volumetric Simulation

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![Version](https://img.shields.io/badge/version-4.0.0--Stable-00ffcc)

Una simulación de alta fidelidad basada en la web que visualiza una **Esfera de Dyson** (variante enjambre) utilizando renderizado volumétrico de 4,000 nodos independientes. El proyecto explora la intersección entre la mecánica orbital, la física de materiales y el renderizado 3D sin librerías externas.

## 🚀 Características Principales

* **Renderizado Volumétrico:** 4,000 módulos (estatitas) procesados en tiempo real con profundidad real.
* **Depth Slicing (Sombreado Avanzado):** Algoritmo dinámico que cambia el color y brillo de los nodos según su posición $Z$, creando una sensación de profundidad atmosférica.
* **Motor de Física Orbital:** Implementación de rotación en 3 ejes ($X, Y, Z$) con proyección de perspectiva manual.
* **Bloom & Oclusión Solar:** El núcleo solar actúa como una fuente de luz real, afectando la visibilidad y el resplandor de los nodos frontales.
* **Estabilidad Estelar:** Lógica de corrección de radio para evitar la deriva orbital y mantener una formación perfecta.

## 🛠️ Tecnologías Utilizadas

* **HTML5 Canvas API:** Para el renderizado de gráficos de alto rendimiento.
* **JavaScript (Vanilla):** Lógica de física y matemáticas (trigonometría aplicada).
* **CSS3:** Interfaz de usuario táctica con estética Cyberpunk/Space-Ops.

## 🧬 Conceptos de Ingeniería Aplicados

En este repositorio se implementaron los siguientes conceptos:
1.  **Mecánica de Sólidos:** Simulación de tensión de rotura en materiales avanzados (Nanotubos de Carbono).
2.  **Proyección 3D a 2D:** Uso de la fórmula de perspectiva: $f = \frac{D}{D + Z}$.
3.  **Z-Sorting:** Algoritmo de ordenamiento por profundidad para garantizar la correcta oclusión de los objetos.
4.  **Feedback Loops:** Sistemas de auto-corrección para mantener el equilibrio gravitatorio.

## 📦 Instalación y Uso

No requiere dependencias externas ni compilación.

1. Clona el repositorio:
   ```bash
   git clone [https://github.com/tu-usuario/dyson-swarm-3d.git](https://github.com/tu-usuario/dyson-swarm-3d.git)
