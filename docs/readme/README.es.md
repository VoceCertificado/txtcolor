<img
    src="https://raw.githubusercontent.com/VoceCertificado/txtcolor/main/images/icon.png"
    alt="TXT Color"
    width="120"
    height="120"
  />

# TXT Color

  [![Open VSX](https://img.shields.io/badge/Open%20VSX-TXT%20Color-blue)](https://open-vsx.org/extension/VoceCertificado/txt-color)
  [![Visual Studio Marketplace](https://img.shields.io/badge/VS%20Marketplace-TXT%20Color-blue)](https://marketplace.visualstudio.com/items?itemName=VoceCertificado.txt-color)

  <a href="../../README.md">English</a> ·
  <strong>Español</strong> ·
  <a href="README.pt-BR.md">Português (Brasil)</a>

  Una extensión atractiva de resaltado de colores para archivos de texto simple y archivos con estilo de configuración, compatible con VS Code, Kiro y otras IDE basadas en VS Code.
  
## Características

- Resalta encabezados, títulos en mayúsculas y bloques `[section]`.
- Resalta comentarios, líneas en formato de lista y pares clave/valor.
- Resalta URL, correos electrónicos, números, fechas, horas y valores booleanos.
- Resalta líneas de severidad de logs (`ERROR`, `WARN`, `SUCCESS`, etc.) con colores distintos para la línea completa.
- Resalta palabras clave inline: `TODO`, `FIXME`, `NOTE`, `INFO`, `DEBUG`.
- Resalta constantes booleanas: `true`, `false`, `yes`, `no`, `on`, `off`, sin distinguir entre mayúsculas y minúsculas.
- Agrega soporte básico para plegado de código. Consulta la sección [Plegado](#plegado) a continuación.
- Agrega pares básicos de cierre automático para corchetes, llaves, paréntesis, comillas, acentos graves, signos menor/mayor y comillas angulares francesas.

## Extensiones de archivo compatibles

TXT Color es útil para notas, logs, archivos de entorno, archivos de configuración y textos estructurados simples.

`.txt`, `.log`, `.ini`, `.conf`, `.cfg`, `.env`, `.properties`, `.toml`, `.editorconfig`, `.gitconfig`

## Plegado

Las secciones se pueden plegar usando marcadores explícitos:

```txt
Section My Section Title
  press the tab ...
  add your content ...
  and keep going ...
  closing the last line with `---`
---
```

Los encabezados `[section]` también funcionan como marcadores de inicio de plegado. Una línea con `---` cierra el bloque plegable.

## Pruebas

Hay un archivo `.txt` de ejemplo disponible en la carpeta `test/`.

## Capturas de pantalla

### Tema Light+

TXT Color aplicado a un archivo `.txt` usando el tema Light+ de la IDE.

![TXT Color aplicado a un archivo TXT usando el tema Light+ de la IDE](https://raw.githubusercontent.com/VoceCertificado/txtcolor/main/images/txt-color-light-theme.png)

### Tema Dark+

TXT Color aplicado a un archivo `.txt` usando el tema Dark+ de la IDE.

![TXT Color aplicado a un archivo TXT usando el tema Dark+ de la IDE](https://raw.githubusercontent.com/VoceCertificado/txtcolor/main/images/txt-color-dark-theme.png)
