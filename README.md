# Bryllupshjemmeside

En simpel statisk hjemmeside med praktisk information til bryllupsgæster.
Siden er bygget med almindelig HTML og CSS og kan derfor publiceres direkte
med GitHub Pages uden build-step eller ekstra dependencies.

## Indhold

Hjemmesiden indeholder:

- Praktisk information til gæster
- Program for dagene
- Information til gæster der overnatter på Klinteborg
- Transportinformation
- Ønskeliste

## Filstruktur

```text
.
├── index.html          # Sidens indhold og tekst
├── styles.css          # Design, layout, fonte og responsiv styling
├── assets/             # Billeder, motiver, screenshots og fonte
└── context/            # Original invitation brugt som designreference
```

## Redigering

De fleste tekstændringer laves i `index.html`.

- Navigationen ligger øverst i filen i `<nav class="nav">`.
- Praktisk information ligger i sektionen `id="alle"`.
- Programmet ligger i sektionen `id="program"`.
- Overnatning ligger i sektionen `id="overnatning"`.
- Transport ligger i sektionen `id="transport"`.
- Ønskelisten ligger i sektionen `id="onskeliste"`.

Design, farver, afstande og mobilvisning ændres i `styles.css`.

## Se siden lokalt

Åbn `index.html` direkte i en browser.

På Windows kan du dobbeltklikke på filen, eller højreklikke og vælge din
foretrukne browser.

## Publicering med GitHub Pages

1. Opret et nyt GitHub-repository.
2. Upload `index.html`, `styles.css` og mappen `assets/`.
3. Gå til repositoryets `Settings`.
4. Vælg `Pages` i menuen.
5. Under `Build and deployment`, vælg:
   - Source: `Deploy from a branch`
   - Branch: `main`
   - Folder: `/root`
6. Tryk `Save`.

Efter et øjeblik får du et offentligt link til hjemmesiden.

## Vigtigt ved upload

Sørg for at disse filer og mapper kommer med:

- `index.html`
- `styles.css`
- `assets/`

Mappen `context/` er kun designreference og behøver ikke nødvendigvis uploades,
medmindre I gerne vil gemme invitationen sammen med projektet.

## Noter

Siden bruger lokale fontfiler og billedmotiver i `assets/`, så den virker uden
eksterne font- eller billedlinks.
