# Solo Hacks 1.0 `code`

## Español (Spanish)

***Explicación general***

Programa que recibe un `PDF` en Español con menos de $1024$ palabras, traduce el texto a Inglés y genera dos archivos

1. Un archivo `MP3` con el texto en Inglés
2. Un archivo `PDF` con el texto en Español y en Inglés

***Tecnologías usadas***

* `pypdf` *para extraer el texto del archivo* `PDF`
* `gtts` *para generar el archivo en* `MP3`
* `transformers` *para usar el* [modelo](https://huggingface.co/Helsinki-NLP/opus-mt-es-en) *de **Hugging Face** por la [University of Helsinki](https://github.com/Helsinki-NLP) y los tokenizers*
* `reportlab` *para crear el archivo en* `PDF`
* `google.colab` *para descargar los archivos*
---
---

## English (Inglés)

***General Explanation***

Program that receives a `PDF` in Spanish with less than $1024$ words, translates the text into English and generates two files

1. An `MP3`with the text in English
2. A `PDF` with the text in Spanish and in English

***Tecnologías usadas***

* `pypdf` *to get the text from the* `PDF` *file*
* `gtts` *to genetare the* `MP3` *file*
* `transformers` *to use the* [model](https://huggingface.co/Helsinki-NLP/opus-mt-es-en) *from **Hugging Face** by the [University of Helsinki](https://github.com/Helsinki-NLP) and the tokenizers*
* `reportlab` *to create the* `PDF` *file*
* `google.colab` *to download the files*