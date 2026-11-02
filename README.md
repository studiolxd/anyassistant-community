# AnyAssistant · Comunidad

Temas y plugins de [AnyAssistant](https://github.com/studiolxd/anyassistant) que comparte la
comunidad. La app los instala desde aquí: lee `index.json` y comprueba el SHA-256 de cada archivo
antes de instalarlo.

- `index.json`: el catálogo. Su formato está en `index.schema.json`.
- `themes/<id>/`: un tema por carpeta (`theme.json`, `theme.html`, `theme.css`…).
- `plugins/<id>/`: un plugin por carpeta (`plugin.json`, `__init__.py`…).

## Publicar un tema o un plugin

Abre una pull request con la carpeta del paquete y su entrada en `index.json`. Cada paquete se
revisa antes de aceptarlo; los plugins con más cuidado, porque ejecutan código en el ordenador de
quien los instala. La guía completa, con el formato y cómo generar la entrada con sus hashes
(`bin/anyassistant community entry`), está en
[docs/comunidad.md](https://github.com/studiolxd/anyassistant/blob/main/docs/comunidad.md).
