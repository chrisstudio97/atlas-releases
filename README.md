# Atlas

**Repositorio oficial de distribución de APKs de Android**

Este espacio centraliza las versiones publicadas de la aplicación Atlas para Android, de forma que cada release quede versionado, trazable y fácil de descargar.

---

## Propósito

Atlas se distribuye fuera de las tiendas tradicionales. Este repositorio actúa como canal de entrega para:

- Publicar builds firmados de producción
- Conservar el historial de versiones
- Facilitar la instalación directa en dispositivos Android

---

## Releases

Las APKs se publican como [**GitHub Releases**](../../releases).

| Acción | Cómo |
| --- | --- |
| Ver la última versión | Abre la release marcada como *Latest* |
| Descargar la APK | Usa el asset `.apk` adjunto a la release |
| Revisar cambios | Consulta las notas de la release correspondiente |

> **Recomendación:** descarga siempre desde la release oficial más reciente.

---

## Versiones

<!-- releases:start -->
## Versiones

### v1.0.7 · 2026-11-21
- El Historial ahora muestra las transferencias USDT on-chain de tu wallet, cargadas por páginas para que la app siga rápida.
- Cada transferencia está etiquetada: pagos de órdenes, recibidos de wallets externas y envíos.
- Toca una transferencia para ver el detalle: monto, estado, fecha, bloque, hash, contraparte y enlace al explorer. En los pagos de órdenes también puedes abrir el detalle del pago.
- Se corrigió el loading infinito del Historial y se mantienen los filtros Todas, Recibidas y Enviadas, con estado vacío cuando no hay resultados.

[Descargar APK](https://github.com/chrisstudio97/atlas-releases/releases/tag/v1.0.7)

### v1.0.6 · 2026-11-20
- Corregida la subida de documentos KYC en conexiones lentas: el tiempo máximo de subida ya no corta el archivo a los 12 segundos.
- Las fotos de identidad y selfie se optimizan más (máximo 1600 px y ~1.5 MB) para que suban más rápido.
- Si una subida se interrumpe, la app muestra un mensaje claro y puedes reintentar sin volver a subir los documentos que ya se enviaron.

[Descargar APK](https://github.com/chrisstudio97/atlas-releases/releases/tag/v1.0.6)

### v1.0.5 · 2026-11-20
- Nuevo control de acceso por país: después del PIN, la app comprueba que el país de tu conexión coincida con el país de tu teléfono registrado.
- Si no coincide, verás el mensaje 'Estás intentando acceder desde un país restringido' y no podrás entrar hasta usar la conexión del país correcto.
- La sesión ya no se borra por un error temporal de autorización; no volverás al registro de teléfono si ya tienes cuenta.
- La sesión se refresca al volver a la app para evitar cierres inesperados.
- Si usas una VPN, desactívala para acceder desde tu país registrado.

[Descargar APK](https://github.com/chrisstudio97/atlas-releases/releases/tag/v1.0.5)

### v1.0.4 · 2026-11-20
- En el detalle de la orden ya puedes ver los documentos de identidad del beneficiario con vista previa.
- La dirección del beneficiario aparece en el detalle y en la tarjeta del chat.
- Nuevo botón de WhatsApp junto al teléfono del beneficiario para contactarlo directamente.
- El teléfono del cliente ya no se muestra en la sección Clientes.
- Si el negocio cambia el beneficiario de una orden, recibirás un aviso en el chat.

[Descargar APK](https://github.com/chrisstudio97/atlas-releases/releases/tag/v1.0.4)

### v1.0.3 · 2026-11-19
- Corregida la vinculación de wallet cuando el reloj del teléfono no coincide con el del servidor.
- La app sincroniza la hora con el backend antes de firmar, evitando el error 'Stale signature'.
- Si la vinculación falla, puedes reintentarla desde Ajustes → Vincular wallet.

[Descargar APK](https://github.com/chrisstudio97/atlas-releases/releases/tag/v1.0.3)

### v1.0.2 · 2026-11-19
- Vinculación de wallet más fiable: la app ahora confirma con el servidor que tu wallet quedó ligada a tu cuenta.
- Si la vinculación falla, tu wallet queda guardada en el dispositivo y puedes vincularla más tarde desde Ajustes → Vincular wallet.
- Puedes vincular una wallet que ya tenías creada sin volver a importar la frase semilla.

[Descargar APK](https://github.com/chrisstudio97/atlas-releases/releases/tag/v1.0.2)

### v1.0.1 · 2026-11-18
- Nuevo ajuste de bloqueo automático en Seguridad.
- El bloqueo está apagado por defecto y puedes elegir entre 1, 5, 15, 30 o 60 minutos.
- Tu PIN sigue siendo necesario al abrir la app desde cero y en las acciones sensibles.

[Descargar APK](https://github.com/chrisstudio97/atlas-releases/releases/tag/v1.0.1)
<!-- releases:end -->

---

## Instalación

1. Descarga el archivo `.apk` desde [Releases](../../releases).
2. En el dispositivo Android, permite la instalación desde fuentes desconocidas (si el sistema lo solicita).
3. Abre el archivo descargado e instala la aplicación.
4. Si ya tienes Atlas instalada, la nueva versión normalmente reemplazará la anterior.

---

## Versionado

Las releases siguen un esquema semántico:

```
vMAJOR.MINOR.PATCH
```

Ejemplo: `v1.2.0`

---

## Notas

- Las APKs publicadas aquí corresponden a builds de distribución de Atlas.
- Conserva únicamente builds firmados y listos para instalación.
- Ante dudas sobre autenticidad, verifica siempre la fuente de descarga (este repositorio / sus releases oficiales).

---

<p align="center">
  <sub>Atlas · Distribución Android</sub>
</p>
