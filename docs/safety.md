# Seguridad y mantenimiento

> Revisa estos puntos antes de operar PepoBot.

## Eléctrica

- Usa regulador de 5 V estable con suficiente corriente para todos los servos.
- Añade fusible e idealmente diodo para protección contra inversión de polaridad.
- Mantén un GND común pero evita lazos de tierra.
- Separa alimentación de lógica (RPi/Arduino) y potencia (motores/servos) con filtros o reguladores independientes si es posible.

## Baterías

- No dejes LiPo sin supervisión durante carga.
- Guarda a voltaje de almacenamiento (3,7–3,8 V por celda).
- Revisa hinchazón, fugas o daños y desecha correctamente.
- Usa siempre bolsa ignífuga durante carga.

## Mecánica

- Revisa tornillería y holguras antes de cada uso.
- Limita el rango de servos en firmware para evitar esfuerzos.
- No fuerces manualmente servos o engranajes.

## Firmware/Software

- Implementa límites suaves (`configs/params.yaml`).
- Añade watchdog o tiempo máximo para movimientos.
- Registra errores y condiciones fuera de rango.
- Implementa un “kill switch” físico o por software para parar motores en emergencia.

## Mantenimiento

- Limpia conectores y comprueba cables/soldaduras.
- Lubrica articulaciones si aplica.
- Haz pruebas periódicas de autonomía y temperatura.

> ⚠️ La seguridad es prioritaria: prueba siempre primero sin carga en servos y con una fuente de alimentación limitada en corriente.
