---
marp: true
---

<style>
@import url('https://fonts.googleapis.com/css2?family=Roboto+Condensed:wght@300&family=Spectral:wght@300&display=swap');

section {
  padding: 40px;
  font-family: 'Roboto Condensed', sans-serif;
  color: #fff;
  background: #000;
}

h1 {
  font-family: 'Spectral', serif;
  font-size: 60px;
  color: #fff;
}

h2 {
  font-family: 'Spectral', serif;
  color: #fffb;
}

/*
 * Synthwave '84 Theme originally by Robb Owen [@Robb0wen] for Visual Studio Code
 * Demo: https://marc.dev/demo/prism-synthwave84
 *
 * Ported for PrismJS by Marc Backes [@themarcba]
 */

code,
pre {
  color: #f92aad;
  font-family: Consolas, monospace;
  text-align: left;
  white-space: pre;
  word-spacing: normal;
  word-break: normal;
  word-wrap: normal;
  line-height: 1.5;
  background: #181818;
  border: none;
  border-radius: 8px;
  color: #fff;
}
pre > code[class="language-python"] {
  color: #fff;
  text-shadow: 0 0 2px #fff4, 0 0 16px #fff4, 0 0 10px #fff4, 0 0 2px #fff4;
}
pre > code[class="language-diff"] {
  color: white;
  text-shadow: none;
}
pre {
  padding: 1em;
  margin: 0.5em 0;
  overflow: auto;
}

.hljs-comment,
.hljs-block-comment,
.hljs-prolog,
.hljs-doctype,
.hljs-cdata {
  color: #9963ff99;
  text-shadow: 0 0 2px #001716, 0 0 5px #03edf933, 0 0 10px #ffff6633;
}

.hljs-punctuation {
  color: #ccc;
}

.hljs-tag,
.hljs-attr-name,
.hljs-namespace,
.hljs-number,
.hljs-unit,
.hljs-hexcode {
  color: #ffcc00;
  text-shadow: 0 0 2px #100c0f, 0 0 3px #ffaa0099, 0 0 5px #ffaa0099, 0 0 10px #ffaa0099;
}

.hljs-property,
.hljs-selector {
  color: #72f1b8;
  text-shadow: 0 0 2px #100c0f, 0 0 10px #257c5575, 0 0 35px #21272475;
}

.hljs-boolean,
.hljs-function,
.hljs-title,
.hljs-params {
  color: #fdfdfd;
}

.hljs-keyword {
      color: #ffcc00;
    text-shadow: 0 0 2px #100c0f, 0 0 3px #ffaa0099, 0 0 5px #ffaa0099, 0 0 10px #ffaa0099;
}

.hljs-string,
.hljs-char,
.hljs-attr-value,
.hljs-regex,
.hljs-variable {
  color: #9963ff;
  text-shadow: none;
}

.hljs-addition,
.hljs-deletion {
  background: #0f02;
  display: inline-block;
  color: white;
  text-shadow: none;
  margin-left: -1ch;
}
.hljs-deletion {
  background: #f002;
}
/**/
ol > li:not(:last-child) {
  opacity: 0.5;
}
</style>

<style scoped>
section {
  text-align: center;
  padding-top: 25%;
}
</style>

![bg vertical 50%](images/splash.png)
![bg 600%](images/splash.png)

# ... og litt om open-source generelt ????

## Niklas M. Hole

### 14. Oktober 2021

---

# Hva er Hacktoberfest for no? ????

---

<!-- header: Hva er Hacktoberfest for no? ???? -->

Den er nesten som Oktoberfest, bare at:

- Man ikke bruker lederhosen eller dirndl

---

<!-- header: Hva er Hacktoberfest for no? ???? -->

Den er nesten som Oktoberfest, bare at:

- Man ikke bruker lederhosen eller dirndl
- Man drikker halvlitere med ??l, og ikke hele liter

---

<!-- header: Hva er Hacktoberfest for no? ???? -->

Den er nesten som Oktoberfest, bare at:

- Man ikke bruker lederhosen eller dirndl
- Man drikker halvlitere med ??l, og ikke hele liter
- Det er egentlig alt

---

<!-- header: Hva er Hacktoberfest for no? ???? -->

# Det er en fest!

Men ikke la deg rive med helt enda

---

<!-- header: Hva er Hacktoberfest for no? ???? -->

# Det er en fest!

Men ikke la deg rive med helt enda

Det handler ogs?? om ?? hjelpe andre ????

---

<!-- header: Hva er Hacktoberfest for no? ???? -->

# Hjelpe med hva da?

Ja n?? kan du lure! Nei da, la oss hoppe rett inn i selve essensen av Hacktoberfest:

- Arrangement av DigitalOcean ????
- 8-ende ??ret ????
- Feire open-source ???? med ?? hjelpe til p?? open-source-prosjekter ????
- Kan gj??res alene eller sammen med andre ????

---

<!-- header: '' -->

# Hvorfor vil vi fremme open-source?

---

<!-- header: 'Hvorfor vil vi fremme open-source?' -->

# Hvorfor vil vi fremme open-source?

Fordi:

- Da kan alle f?? v??re med ?? si noe p?? prosjektet! **#demokrati-ish**
- Koden kan kvalitetssjekkes av andre **#trygghet**
- Man kan l??re av andres prosjekter **#l??ring**

---

<!-- header: '' -->

# Hvorfor skal akkurat _du_ bruke open-source?

---

<!-- header: 'Hvorfor skal akkurat *du* bruke open-source?' -->

# Hvorfor skal akkurat _du_ bruke open-source?

- Du f??r ??velse i ?? dele ideene dine med andre
- Du kan inspirere andre
- Mange gratis verkt??y:
  - Hosting av nettside (Vercel, GitHub)
  - Bygging av nettside (Drone, CircleCI, Travis, Vercel, GitHub Actions)
- Enkelt ?? dele med andre
- Mulighet til ?? f?? hjelp av andre du ikke kjenner

---

<!-- header: '' -->

# "Men jeg er jo bare en vanlig person. Hvordan kan _jeg_ bidra?"

---

<!-- header: 'Hvordan bli en open-sourcerer p?? 1-2-3 ?????????????' -->

# Hvordan bli en open-sourcerer p?? 1-2-3 ?????????????

Hold fast i datamaskinen din!

---

1. G?? p?? Google, skriv **"<hva du vil bidra p??> github"**

![bg right contain](images/figma-google.png)

---

<!-- header: 'Hvordan bli en open-sourcerer p?? 1-2-3 ?????????????' -->

1. G?? p?? Google, skriv **"<hva du vil bidra p??> github"**
2. Trykk p?? f??rste linken

![bg right 150%](images/figma-google.png)

---

<!-- header: 'Hvordan bli en open-sourcerer p?? 1-2-3 ?????????????' -->

1. G?? p?? Google, skriv **"<hva du vil bidra p??> github"**
2. Trykk p?? f??rste linken
3. Finn hvor prosjektet ligger (antall stjerner ??? og forks ???? er ofte en god indikator)

![bg right contain](images/figma-github.png)

---

<!-- header: 'Hvordan bli en open-sourcerer p?? 1-2-3 ?????????????' -->

1. G?? p?? Google, skriv **"<hva du vil bidra p??> github"**
2. Trykk p?? f??rste linken
3. Finn hvor prosjektet ligger (antall stjerner ??? og forks ???? er ofte en god indikator)
4. HAR DE IKKE LOGO I README'EN!?

![bg right contain](images/figma-github-project.png)

---

<!-- header: 'Hvordan bli en open-sourcerer p?? 1-2-3 ?????????????' -->

1. G?? p?? Google, skriv **"<hva du vil bidra p??> github"**
2. Trykk p?? f??rste linken
3. Finn hvor prosjektet ligger (antall stjerner ??? og forks ???? er ofte en god indikator)
4. HAR DE IKKE LOGO I README'EN!??
5. Bli litt sinna, ha en liten rant i hodet ditt

![bg right contain](images/figma-github-project-angry.png)

---

<!-- header: 'Hvordan bli en open-sourcerer p?? 1-2-3 ?????????????' -->

1. G?? p?? Google, skriv **"<hva du vil bidra p??> github"**
2. Trykk p?? f??rste linken
3. Finn hvor prosjektet ligger (antall stjerner ??? og forks ???? er ofte en god indikator)
4. HAR DE IKKE LOGO I README'EN!??
5. Bli litt sinna, ha en liten rant i hodet ditt
6. Naviger til filen og trykk p?? blyanten

![bg right contain](images/figma-github-project-edit.png)

---

<!-- header: 'Hvordan bli en open-sourcerer p?? 1-2-3 ?????????????' -->

1. G?? p?? Google, skriv **"<hva du vil bidra p??> github"**
2. Trykk p?? f??rste linken
3. Finn hvor prosjektet ligger (antall stjerner ??? og forks ???? er ofte en god indikator)
4. HAR DE IKKE LOGO I README'EN!??
5. Bli litt sinna, ha en liten rant i hodet ditt
6. Naviger til filen og trykk p?? blyanten
7. Legg inn endringen din

![bg right contain](images/figma-github-project-edit-done.png)

---

<!-- header: 'Hvordan bli en open-sourcerer p?? 1-2-3 ?????????????' -->

1. G?? p?? Google, skriv **"<hva du vil bidra p??> github"**
2. Trykk p?? f??rste linken
3. Finn hvor prosjektet ligger (antall stjerner ??? og forks ???? er ofte en god indikator)
4. HAR DE IKKE LOGO I README'EN!??
5. Bli litt sinna, ha en liten rant i hodet ditt
6. Naviger til filen og trykk p?? blyanten
7. Legg inn endringen din
8. Beskriv endringen og trykk p?? gr??nn knapp

![bg right contain](images/figma-github-project-edit-done-button.png)

---

<!-- header: 'Hvordan bli en open-sourcerer p?? 1-2-3 ?????????????' -->

1. G?? p?? Google, skriv **"<hva du vil bidra p??> github"**
2. Trykk p?? f??rste linken
3. Finn hvor prosjektet ligger (antall stjerner ??? og forks ???? er ofte en god indikator)
4. HAR DE IKKE LOGO I README'EN!??
5. Bli litt sinna, ha en liten rant i hodet ditt
6. Naviger til filen og trykk p?? blyanten
7. Legg inn endringen din
8. Beskriv endringen og trykk p?? gr??nn knapp
9. Arrg!! Noen var raskere enn meg ????

![bg right contain](images/figma-github-project-edit-aftermath.png)

---

<!-- header: 'Hvordan bli en open-sourcerer p?? 1-2-3 ?????????????' -->

## Men det g??r fint!

Det handler ikke om ?? v??re f??rst. Det handler om ?? hjelpe til ????

N?? kan du ta en slurk til av pilsen din.

---

<!-- header: 'Hvordan bli en open-sourcerer p?? 1-2-3 ?????????????' -->

# Husk ?? registrer deg p?? https://hacktoberfest.digitalocean.com

F??r du godkjent\* 4 PR'er f??r du en t-skjorte med masse klistremerker! ????

Men v??r kjapp; det er bare 50 000 stk ???? (godt under 0.01% av jordas befolkning f??r dette)

Man m?? ikke ta i mot t-skjorte, man kan ogs?? velge ?? plante et tre ????????

Du kan finne mer informasjon p?? nettsiden deres.

\*godkjent betyr at PR'en din ikke blir rapportert p?? 14 dager med "spam" eller "invalid" label.

---

<!-- header: '' -->
