# Tropicasa × Vistana Costa Blanca — Campaña publicitaria

Repositorio de contenidos, assets y documentación de la campaña publicitaria de **Vistana Costa Blanca** (Boca Chica, República Dominicana), comercializada por **Tropicasa**.

## Qué hay aquí

Este repositorio centraliza todo lo necesario para producir las piezas de la campaña (valla de carretera, posts, carruseles e historias): la investigación de mercado, los textos exactos por pieza, el banco de imágenes/logos, y los prompts usados para generar diseños con IA.

## Estructura

```
docs/
├── costa-blanca-investigacion-y-conclusiones.html     # Documento maestro: investigación, diferenciadores y conclusiones (LEER PRIMERO)
├── costa-blanca-contenido.html         # Textos exactos: 1 valla + 5 posts + 3 carruseles + 5 historias
├── costa-blanca-banco-imagenes.html    # Catálogo de todas las fotos, planos, zonificación y logos disponibles
└── prompt-claude-design-completo.md    # Prompt autocontenido para generar diseños con Claude Design

assets/
├── fotos/         # Fotos y renders del proyecto (CB_*.jpg, CB_MASTER.jpg, etc.)
├── floor_plans/   # Plantas arquitectónicas de los apartamentos (Asset *.png)
├── areas/         # Zonificación del master plan por uso de suelo (master_plan_area_resaltada_*.png)
└── logos/
    ├── logo_costa_blanca_proyecto_completo/  # Logo del proyecto (color, blanco, blanco con sombra)
    ├── logo_vistana_costa_blanca/             # Logo del producto residencial (default, letras blancas)
    └── logo_tropicasa/                        # Logo de la agencia (color, blanco)
```

## Por dónde empezar

Si eres una IA (Claude Code, Claude Design, u otra) retomando este proyecto, lee en este orden:

1. `docs/costa-blanca-investigacion-y-conclusiones.html` — contexto completo del proyecto, diferenciadores frente a la competencia, y los caveats de lo que NO está confirmado.
2. `docs/costa-blanca-banco-imagenes.html` — qué imagen/logo usar para cada propósito.
3. `docs/costa-blanca-contenido.html` — el texto exacto que va en cada pieza.

## El diferenciador central de la campaña

Costa Blanca no es un edificio aislado: es un plan maestro de uso mixto de +600,000 m², respaldado por el Grupo Inicia y un plan de Estado de más de US$530 millones. La estrategia de comunicación compite en **escala de ciudad y respaldo institucional** — no en "vista al mar" ni "amenidades", terreno donde la competencia directa (Vista Marina, Oceanic, Aquarena) ya está mejor posicionada.

**Eslogan en uso:** "Redescubre Boca Chica. Antes que todos."

## Datos de contacto (usar en todo el material publicitario)

| Dato | Valor |
|---|---|
| Email (Tropicasa) | tropicasa@gmail.com |
| Teléfono (Tropicasa) | +1 (829) 344-7291 |
| Web del proyecto | costablanca.com.do |

## Reglas de marca

- **Jerarquía:** Costa Blanca/Vistana es siempre la marca protagonista. El logo de Tropicasa va en un chip blanco pequeño, nunca compitiendo en tamaño, y nunca directo sobre una foto.
- **Colores de Tropicasa:** `#EF6E21` (principal) · Blanco (fondo obligatorio del logo) · `#6D6E71` (secundario, uso minoritario).

## Disponibilidad del inventario (corte 20/06/2026)

144 unidades totales en edificios B, C y D → **24 disponibles (17%)** / 120 reservadas. Tipología 1H agotada. 2H: 16 disponibles desde US$166,016. 3H: 8 disponibles desde US$209,995. El Edificio D tiene el mayor inventario disponible.

## Diseños ya aprobados

- **Valla de carretera (12x8 pies):** archivo fuente editable en `assets/fotos/FOTO VALLA.psd`.

## Flujo de trabajo

- Los cambios de contenido/estrategia se discuten y redactan en conversación con Claude (chat).
- Los diseños visuales se generan en **Claude Design**, importando este repositorio como fuente de imágenes/logos (Import → From GitHub).
- Los commits y el push a este repositorio los gestiona **Claude Code**, conectado localmente con acceso de escritura a GitHub.
