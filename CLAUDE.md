# Castelli 97 — Propiedad única (alquiler)

Proyecto de Propietas Inmobiliaria. Hereda de `../CLAUDE.md`: datos de la firma, manual de marca y reglas generales. Acá solo lo específico.

## El proyecto
- **Qué es:** dúplex en alquiler, comercializado por Propietas Inmobiliaria. Ficha original: https://www.ipropietas.com.ar/listing_details_05/64bf98ef-0d70-4ba1-abce-2aff46b257ca
- **Ubicación:** Castelli 97, Rawson, Chubut
- **Oferta:** alquiler ARS 950.000 por mes · 3 ambientes · 2 dormitorios · 2 baños · antigüedad 20 años
- **Superficie:** 85 m² (confirmado por el corredor; la ficha web dice 75 m², está desactualizada).
- **Estado:** disponible
- **Ref:** LEGACY-6FF48C05
- **Requisitos de alquiler (de la ficha web):** DNI y recibo de sueldo de locatario y garante(s), antigüedad laboral mínima de 1 año; el garante no puede ser jubilado, ni cónyuge/pareja/conviviente del locatario, ni tener deuda por cuota alimentaria; el alquiler no puede superar el 30% de los ingresos netos mensuales del garante. Validar antes de publicar.
- **Contacto específico:** usa el WhatsApp de la firma (`https://wa.me/5492804503151`), con el mensaje precargado mencionando "Castelli 97".

## Identidad
- **Marca propia del desarrollo:** no. Usa solo la identidad de Propietas (azul `#2e3092` / celeste `#27aae1`, Montserrat).
- **Rol de Propietas:** comercializadora (logo en header/footer + pie legal)
- **Paleta / tipografía:** manual de marca; ver DESIGN.md cuando exista

## Técnico
- **Stack:** delegado → HTML/CSS estático (una sola propiedad, sin lógica)
- **Assets:** `assets/logos/` (copiados de `_shared`), `assets/img/castelli-01..12.jpg` (fotos originales de la ficha web de la firma, sin optimizar ni modificar; falta definir orden y `alt`)
- **Deploy:** PENDIENTE — publicar solo con confirmación del usuario

## Estado
- Sitio construido: `index.html` + `styles.css` (hero con fachada, datos, galería con snap, requisitos, cierre, pie legal, barra WhatsApp fija en celular). Patio incluido y 85 m² confirmados. Pet friendly NO (el corredor confirmó que no).
- Fotos 06 y 11 omitidas a propósito (ventana con vista a un muro quemado). `og.jpg` y `favicon.svg` generados.
- Fase 5 hecha en una pasada: `svh` en la galería, objetivos táctiles de 44px o más en header y pie, `color-scheme: light`, y un solo movimiento (revelado del hero, apagado con `prefers-reduced-motion`). `break-ui` no aplica (sin listados ni datos variables). Falta probar en celular real y el checklist de cierre completo (ver Pendientes).

## Contexto de diseño
- `PRODUCT.md` (impeccable init) y `DESIGN.md` (cuando exista) son la fuente de verdad visual y de producto.

## Pendientes
- Confirmar si el precio es fijo o hay ajuste/actualización, y si hay expensas, depósito o comisión (no inventar)
- Pie legal: validar con el corredor (requisitos ya confirmados)
- Optimizar fotos (peso, WebP/AVIF) y escribir `alt`
- Deploy y dominio
