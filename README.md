# OrbePet — firmware publicado

Aquí solo están las versiones compiladas del orbe. El orbe lee `version.json` y baja `mascota.bin`
(Ajustes → Versión → ACTUALIZAR). El código vive en un repositorio privado.

Para grabar por cable (esptool, ESP32-S3, flash 32 MB): `bootloader.bin` en 0x0, `partition-table.bin` en 0x8000,
`ota_data_initial.bin` en 0x19000 y `mascota.bin` en 0x20000. Normalmente basta con el probador o con la página
del orbe (http://192.168.4.1 en su modo actualizar).
