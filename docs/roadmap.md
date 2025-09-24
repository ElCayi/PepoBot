# Roadmap corto — PepoBot

**Versión actual:** v0.0 — Preparación del proyecto

Roadmap — PepoBot

Borrador inicial del plan. Ajusta fechas y alcance según avance.

Fase 0 — Base del proyecto (Semana 0)

 Crear repo y estructura inicial de carpetas

 Añadir .gitignore, README.md, roadmap.md y safety.md

 Configurar tablero Kanban (Backlog / En progreso / Hecho)

Fase 1 — MVP locomoción + visión (Semanas 1–2)

 Chasis básico con ruedas y cámara (RPi + driver motores)

 Nodo ROS2 perception inicial (streaming cámara simple)

 Validar que Pepo se mueve y “ve”

Fase 2 — Expresividad corporal (Semanas 3–4)

 Cableado y control de 6–8 servos (orejas/cola/cuello)

 Firmware Arduino + PCA9685

 Nodo ROS2 gesture_bridge para poses básicas

Fase 3 — Tacto y sonido (Semanas 5–6)

 Sensores capacitivos en orejas, cabeza y lomo

 Nodo ROS2 touch_bridge publica eventos pet(zone,intensity)

 Micro + altavoz: sonidos básicos de Pepo

Fase 4 — Emoción y comportamientos (Semanas 7–8)

 emotion_engine con variables internas (curiosidad, energía, afecto, miedo)

 behaviors que reaccionan a eventos + estados

 Rutinas autónomas (explorar, aburrimiento, micro-aleatoriedad)

Fase 5 — Carcasa y seguridad (Semanas 9–10)

 Carcasa 3D (PLA) + zonas blandas (silicona fina)

 Revisión de cableado y BMS en batería

 Validaciones de seguridad eléctrica/mecánica

 Documentación y video demo

Hitos

✅ Repo inicial con docs y estructura

✅ Pepo se mueve y ve

✅ Gestos reproducibles

✅ Interacción táctil + sonidos

✅ Rutinas emocionales básicas

✅ Demo final con carcasa y seguridad
