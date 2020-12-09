# The JavaFX Documentation Project
The JavaFX Documentation Project is designed to collect important JavaFX information from around the web and, with the permission of the authors, to collate it into a single source to form a cohesive book.

This project was initiated by <a href="http://www.jonathangiles.net">Jonathan Giles</a>, but anyone can contribute. Any questions, concerns, or feedback should be in the first instance be directed to Jonathan via <a href="mailto:jonathan@jonathangiles.net">email</a>.

## Reading The Documentation
Documentation is available for reading online, and will always reflect the very latest edits. It is currently available in two forms:
 
<ul>
  <li>As a <a href="https://fxdocs.github.io/docs/html5/index.html">single-page website</a>.</li>
  <li>As a <a href="https://fxdocs.github.io/docs/pdf/index.pdf">single PDF</a>.</li>
</ul>

## Build Process
The documentation is written in AsciiDoc. On every commit to this GitHub repo a build process is run, resulting in newly-built content available in <a href="https://fxdocs.github.io/docs/html5/index.html">HTML</a> and as a <a href="https://fxdocs.github.io/docs/pdf/index.pdf">single PDF file</a>. The JavaFX Documentation Project uses GitHub Actions to perform continuous builds of the AsciiDoc source. The current status of the build is:

![Build Docs](https://github.com/FXDocs/docs/workflows/Build%20Docs/badge.svg)

To build manually:

```
./gradlew run
```

This will produce `html5` and `pdf` directories with the appropriate files inside `build/docs/`.
