# Proyecto de Maquetación (HTML/CSS)

Este repositorio contiene múltiples páginas estáticas organizadas por carpeta numérica (`3`, `4`, `6`, `10`, etc.).
Cada carpeta representa una maqueta independiente.

## Objetivo del proyecto
- Reescribir y ajustar páginas HTML/CSS manteniendo la apariencia esperada.
- Respetar la estructura base por carpeta.
- Garantizar diseño responsivo sin romper el diseño original.

## Estructura
Cada carpeta sigue este patrón:

- `index.html`
- `CSS/style.css` o `CSS/styles.css`
- `media/` con imágenes de la maqueta

Ejemplo:

- `12/index.html`
- `12/CSS/styles.css`
- `12/media/*`

## Flujo de trabajo recomendado
1. Abrir la carpeta objetivo.
2. Revisar `index.html` y la hoja CSS asociada.
3. Confirmar nombre correcto del CSS (`style.css` vs `styles.css`).
4. Hacer cambios mínimos y controlados según el objetivo.
5. Verificar visualmente en desktop y móvil.
6. Entregar el código final para copiar/pegar.

## Reglas de edición
- No modificar carpetas ajenas a la solicitada.
- No renombrar archivos existentes.
- Mantener rutas relativas de imágenes y CSS.
- Si se pide “solo reescribir HTML”, no alterar estilos ni contenido.
- Si se pide ajuste visual, priorizar mantener el diseño original.
- Evitar agregar dependencias nuevas sin necesidad.

## Checklist por entrega
- `index.html` válido (estructura completa con `<!DOCTYPE html>`, `head`, `body`).
- `meta viewport` presente.
- Enlace a CSS correcto.
- Imágenes cargan con rutas válidas.
- No hay etiquetas rotas o mal cerradas.
- Layout funcional en:
  - escritorio (>= 1024px)
  - tablet (~768px)
  - móvil (<= 480px)

## Convenciones sugeridas
- Indentación: 2 espacios.
- Etiquetas en minúscula.
- Clases con convención consistente (ej. `bloque__elemento`).
- Mantener comentarios solo cuando aporten contexto real.

## Notas
- Algunas carpetas usan Google Fonts o íconos externos.
- Algunas maquetas dependen mucho de posicionamiento absoluto; validar superposiciones al ajustar responsive.
- Si el usuario comparte una referencia visual, adaptar proporciones y espaciados antes que cambiar concepto de diseño.

## Autor 
- Camilo Andres Garcia Almeida