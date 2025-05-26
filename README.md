# snakker du fjernbetjening?

En oversætter fra en fjernbetjening til en soundbar, men det kan jo i
virkeligheden være hvad som helst. Modtag IR signal og send et andet IR signal
er hele formålet.

# Setup

Projektet er originalt sat op med
```bash
pio project init -d snakker-du-fjernbetjening --ide vim -b uno
```

Åbenbart skal man køre følgende hver gang et bibliotek tilføjes for at LSPen
forbliver glad.
```bash
pio run -t compiledb
```

Projektet kan bygges med med
```bash
pio run
```
og uploades med
```bash
pio run -t upload
```
