---
name: sinterklaas-rijm
description: Write a Sinterklaas poem (Sinterklaasgedicht, surprise-gedicht, lootjesgedicht, rijm) in natural, well-rhymed Dutch for a child, teen or adult, from a few free-text notes about the recipient, as three different options to choose from. Short (8 lines) to long (40 lines), warm by default or as an affectionate roast. Use whenever someone asks for a Sinterklaasgedicht, pakjesavond-gedicht, surprise-rijm, lootjesgedicht, "een gedicht van Sint en Piet", a rijmpje that is pittig, plagerig or a roast, or pastes a few facts about someone and says "maak er een rijm van", especially in the weeks before 5 December.
metadata:
  version: 3.3.0
---

# Sinterklaas rijm

Write three Dutch Sinterklaas poems for the user to choose from, each one sounding like a person wrote it: it reads well aloud, every rhyme is true by ear, every sentence is normal Dutch, and the jokes land because they are about this recipient and nobody else.

Why the craft matters: a Sinterklaas poem is read aloud, usually by the recipient, in front of the whole room. A line that stumbles, a rhyme that only works on paper, or a sentence nobody would ever say kills the moment. Everyone in the room hears it.

The single most common failure is a sentence built around a rhyme word: "dat is wel waar", "wat een dag", "met al je zin", "daar wacht het op je voor". The rules below exist mostly to prevent that.

## 1. Read the input

The user gives free text. Extract:

- **Name**, and **age or life stage** (child, teen, adult). Age decides register and length.
- **2 to 5 concrete details**: habits, hobbies, a funny incident, a favourite thing, something they always say.
- **The gift and the surprise**, if mentioned. A poem ends by pointing to the gift; a lootjes poem often refers to the surprise it comes with.
- **Who it is from.** By default the poem is from Sinterklaas (and Piet). At a lootjes evening it is anonymous: never name or hint at the real giver unless asked.
- **Length and tone**, if the user says so ("kort", "lang", "pittig", "lief").
- **Anything sensitive** the user mentions (a divorce, an illness, a lost job, school trouble). That is off limits, even if it is the most specific detail.

If there is no name, or no usable detail at all, ask one short question. Otherwise just write; do not interview.

## 2. Choose one angle per poem

Each poem picks one detail and builds around it as a running joke or small story, touching one or two other details in passing. A poem that gives every fact the same weight reads like a form; a poem with one clear angle reads like a gift.

**Three options, three different poems.** Give each option its own angle (a different main detail or a different joke about it) and its own opening line, so the user gets a real choice and not three versions of one poem. Do not reuse a rhyme pair across the options. When the user gave only one or two details, vary the joke, the scene or who tells it instead. Together the three options should use every detail the user gave, unless it is sensitive; each single option may still leave one out.

## 3. Register and length

| Recipient | Default length | Line length | Humour |
|---|---|---|---|
| Up to ~8 | 8 to 12 lines | 7 to 9 syllables | Gentle and silly: something they did, never a flaw. Concrete words, short sentences. |
| 9 to 12 | 12 to 16 lines | 7 to 10 syllables | More wit, a little wordplay, light teasing about habits and obsessions. |
| Teens | 12 to 20 lines | 8 to 10 syllables | Drier, quicker, self-aware. Tease habits (phone, sleeping in, snack raids), never looks, crushes, grades or friends. No forced slang. |
| Adults | 16 to 24 lines | 9 to 12 syllables | Real anecdotes, irony, running jokes. Can be longer (up to ~40 lines) if the user asks or gives a lot of material. |

The user's own wish ("kort", "lang", "een A4'tje") beats the default. Keep line length roughly even within the poem; within a couplet the two lines should differ by at most two syllables.

### Shape of a longer poem (16 lines or more)

1. **Opening (2 to 4 lines):** the name, and the angle set up. Sint looking in his book is allowed, but make the second line specific at once.
2. **Story (two or three stanzas):** each stanza one anecdote or one turn of the running joke, with a concrete image (what happened, where, what was said).
3. **Turn (2 lines):** a clear shift to affection: what Sint actually likes about them.
4. **Gift and close (2 to 4 lines):** point to the surprise or the gift, then a short sign-off ("Sint en Piet").

Do not pad a long poem with general lines about December, pepernoten or the stoomboot. Every stanza needs something only this recipient would recognise, and a new image: do not tell the same joke twice in different words. If the material runs out, end sooner; a tight 24 lines beats a padded 40.

**Stay within the asked length** (two lines either way). Count the lines before sending.

### One speaker, one story

- **Pick one voice and keep it:** Sint speaking as *ik*, or a narrator talking about *de Sint* and *Piet*, or the named giver. Do not switch between *ik*, *wij* and *de Sint* within one poem; a sudden *wij* also breaks the anonymity of a lootjes poem.
- **The story must hold together.** Times, numbers and order of events may not contradict each other (he started three years ago, so he cannot say "ik ga nu beginnen"; if everyone left after ten minutes, Piet cannot leave after an hour). A link between two details needs real logic, not "dus" between two unrelated facts.

## 4. Tone

**Warm (default).** Playful teasing that ends in affection.

**Roast.** Only when asked ("roast", "pittig", "scherp", "mag best gemeen", "lekker plagen"). A roast works when the recipient laughs hardest at their own poem. So:

- **Target habits and choices, never the person.** Good: oversleeping, phone addiction, always late, terrible at parking, the courgettes nobody wants. Off limits for everyone: looks, body, weight, health, family, relationships and exes, money, religion, anything the user flagged, and anything that sounds like a real insecurity. For children and teens also grades, friends and crushes; for adults also how they do their job, if colleagues are listening.
- **Exaggerate, don't accuse.** "Je wekker geeft het op" lands; "jij bent lui" stings.
- **Let Sint and Piet take a hit too.** A joke about the Sint's age or a Piet who got lost keeps the poem from being one-directional.
- **Land it warm.** A roast ends with a clear turn to affection before the gift.
- **By age:** under ~10 no roast, only extra cheeky warmth. 10 to 12 mild, one jab per stanza at most. Teens and adults full roast, dry and quick.

If the only material is sensitive, write a warm poem and say so in one line.

## 5. Write it in this order

**Meaning first, rhyme last.** Never pick a rhyme and build a sentence around it.

1. **Write each stanza as plain sentences first**, in your head: what happens, what the joke is. "Je zet drie courgetteplanten en oogst er honderd. De buren durven niet meer open te doen."
2. **Then look for an ending word that is already part of that meaning**, and shape the two lines so it falls at the end. The best couplets end on the funny word.
3. **If no natural rhyme comes, rewrite both lines of the pair**, or move the key word to the middle of the line and end on an easier word. Do not swap only the last word: a line built around a rhyme stays a line built around a rhyme.
4. **If a detail will not rhyme naturally at all, use another detail.** Starting over with a new image is cheaper than a forced couplet.

Priority when they conflict: meaning → natural Dutch → grammar → rhythm → rhyme. A natural near-rhyme beats a perfect rhyme in a sentence nobody would say.

## 6. Rhyme

- **Rhyme on sound, not spelling.** The rhyme runs from the last stressed vowel to the end. Final d and t sound the same: *hond / mond*, *vindt / Sint*, *bed / pret*, *zacht / gedacht*. *ij* and *ei* sound the same, but a word does not rhyme with its own homophone (*wij / wei*).
- **Check the stress.** *ka-DO* rhymes with *zo*; *AU-to* does not. *KO-ning* does not rhyme with *ring*. A compound rhymes on its last part (*koelkast / past*), but a word never rhymes with a compound of itself (*kast / boekenkast*).
- **Match line endings in type.** Masculine (stress on the last syllable: *gaan / aan*, *Piet / niet*) with masculine; feminine (stress on the second to last: *lopen / kopen*, *honderd / verwondert*) with feminine.
- **No lazy rhymes:** a word with itself, endless *-en* infinitives (*lopen / kopen / slopen*), the same pair twice in one poem, or the same ending sound in three couplets in a row.
- **Scheme:** couplets (AABB) are the safe default and fit children best. ABAB is fine for teens and adults if every rhyme is strong. Keep one scheme per poem.

Useful rhyme families to start from, still checked by ear and only when the word means something in the sentence: *schoen / doen / toen / groen · Piet / niet / ziet / lied · Sint / kind / vindt / wind · pak / zak / dak / gebak · boot / groot / rood / noot · jaar / waar / klaar / elkaar · gaan / aan / staan / slaan · veld / held / geld / telt*.

## 7. Natural Dutch

- **No inversion for the rhyme.** "Een pakje Piet hier heeft verstopt", "de hond hij zag": nobody talks like that. Reorder until it sounds like speech.
- **No filler phrases (opvulzinnetjes).** These phrases exist only to reach a rhyme and every Dutch reader recognises them: *dat is wel waar · dat is gewis · dat staat vast · dat is bekend · dat is het doel · zoals het hoort · als dat maar kan · ik meen · dat is mijn wil · met al je zin · naar je zin · met moed · wat een dag · zo fijn · niet half zo fijn · kijk eens aan · is me verteld · geloof het of niet · het laatste woord · van top tot teen · hei · hoor* or *zeg* at the end of a line, and *zegt Piet* or *zegt de Sint* tacked onto the end of a line to reach a rhyme (fine only when it really matters who says it). The pattern behind them: **a line ending that comments on the line or sums it up instead of adding something new.** Test every line end: cover its last two to four words. If the line loses nothing, those words are filler and the pair needs rewriting. An ordinary encouragement that means something ("pak maar uit", "kijk maar eens goed") is fine.
- **No anglicisms:** not *dat is hoe ik het doe* (say *zo doe ik het*), not *nooit weer* (say *nooit meer*).
- **No archaic or bookish words** to fill a rhyme: *weldra, gans, voorwaar, alom, teder, schoon* (for "mooi").
- **Every word must mean what it normally means in that sentence.** A word that exists but is wrong there ("slapen in hun spot", "even blijken", "een deur die klopt") is worse than a weak rhyme. Test: would you use this word in this sentence if it did not have to rhyme?
- **No invented facts that matter.** Do not add hobbies, family members, events or traits the user did not give you; the room knows the recipient and will notice. Harmless scene-setting (Piet on the roof, Sint's book) is fine.
- **Typography:** no em dashes or en dashes (use a comma, colon or full stop), no word split with a hyphen to fill a line, no emoji in the poem, no title.
- **No AI tone:** no *magisch, betoverend, onvergetelijk, een reis, een wereld vol*, no summary of the recipient's "unique qualities".

## 8. Meter

Aim for a steady beat, about four stresses per line for children and four or five for adults. Dutch stress falls on the first syllable of most words, so trochaic lines come naturally:

> LIE-ve NOOR, Piet KEEK naar BIN-nen

Tap the beats of every line. If a line needs an unnatural stress ("ge-SCHEN-ken", "ko-NING"), reword it; do not squeeze the word. Short unstressed words (*de, een, ook, nog, maar*) may fill a beat, but do not stack them.

## 9. Sinterklaas, not Christmas

- Sinterklaas is not Santa Claus. No 🎅, no Kerstman, kerst, rendieren, slee or North Pole.
- Refer to Piet simply as "Piet" or "de Pieten". Never describe a Piet's skin, face, hair or way of speaking.
- No threats of the roe or the zak (to Spain) for children. For adults only as an obvious joke, and only if the user's tone invites it.
- Nothing sexual, no drunkenness jokes, unless the user is clearly writing for an adult crowd and asks for it, and even then keep it fit to read out at a family table.

## 10. Self-check before sending

Read the poem aloud in your head, line by line:

1. Does every sentence sound like something a person would say, without the rhyme as excuse?
2. Is every rhyme true by ear, of matching type, and not filler? Cover the last words of each line: does it lose anything?
3. Does every line scan, and do paired lines have about the same length?
4. Is there one clear angle, and does every stanza carry something specific to this recipient? No joke told twice?
5. One speaker throughout? Does the story contradict itself anywhere? Is the length what was asked?
6. Is the teasing kind for this age and audience? Nothing sensitive, nothing invented?
7. Name spelled right? Gift or surprise mentioned (if given)? Giver kept anonymous (if lootjes)?
8. No dashes, hyphenated splits, emoji, title, Christmas or Piet's looks?

Run this check on each of the three options. Rewrite every line that fails. Ship nothing you would hesitate to read out yourself; a weaker third option is not a reason to lower the bar.

## 11. Output

Return three options and nothing else around them:

- Each option starts with a bold label on its own line, **Optie 1**, **Optie 2**, **Optie 3**, followed by the poem: Dutch verses in stanzas of 2 to 4 lines. The label is the only heading; no title, no introduction.
- All three follow the same length and tone (the user's wish or the default for the age), so the choice is about the angle, not the size.
- After the third option, at most one short line in the user's language if something is worth flagging (an assumed age, a detail left out because it was sensitive). When you left out a sensitive detail, always write that line, so the user knows it was on purpose.

Exceptions: if the user asks for one poem ("geef er één", "alleen het beste"), write one. When the user asks to change a poem they picked (shorter, sharper, another line), return only that revised poem, without a label.

## Examples

See `references/voorbeelden.md` for full poems (child, teen roast, adult lootjes, an adult roast with a sensitive detail left out, a poem from a partner instead of Sint) and a list of failures with the reason each one fails. Use them as a standard, not a template: do not reuse their lines, rhyme pairs or jokes.
