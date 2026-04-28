# Actividad: Propuesta de Práctica Temática (Proyecto Pequeño)

## 1) Título de la práctica
**Diseña un título claro y específico para tu propuesta.**  
Puedes inspirarte en ejemplos como:
- Mini Toolkit en ARM64
- Asistente de Estudio en Terminal
- Reporteador de Información del Sistema
- Organizador de Archivos
- Juego de Aprendizaje en Línea de Comandos

> **Tu título propuesto:** `______________________________`

---

## 2) Descripción general
En esta actividad vas a **diseñar una propuesta de proyecto pequeño**, con enfoque en documentación y planeación, antes de programar en grande.

Tu propuesta debe plantear una práctica temática que pueda implementarse en terminal y que sea viable con recursos limitados (por ejemplo, usando versiones gratuitas de herramientas de IA).

### Lenguaje principal (elige uno)
- ARM64 Assembly
- C
- Python
- Bash

> Si eliges **ARM64 Assembly**, se recomienda que el alcance sea **muy pequeño** (programas simples y objetivos acotados).

### Enfoque prioritario
1. Documentar claramente el problema o necesidad.
2. Justificar el caso de uso.
3. Definir la estructura del repositorio.
4. Proponer plan de pruebas.
5. (Opcional) Implementar un prototipo mínimo.

> **Importante:** primero calidad de documentación, después cantidad de código.

---

## 3) Entregables del estudiante
Tu repositorio debe incluir, como mínimo:

- `README.md`
- `docs/propuesta.md`
- `docs/caso_de_uso.md`
- `docs/estructura_repositorio.md`
- `docs/plan_de_pruebas.md`
- opcional: `src/`
- opcional: `scripts/`
- opcional: `tests/`

---

## 4) Estructura recomendada del repositorio
Usa esta base mínima para organizar tu entrega:

```text
nombre-del-proyecto/
├── README.md
├── docs/
│   ├── propuesta.md
│   ├── caso_de_uso.md
│   ├── estructura_repositorio.md
│   └── plan_de_pruebas.md
├── src/
│   └── main.<ext>
├── scripts/
│   └── run.sh
└── tests/
    └── test_plan.md
```

---

## 5) Contenido esperado por archivo

### `README.md`
Incluye:
- Nombre del proyecto.
- Resumen en 5–8 líneas.
- Lenguaje principal elegido.
- Objetivo general.
- Instrucciones básicas de uso (aunque sea preliminar).
- Estado del proyecto (propuesta, prototipo o avance).

### `docs/propuesta.md`
Incluye:
- Tema de la práctica.
- Problema que atiende.
- Objetivo general y 2–4 objetivos específicos.
- Alcance (qué sí incluye y qué no incluye).
- Justificación técnica y académica.
- Lista breve de funcionalidades planeadas.
- Estimación de tamaño (pequeño, mediano; se espera **pequeño**).

### `docs/caso_de_uso.md`
Incluye:
- Usuario objetivo.
- Escenario de uso paso a paso.
- Entradas esperadas.
- Salidas esperadas.
- Ejemplo concreto de ejecución (texto o pseudoejecución).

### `docs/estructura_repositorio.md`
Incluye:
- Árbol del repositorio actualizado.
- Propósito de cada carpeta y archivo.
- Convenciones de nombres (archivos, scripts, funciones).
- Estrategia de crecimiento del proyecto sin volverlo complejo.

### `docs/plan_de_pruebas.md`
Incluye:
- Casos de prueba funcionales mínimos (al menos 5).
- Pruebas de error o entradas inválidas (al menos 2).
- Criterios de aceptación.
- Evidencia esperada (salida en terminal, capturas o logs).

---

## 6) Restricciones del proyecto
Para mantener el proyecto alcanzable y bien documentado:

- Debe ser **proyecto pequeño**.
- Evita frameworks pesados.
- No uses APIs pagadas.
- No uses bases de datos.
- No uses servicios en la nube.
- No uses contenedores (Docker, etc.).
- Evita dependencias complejas o difíciles de instalar.
- Prioriza herramientas locales y ejecución por terminal.

---

## 7) Criterios de evaluación (sugeridos)
Puntaje total sugerido: **100 puntos**

- Claridad y viabilidad de la propuesta: **25 pts**
- Calidad del caso de uso: **20 pts**
- Coherencia de la estructura del repositorio: **20 pts**
- Calidad y cobertura del plan de pruebas: **20 pts**
- Redacción técnica, orden y formato Markdown: **15 pts**

---

## 8) Rúbrica breve

| Criterio | Excelente | Suficiente | Insuficiente |
|---|---|---|---|
| Propuesta | Objetivo claro, alcance realista y justificación sólida | Objetivo entendible con alcance parcial | Idea ambigua o poco viable |
| Caso de uso | Flujo completo con entradas/salidas claras | Flujo básico con detalles faltantes | No define flujo útil |
| Estructura repo | Organización limpia y consistente | Organización aceptable con vacíos | Estructura confusa |
| Plan de pruebas | Casos bien definidos y medibles | Casos básicos sin criterios claros | Pruebas incompletas |
| Documentación | Clara, técnica y bien escrita | Entendible con errores menores | Desordenada o insuficiente |

---

## 9) Recomendaciones por lenguaje

### Si eliges ARM64 Assembly
- Limita la práctica a una sola función central.
- Usa entradas simples.
- Evita lógica extensa.

### Si eliges C
- Enfócate en manejo de archivos, argumentos de línea de comandos o procesamiento básico de texto.

### Si eliges Python
- Prioriza scripts de automatización local y utilidades de consola.

### Si eliges Bash
- Diseña flujos cortos de administración de archivos, monitoreo básico o validaciones simples.

---

## 10) Guía de inicio rápido para el estudiante
1. Define el tema y título de tu práctica.
2. Elige el lenguaje principal.
3. Crea la estructura mínima del repositorio.
4. Redacta primero los archivos en `docs/`.
5. Revisa que tu alcance sea pequeño y realista.
6. (Opcional) Implementa un prototipo mínimo en `src/`.
7. Verifica que tus casos de prueba sean ejecutables.

---

## 11) Checklist de entrega
Marca cada punto antes de entregar:

- [ ] Incluí `README.md` con resumen y objetivo.
- [ ] Documenté la propuesta en `docs/propuesta.md`.
- [ ] Documenté el caso de uso en `docs/caso_de_uso.md`.
- [ ] Expliqué la estructura del repositorio en `docs/estructura_repositorio.md`.
- [ ] Definí plan de pruebas en `docs/plan_de_pruebas.md`.
- [ ] El proyecto mantiene alcance pequeño y viable.
- [ ] No usé dependencias complejas ni servicios externos innecesarios.

---

## 12) Formato de entrega
- Publica tu propuesta en el repositorio asignado en GitHub Classroom.
- Asegúrate de que todos los archivos `.md` se visualicen correctamente.
- Cuida ortografía, claridad y consistencia técnica.
