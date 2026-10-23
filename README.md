# Observatorio institucional de materiales aprovechables — Fundación Ecopiensa Evolution

**Versión 1.2.0 | corte documental 23 de octubre de 2026 | Colombia / Valle del Cauca**

## Panel principal
Abra [index.html](./index.html). Para publicación como página web, configure **Settings → Pages → Deploy from a branch → main → /(root)** si GitHub Pages no estuviera activo.

![Logo oficial de la fundación](./logo%20ecopiensa%20%20traspaewncia.png)

## Datos auditables
- [Base de observaciones y costos](./datos/observaciones_precios_costos_2026.csv): 274 registros con su fuente, unidad y situación de verificación.
- [Precios regionales Valle del Cauca](./datos/precios_municipales_valle_2026.csv): 55 registros por municipio (con campos vacíos cuando no se halló un precio comparable).
- Catálogo de **171 materiales** incluido en el HTML: nombre, familia, composición, proceso, costos estimados, precio nacional histórico y referencias externas.
- Comparación de los documentos aportados por DeepSeek (**11 registros**) y Gemini (**43 registros**) identificados como estimaciones sin validación individual.
- Exportaciones CSV/JSON desde los botones en la misma página.

## Interpretación financiera
La columna de precio local es una observación puntual, **no tarifa nacional**. El precio de venta en ECA derivado de Acoplásticos es de **mayo de 2025**; no está actualizado automáticamente a octubre 2026. Las referencias internacionales corresponden a grados y mercados distintos; **no son cotizaciones FOB Buenaventura**. Los costos de transformación son **escenarios modelados sin cotización industrial comprobada**.

La tarifa regulada de aprovechamiento es **ingreso por servicio público** y no una tarifa de compra comercial por kilogramo. Antes de proyectar su reconocimiento se requiere comprobar requisitos CRA/SSPD/RUPS/SUI, prestación efectiva y las reglas de transición de la Resolución CRA 1040 de 2026.

## Investigación regional
La página distingue **Cali, Tuluá, Buga, Palmira, Cartago, Zarzal, Yumbo y Jamundí**. Algunas cifras de Tuluá proceden de un estudio de hace años y **no se presentan como vigentes**. Los avisos comerciales locales pueden cambiar sin previo aviso; no extrapolar las tarifas de Cali a municipios vecinos sin negociar directamente. Los campos vacíos se conservan para futuras cotizaciones.

## Registro de cambios
- **v1.2.0**: identidad institucional real, una tabla maestra empresarial, base de evidencia por observación, comparación Gemini/DeepSeek y precios separados por municipio del Valle del Cauca.
