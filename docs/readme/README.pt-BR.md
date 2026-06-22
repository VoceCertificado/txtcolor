<img
    src="https://raw.githubusercontent.com/VoceCertificado/txtcolor/main/images/icon.png"
    alt="TXT Color"
    width="120"
    height="120"
  />

# TXT Color

  [![Open VSX](https://img.shields.io/badge/Open%20VSX-TXT%20Color-blue)](https://open-vsx.org/extension/VoceCertificado/txt-color)
  [![Visual Studio Marketplace](https://img.shields.io/badge/VS%20Marketplace-TXT%20Color-blue)](https://marketplace.visualstudio.com/items?itemName=VoceCertificado.txt-color)

  <p>
    <a href="../../README.md">English</a> ·
    <a href="README.es.md">Español</a> ·
    <strong>Português (Brasil)</strong>
  </p>

  Uma extensão bonita de realce de cores para arquivos de texto simples e arquivos no estilo de configuração, compatível com VS Code, Kiro e outras IDEs baseadas no VS Code.

## Recursos

- Destaca cabeçalhos, títulos em letras maiúsculas e blocos `[section]`.
- Destaca comentários, linhas em formato de lista e pares de chave/valor.
- Destaca URLs, e-mails, números, datas, horários e valores booleanos.
- Destaca linhas de severidade de logs (`ERROR`, `WARN`, `SUCCESS`, etc.) com cores distintas para a linha inteira.
- Destaca palavras-chave inline: `TODO`, `FIXME`, `NOTE`, `INFO`, `DEBUG`.
- Destaca constantes booleanas: `true`, `false`, `yes`, `no`, `on`, `off`, sem diferenciar maiúsculas de minúsculas.
- Adiciona suporte básico a dobramento de código. Consulte a seção [Dobramento](#dobramento) abaixo.
- Adiciona pares básicos de fechamento automático para colchetes, chaves, parênteses, aspas, crases, sinais de menor/maior e aspas angulares francesas.

## Extensões de arquivo compatíveis

O TXT Color é útil para anotações, logs, arquivos de ambiente, arquivos de configuração e textos estruturados simples.

`.txt`, `.log`, `.ini`, `.conf`, `.cfg`, `.env`, `.properties`, `.toml`, `.editorconfig`, `.gitconfig`

## Dobramento

As seções podem ser dobradas usando marcadores explícitos:

```txt
Section My Section Title
  press the tab ...
  add your content ...
  and keep going ...
  closing the last line with `---`
---
```

Cabeçalhos `[section]` também funcionam como marcadores de início de dobramento. Uma linha com `---` fecha o bloco dobrável.

## Testes

Um arquivo `.txt` de exemplo está disponível na pasta `test/`.

## Capturas de tela

### Tema Light+

TXT Color aplicado a um arquivo `.txt` usando o tema Light+ da IDE.

![TXT Color aplicado a um arquivo TXT usando o tema Light+ da IDE](https://raw.githubusercontent.com/VoceCertificado/txtcolor/main/images/txt-color-light-theme.png)

### Tema Dark+

TXT Color aplicado a um arquivo `.txt` usando o tema Dark+ da IDE.

![TXT Color aplicado a um arquivo TXT usando o tema Dark+ da IDE](https://raw.githubusercontent.com/VoceCertificado/txtcolor/main/images/txt-color-dark-theme.png)
