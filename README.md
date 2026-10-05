# Mihon Hands-Free Extensions

Repositorio personal de extensiones compatibles con Mihon Hands-Free.

## Catálogos

- Extensiones principales: `https://raw.githubusercontent.com/hydekiRyuga3026/mihon-handsfree-extensions/main/handsfree/index.min.json`
- TMOHentai (firma heredada): `https://raw.githubusercontent.com/hydekiRyuga3026/mihon-handsfree-extensions/main/tmohentai/index.min.json`

TMOHentai utiliza un catálogo separado porque su APK original fue firmado con una clave distinta. Esto permite actualizarla sin desinstalarla.

Mihon Hands-Free `0.20.4-handsfree.5` añade ambos catálogos automáticamente. En Mihon estándar se pueden pegar las dos direcciones anteriores en **Ajustes > Explorar > Repositorios de extensiones**.

## Publicación

Cada actualización debe conservar el nombre de paquete y la firma de su catálogo, aumentar `versionCode` y reemplazar la entrada correspondiente en `index.json` e `index.min.json`.
