---
title: Omni Auth
permalink: /omni-auth/es/
---

[English](/omni-auth/) · **Español**

# Omni Auth

**Un autenticador rápido y privado para tus códigos de doble factor.**

Omni Auth genera los códigos de seis dígitos que protegen tus cuentas. Funciona totalmente sin
conexión, tus secretos se cifran en tu dispositivo y no hay ninguna cuenta que crear, porque no hay
ningún servidor donde crearla.

<img src="/omni-auth/img/es/01-vault.png" alt="La bóveda de Omni Auth con códigos en directo y anillos de cuenta atrás" width="270">
<img src="/omni-auth/img/es/04-security.png" alt="Ajustes de seguridad: bloqueo de la app, sincronización cifrada de extremo a extremo y kit de recuperación" width="270">

## Privacidad desde el diseño

- **No se recopila nada.** Sin analíticas, sin rastreo, sin publicidad, sin SDK de terceros.
- **Tus secretos se quedan en tu dispositivo**, cifrados con AES-256-GCM bajo una clave guardada en
  el llavero de iOS, además de la propia protección de datos del sistema.
- **La sincronización con iCloud es opcional y cifrada de extremo a extremo.** Solo se suben datos
  cifrados, a tu propia base de datos privada de iCloud. Ni Apple ni nosotros podemos leerlos.
- **Sin conexión de forma predeterminada.** La única otra petición de red es una comprobación de la
  precisión del reloj que inicias tú.

## Pensado para el día a día

- Toca un código para copiarlo. Lo copiado se queda en este dispositivo y caduca solo.
- Un anillo de cuenta atrás en cada cuenta, y el código siguiente aparece en los últimos segundos
  para que ninguno caduque a mitad de un inicio de sesión.
- **Widgets** para la pantalla de inicio y la pantalla bloqueada: en la pantalla bloqueada los
  códigos se ocultan, y un widget puede permanecer oculto hasta que lo toques.
- **Carpetas, etiquetas, favoritos**, búsqueda y orden manual o alfabético.
- Compatible con Siri y Atajos.

## Protección adicional cuando la quieras

- **Bloqueo de la app** con Face ID, Touch ID o tu código.
- **Face ID por cuenta**: marca una cuenta sensible y su código permanece oculto hasta que te
  autentiques. Esas cuentas nunca aparecen en widgets ni en Atajos.
- El contenido se difumina en el selector de apps y mientras se graba la pantalla, y se te avisa si
  se hace una captura.

## Mudarte es fácil

Importa desde **Google Authenticator**, **2FAS**, **Aegis**, **FreeOTP**, archivos CSV o una copia de
seguridad de Omni Auth, incluidos los archivos de 2FAS y Aegis protegidos con contraseña. Escanea un
código QR, elige uno de tus fotos, pega un enlace o escríbelo a mano.

Compatible con TOTP y HOTP, SHA-1/SHA-256/SHA-512 y códigos de 6 a 8 dígitos.

## Tú controlas la recuperación

Como no se guarda nada en ningún servidor, la recuperación depende de ti, así que Omni Auth te lo
pone fácil:

- **Copias de seguridad cifradas**, protegidas con una contraseña que solo tú conoces.
- Un **kit de recuperación** —una clave de recuperación más un archivo— que restaura tu bóveda en un
  dispositivo nuevo.

Si pierdes el dispositivo sin ninguno de los dos, nadie podrá recuperar los códigos, tampoco
nosotros. Esa contrapartida es lo que mantiene privado todo lo demás.

---

[Política de Privacidad](/omni-auth/es/privacy/) · [Términos de Uso](/omni-auth/es/terms/) ·
[Soporte](/omni-auth/es/support/)
