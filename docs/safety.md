# Seguridad y mantenimiento

> Revisa estos puntos antes de operar PepoBot.

## Eléctrica

- Usa regulador de 5V con suficiente corriente para servos.
- Añade fusible y protección contra inversión de polaridad.
- Separa GND común, evita lazos de tierra.

## Baterías

- No dejes LiPo sin supervisión durante carga.
- Guarda a voltaje de almacenamiento.
- Revisa hinchazón o daños y desecha correctamente.

## Mecánica

- Revisa tornillería y holguras antes de uso.
- Limita el rango de servos para evitar esfuerzos.

## Firmware/Software

- Implementa límites suaves (`configs/params.yaml`).
- Añade watchdog/tiempo máximo para movimientos.
- Registra errores y condiciones fuera de rango.

## Mantenimiento

- Limpia conectores, verifica cables y soldaduras.
- Lubrica articulaciones si aplica.

> La seguridad es prioritaria: prueba primero sin carga en servos y con fuente limitada en corriente.
