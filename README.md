# CV

Vitalii Titarenko — Senior Software Developer.

Live: https://ti-tar.github.io/CV/ · PDF: Vitalii_Titarenko_CV.pdf

Plain HTML + CSS. Regenerate the PDF with headless Chrome:

```
docker run --rm -v "$PWD":/w zenika/alpine-chrome --no-sandbox --no-pdf-header-footer --print-to-pdf=/w/Vitalii_Titarenko_CV.pdf file:///w/index.html
```
