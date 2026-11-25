# Tema Hatsune Miku para Kino

Tema de app completo (apiVersion 26) inspirado en Hatsune Miku.

**Versión actual: 1.5.5** — necesita **Kino 0.9.87 o posterior**.

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
- Ambos conservan la paleta turquesa, los detalles rosas y las variantes de móvil y TV.

## Logo Miku

El logo vectorial personalizado se muestra en el menú, la cabecera y el riel de TV:

- Flequillo turquesa con una V central más definida.
- Coletas laterales y lazos rosas con formas más visibles.
- Ojos azules con destellos blancos adicionales.
- Rostro ovalado y texto **MIKU** en turquesa y blanco.
- El diseño se adapta a los dos temas y no necesita archivos de imagen ni descargas.

## Efectos visuales

- Brillo general sutil (`style.gloss: 0.36`).
- Botón principal con degradado turquesa y borde claro.
- Botones secundarios e iconos con superficies azul oscuro.
- Elemento de navegación inactivo con fondo y borde discretos; el elemento activo conserva su píldora turquesa y resplandor.
- Tarjetas normales sin contorno turquesa global; el borde de selección aparece únicamente en la tarjeta enfocada.
- Tarjetas enfocadas con contorno claro y halo más intenso; el marco se desplaza al cambiar el foco.
- Anillo de foco visible, especialmente útil al navegar con control remoto.
- Héroe enmarcado y riel flotante en TV.

Los efectos son complementarios: el tema conserva sus colores, contraste y estructura aunque se apaguen los brillos, degradados, contornos o capas desde **Ajustes ▸ Experiencia visual ▸ Personalizar uno por uno**. Los interruptores del dispositivo siempre tienen prioridad.

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
