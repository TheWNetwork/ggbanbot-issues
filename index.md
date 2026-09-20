---
layout: default
---

# Elsa - Global Banhammer

Elsa - Global Banhammer es un bot de Telegram que veta de forma global las cuentas que distribuyen Material de Abuso Sexual Infantil (CSAM).
Está destinado exclusivamente a sancionar a usuarios que deben quedar restringidos en la totalidad de grupos y canales de la red, por lo que no debe utilizarse para moderaciones específicas de un solo canal.

Contamos con dos cuentas oficiales: **@ggbanbot** y **@elsabanbot**.

## Qué veta, y qué no

El bot veta **únicamente** por Material de Abuso Sexual Infantil. No sanciona por spam, insultos, estafas, discusiones ni opiniones: los reportes por esos motivos se ignoran.

### La norma que aplicamos

El criterio es el **artículo 189.1.d del Código Penal español**, que tras la reforma de la Ley Orgánica 1/2015 tipifica la pornografía infantil virtual, pero exige que el material consista en:

> Imágenes realistas de un menor participando en una conducta sexualmente explícita o imágenes realistas de los órganos sexuales de un menor, con fines principalmente sexuales.

Para delimitar qué es una «imagen realista», la **Circular 2/2015 de la Fiscalía General del Estado** concluye:

> Por tanto, solo serán «imágenes realistas» potencialmente subsumibles en el concepto de pornografía infantil aquéllas que se aproximan en alto grado a la representación gráfica de un auténtico menor, o de sus órganos sexuales. Por ello, no deberán los Sres. Fiscales entender incluidos dibujos animados, manga o representaciones similares, pues no serían propiamente «imágenes realistas», en tanto no perseguirían ese acercamiento a la realidad.

La misma Circular precisa que las «imágenes realistas» «podrían abarcar imágenes alteradas de personas existentes e incluso las imágenes generadas mediante ordenadores».

Conforme al principio de unidad de actuación, las circulares de la Fiscalía General vinculan a los fiscales, de modo que ese criterio rige para toda la acusación pública en España.

**En la práctica, para este bot:**

- La ilustración de estilo manga, anime o cómic **no** es motivo de veto.
- **Sí** lo es el dibujo hiperrealista: el creado por ordenador, por inteligencia artificial o a mano con tal grado de detalle que se aproxima en alto grado a la representación gráfica de un menor real.
- **Sí** lo es el elaborado alterando la imagen de una persona existente, usando la cara o el cuerpo de un menor de edad real.

## Cómo funciona

Un modelo de inteligencia artificial analiza el texto de los mensajes de los grupos donde el bot está presente —incluidos los pies de foto y de vídeo— y las imágenes se comparan con ficheros que un moderador ya marcó.

**La IA nunca veta.** Cuando un mensaje resulta sospechoso, el bot puede silenciar a su autor durante una hora para frenar el daño y envía el caso a los moderadores humanos. La expulsión la decide siempre una persona, y cuando se decide vale en todos los grupos de la red a la vez.

El modelo se reentrena con mensajes reales etiquetados a mano por un grupo cerrado de revisores, bajo un criterio escrito y común.

## Reportes

Cualquier usuario puede reportar con `/new`. Los reportes de cuentas con una confianza baja se descartan automáticamente para evitar el uso del bot como herramienta de acoso.

- [Flujo de Reporte](report.md)
- [Política de Privacidad](privacidad.md)

[Invita al bot a tu grupo con este enlace](https://t.me/elsabanbot)

Para actuar, el bot necesita ser administrador con permiso para restringir miembros y borrar mensajes. Sin esos permisos solo puede observar.

### Aviso legal / Exención de responsabilidad
Elsa - Global Banhammer es un bot propiedad de [@TheWNetwork](https://t.me/TheWNetwork) y [Yuuu](https://yuuu.es)
TheWNetwork Telegram no tiene relación con wnetwork.com ni con Corus Entertainment.
