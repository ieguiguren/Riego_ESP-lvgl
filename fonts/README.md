# Fuentes

El YAML necesita aquí el fichero **`materialdesignicons-webfont.ttf`** (iconos de la pantalla).
La fuente Roboto no hace falta: ESPHome la descarga sola desde Google Fonts.

## Cómo conseguir los iconos

Opción A (web): descarga el paquete de fuente desde <https://pictogrammers.com/library/mdi/>
y copia `materialdesignicons-webfont.ttf` en esta carpeta.

Opción B (npm):

```bash
npm pack @mdi/font
tar xzf mdi-font-*.tgz
cp package/fonts/materialdesignicons-webfont.ttf fonts/
```

Los iconos son de Material Design Icons (Pictogrammers, licencia Apache 2.0).
Los códigos usados (p. ej. `\U000F0597` lluvia, `\U000F0599` sol) son los de la serie 7.x.
