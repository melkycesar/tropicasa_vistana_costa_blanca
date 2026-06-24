# Design Log — Costa Blanca / Vistana Costa Blanca

Documento vivo de banco de conocimiento para **Claude Design** (o cualquier otra IA de diseño que reciba este repositorio). Registra las preferencias de diseño acordadas con el cliente y los errores ya corregidos, para no repetirlos en sesiones futuras.

**Antes de diseñar cualquier pieza, leer:** [`costa-blanca-investigacion-y-conclusiones.html`](costa-blanca-investigacion-y-conclusiones.html) (contexto del proyecto) y este documento (reglas de diseño y errores a evitar).

---

## 1. Reglas de diseño confirmadas

- **Jerarquía de marca:** Costa Blanca / Vistana Costa Blanca es siempre la marca protagonista de la pieza. El logo de Tropicasa (agencia comercializadora) va en segundo plano, en un chip o barra blanca pequeña — nunca del mismo tamaño ni más prominente que el logo del proyecto.
- **Logo de Tropicasa:** siempre sobre **fondo blanco**. Nunca colocarlo directo sobre una foto o render. Si la pieza tiene fondo de imagen, usar la variante blanca del logo o un chip/barra blanca debajo.
- **Colores de Tropicasa** (en orden de proporción de uso):
  1. `#EF6E21` — principal, usar en acentos/detalles, no para texto corrido.
  2. Blanco — fondo obligatorio del logo de Tropicasa, color dominante de soporte.
  3. `#6D6E71` — secundario, uso minoritario. Nunca debe competir con el naranja ni el blanco.
- **Datos de contacto correctos (usar siempre estos, no otros):**
  - Email: `tropicasa@gmail.com`
  - Teléfono: `+1 (829) 344-7291`
  - Web del proyecto: `costablanca.com.do`
- **Tagline oficial:** "Redescubre Boca Chica" / "Un destino legendario se transforma".
- **Valla de carretera:** fuera del alcance de este repositorio y de cualquier herramienta de IA — se produce de forma externa.
- **Tipología 1H:** está agotada. No usar fotos `CB_1H_*` en piezas con llamado de venta directo — solo como referencia visual de diseño interior si es necesario.

## 2. Errores ya cometidos y corregidos (no repetir)

| Error | Corrección | Contexto |
|---|---|---|
| Usar el email `info@costablanca.com.do` en CTAs | Usar siempre `tropicasa@gmail.com` — Tropicasa es quien paga y comercializa la campaña, no el desarrollador | Corregido en todo `costa-blanca-contenido.html` y `prompt-claude-design-completo.md` |
| Textos con jerga técnica de urbanismo ("plan maestro de uso mixto que habilita el desarrollo del destino") | Simplificar a lenguaje publicitario directo, fácil de entender a la primera lectura | Carrusel 1, slide 2 — ver registro de cambios abajo |
| Atribuir el respaldo institucional del plan maestro a Constructora Vistana | Separar claramente: el plan maestro lo respalda el Grupo Inicia/Estado; Constructora Vistana construye el producto residencial | Carrusel 3, slide 2 |
| Preguntas o frases ambiguas en ganchos de carrusel ("¿Cuál es tu Costa Blanca ideal?") | El gancho debe decir explícitamente de qué trata la pieza (en este caso, elegir tipología de apartamento) | Carrusel 2, slide 1 |

## 3. Registro de cambios

Agregar una fila nueva cada vez que se apruebe o ajuste una decisión de diseño relevante (no es necesario registrar cada iteración menor, solo decisiones que otra IA debería conocer para no repetir el error o desconocer la preferencia).

| Fecha | Pieza / archivo | Cambio | Motivo |
|---|---|---|---|
| 2026-06-24 | `costa-blanca-contenido.html` (carruseles 1, 2 y 3) | Se simplificó el lenguaje técnico, se corrigió la atribución del respaldo institucional vs. la constructora, y se aclaró el gancho del carrusel 2 | Los textos originales eran difíciles de interpretar para el público general |
