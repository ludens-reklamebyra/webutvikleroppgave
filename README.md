# webutvikleroppgave

## Oppgaveinstruksjoner
Oppgaven forutsetter at du har NodeJS og npm installert.
Globale npm-moduler du trenger for oppgaven er `gulpJS`, som kan installeres ved kommandoen `$ npm install -g gulp`

### Installasjon av oppgaven
1. Fork prosjektet.
2. Klon prosjektet lokalt på din maskin.
3. Utfør kommandoene nedenfor:
```
$ cd webutvikleroppgave
$ npm install
```

### Start kompilering
For å starte kompileringen av JavasScript og SCSS utfør kommandoen:
(Gulp-scriptet bruker live-reload, slik at du kan se dine endringer i browseren med engang du lagrer filen du jobber på)
```
$ npm run dev
```
Hvis du ønsker å skru av live-reload, fjern linjen `.pipe(gulpif(dev, livereload()))` i `gulpfile.babel.js`

### Oppgavetekst
[Oppgavetekst](oppgave.md)

### Når oppgaven er utført
Send lenke fra deres Fork til kristian@ludensreklame.no
### Ekstra
- JavaScript kan både skrives i ES5 og ES6, men vi setter ekstra pris på ES6.
- Eksterne JavaScript-biblioteker/rammeverk kan lastes ned og brukes, men må konfigureres på egenhånd.
- Bruk gjerne `Zurb Foundation` istedenfor `Bootstrap`.
