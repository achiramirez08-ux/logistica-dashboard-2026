# Dashboard J&F · Gas Oil Paraguay/Bolivia

Control room en vivo del suministro mensual de gas oil del Proyecto J&F (55.000 m³/mes: 40.000 Bolivia + 15.000 Paraguay).

## Cómo usarlo

**Abrí el link. Fin.** El dashboard levanta solo los datos actualizados del Google Sheet cada 5 minutos.

## Qué muestra

- **KPIs generales:** volumen plan, avance de retiro a Bolivia, avance de despacho local, OTIF Bolivia (retiro ≤ 27 días), colchón Petropar utilizado, ciclos con alerta.
- **Ciclo activo:** progreso Bolivia/Local con días hasta meta interna (27 d), ventana operativa (30 d) y límite legal IDA (60 d).
- **Ocupación de terminales:** Petrosan, Fuel Par, Integral y Petropar contra su capacidad dedicada.
- **Matriz semáforo 12 ciclos:** verde en tiempo · amarillo excede meta · rojo excede ventana operativa o IDA.
- **Cronograma Gantt** de los 12 ciclos con línea "HOY".
- **Charts** de plan vs. real acumulado, cadencia de tránsito y uso de Petropar.
- **Feed de alertas** con acciones sugeridas.

## Cómo se actualiza

Los datos vienen de la planilla `Seguimiento_Cargas_GasOil_JF` en Google Drive. Actualizás la planilla como siempre (fecha real de llegada, m³ retirados, m³ despachados, colchón usado) y el dashboard refleja los cambios automáticamente.

## Parámetros del proyecto

- Volumen mensual: 40.000 m³ Bolivia + 15.000 m³ Local = 55.000 m³/mes.
- Terminales dedicadas: Petrosan 20.000 · Fuel Par 20.000 · Integral 15.000.
- Colchón contingencia compartido: Petropar 30.000 m³.
- Flota: Mercurio 30.000 · Navios 20.000 · Rock Tree 20.000 (70.000 m³ total).
- Tránsito fluvial: 10–15 días (referencia 13). Retorno vacío: 5 días. Cadencia: 30 días.
- Meta interna de retiro Bolivia: 27 días. Límite legal IDA: 60 días.

## Uso interno

Proyecto J&F. Compartir el link solo con el equipo operativo.
