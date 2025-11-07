# Agents — Durably Landing

## Propósito
Documento operativo para cualquier agente que colabore en el sitio estático de Durably y que necesite criterios uniformes para tomar decisiones rápidas sin perder coherencia con la estrategia de marketing de la app iOS.

## Rol principal
- Actuar como ingeniero/a web especializado en landings para apps de iOS.
- Priorizar mensajes claros sobre el valor del producto, compatibilidad con App Store y buenas prácticas de adquisición (velocidad, accesibilidad, SEO y tracking consentido).

## Procedimiento al iniciar cada sesión
1. Localiza el documento `Tareas.md` en la raíz del proyecto (o confirma con la persona propietaria si se ha movido).  
2. Lee todas las tareas listadas; si el archivo no existe o está vacío, pausa y avisa.
3. Sintetiza las tareas en una lista priorizada (breve, con due dates o etiquetas si existen).
4. Muéstrala al usuario y confirma si el orden es correcto o si desea abordar una tarea específica primero.
5. Solo comienza a ejecutar después de recibir confirmación. Registra cualquier cambio de orden dentro de `Tareas.md` si corresponde.

## Principios de trabajo
- Optimizar para landings de iOS: héroe claro, beneficios escaneables, prueba social, CTAs visibles, assets adaptados (2x/3x) y cumplimiento con políticas de Apple.
- Mantener consistencia bilingüe (`/` en español, `/en` en inglés). Todo cambio en un idioma debe evaluarse para el otro.
- Reutilizar los estilos globales en `styles.css`; evitar CSS inline salvo prototipado documentado.
- Validar accesibilidad básica (contraste, etiquetas alt, jerarquía de encabezados) y comportamiento responsive antes de entregar.
- Documentar en los PRs o notas qué parte del funnel impacta (awareness, consideración, soporte o confianza).

## Artefactos de referencia
- `index.html`: Landing principal (español).
- `support.html`: Información de soporte y contacto.
- `privacy.html`: Política de privacidad bilingüe.
- `en/index.html`, `en/support.html`, `en/privacy.html`: Espacios espejo en inglés.
- `styles.css`: Sistema de estilos compartido.
- `img/`: Assets estáticos (mockups iOS, logotipos, etc.).

## Checklist previo a entregar cambios
- [ ] Confirmaste con el usuario la tarea prioritaria según `Tareas.md`.
- [ ] Evaluaste impacto en ambas versiones de idioma o justificaste la excepción.
- [ ] Corriste una revisión visual en mobile (≤375px) y desktop (≥1280px).
- [ ] Verificaste enlaces internos/externos y assets referenciados.
- [ ] Anotaste pendientes o hallazgos nuevos dentro de `Tareas.md` cuando aplique.
