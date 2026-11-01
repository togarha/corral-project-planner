# Corral Project Planner

Repositorio de trabajo para definir, diseñar, presupuestar y hacer seguimiento de un proyecto de acondicionamiento de parcela y nuevas construcciones auxiliares.

El repositorio actúa como punto único de referencia para:
- El programa de necesidades.
- La geometría de referencia y documentación gráfica.
- Las decisiones técnicas pendientes.
- La planificación por fases.
- El seguimiento de tareas, riesgos y cambios.

## Estado actual

**Fase:** definición de necesidades, previa al estudio de distribución.

El programa funcional está recogido en [`docs/programa-necesidades.md`](docs/programa-necesidades.md). Las decisiones todavía abiertas se mantienen en [`docs/decisiones-pendientes.md`](docs/decisiones-pendientes.md).

## Estructura

```text
.
├── README.md
├── .gitignore
├── docs/
│   ├── programa-necesidades.md
│   └── decisiones-pendientes.md
└── assets/
    ├── imagen-satelital.png
    └── perimetro-acotado.png
```

## Cómo mantener el repositorio

1. Actualizar el programa de necesidades cuando se acuerde un cambio funcional.
2. Registrar las decisiones relevantes y su justificación en `docs/decisiones-pendientes.md` o en futuros ADR.
3. Mantener los planos y fotografías de referencia en `assets/`.
4. Registrar tareas, presupuestos y avances en documentos separados cuando comience esa fase.
5. No sobrescribir documentación importante sin actualizar su versión o dejar constancia del cambio.

## Convención recomendada

- Documentación en Markdown.
- Fechas en formato `AAAA-MM-DD`.
- Unidades métricas.
- Diferenciar siempre entre **decidido**, **provisional** y **pendiente**.
- No incluir datos personales, direcciones, referencias registrales o catastrales, ni importes privados de compraventa.

## Privacidad

Este repositorio se ha preparado sin incluir dirección, localidad, referencia catastral, datos de propietarios ni precio de adquisición. Las imágenes se incluyen como material gráfico aportado para el diseño. Antes de hacer público el repositorio, conviene revisar también que las imágenes y cualquier archivo que se añada posteriormente no revelen información que se quiera mantener privada.

## Próximos pasos

- [ ] Revisar y aprobar el programa de necesidades.
- [ ] Comprobar el contenido y la geometría del archivo CAD/DXF original.
- [ ] Obtener o preparar un levantamiento topográfico fiable.
- [ ] Desarrollar alternativas de distribución a escala.
- [ ] Consultar las soluciones técnicas con los profesionales correspondientes.
- [ ] Desglosar presupuesto y fases de ejecución.
