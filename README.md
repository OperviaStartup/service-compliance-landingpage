# Opervia — Service Compliance Landing Page

Landing page estática y responsive para presentar Service Compliance, la propuesta de Opervia para mantener trazabilidad entre el plan de servicio, las obligaciones, la ejecución, la evidencia y las acciones correctivas en servicios de limpieza tercerizada B2B.

## Contenido

- Propuesta de valor y demostración ilustrativa del producto.
- Flujo de trazabilidad de cinco etapas.
- Experiencias diferenciadas para supervisores y operarios.
- Alcance y limitaciones comunicados de forma transparente.
- Secciones de Opervia, equipo, preguntas frecuentes y llamada a la acción.
- Internacionalización ES/EN con preferencia persistida en `localStorage`.
- Navegación responsive, accesible y compatible con movimiento reducido.

## Estructura

```text
.
├── assets/
│   ├── opervia-logo.png
│   └── team/
├── index.html
├── styles.css
├── script.js
└── .github/workflows/pages.yml
```

## Ejecutar localmente

No requiere dependencias ni proceso de compilación. Inicia un servidor estático desde la raíz:

```bash
python -m http.server 8000
```

Luego visita [http://localhost:8000](http://localhost:8000).

## Despliegue

El workflow de GitHub Pages publica el contenido estático al hacer `push` a `main` o mediante una ejecución manual desde GitHub Actions.

## Fuentes de contenido

La propuesta, el alcance, los segmentos, las capacidades, las limitaciones y los perfiles del equipo provienen de los capítulos 1 y 2 del informe de Service Compliance. Los enlaces técnicos se tomaron de los capítulos 3 y 4 reformulados.

Los datos que aparecen en los mockups de interfaz son ejemplos ilustrativos y no representan métricas reales, clientes ni resultados comerciales.
