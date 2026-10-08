# StoryVoice — Plan de experimentos comerciales y técnicos

## Experimento A: demanda (semana 1)
- Entrevistar 20 adultos con niños de 3–8 años.
- Mostrar concepto y audio demostrativo claramente identificado como sintético.
- Preguntar por frecuencia de cuentos, alternativas y última compra comparable.
- Ofrecer compra piloto real; registrar conversiones, rechazos y razones.
- **Señal inicial:** 5 pagos entre 20 personas; es un umbral operativo exploratorio, no prueba de demanda estadística.

## Experimento B: calidad de voz (semanas 1–2)
- Solo voces propias de participantes con consentimiento verificable.
- Pruebas ciegas de semejanza, naturalidad, pronunciación, emociones y aceptación.
- Verificar licencia comercial de código, pesos y datos de entrenamiento cuando corresponda.
- No publicar voces ni grabaciones sin autorización.

## Experimento C: latencia (semanas 2–3)
- Medir tiempo desde pulsar «Escuchar» hasta primer fragmento audible.
- Objetivos aspiracionales: p50 <=3 s y p95 por determinar con benchmark.
- Probar GPU caliente, concurrencia 1/5/10, fallos y reintentos.
- Medir si el streaming supera la velocidad de reproducción sostenida.

## Experimento D: economía (semanas 3–4)
- Registrar GPU activa/ociosa, minutos de salida, regeneraciones, costos de almacenamiento y cobro.
- Calcular margen por cuento pagado y break-even mensual.
- Simular 20, 100, 500 y 1,000 compradores, separando clientes de cuentos vendidos.

## Gates
- GO: compras reales + calidad aceptada + licencias aptas + seguridad básica + margen de contribución positivo medido.
- PIVOT: interés sin pago, o mala calidad/latencia corregible.
- NO-GO: uso comercial no permitido, riesgos no mitigables o economía estructuralmente inviable.
