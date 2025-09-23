# Lista de Materiales (BOM)

> Proyecto: PepoBot
> Estado: Borrador inicial — completa y ajusta según tus componentes reales.

## Tabla de materiales

| Cantidad | Componente            | Especificación / Nota                 | Proveedor/Link | Precio aprox. |
|---------:|-----------------------|---------------------------------------|----------------|---------------|
| 1        | Microcontrolador      | Arduino/ESP32 (modelo a definir)      | TODO           | TODO          |
| 2-4      | Servomotores          | SG90/MG90S o similares                | TODO           | TODO          |
| 1        | Sensor de tacto       | Resistencia/Capacitivo (p.ej. TTP223) | TODO           | TODO          |
| 1        | Batería               | LiPo 2S/18650 con BMS                 | TODO           | TODO          |
| 1        | Regulador de voltaje  | 5V 3A (para servos)                   | TODO           | TODO          |
| —        | Cables y conectores   | Dupont/JST según diseño               | —              | —             |
| —        | Tornillería           | M2/M3 y separadores                   | —              | —             |

> Sugerencia: Divide la BOM por módulos (alimentación, control, actuadores, sensores, carcasa) y añade enlaces reales.

## Notas

- Asegura margen de corriente suficiente para servos (picos >1A por servo).
- Separa alimentación lógica (MCU) de potencia (servos) y comparte GND.
- Incluye fusible y protección contra inversión de polaridad.

## Herramientas necesarias

- Soldador, estaño, termorretráctil.
- Crimpadora para JST/Dupont (opcional pero recomendable).
- Multímetro.
- Impresora 3D (para piezas en `hardware/stl`).
