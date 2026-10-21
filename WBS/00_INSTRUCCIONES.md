# Plantilla WBS / EDT — ITERA

## Reglas de redacción (obligatorias)

| Nivel | Qué representa | Cómo se redacta | Ejemplo |
|-------|----------------|-----------------|---------|
| 1 | Proyecto | Nombre del producto | ITERA |
| 2 | Disciplina / workstream | Sustantivo o área de trabajo | Autenticación y perfiles |
| 3 | Entregable | **Sustantivo** (resultado tangible) | Servicio de autenticación |
| 4 | Actividad / paquete de trabajo | **Verbo** en infinitivo (acción) | Diseñar modelo de usuarios |

> **IMPORTANTE:** el entregable se redacta como **sustantivo** y la actividad como **verbo**.

## Niveles de desglose

```
1. ITERA
├── 1.1 Disciplina / workstream
│   ├── 1.1.1 Entregable
│   │   ├── 1.1.1.1 Actividad
│   │   └── 1.1.1.2 Actividad
│   └── 1.1.2 Entregable
└── 1.2 ...
```

- Nivel 1: proyecto completo.
- Nivel 2: grandes áreas de trabajo (disciplinas o workstreams).
- Nivel 3: entregables del plan de alcance (E01–E19 u otros).
- Nivel 4: paquetes de trabajo / actividades que producen el entregable.

## Cómo usar esta carpeta

1. Completar `01_WBS_JERARQUIA.md` con la estructura jerárquica.
2. Completar `02_DICCIONARIO_WBS.md` (una fila por elemento del WBS).
3. Opcional: editar `03_WBS_TABLA.csv` en Excel / Google Sheets / LibreOffice.
4. Validar con la lista de chequeo al final de este archivo.

## Criterios de una buena WBS

- El 100 % del alcance incluido está representado (regla del 100 %).
- Lo excluido del alcance **no** aparece como entregable.
- Cada entregable tiene al menos una actividad.
- Los códigos WBS son únicos y estables (`1`, `1.1`, `1.1.1`, `1.1.1.1`).
- Cada paquete de trabajo tiene dueño, criterio de aceptación y estimación (en el diccionario).

## Lista de chequeo antes de entregar

- [ ] Nivel 1 = nombre del proyecto
- [ ] Nivel 2 = disciplinas/workstreams (sustantivos)
- [ ] Nivel 3 = entregables (sustantivos)
- [ ] Nivel 4 = actividades (verbos)
- [ ] Todos los entregables E01–E19 del Capítulo 2 están mapeados
- [ ] No hay componentes de “qué no incluye”
- [ ] Diccionario WBS completo para niveles 3 y 4
- [ ] Códigos coherentes entre jerarquía, diccionario y CSV
