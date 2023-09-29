# Bilde Galleri (oppgave instrukser)

Denne ukens oppgave vil være å lage et bildegalleri der du bruker CSS media-queries for å sette opp ulike bryte punkt på hvordan nettsiden skal se ut på ulike skjermer. Et eksempel kan være tre bilder på desktop, to bilder på tablet og et bilde på mobil. Du skal selv velge hvilket tema du ønsker å bruke og hvor mange elementer du vil skal være med. Inspirasjon kan være en hobby. Et bilde galleri trenger ikke nødvendigvis å kun være bilder, eller kun være om en ting. Bruk kreativitet og del ideer med hverandre😄

Tenk over hvordan nettsiden ser ut både med plassering, farger og tekst som er med. Oppgaver vi har igjennom kurset er prosjekter som skal inn på portfolio hjemmesiden deres. Så tenk over hva dere velger å ha tema om og hvordan dere velger å presentere det.

        # Krav:
        - Semantisk korrekt HTML
        - En fornuftig fargepalett på nettsiden (Hint: coolors.co)
        - Tre media-query bryte punkt: Mobil, Tablet og Desktop

        # Leverings Metode:
        - Lenke til GitHub Repo (Dette repositoriet må være Public)
        - Lenke til live nettside (Netlify)

Frist: 29 sept 2023, kl. 15:00




# Egne notater:
- Etter mye grubling på hva sidens fokus/tema skulle være, da der var et hav av muligheter, landet jeg på The Good Place, en "feel-good" serie fra 2016-2020.
- Tanken er å lage noen kort til hver av hovedrollene med et sitat, muligens se over "famous last words". Der er jo litt å velge av i den kategorien, ettersom at de dør mer enn en gang i løpet av serien.
- Steg 1 er i midlertid å samle matriell, som bilder, litt info og se etter passende sitater.
- Da det var vanskelig å finne gode bilder i lignende og greie størrelser, valgte jeg å fokusere på å finne bilder som passer rollenes personlighet og redigerte dem i Paint MS og Gimp.
- Farge palett er også en grei ting å finne, hentet fra coolors.co:
        - Mørkest blå: #000814
        - Mellom blå: #001d3d
        - Blå: #003566
        - Gul(oak?): #ffc300 
        - Lys Gul: #ffd60a

- Vurderte først å ha mellomblå bakrgunn med gul tekst, men syns siden blir for mørk i kontrast til serien, som for det meste er lett og fokuserer på humor, prøver derfor med gul bakgrunn og mørkeblå tekst. 
- Vil endre teksten til en litt lysere blåfarge, da den ikke var så tydlig blå slik den er nå.

- Satt en stund og undret på hvorfor siden ikke ville skalere riktig, så nå at jeg hadde glemt å targette class med grid'en som skal skaleres i @media query...
- Er godt mulig jeg ikke trenger max-width på både img og imgBox, men syns siden fungerte bedre når den er på begge to.
- På tide å leke seg litt med fargene på rolle-kortene(imgBox), satt det orginalt opp som background-color: #ffc300 og border: 3px solid #f8f85d. Prøvde på en blå border (#001d3d). Testet blå background, gul(oak) border og gul tekst, kunne muligens vært en grei idè til darkmode setting? - endret gul(oak) border til #f8f85d, da oak fargen var vanskelig å se.
- Syns kortene popper mer frem når bakgrunnen er gul og kortene er blå, blir trolig denne kombinasjonen. Ser at border-radius kan justeres for en bedre representasjon. Kankje greit å teste om den skal være solid eller ha en annen form.
- Tanke: light-mode med gul bakgrunn - blå tekst og blå kort med gul tekst. Dark mode med blå bakgrunn - gul tekst og gule kort med blå tekst? 
- Merker jeg ikke er veldig glad i farge kombinasjonen, men valgte farger som minner om en av de mer kjente plakatene og dvd-coveret til serien.
- Ser nå at blåfargen fra coolors.co er noe mørk i henhold til seriens blåfarge, vurderer å endre den til en blåfarge som er nærmere seriens.
- Føler teksten er liten, juster i css! Sett undeline på rollenes navn.
- prøvde å minimere css kode og heller ha flere klasser, skal se over når koden er helt ferdig å se hvor/hvordan jeg kan gjøre den tørrere.

- Legger ved en footer med et sitat som er mye brukt av flere av rollene i serien på toppen, kildekode, mitt navn og navn på skapere av serien og hovedrollenes skuespillere.
- Ble litt ekstra css til flex bokser i footeren, vil tro dette kan gjøres tørrere, men begynner å gå tom for tid da lokalene her stenger tidligere idag. Så da velger jeg å fokusere på funksjon via Netlify og eventuell "troubleshooting".



# Sitater til vurdering: (sitater markert med 1-tall er mest aktuell)

Eleanor Shellstrop:
- "Ya basic!" (1)
- All humans are aware of death. So we're all a little bit sad all the time. That's just the deal.
- I know it sounds crazy, but if it weren’t crazy, they wouldn’t call it a leap of faith. They’d call it a sit of doubting
- I mean, somebody royally forked up. Somebody forked up. Why can't I say 'fork'?
- Holy Forking shirtballs, we're in the good place. (2)

Chidi Anagonye:
- Well, I've narrowed it down to two possibilities: yes and no.
- You broke the world. It's not a compliment!
- Ugh, I Have a stomach ache (1)
- I once got lost on an escalator
- Please don't ask me that right now! (2)

Tahani Al Jamil:
- I Just Want To Sit, Stare At Nothing, And Silently Scream For The Rest Of Time.
- I want to speak to your manager. (1)
- I would say I outdid myself, but I'm always this good. So I simply did myself.
- Such fun, cheers!
- I died.. in Cleveland? (2)

Jason Mendoza:
- I'm from Jacksonville, florida. It happens a lot.
- Oh dip! (1)
- I wasn't a failed DJ — I was pre-successful. (2)
- Jacksonville Jaguars rule!
- Bortles!

Janet(Entity of knowledge):
- Not a girl (1)
- Oh, really? Is it an error to act unpredictably and behave in ways that run counter to how you were programmed to behave? (2)
- Just press that button and it's "goodbye Janet"
- Hello, how can I help you?

Michael (Demon)
- Time in the afterlife moves in a Jeremy Bearime
- Yeah, ok, it's a torture museum. (3)
- Fair is the stupidest word humans ever invented, except for 'staycation.
- Kissing is gross (2)
- I don't know, it makes people happy? (1)