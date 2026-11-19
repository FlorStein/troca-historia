# Troca — Contexto maestro del proyecto

## Producto

Troca es una membresía LATAM, inicialmente Argentina y Brasil, que combina intercambio de casas entre personas con beneficios en hoteles aliados. La propuesta busca viajes más cercanos, seguros y contextualizados.

## Decisiones cerradas

### Membresías

| Plan | Mensual | Anual | Alcance |
| --- | ---: | ---: | --- |
| Base | USD 6 | USD 39 | Sin casa: hoteles aliados, beneficios y comunidad. |
| Viajero | USD 12 | USD 79 | Con casa: intercambio y puntos. |
| Premium | USD 20 | A definir | Próximamente; sin checkout ni beneficios activos. |

### Puntos

- Modelo 1:1, sin decimales.
- Una noche alojada, cumplida y evaluada acredita 1 punto.
- Una noche solicitada consume 1 punto.
- Publicar o declarar disponibilidad no genera puntos.
- Vencen anualmente; no se transfieren ni se canjean por dinero.
- Plan Viajero pago + identidad verificada + propiedad aprobada: 3 puntos de bienvenida una sola vez.
- Cancelación tardía, menos de 15 días: -2 puntos.

### Seguridad

- Identidad, email, teléfono y domicilio verificados antes de publicar.
- Fotos obligatorias pre y post estadía.
- Depósito virtual durante el intercambio.
- Reviews mutuas ciegas.
- Dirección exacta sólo después de confirmar.
- Pagos, depósitos, cambios, mensajería e incidencias dentro de Troca.

### Partners / hoteles

- Fee mensual USD 50–150 según categoría.
- Upgrade opcional de placement patrocinado.
- Sin comisión por reserva.
- Partner carga hotel, habitaciones, fotos, promociones, disponibilidad y estadísticas.

### Post-MVP

- Vuelos completos, embajadores, Premium completo y proyecciones financieras detalladas no se implementan aún.

## Diseño

- Paleta: Linen `#FAEEE5`, Prussian `#18334B`, Hunter `#566746`, arena `#C9B79F`.
- Títulos: Fraunces / Playfair Display. UI: DM Sans, Inter o Plus Jakarta Sans.
- Estilo: editorial, cálido, contemporáneo y latinoamericano.
- Evitar tarjetas genéricas, marcos decorativos, fotos incongruentes y pitch vacío.
- Toda imagen debe corresponder al destino que nombra.

## Aplicaciones

### Troca usuarios

Inicio, casas, hoteles, promos, beneficios, favoritos, viajes, mensajes, perfil, propiedad, pagos, seguridad, FAQ y configuración deben ser navegables como mockup realista; no usar popups vacíos. Debe contemplar safe area de Android, back nativo, ES/PT y bot de ayuda.

### Troca Partners

Dashboard, hotel, habitaciones, carga de fotos, promociones, vista previa para miembros, estadísticas, mensajes, perfil y bot. Mantener logo y lenguaje propios de Partners.

## Sitios

- Web pública de usuarios: repositorio `FlorStein/Troca`.
- Web institucional: repositorio `FlorStein/troca-presentacion`.
- Historia experimental: repositorio `FlorStein/troca-historia`.

## Troca Historia: dirección correcta

No debe ser una landing tradicional con fotos flotantes. Debe ser *scrollytelling* inmersivo: el scroll equivale a viajar dentro de una escena con profundidad, aproximación, llegada, pausa de lectura y salida.

### Secuencia narrativa requerida

1. Despegue sobre Buenos Aires.
2. Vuelo continuo entre nubes reales/en movimiento.
3. Llegada estable a Buenos Aires, con Obelisco completo y reconocible.
4. Explicación pausada de origen de Troca, intercambio 1:1, confianza y comunidad.
5. Descenso hacia Río de Janeiro: costa, ciudad y geografía a pantalla completa, no tarjetas flotantes.
6. Llegada final: entrar a una casa luminosa frente a la playa, con mar visible desde una ventana.
7. Cierre: “Llegaste, trocaste” y CTA para explorar Troca.

### Criterios de calidad

- El texto debe alcanzar opacidad total y quedar nítido durante un tramo suficiente.
- Cada destino debe tener tiempo de lectura e imagen estable antes de la siguiente transición.
- Nada de cortes Buenos Aires → Río → casa como diapositivas.
- No usar cierre nevado: este recorrido termina en Río y playa.
- Aviones delicados y de trazo, no íconos grandes tipo juguete.
- Construir primero escenas legibles y luego sumar movimiento.

## Regla de trabajo

No declarar una iteración lista si no fue implementada, subida y verificable. Mantener este archivo actualizado ante cambios de lógica o dirección creativa.
