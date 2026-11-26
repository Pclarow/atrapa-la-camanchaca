# Atrapa la Camanchaca

**Proyecto final · Unidad 3: Interfaces Gráficas** — Taller de Diseño de Interfaces, Universidad Adolfo Ibáñez, 2026
**Autor:** Pedro Claro
**Concurso:** Chile Re-Descubre (Congreso Futuro · ACHIPEC · CRTIC)
**Hito elegido:** Atrapanieblas — *Hecho en Chile. 50 ideas, descubrimientos e innovaciones*

▶️ **Probar en línea:** https://pclarow.github.io/atrapa-la-camanchaca/  
🎬 **Cápsula audiovisual:** https://youtu.be/foksx6VJ_vg  
📊 **Presentación:** https://pclarow.github.io/atrapa-la-camanchaca/presentacion.html (flechas o clic para avanzar, F para pantalla completa)

---

## Descripción conceptual

En el desierto de Atacama casi no llueve, pero desde el mar llega la **camanchaca**: una niebla espesa hecha de millones de gotitas de agua. En los años 60, frente a la sequía de Antofagasta, el físico chileno **Carlos Espinosa Arancibia** ideó una malla vertical capaz de interceptar esa niebla y convertirla en agua: el **atrapanieblas**. Espinosa donó su patente a la UNESCO para que cualquiera pudiera usarla, y en 1992 el pueblo de pescadores de **Chungungo** (Región de Coquimbo) pasó del camión aljibe a tener agua de niebla en cada casa.

En esta experiencia **la mano del visitante es la malla**. Al levantarla frente a la cámara, atrapa la niebla que viene del mar; cada gota cae a la canaleta y llena el estanque de Chungungo. A medida que sube el agua, aparece el relato del invento, hasta llegar a los 15.000 litros diarios que recibía el pueblo.

## Instrucciones de uso

1. Abrir la página en **Google Chrome** (computador con cámara).
2. Presionar **Comenzar** y aceptar el permiso de cámara.
3. Levantar la **mano abierta** frente a la cámara: la malla sigue la palma.
4. Moverla hacia la niebla para atraparla y llenar el estanque.
5. Acercar la mano a la cámara hace la malla más grande.
6. Al llenar el estanque aparece tu tiempo y tu récord; presionar **Jugar de nuevo** (o la tecla **R**) para volver a empezar.

Sin cámara, la malla se mueve con el mouse.

## Tecnologías

- **MediaPipe Hand Landmarker** (`@mediapipe/tasks-vision`): detección de 21 puntos de la mano en tiempo real; el centro de la palma controla la malla.
- **Canvas 2D**: escena, niebla, gotas y estanque.
- **Web Audio API**: viento generado y sonido de cada gota.
- HTML, CSS y JavaScript, sin servidor. Publicado con **GitHub Pages**.

## Datos y fuentes del relato

- Carlos Espinosa Arancibia ideó los atrapanieblas en los años 60 en Antofagasta y donó su patente a la UNESCO.
- Un metro cuadrado de malla capta entre 3 y 10 litros diarios en proyectos operativos.
- Chungungo (El Tofo, Región de Coquimbo): desde 1992, agua de niebla en las casas; promedio cercano a 15.000 litros diarios.

Fuentes: FAO; Centro del Desierto de Atacama UC (*Agua de Niebla*); El Desconcierto; Portal Frutícola; tesis UNAM sobre colectores de niebla.

## Ejercicios de la unidad

- Módulo 01 · MediaPipe: https://github.com/Pclarow/mediapipe-manos
- Módulo 02 · AR.js: https://github.com/Pclarow/realidad-aumentada
- Módulo 03 · A-Frame: https://github.com/Pclarow/aframe-cielo
