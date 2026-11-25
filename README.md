# Tema Hatsune Miku para Kino

Tema de app completo (apiVersion 26) inspirado en Hatsune Miku.

**Versión actual: 1.5.9** — necesita **Kino 0.9.87 o posterior**.

## Instalación

En Kino: **Ajustes ▸ Plugins** → escribe:

```
yumehotaru41-rgb/Kino-plugin-Theme-Hatsune-Miku
```

Luego ve a **Ajustes ▸ Apariencia** y elige **Hatsune Miku** o **Hatsune Miku (color)**.

Para personalizar: **Ajustes ▸ Apariencia ▸ Personalizar** (aparece solo cuando el tema está activo).

## Los dos temas

- **Hatsune Miku**: fondo de imagen (`assets/background.png`), oscurecido con `dim: 0.5` y color de respaldo.
- **Hatsune Miku (color)**: degradado azul-turquesa, sin depender de una imagen externa.
- Ambos conservan la paleta turquesa, los detalles rosas y el logo vectorial de Miku.

## Logo Miku

El logo vectorial personalizado se muestra en el menú, la cabecera y el riel de TV:

- Flequillo turquesa con una V central más definida.
- Coletas laterales y lazos rosas con formas más visibles.
- Ojos azules con destellos blancos adicionales.
- Rostro ovalado y texto **MIKU** en turquesa y blanco.
- El diseño se adapta a los dos temas y no necesita archivos de imagen ni descargas.

## Apariencia y selección

La versión 1.5.9 vuelve a la estructura de dibujo nativa de Kino para las tarjetas y los controles de selección:

- No declara superficies pintadas personalizadas (surfaces): Kino dibuja las tarjetas, sus estados normales y el foco con su renderizador original.
- Mantiene shape.cardBorder: 0, igual que los valores base del creador oficial de temas.
- Conserva la paleta turquesa y azul, los dos fondos y el logo vectorial de Miku.
- Conserva ambos temas y los ajustes de personalización compatibles.
- No fuerza bordes, rellenos ni halos sobre todas las tarjetas; el comportamiento de selección queda en manos de Kino.

Se priorizó la compatibilidad con la interfaz base sobre los efectos de superficie personalizados. Los colores y fondos Miku siguen aplicándose a toda la interfaz temática.

## Personalización disponible

En **Ajustes ▸ Apariencia ▸ Personalizar** puedes ajustar:

- Acento (turquesas, cianes, teales profundos, rosas y lila).
- Superficies, superficies elevadas, bordes y favoritos.
- Radios de tarjetas, botones, diálogos y chips.
- Escala general del texto y de los títulos.
- Tamaño de botones y barra del reproductor.
- Zoom de foco y sombra de tarjetas.
- Fondo, cuando el ajuste correspondiente está disponible.

## Tipografía y compatibilidad

El tema utiliza la tipografía nativa de Kino; no descarga ni declara fuentes externas. El manifiesto usa `apiVersion: 26` y requiere Kino 0.9.87 o posterior.

## Limitaciones de Kino

Algunas pantallas **nunca** toman el tema del plugin por diseño:

- Pantalla inicial y puerta de entrada de Kino.
- Diálogo de control parental / código +18.
- Hojas de consentimiento al instalar o actualizar plugins.
- Pantallas de bloqueo y de decisión crítica.
- Ajustes ▸ Apariencia y su vista previa.

## Autor

- **author**: Hotaru Yume
- **creator**: hotaruyume

## Compatibilidad de la interfaz (v1.5.9)

Se eliminaron las superficies pintadas personalizadas, los overrides de móvil/TV y las capas de estilo que podían interferir con la presentación de las tarjetas. La forma, tipografía, elevación, movimiento y controles vuelven a los valores base del creador oficial de Kino. Se mantienen los colores, fondos, logo y los dos identificadores de tema.
