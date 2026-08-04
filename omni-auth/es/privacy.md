---
title: Política de Privacidad
permalink: /omni-auth/es/privacy/
---

[English](/omni-auth/privacy/) · **Español**

# Política de Privacidad

**Última actualización: 3 de agosto de 2026**

Omni Auth es una app de autenticación que funciona sin conexión. **No recopilamos, transmitimos,
vendemos ni compartimos ningún dato personal.** No hay ninguna cuenta que crear, ni analíticas, ni
publicidad, ni rastreo, ni SDK de terceros en la app.

## Qué guarda Omni Auth

Todo lo que Omni Auth guarda está **en tu dispositivo**:

- Los secretos de doble factor que añades, junto con sus nombres de emisor y de cuenta, iconos,
  colores, carpetas y etiquetas.
- Tus ajustes (preferencia de bloqueo de la app, retardo del bloqueo automático, orden de la lista).

Tus secretos de doble factor se cifran con **AES-256-GCM** bajo una clave guardada en el llavero del
dispositivo, además de la propia protección de datos del sistema operativo. No tenemos servidor, ni
copia de tus datos, ni forma de recuperarlos por ti.

## Qué sale de tu dispositivo

Omni Auth solo hace peticiones de red en dos situaciones, ambas opcionales y ambas desactivadas de
forma predeterminada:

**1. Sincronización con iCloud (opcional).** Si activas la sincronización con iCloud, tus cuentas se
cifran **en tu dispositivo** y solo se sube el resultado cifrado a *tu propia base de datos privada
de iCloud*. Nosotros nunca lo recibimos. Apple almacena el bloque cifrado pero no puede leer su
contenido; Apple sí puede ver metadatos técnicos, como cuándo se modificó un registro por última
vez. De la sincronización se encarga CloudKit, de Apple, y está sujeta a la
[Política de Privacidad de Apple](https://www.apple.com/legal/privacy/). Puedes desactivar la
sincronización cuando quieras en los ajustes, y eliminar los datos guardados de tu cuenta de iCloud.

**2. Comprobación de la precisión del reloj (opcional y manual).** Los códigos basados en tiempo
solo funcionan si el reloj de tu dispositivo es correcto. Si tocas **Comprobar la precisión del
reloj** en los ajustes, la app hace una única petición `HEAD` a `https://www.apple.com` y lee
únicamente la cabecera `Date` de la respuesta para compararla con el reloj de tu dispositivo. No se
envía ningún dato personal, identificador ni información de cuenta, y no se guarda nada. Esto ocurre
solo cuando tocas el botón.

Aparte de esto, Omni Auth funciona totalmente sin conexión.

## Cámara y fotos

- La **cámara** se usa únicamente para escanear códigos QR cuando añades una cuenta. Los fotogramas
  se procesan en tu dispositivo y nunca se guardan ni se transmiten.
- Solo se accede a **Fotos** cuando eliges tú una imagen para escanear un código QR desde ella. La
  imagen se descodifica en tu dispositivo y no se guarda ni se transmite.

## Portapapeles

Cuando copias un código, se coloca únicamente en el portapapeles local de tu dispositivo: está
marcado para que no se sincronice con tus otros dispositivos mediante el Portapapeles Universal, y
caduca automáticamente.

## Conservación y eliminación de datos

Como tus datos se guardan solo en tu dispositivo, eliminar la app los elimina. También puedes
eliminar cuentas concretas dentro de la app, y borrar los datos sincronizados de tu cuenta de iCloud
cuando quieras. Por nuestra parte no hay nada que eliminar.

## Menores

Omni Auth es una utilidad de seguridad de uso general y no está dirigida a menores. No recopila
datos personales de nadie, tampoco de menores.

## Cambios en esta política

Si esta política cambia, la versión actualizada se publicará en esta página con una nueva fecha de
«Última actualización».

## Contacto

Preguntas sobre esta política: **[thepod32g@gmail.com](mailto:thepod32g@gmail.com?subject=Omni%20Auth%20Privacy)**

---

Esta es una traducción de cortesía. En caso de discrepancia, prevalece la
[versión en inglés](/omni-auth/privacy/).
