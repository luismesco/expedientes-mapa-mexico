# Expedientes — Mapa de México

Sección Expedientes del Sistema Digital de la Dirección Jurídica de
Fiscalización (DJF): mapa interactivo de México con las 32 entidades
federativas. Al elegir una entidad se abre su ficha con botón
«Volver al mapa» y cinco accesos, en este orden:

1. **Errores y Omisiones** — Oficios, observaciones y respuestas
   vinculados a los expedientes de la entidad.
2. **Normatividad** — Leyes, reglamentos, lineamientos y acuerdos
   aplicables, con enlaces a sus fuentes.
3. **OPLE** — Nombre del instituto electoral y enlaces a sus
   publicaciones, acuerdos y estrados.
4. **Topes de campaña** — Acuerdos y montos por proceso, cargo y
   demarcación, proceso 2026–2027.
5. **Expedientes** — Sentencias y jurisprudencia filtradas a la
   entidad, con búsqueda por folio.

## Uso

Abrir `index.html` en el navegador. Página estática, sin servidor:
el mapa, los datos y los estilos van incrustados en el mismo archivo.
Todos los enlaces a documentos abren en pestaña nueva.

## Fuentes de los enlaces

- **Acervo electoral organizado** (Drive):
  `https://drive.google.com/drive/folders/1mOoV3PmfIzDbmzyqqnctWS16qi3LDQES`
  — 01 Sentencias federales, 02 Sentencias locales 2023–2026,
  03 Sentencias locales 2014–2022, 04 Normativa federal,
  05 Normativa local, 06 Jurisprudencia electoral,
  07 Informes e inventarios, 08 Publicaciones de los 32 OPLE,
  09 Diario Oficial de la Federación — materia electoral,
  10 Incorporaciones verificadas.
  Los enlaces están desglosados por entidad y por año.
  Inventario verificado en `docs/inventario_acervo.md` y desglose
  anual de sentencias en `docs/anos_sentencias_02_03_01.json`.
- **Topes de gastos de precampaña — OPLE 2026–2027** (Drive):
  `https://drive.google.com/drive/folders/1dUjol_T11rON3SvEY2ONiUUBYLNl8hz1`
  — 22 de 32 entidades con acuerdo, 29 PDFs. Inventario en
  `docs/inventario_topes_2026-2027.md`. Los topes no están dentro
  del Acervo; viven en su carpeta propia.
- Tope federal verificado: INE/CG660/2026, diputaciones federales
  de mayoría relativa — precampaña $440,652 MXN, campaña
  $2,491,466 MXN. Los montos locales por cargo están pendientes de
  extracción y verificación en cada PDF oficial.

## Advertencias

- En el Acervo no hay carpeta de Errores y Omisiones; la ficha lo
  indica y enlaza a la raíz del Acervo y a 07 Informes e
  inventarios, sin inventar carpetas.
- En sentencias locales faltan carpetas por entidad: 6 en
  02 (2023–2026) y 8 en 03 (2014–2022). La ficha dice «sin carpeta»
  donde no existe.
- En el DOF faltan carpetas de año: 1983, 1995, 1997–2006 y
  2021–2023.
- Esta sección es una pieza lista para integrar a la plataforma DJF
  (`luismesco/djf-plataforma`); por sí sola no está desplegada en
  producción ni sustituye el sistema.

## Estilo

Idéntico al sistema DJF (MorenAI): vino `#6d1738`, línea `#e7dfe3`,
fondos `#f7f3f5` / `#f1ecef`, dorado `#b49b63`, tipografía Montserrat,
contenedor de 1260 px.

Autor: Luis Montañez Escobar.
