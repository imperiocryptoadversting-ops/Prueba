## Identificacion del Cambio
- **Ticket CCB:** CCB-2026-XXX (Obligatorio)
- **Tipo:** [ ] Frontend/UI  [ ] Backend  [ ] BD  [ ] Infra  [ ] Documentacion
- **Justificacion de Negocio:**
  <!-- Vincular con prioridad operativa o SOW. Ej: "Mejora UX para KPIs diarios del cliente" -->

## Evaluacion de Impacto y Riesgo (Matriz CCB)
- **Alcance tecnico real:**
  <!-- Que archivos/logica se modifica. Ej: "Solo CSS/HTML, sin tocar PHP o BD" -->
- **Riesgo identificado:** [ ] Bajo  [ ] Medio  [ ] Alto  [ ] Critico
- **Mitigacion:** <!-- Si es Alto/Critico, describir plan de contingencia -->
- **Reversibilidad:** [ ] Git revert en <15min  [ ] Requiere rollback manual  [ ] Irreversible

## Checklist de Validacion Tecnica (CI/QA)
- [ ] Linting CSS/JS/PHP aprobado (sin warnings ni errores)
- [ ] Tests PHPUnit ejecutados con cobertura >=80% (si aplica backend)
- [ ] Responsividad validada en 3 breakpoints: 320px, 768px, 1280px
- [ ] No se modifica logica de negocio ni estructura de BD (salvo aprobacion explicita CCB)
- [ ] CHANGELOG.md actualizado con version y descripcion del cambio

## Aprobaciones Requeridas (Gobernanza)
- [ ] Revision de par (Dev) - Comentarios resueltos
- [ ] Visto bueno Arquitecto/QA - Validacion tecnica
- [ ] Aprobacion CCB - Solo para cambios de alcance, BD o criticos (adjuntar acta si aplica)

## Evidencias (Opcional pero recomendado)
- [ ] Capturas de pantalla del cambio UI
- [ ] Link a prueba de concepto o staging
- [ ] Reporte de cobertura de tests
