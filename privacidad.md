---
layout: default
---

# Política de Privacidad del Sistema de Bots (@elsabanbot / @ggbanbot)

**Última actualización:** Septiembre de 2026

En cumplimiento del Reglamento (UE) 2016/679 General de Protección de Datos (**RGPD**), la Ley Orgánica 3/2018 (**LOPDGDD**) y la Ley 34/2002 (**LSSI-CE**), se informa a los usuarios y administradores sobre cómo el sistema de bots (**@elsabanbot** y **@ggbanbot**) recopila, trata y protege los datos en los chats donde están presentes.

---

## 1. Responsable del Tratamiento
* **Proyecto / Entidad:** Equipo de Desarrollo (*Elsa Security Project*)
* **Bots cubiertos:** @elsabanbot y @ggbanbot
* **Contacto de Privacidad:** `elsabot@proton.me`
* **Soporte en Telegram:** t.me/twn_supportbot

---

## 2. Marco Normativo Aplicable

Esta Política de Privacidad se rige formalmente por la legislación española y europea en materia de protección de datos y servicios digitales:
* **RGPD (UE) 2016/679:** Reglamento General de Protección de Datos de la Unión Europea.
* **LOPDGDD (Ley Orgánica 3/2018):** Ley Orgánica de Protección de Datos Personales y garantía de los derechos digitales (España).
* **LSSI-CE (Ley 34/2002):** Ley de Servicios de la Sociedad de la Información y de Comercio Electrónico (España).

El criterio material —qué contenido se persigue y cuál no— se rige además por:
* **Código Penal español, artículo 189.1.d**, en la redacción dada por la **Ley Orgánica 1/2015**: tipifica la pornografía infantil virtual y exige que se trate de «imágenes realistas».
* **Circular 2/2015 de la Fiscalía General del Estado**, sobre los delitos de pornografía infantil tras la reforma de la LO 1/2015: delimita qué se entiende por «imagen realista» y excluye expresamente los dibujos animados, el manga y representaciones similares.

---

## 3. Datos Recopilados y Finalidad del Tratamiento
Los bots **@elsabanbot** y **@ggbanbot** procesan de forma automatizada la actividad en los chats donde están presentes (texto de los mensajes y pies de foto y de vídeo, identificadores únicos de usuario y de grupo, alias, nombres de usuario y registros de sanciones) con una finalidad exclusiva:

**Detección y prevención de un delito grave:** identificar, bloquear y denunciar Material de Abuso Sexual Infantil (CSAM).

Los bots **no sancionan por spam, acoso, estafa ni por ningún otro motivo**. Los reportes ajenos a esa finalidad se descartan.

*Bajo ninguna circunstancia la información recopilada será comercializada, cedida o utilizada para el perfilado publicitario o comercial de usuarios o grupos.*

### 3.1. Criterio aplicado para identificar el material

A efectos de esta política, se considera CSAM lo que define el **artículo 189.1.d del Código Penal español** tras la Ley Orgánica 1/2015:

> Imágenes realistas de un menor participando en una conducta sexualmente explícita o imágenes realistas de los órganos sexuales de un menor, con fines principalmente sexuales.

La **Circular 2/2015 de la Fiscalía General del Estado** delimita ese concepto:

> Por tanto, solo serán «imágenes realistas» potencialmente subsumibles en el concepto de pornografía infantil aquéllas que se aproximan en alto grado a la representación gráfica de un auténtico menor, o de sus órganos sexuales. Por ello, no deberán los Sres. Fiscales entender incluidos dibujos animados, manga o representaciones similares, pues no serían propiamente «imágenes realistas», en tanto no perseguirían ese acercamiento a la realidad.

La misma Circular precisa que las imágenes realistas «podrían abarcar imágenes alteradas de personas existentes e incluso las imágenes generadas mediante ordenadores».

En consecuencia, la ilustración de estilo manga, anime o cómic **no** se trata como material ilícito. Sí se tratan como tales el dibujo que se aproxima en alto grado a la representación gráfica de un menor real —incluido el generado por ordenador o por inteligencia artificial— y el elaborado alterando la imagen de una persona existente.

---

## 4. Tratamientos Automatizados Concretos
1. **Clasificación del texto.** El texto de los mensajes se envía a un servicio de clasificación propio del proyecto, que le asigna una puntuación de riesgo. Ese servicio no comparte los datos con terceros ni los utiliza para ninguna otra finalidad.
2. **Comparación de imágenes y vídeos.** Los ficheros se comparan con material que un moderador marcó previamente. La comparación se realiza por identificador de fichero y, en el caso de cuentas nuevas o de baja confianza, calculando una huella digital del contenido. **El fichero no se conserva**: se descarga de forma transitoria para calcular esa huella y se descarta.
3. **Ninguna sanción es automática.** La puntuación del modelo puede provocar, como máximo, una restricción temporal de una hora. Toda expulsión es revisada y aprobada por una persona.

---

## 5. Revisión y Etiquetado Humano
Para mantener y mejorar el modelo de clasificación, un **grupo cerrado y designado de revisores** examina mensajes reales procedentes de los grupos protegidos y los etiqueta conforme a un criterio escrito.

* Los revisores acceden **únicamente al texto del mensaje** y a su fecha, nunca a la identidad de su autor.
* Los nombres de usuario, enlaces, teléfonos y direcciones de correo que aparezcan dentro del texto **se ocultan automáticamente** antes de mostrarlo.
* Los revisores están sujetos a deber de confidencialidad.

---

## 6. Conservación de Datos
* **Tratamiento habitual y registros de moderación:** Los mensajes se procesan para las labores de moderación y se conservan asociados al caso mientras sea necesario. Los registros de vetos (identificador de usuario y motivo) se conservan mientras sea necesario para la aplicación efectiva de la seguridad en los grupos.
* **Evidencias de delitos (CSAM):** El sistema **no almacena el material**. Se conservan los identificadores y las huellas digitales necesarios para reconocerlo si vuelve a aparecer, y la prueba se remite al canal interno de revisión durante el tiempo imprescindible para formalizar la denuncia ante las autoridades correspondientes.

---

## 7. Destinatarios de los Datos
Los datos no se compartirán con terceros, salvo en cumplimiento de una obligación legal o requerimiento judicial, siendo receptores únicamente:
* **Fuerzas y Cuerpos de Seguridad del Estado** (Policía Nacional / Guardia Civil en España) u organismos internacionales autorizados de protección al menor (ej. NCMEC / INHOPE).

---

## 8. Base Jurídica del Tratamiento
* **Interés Legítimo (Art. 6.1.f RGPD y LOPDGDD):** Preservar la seguridad, la administración técnica, el correcto funcionamiento y la protección de los miembros en los grupos de Telegram gestionados por los bots.
* **Interés Público Esencial y Obligación Legal (Art. 6.1.c y Art. 9.2.g RGPD / Art. 189 del Código Penal Español):** La prevención, detección y denuncia de delitos que atenten contra la protección de menores.

---

## 9. Derechos de los Usuarios y Autoridad de Control
Los usuarios pueden ejercer sus derechos de **Acceso, Rectificación, Supresión, Limitación y Oposición** dirigiendo una solicitud por correo electrónico a `elsabot@proton.me`.

* **Limitación por motivos legales y de seguridad:** El derecho de supresión u oposición podrá ser denegado cuando los datos sean necesarios para la investigación o denuncia de un delito, o para mantener la efectividad de las medidas de seguridad y vetos en la red de bots frente a conductas maliciosas reincidentes.
* **Reclamación ante la Autoridad de Control:** Si consideras que el tratamiento vulnera la normativa vigente, tienes derecho a presentar una reclamación ante la **Agencia Española de Protección de Datos (AEPD)** a través de su sede electrónica en [aepd.es](https://www.aepd.es).

---

## 10. Cambios en la Política de Privacidad
Esta política puede actualizarse periódicamente para reflejar ajustes técnicos, inclusión de nuevos bots del proyecto o cambios legislativos. Se recomienda su revisión regular.
