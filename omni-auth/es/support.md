---
title: Soporte
permalink: /omni-auth/es/support/
---

[English](/omni-auth/support/) · **Español**

# Soporte

## Cómo conseguir ayuda

Escribe a **[thepod32g@gmail.com](mailto:thepod32g@gmail.com?subject=Omni%20Auth%20Support)**.

Ayuda mucho que incluyas tu versión de iOS, el modelo de tu dispositivo, la versión de la app
(Ajustes ▸ Información ▸ Versión) y qué estabas haciendo cuando ocurrió el problema. **Nunca
incluyas un secreto de doble factor, un código QR, un archivo de copia de seguridad ni una clave de
recuperación** en una solicitud de soporte: cualquiera que los vea podrá generar tus códigos.

## Preguntas frecuentes

### Mis códigos son rechazados

Casi siempre es un problema de reloj: los códigos basados en tiempo se derivan de la hora actual, así
que un reloj desajustado en más de unos 30 segundos genera códigos que el servidor no acepta. En Omni
Auth, abre **Ajustes ▸ Comprobar la precisión del reloj**. Si informa de un desfase importante,
corrígelo en la app Ajustes del sistema, en **General ▸ Fecha y hora** (normalmente basta con activar
«Ajuste automático»).

### Tengo un móvil nuevo, ¿cómo llevo mis cuentas?

Dos opciones, ambas que hay que configurar *antes* de perder el acceso al dispositivo anterior:

- **Sincronización con iCloud** (Ajustes ▸ Sincronización con iCloud). Requiere un kit de
  recuperación, porque tus datos están cifrados de extremo a extremo y el dispositivo nuevo necesita
  tu clave para leerlos.
- **Copia de seguridad cifrada** (Ajustes ▸ Copia de seguridad ▸ Exportar copia cifrada). Guarda el
  archivo en un lugar seguro y recuerda la contraseña.

### Perdí mi dispositivo y no tenía copia de seguridad

Lo sentimos: los códigos no se pueden recuperar. Omni Auth guarda los secretos solo en tu dispositivo
y nosotros no tenemos ninguna copia. Tendrás que usar el proceso de recuperación de cuenta de cada
servicio (para eso sirven los códigos de recuperación que te dan al configurarlo) y volver a
registrar la autenticación de doble factor.

### ¿Qué es un kit de recuperación?

Una clave de recuperación (que se muestra una sola vez) más un archivo del kit de recuperación.
Juntos permiten que un dispositivo nuevo descifre tu bóveda sincronizada. Hacen falta los dos, y
ninguno se puede recuperar por ti: guárdalos separados de tu dispositivo.

### ¿Puedo importar desde otro autenticador?

Sí: Google Authenticator (exportación por QR), 2FAS, Aegis, FreeOTP, CSV y copias de seguridad de
Omni Auth, incluidos los archivos de 2FAS y Aegis protegidos con contraseña. Microsoft Authenticator
no se puede importar porque no permite exportar los secretos; tendrás que volver a registrar esas
cuentas.

### ¿Por qué mi widget no muestra ningún código?

Los widgets nunca muestran, de forma deliberada, las cuentas que has marcado con **Exigir Face ID
para mostrar**, y ocultan los códigos en la pantalla bloqueada. Las cuentas basadas en contador
(HOTP) no están disponibles en widgets porque un widget no puede avanzar el contador.
