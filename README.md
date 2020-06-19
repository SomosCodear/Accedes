# Subtitulos

[Read this in English](README.en.md) |  [Leer em portugués](README.pt.md)

Este repositorio pretende llevar un registro del trabajo necesario para crear subtítulos para los videos de CoDeAr en YouTube.

Vamos a estar subtitulando en tres idiomas: español, inglés y portugués.

## ¿Cómo puedo contribuir?

Sumate a cualquiera de los [proyectos de subtitulado](https://github.com/SomosCodear/Subtitulos/issues?q=is%3Aissue+is%3Aopen+label%3A%22control+de+traducci%C3%B3n%22) y dejá un comentario indicando que querés participar.

## ¿Cómo deben crearse los subtítulos?

Utilizaremos el formato SubRip (.srt) para todos los subtítulos. Este formato es fácil de trabajar y no requiere de software especializado.

## ¿Es tu primera vez haciendo subtítulos?

¡No te preocupes! Podés contribuir escribiendo todo lo que se dice en el vídeo en un archivo .txt y que otras personas que conozcan el formato SubRip puedan ayudarte.

## Flujo de trabajo

1) [Realizar un fork](https://github.com/SomosCodear/Subtitulos/fork) de este repositorio.
2) En la carpeta del idioma que estemos trabajando:
 - Si estamos creando un subtítulo, crear un archivo SRT cuyo nombre sea el número de issue del vídeo. Ejemplo: si estamos trabajando en el video "Educar en tiempos de #YoMeQuedoEnCasa" en inglés, la ruta y el nombre del archivo es `en-US/1.srt`.
 - Si estamos creando una transcripción (para que otra persona pueda convertirla en subtítulo), crear un archivo TXT cuyo nombre sea el número de issue del vídeo.  Ejemplo: si estamos trabajando en el video "Educar en tiempos de #YoMeQuedoEnCasa" en inglés, la ruta y el nombre del archivo es `en-US/1.txt`.
3) Enviar un pull request y referenciar al video que se está trabajando a través de su número de issue, completando los datos que pide la plantilla de pull request.
4) El staff de CoDeAr va a probar los subtítulos y revisarlos. Cuando estén chequeados y funcionando, el PR se aprueba y se mergea.

## Algunos términos y condiciones

Este repositorio servirá como referencia de atribución para aquellas personas autoras que produzcan subtítulos o transcripciones.

- Participar de repositorio implica la aceptación del [código de conducta](./CODE_OF_CONDUCT.md) de CoDeAr.
- Contribuir a este repositorio implica que aceptás ceder los textos redactados bajo una [licencia CC0 (Creative Commons Zero)](./LICENSE).
