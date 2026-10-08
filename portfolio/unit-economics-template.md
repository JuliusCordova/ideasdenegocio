# Plantilla de economía unitaria

## Variables
- Precio bruto por unidad y descuentos
- Impuestos y comisiones de cobro
- Unidades vendidas por mes
- Costo variable de inferencia (LLM/TTS) por unidad exitosa
- Reintentos y regeneraciones
- Costo de almacenamiento y tráfico por unidad
- Soporte variable por unidad
- GPU / servicios de capacidad reservada (fijos mensuales)
- Otros costos fijos mensuales
- CAC por cliente y tasa de recompra

## Fórmulas
- Ingreso neto unitario = precio bruto - descuentos - impuestos trasladados - comisiones de pago (según tratamiento contable).
- Contribución unitaria = ingreso neto unitario - costo variable unitario.
- Margen de contribución = contribución unitaria / ingreso neto unitario.
- Resultado mensual aproximado = unidades × contribución unitaria - costos fijos.
- Break-even unidades = techo(costos fijos / contribución unitaria), si contribución > 0.
- Costo IA por tarea exitosa = costo total de inferencia (incluidos reintentos) / tareas exitosas.

## Escenarios a completar con datos
Conservador, base, optimista: volumen, precio, conversión, tasa de regeneración, ocupación de GPU, soporte, CAC y margen. No usar precios hipotéticos como cotizaciones.
