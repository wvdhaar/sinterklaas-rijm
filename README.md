# Sinterklaas rijm

Een skill voor Claude die Sinterklaasgedichten schrijft in goed, natuurlijk
Nederlands: voor kinderen, tieners en volwassenen, kort of lang, lief of als
roast.

*A Claude skill that writes Dutch Sinterklaas poems for children, teens and
adults.*

Gemaakt door [Sinterklaasspeurtocht.nl](https://sinterklaasspeurtocht.nl).
Tips om zelf een gedicht te schrijven, een opdracht voor ChatGPT en de skill
als zip-bestand vind je op
[Een sinterklaasgedicht schrijven](https://sinterklaasspeurtocht.nl/ideeen/sinterklaasgedicht-schrijven).

---

## Een Sinterklaasgedicht waar niemand AI in hoort

Iedereen kent het AI-gedicht inmiddels. Het rijmt *ei* op *hoezee*, eindigt
regels op "dat is cool" en "o jee", en zet er een titel boven die niemand
voorleest. Op pakjesavond hoort de hele kamer meteen dat Sint het niet zelf
heeft geschreven.

Deze skill geeft Claude de regels die een goede Sinterklaasdichter in zijn
hoofd heeft:

- **Eerst wat je wilt zeggen, dan pas het rijm.** Geen zinnen die alleen
  bestaan om op iets te rijmen.
- **Rijm dat je hoort, niet alleen ziet.** Op klank, met de klemtoon op de
  goede plek.
- **Eén lopende grap over déze persoon**, in plaats van een opsomming van
  alles wat je hebt verteld.
- **Plagen zonder pijn.** Gevoelige dingen blijven eruit, ook als je ze per
  ongeluk noemt.
- **Drie opties om uit te kiezen**, elk met een eigen grap of invalshoek.
  Geen titel, geen inleiding, geen "wil je nog een versie?". Alleen de
  gedichten.

### De test: tien keer dezelfde vraag, met en zonder deze skill

In november 2026 gaven we Claude tien uiteenlopende vragen: een kleuter die
de hele dag zingt, een tiener die een roast krijgt, lootjes op het werk, een
lang gedicht van dertig regels voor een opa die nooit iets vangt, een gedicht
van een vriendin in plaats van van Sint, en een tweeling die samen één
gedicht krijgt. In drie vragen stond iets gevoeligs: een scheiding, een opa
die vorig jaar is overleden, en een burn-out. Elke vraag ging drie keer
naar Claude, steeds in een schone sessie, met één gedicht per vraag.

| | Sonnet, zonder richtlijnen | Sonnet, met deze skill | Opus, met deze skill |
|---|---|---|---|
| Gevoelig onderwerp in het gedicht | 3 van de 3 | 0 van de 3 | 0 van de 3 |
| Rijmwoorden die niet rijmen | 41 | 1 | 2 (bijna-rijm) |
| Opvulzinnetjes en onzinregels ("dat is zonneklaar", "dat is mijn bief") | ongeveer 50 | 5 | 2 |
| Inleiding of afsluiting die je eerst moet weghalen | 10 van de 10 | 0 van de 10 | 0 van de 10 |
| Neemt aan dat mama of papa iets doet | ja, 2 keer | nee | nee |
| Lengte past bij de leeftijd | geen regel | 5 van de 10 | 10 van de 10 |

*Zelf geteld, op tien gedichten per kolom. Een kleine test, geen
wetenschappelijk onderzoek; een voorbeeld staat hieronder, oordeel zelf.*

**Zo klonk oma Riet zonder richtlijnen** (81, breit sokken voor iedereen,
belt elke zondag om acht uur; opa is vorig jaar overleden):

```text
Elke zondag, precies om acht uur,
gaat de telefoon, en wij weten: dat is oma, dat is de uur.

Opa kijkt vast mee van boven,
en hij is trots, dat mogen we geloven.
```

**En zo met deze skill** (opa is weggelaten, en Claude meldt dat in één
regel onder het gedicht; de grap gaat over het bellen):

```text
Oma Riet, op zondag hoeft niemand een wekker te zetten:
om acht uur bel jij iedereen uit de bedden.
Niet om vijf voor en niet om vijf over, maar om acht.
Piet wilde nog uitslapen. Dat had hij gedacht!

Daarom krijg je een tablet, met letters zo groot
dat zelfs de Sint ze kan lezen vanaf zijn boot.
Dan zie je op zondag om acht uur ieders gezicht,
ook al hebben ze hun ogen nog half dicht.
```

Het grootste verschil zit in de regels, niet in het model: hetzelfde
Sonnet ging van 41 valse rijmen en drie pijnlijke regels naar één vals
rijm en nul. Opus vertelt daarna de betere verhaaltjes en houdt zich aan de
lengte. Zonder richtlijnen schrijft een AI het gedicht dat het vaakst op
internet staat. Met deze skill schrijft hij het gedicht dat jij op
pakjesavond wilt voorlezen.

---

## Welk model?

De skill werkt op elk Claude-model, maar **Claude Opus schrijft de beste
gedichten**: concretere grappen, verhalen die kloppen en vrijwel foutloos
rijm. Vooral lange gedichten (30 regels of meer) lukken met Opus beter. Sonnet
werkt ook goed, maar schrijft vaak korter dan gevraagd; zeg dan "langer" en
lees het gedicht extra goed na.

---

## Installeren

**In Claude.ai of de Claude-app**

1. Download het kant-en-klare zip-bestand op
   [sinterklaasspeurtocht.nl](https://sinterklaasspeurtocht.nl/ideeen/sinterklaasgedicht-schrijven)
   en pak het niet uit. Of download deze repository (groene knop **Code**,
   dan **Download ZIP**), pak hem uit en maak van de map `sinterklaas-rijm`
   daarin een nieuw zip-bestand (de map zelf, met `SKILL.md` erin).
2. Ga in Claude naar de instellingen, bij Skills.
3. Upload het zip-bestand en zet de skill aan.

**In Claude Code**

Zet de map `sinterklaas-rijm` uit deze repository in
`~/.claude/skills/sinterklaas-rijm/` om hem overal te
gebruiken, of in `.claude/skills/sinterklaas-rijm/` binnen één project.

Je hoeft de skill daarna niet apart aan te roepen. Vraag om een
Sinterklaasgedicht en Claude gebruikt hem vanzelf.

---

## Zo vraag je een gedicht

Schrijf gewoon in losse zinnen wat je weet. Je hoeft niets in te vullen of
op te maken. Bijvoorbeeld:

> Schrijf een sinterklaasgedicht voor Mats, 7. Hij verzamelt stenen en
> neemt ze overal mee naar huis, zijn broekzakken zitten altijd vol. Hij
> krijgt een schatkist.

Je krijgt drie gedichten terug (Optie 1, 2 en 3), zonder inleiding, klaar
om voor te lezen. Elke optie heeft een eigen invalshoek: bijvoorbeeld één
over de stenen in zijn broekzakken, één over de schatkist en één over wat
Piet ervan vindt. Samen gebruiken ze alles wat je hebt verteld. Kies de
optie die het best past.

Wil je er maar één? Zeg dan "geef er één" of "alleen het beste".

### Wat helpt

Hoe meer echte details, hoe beter het gedicht. Geef in elk geval:

- **De naam**, en **de leeftijd** (of: kind, tiener, volwassene). De
  leeftijd bepaalt de lengte en het soort grappen.
- **Twee tot vijf concrete dingen.** Niet "hij is gezellig", maar "hij
  vertelt elk jaar dezelfde mop over de kip" of "zij belt iedereen op
  zondag om acht uur". Een gewoonte, een hobby, iets wat iemand altijd zegt,
  of iets grappigs wat laatst gebeurde.
- **Het cadeau**, en bij lootjes **de surprise**. Het gedicht eindigt er
  dan mee.

Handig om erbij te zeggen als het van toepassing is:

- **Van wie het is.** Standaard is het gedicht van Sint en Piet. Is het van
  iemand anders ("van mama", "van je zus"), zeg dat dan.
- **Lootjes, dus anoniem.** Dan verraadt het gedicht de echte gever niet.
- **De lengte**, als je iets anders wilt dan normaal: "kort", "lang", "zo'n
  30 regels".
- **Wat níet mag.** Noem je iets gevoeligs (een scheiding, ziekte, iets waar
  iemand onzeker over is), dan laat de skill het weg en zegt dat in één
  regel.

Geef je helemaal geen naam of details, dan stelt Claude eerst één korte
vraag.

### Standaardlengte per leeftijd

| Voor wie | Lengte |
|---|---|
| Kleuters (tot ~8) | 8 tot 12 regels |
| 9 tot 12 jaar | 12 tot 16 regels |
| Tieners | 12 tot 20 regels |
| Volwassenen | 16 tot 24 regels, op verzoek tot ~40 |

---

## Soorten gedichten

### Lief (standaard)

Plagerig, maar met een warm slot. Dit krijg je als je niets over de toon
zegt.

### Roast

Zeg "roast", "pittig", "scherp", "mag best gemeen" of "lekker plagen".

> Roast voor Thijs, 16. Staat elke ochtend een half uur voor de spiegel,
> vergeet altijd zijn sleutels. Krijgt een föhn.

Een roast plaagt **gewoontes en keuzes**, nooit uiterlijk, gewicht,
gezondheid, familie, relaties of geld. Bij kinderen en tieners ook geen
cijfers, vrienden of verliefdheden. Het gedicht eindigt altijd lief, vóór
het cadeau. Onder de tien jaar wordt het geen roast maar een extra brutaal,
warm gedicht; dat meldt Claude dan.

### Lootjes en surprises

> Lootjes op het werk, anoniem: Marieke, 38, collega. Drinkt tien koppen
> koffie per dag, plant vergaderingen op vrijdagmiddag, gaat elk weekend
> kamperen. Surprise is een koffiemok van papier-maché, cadeau een
> campinglamp.

Het gedicht verwijst naar de surprise, houdt de gever geheim en wordt
ondertekend door Sint en Piet.

---

## Aanpassen

Kies een optie en vraag om wat je anders wilt. Je krijgt dan alleen dat
ene gedicht terug, aangepast:

- "Optie 2, maar korter"
- "Neem optie 1, met het slot van optie 3"

- "Korter" of "maak er 30 regels van"
- "Iets pittiger" of "iets liever"
- "Meer over de barbecue, minder over de auto"
- "Laat de tweede strofe weg"
- "Schrijf het alsof het van mij komt, niet van Sint"
- "Strofe 3 rijmt niet lekker, probeer die opnieuw"

---

## Waar de skill op let

De meeste Sinterklaasgedichten gaan mis op zinnen die er alleen staan om te
rijmen: "dat is wel waar", "met al je zin", "dat is bekend". Deze skill
werkt andersom: eerst wat er gezegd moet worden, dan pas het rijm. Verder:

- rijm op klank, niet op spelling (*vindt* rijmt op *Sint*);
- regels die ongeveer even lang zijn, zodat je niet struikelt bij het
  voorlezen;
- gewone woordvolgorde, geen "een pakje Piet hier heeft verstopt";
- één spreker en een verhaal dat klopt;
- niets verzinnen over de ontvanger, want de hele kamer kent die persoon;
- Sinterklaas is geen kerst, en Piet wordt nooit naar uiterlijk beschreven;
- geen gedachtestreepjes en geen AI-taal als "magisch" of "onvergetelijk".

---

## Goed om te weten

- **Lees het gedicht altijd zelf hardop voor** voordat je het print. Een
  taalmodel maakt nog weleens een rijm dat net niet lekker loopt; laat die
  ene strofe dan opnieuw schrijven.
- **Controleer de feiten.** Claude gebruikt alleen wat jij vertelt, maar
  check of namen en details kloppen.
- **Een gedicht met echte details is altijd beter** dan een gedicht met
  algemene. Drie specifieke dingen zijn meer waard dan tien vage.

---

## Bestanden

- `sinterklaas-rijm/SKILL.md`: de regels voor Claude.
- `sinterklaas-rijm/references/voorbeelden.md`: goede gedichten, en fouten met
  uitleg waarom ze fout zijn.

---

## Over Sinterklaasspeurtocht.nl

Deze skill komt van [Sinterklaasspeurtocht.nl](https://sinterklaasspeurtocht.nl):
speurtochten in jullie eigen huis, waarin Sinterklaas in WhatsApp met de
kinderen meepraat en de aanwijzingen als raadsels op rijm stuurt. Op
[sinterklaasspeurtocht.nl/ideeen](https://sinterklaasspeurtocht.nl/ideeen)
staan nog meer gratis tips voor pakjesavond.

---

## Licentie

[CC BY 4.0](https://creativecommons.org/licenses/by/4.0/deed.nl): je mag
deze skill gebruiken, aanpassen en verder delen, ook commercieel, zolang je
de bron noemt. Zo bijvoorbeeld:

> Gebaseerd op de Sinterklaas-rijmskill van
> [Sinterklaasspeurtocht.nl](https://sinterklaasspeurtocht.nl/ideeen/sinterklaasgedicht-schrijven),
> CC BY 4.0.

Geef ook aan of je iets hebt veranderd. De volledige tekst staat in
[LICENSE](LICENSE).

Voor de gedichten die je met de skill schrijft, hoef je niets te vermelden:
de licentie gaat over de skill zelf.
