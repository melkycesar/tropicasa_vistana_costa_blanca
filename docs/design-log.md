# Design Log — Diseños Tropicasa Costa Blanca

Banco de conocimiento de diseño. Cualquier IA o diseñador que trabaje en estas piezas
debe leer este archivo **antes** de empezar, junto con
`docs/costa-blanca-investigacion-y-conclusiones.html` (reglas de marca) y
`docs/costa-blanca-contenido.html` (textos oficiales / fuente de verdad para el copy).

---

## Reglas de diseño confirmadas

### Marca y logos
- **Vistana Costa Blanca** es la marca protagonista (el proyecto). **Tropicasa** es la agencia
  que comercializa: su logo va en un chip/pestaña blanca y **nunca** más grande que el de Vistana.
- **Portada de los carruseles** (y piezas tipo portada): diseño *hero* — foto a sangre + claim.
  El logo de **Vistana Costa Blanca en modo default (a color)** va dentro de una **pestaña blanca**
  redondeada en la esquina superior izquierda (nunca el logo suelto sobre la foto).
- **Logo de Tropicasa + chip web `CostaBlanca.COM.DO`**: solo en la **portada** y en la
  **última página (contacto)** de cada carrusel. **No** se repiten en las páginas interiores.
- **Header de las páginas interiores**: el logo es **Tropicasa** — versión *default* (a color)
  sobre fondos claros, versión *blanca* sobre fondos de color. En la página de **contacto** el
  header es **Vistana Costa Blanca**.
- Existen dos versiones de cada logo (default a color / letras blancas). Elegir según el fondo.
- Fuente oficial de logos: repositorio GitHub `melkycesar/tropicasa_vistana_costa_blanca`
  (`assets/logos/...`). Usar de aquí en adelante los recursos del repo.

### Color
- **Naranja Tropicasa `#EF6E21`** = acento protagonista.
- **Gris `#6D6E71`** = secundario (chip de marca, etiquetas sobre claro).
- **No usar fondos grises**, ni siquiera claros (se eliminó el `#d6d7d7`). Fondos permitidos en
  interiores: blanco, crema (`#f4f2ee`) y naranja.
- En slides de **fondo claro (blanco/crema)**: los **títulos van en naranja** y las **etiquetas
  (eyebrow) en gris**. Sobre fondo naranja, el título va en blanco.
- **Banda decorativa naranja**: rectángulo que sube desde el borde inferior hasta ~1/3 de la
  altura del slide, para dar variedad. Se coloca solo donde **no quede debajo de los textos**
  (funciona en los layouts `feature` y `stat`; no en `split`, `plano` ni `contact`).

### Composición / layouts
- **Las páginas interiores NO deben repetir el diseño de la portada.** Es mala práctica que todos
  los slides luzcan iguales. Usar variedad de layouts: `split`, `feature`, `stat`, `plano`, `contact`.
- Header (logo + contador) constante en todos los slides para que el carrusel se sienta una familia;
  lo que cambia es la composición del cuerpo.
- **Floor plans**: imagen grande y centrada, a ancho completo. La ficha de distribución
  (m² · habitaciones · baños · disponibles) va **horizontal debajo** del plano, nunca a un lado
  (no robarle ancho al plano).
- El **nombre distintivo** del apartamento (**Apartamento 1H / 2H / 3H**) va como título del slide
  de plano. No usar "Distribución" ni "Tipología" como encabezado.
- En interiores los **títulos y textos van centrados**, **excepto** el layout de **dos columnas
  (`feature`)**, que va **justificado a la izquierda**.
- El **marco** decorativo de la portada: las líneas bajan hasta el **borde inferior de la foto**.

### Tipografía
- Familia **Montserrat** en todo.
- Las **cifras grandes** (stat: 83%, +20, etc.) usan peso **semibold (600)**, no extra-bold:
  a la dueña de Tropicasa no le gustan las letras demasiado *bold* en tamaños grandes.
- Textos de apoyo legibles para público mayor (subtítulos ~38px).
- Usar siempre los **textos literales** del documento de contenidos del repo.

### Datos de contacto
- Correo: **tropicasa@gmail.com** (sustituye a `info@costablanca.com.do`).
- Web: **costablanca.com.do** · Tel: **+1 (829) 344-7291**.

### Contenido / copy — feedback directo de Loli (dueña de Tropicasa)
- **Carruseles cortos:** entre **3 y 4 slides**, nunca más de 4. Los clientes de bienes raíces no
  leen mucho ni completan carruseles largos.
- **Las amenidades venden más que el discurso de "ciudad/plan maestro".** Loli pidió que el
  contenido se dirija **primordialmente** a destacar amenidades concretas, porque es lo que
  más motiva a los clientes:
  - Piscina
  - Cancha de tenis
  - Cancha de baloncesto
  - Proyecto cerrado (seguridad/acceso controlado)
  - Áreas recreativas para niños
  - Estar a 10 minutos de la playa
- **Nota de tensión con la estrategia original:** la investigación inicial (ver
  `costa-blanca-investigacion-y-conclusiones.html`, sección "Diferenciador") recomendaba NO competir
  en amenidades porque ahí Costa Blanca pierde frente a Oceanic/Vista Marina, y enfocarse en escala
  de ciudad y respaldo institucional. El feedback de Loli, como dueña del cliente que paga la
  campaña, tiene prioridad sobre esa hipótesis estratégica: el copy debe liderar con amenidades
  concretas y mantener los carruseles cortos (3–4 slides). El mensaje de "ciudad/plan maestro" puede
  seguir usándose, pero como apoyo secundario, no como gancho principal.

---

## Errores ya cometidos y corregidos (no repetir)

- **Aplanar todos los slides al diseño de portada** (todos iguales). → Se restauró el sistema de
  layouts variados; la portada es la única *hero*.
- **Repetir el logo de Tropicasa y el chip web en las páginas interiores.** → Se movieron a la
  portada y la última página únicamente.
- **Parafrasear el copy / convertirlo en cifra** (p. ej. el slide 3 del Carrusel 1 se reescribió
  como "US$530M" en vez de la frase del documento). → Usar siempre el texto **literal** del
  documento de contenidos.
- **Centrar el layout de dos columnas (`feature`).** → Ese layout va justificado a la izquierda.
- **Usar fondos grises** (incluido el gris claro `#d6d7d7`). → Eliminados.
- **Poner el logo suelto sobre la foto** en la portada. → Va dentro de la pestaña blanca.

---

## Registro de cambios

| Fecha | Pieza / archivo | Qué cambió | Por qué |
|---|---|---|---|
| 2026-06-24 | 03 Carruseles / CBInterior | Las páginas interiores dejan de copiar la portada; se crean layouts variados (split, feature, stat, plano, contact). | Evitar que todos los slides luzcan iguales (mala práctica). |
| 2026-06-24 | 03 Carruseles / CBInterior | Logo Tropicasa + chip web solo en portada y última página; se quitan de los interiores. | Reducir repetición y ganar espacio para el plano y la información. |
| 2026-06-24 | CBInterior (plano) | La ficha de distribución pasa a horizontal debajo del plano. | Que el plano crezca y no le roben ancho. |
| 2026-06-24 | Todas las piezas | Correo `info@costablanca.com.do` → `tropicasa@gmail.com`. | Indicación del cliente. |
| 2026-06-24 | CBInterior (plano) | El encabezado del plano usa el nombre distintivo (Apartamento 1H/2H/3H); se quita "Distribución" y "Tipología". | El nombre del tipo es la referencia real. |
| 2026-06-24 | CBSlide (portada) | Logo Vistana Costa Blanca en pestaña blanca (modo color) en la esquina superior izquierda; las líneas del marco bajan hasta el borde de la foto. | Alinear con la referencia de marca. |
| 2026-06-24 | CBInterior | Fondos negros → grises y luego eliminados por completo; nuevo fondo de variedad es la banda naranja inferior. | El cliente no quiere fondos grises. |
| 2026-06-24 | CBInterior (stat) | Cifras grandes a peso semibold (600). | A la dueña no le gustan las letras demasiado bold en tamaños grandes. |
| 2026-06-24 | CBInterior | Subtítulos y textos de apoyo agrandados (~38px). | Legibilidad para clientes de mayor edad. |
| 2026-06-24 | CBInterior | Títulos y textos centrados; el layout de dos columnas (feature) se mantiene a la izquierda. | Indicación de composición del cliente. |
| 2026-06-24 | CBInterior | Fondo claro: títulos en naranja y etiquetas en gris; banda decorativa naranja inferior (~1/3) en feature/stat. | Reglas nuevas de color y variedad. |
| 2026-06-24 | Logos | Se adoptan los logos de Vistana Costa Blanca del repositorio GitHub como fuente oficial. | Centralizar recursos de marca. |
| 2026-06-25 | Estrategia de contenido (todos los carruseles) | Carruseles deben tener 3–4 slides máximo (nunca más); el copy debe destacar amenidades concretas (piscina, cancha de tenis, cancha de baloncesto, proyecto cerrado, áreas para niños, 10 min de la playa) como gancho principal. | Feedback directo de Loli (dueña de Tropicasa) tras revisar los carruseles y posts: los clientes de bienes raíces no leen mucho y responden mejor a amenidades concretas que al discurso de "ciudad/plan maestro". |
