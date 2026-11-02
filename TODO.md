# Onda Frontera — Entregables

- [x] **Experiencia de radio online rediseñada**
  - Se conservaron los cuatro streams de audio existentes.
  - Se implementó un reproductor principal protagonista con selección y reproducción de las cuatro señales.
  - Se añadieron estados visibles de reproducción, pausa, conexión y error.
  - La señal principal usa su endpoint redirigible, evitando fijar un token temporal vencido.

- [x] **Identidad territorial de la Triple Frontera**
  - Se incorporó la portada local de Onda Frontera y el icono de marca desde archivos planos de la raíz.
  - Se añadió una capa de territorio e idioma para Paraguay, Brasil, Argentina, español, português y guaraní.
  - Se dejó preparado el recorrido editorial para futuras noticias, programas, agenda y contenidos bajo demanda.

- [x] **Campaña y contenidos comunitarios**
  - Se añadieron las tres piezas entregadas por el usuario como galería local, sin carpetas.
  - La galería está separada de auspiciantes y reproductor, con identificación explícita de contenido comunitario.
  - Cada imagen tiene nombre seguro para GitHub y texto alternativo descriptivo.

- [x] **Navegación, responsive y accesibilidad**
  - Se incorporaron accesos directos a escuchar, territorio, auspiciantes y campaña.
  - Se mantuvo el carrusel responsive de auspiciantes con sus destinos actuales.
  - Se optimizó la composición para teléfonos y escritorio; se conservaron foco visible, navegación por teclado, estados `aria-pressed`, `aria-live` y control de pausa del carrusel.

## Investigación aplicada

Se compararon iHeartRadio y NPR en Estados Unidos, BBC Sounds y Radio France en Europa, y China National Radio y Qingting FM en China. La primera fase aplicada toma de esas referencias el reproductor como puerta principal, la separación entre en vivo y contenido bajo demanda, el contexto territorial, los módulos editoriales pequeños y los metadatos mínimos. Se evita copiar su escala, sus promesas de app o una navegación saturada.
