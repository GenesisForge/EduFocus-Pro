# 🇩🇰 Danish (Dansk)

# Privatlivspolitik - EduFocus Pro

**Sidst opdateret:** 5. oktober 2025  
**Version:** 3.0.0  
**Ikrafttrædelsesdato:** 1. oktober 2025

---

## Vores privatlivsforpligtelse

EduFocus Pro er designet med **privatlivs-først principper**. Vi tror på, at elever fortjener værktøjer, der respekterer deres data og deres ret til at lære uden overvågning.

Denne politik bruger et klart sprog, fordi privatliv ikke bør kræve en juridisk grad at forstå.

**Vores kerne-løfte: Dine data forbliver på din enhed. Punktum.**

---

## Indholdsfortegnelse

1. [Hvilke data vi indsamler](#hvilke-data-vi-indsamler)
2. [Hvor dine data bor](#hvor-dine-data-bor)
3. [Hvad vi IKKE gør](#hvad-vi-ikke-gør)
4. [Browser-tilladelser](#browser-tilladelser)
5. [Internetforbindelser](#internetforbindelser)
6. [GDPR-overholdelse](#gdpr-overholdelse-europaeiske-union)
7. [Børns privatliv](#boerns-privatliv-coppa--gdpr-k)
8. [Håndtering af dine data](#haandtering-af-dine-data)
9. [Datasikkerhed](#datasikkerhed)
10. [Tredjeparts-tjenester](#tredjeparts-tjenester)
11. [Ændringer i denne politik](#aendringer-i-denne-politik)
12. [Kontakt & verifikation](#kontakt--verifikation)

---

## Hvilke data vi indsamler

**Ingen.**

EduFocus Pro indsamler **nul personlige data**. Vi sporer dig ikke, vi profilerer dig ikke, og vi ved ikke, hvem du er.

**Ingen analyser. Ingen telemetri. Ingen sporing. Intet.**

Vi ved ikke:
- ❌ Hvem du er (navn, e-mail, alder, placering)
- ❌ Hvad du studerer, eller hvordan du præsterer
- ❌ Hvornår eller hvor længe du bruger udvidelsen
- ❌ Hvilken enhed eller browser du bruger
- ❌ Nogen brugsstatistik eller mønstre
- ❌ Bogstaveligt talt noget som helst om dig

---

## Hvor dine data bor

Alle data, der oprettes i EduFocus Pro, gemmes **lokalt på din enhed** ved hjælp af Chromes krypterede lokale lager-API (`chrome.storage.local`).

### Hvad der gemmes lokalt

Din enhed gemmer:

- ⏱️ **Timer-indstillinger og historik** - Pomodoro-konfigurationer, afsluttede sessioner
- 🎯 **Fokus-statistik** - Studietid, streaks, produktivitetsmålinger
- 📝 **Noter** - Al tekst, formatering, tags og organisering
- 🧠 **Quiz** - Brugerdefinerede quiz, spørgsmål, svar, resultater
- 🗂️ **Flashcards** - Dæk, kort, studie-fremskridt, data for spredt gentagelse
- 📅 **Opgaver** - To-dos, deadlines, prioriteter
- ⚙️ **Indstillinger** - Sprog, tema, tilgængelighedsindstillinger

### Hvordan det gemmes

- **Format:** JSON (JavaScript Object Notation) - læsbart, standardformat
- **Kryptering:** Beskyttet af Chromes indbyggede lagerkryptering
- **Placering:** Din browsers profilmappe på din harddisk
- **Adgang:** Kun du og EduFocus Pro-udvidelsen kan få adgang til disse data

### Hvad dette betyder

**Disse data forlader aldrig din computer.** De er ikke:
- ❌ Uploadet til servere
- ❌ Sendt til cloud-tjenester
- ❌ Delt med tredjeparter
- ❌ Tilgængelige for Genesis Forge
- ❌ Overført over internettet

**Tænk på det som en notesbog:** Når du skriver i en fysisk notesbog, forbliver noterne i den notesbog. Samme koncept, men digitalt.

### Chrome Sync (Valgfrit)

Hvis du har Chrome sync aktiveret i dine browserindstillinger:
- Chrome kan synkronisere dine EduFocus Pro-data til din Google-konto
- Dette er en **Chrome-funktion**, ikke en EduFocus Pro-funktion
- Vi har ingen kontrol over eller indsigt i Chrome sync
- Data synkroniseret via Chrome er krypteret af Google

**For at deaktivere udvidelsessync:**
1. Gå til `chrome://settings/syncSetup`
2. Klik på "Administrer sync"
3. Deaktiver "Udvidelser" sync
4. Dine EduFocus Pro-data vil forblive kun lokale

---

## Hvad vi IKKE gør

### Dataindsamling
- ❌ Indsamle personlige oplysninger
- ❌ Spore browserhistorik
- ❌ Bruge analyser eller telemetri
- ❌ Installere cookies eller sporingspixels
- ❌ Overvåge aktiviteter
- ❌ Profilere eller fingeraftrykke brugere
- ❌ Logge IP-adresser
- ❌ Optage tastetryk
- ❌ Indsamle brugsstatistik

### Datadeling
- ❌ Dele data med tredjeparter
- ❌ Sælge eller monetisere dine data
- ❌ Levere data til annoncører
- ❌ Sende data til eksterne tjenester
- ❌ Rapportere til skoler eller forældre

### Annoncering & Marketing
- ❌ Vise annoncer
- ❌ Bruge annoncenetværk
- ❌ Markedsføre til børn
- ❌ Sende reklame-e-mails
- ❌ Bygge målrettingsprofiler

### Konti & Autentificering
- ❌ Kræve kontooprettelse eller login
- ❌ Anmode om adgangskoder
- ❌ Gemme legitimationsoplysninger
- ❌ Autentificere brugere

### Enhedsadgang
- ❌ Få adgang til dit kamera (nogensinde)
- ❌ Få adgang til din mikrofon (undtagen stemmenoter - se nedenfor)
- ❌ Få adgang til din placering
- ❌ Læse dine filer
- ❌ Få adgang til dine kontakter
- ❌ Overvåge udklipsholder (undtagen når du indsætter)

---

## Browser-tilladelser

EduFocus Pro anmoder om minimale Chrome-tilladelser. Her er præcis, hvad vi beder om og hvorfor:

### ✅ Lager (Påkrævet)
**Tilladelse:** `storage`

**Hvorfor vi har brug for det:**
- For at gemme dine noter, timere, indstillinger og studiematerialer lokalt
- Uden dette ville intet blive gemt, når du lukker udvidelsen

**Hvad vi kan få adgang til:**
- Kun vores eget lagerplads (isoleret fra andre udvidelser og websteder)
- Kan ikke læse data fra andre udvidelser
- Kan ikke få adgang til cookies eller browserhistorik

**Sikkerhed:**
- Data krypteret af Chrome automatisk
- Ingen netværksoverførsel af disse data

### 🎤 Mikrofon (Valgfrit - Kun når anmodet)
**Tilladelse:** `microphone` (valgfrit)

**Hvorfor vi har brug for det:**
- Til stemmediktat-funktionen i fanen Noter
- Tillader stemme-til-tekst notetagning

**Når det bruges:**
- **Kun** når du klikker på mikrofonknappen i Noter
- Kører aldrig i baggrunden
- Tilladelsesanmodning vises første gang du bruger funktionen

**Hvordan du kan kontrollere det:**
- Afvis tilladelsesanmodningen, når den vises
- Tilbagekald når som helst: `chrome://settings/content/microphone`
- Eller: `chrome://extensions` → EduFocus Pro → Fjern tilladelser

**Hvad vi gør med lyd:**
- Lyd behandles lokalt af Chromes Web Speech API
- Ingen lyd optages, gemmes eller overføres
- Ingen lydfiler oprettes
- Behandling sker helt på din enhed

### ❌ Tilladelser vi IKKE anmoder om

Vi anmoder **ikke** om:
- `tabs` - Kan ikke se, hvilke websteder du besøger
- `history` - Kan ikke få adgang til browserhistorik
- `cookies` - Kan ikke læse cookies
- `webRequest` - Kan ikke opsnappe netværkstrafik
- `geolocation` - Kan ikke få adgang til placering
- `camera` - Kan ikke få adgang til webcam
- `downloads` - Kan ikke få adgang til downloads
- `bookmarks` - Kan ikke læse bogmærker

### Hvordan man verificerer tilladelser

1. Gå til `chrome://extensions/`
2. Find EduFocus Pro
3. Klik på "Detaljer"
4. Rul til "Tilladelser"
5. Gennemgå alle anmodede tilladelser

Du bør kun se Lager (og Mikrofon, hvis du har aktiveret stemmenoter).

---

## Internetforbindelser

EduFocus Pro fungerer **100% offline** efter den indledende installation.

### 1. Eksterne ressource-links (Valgfrit)

Ressource-fanen giver links til uddannelseswebsteder. Disse er standard hyperlinks, der åbner i din browser.

**Danske uddannelsesressourcer:**
- 📚 **Undervisningsministeriet** (uvm.dk) - Undervisningsministeriet
- 🎓 **Khan Academy** (da.khanacademy.org) - Gratis uddannelsesvideoer
- 🔬 **Videnskab.dk** - Videnskabsnyheder og artikler
- 📖 **Den Store Danske** (lex.dk) - Dansk encyklopædi
- 📺 **DR Skole** (dr.dk/skole) - DR's uddannelsesindhold

**Hvad vi gør:**
- ✅ Levere bekvemme links til uddannelsesressourcer
- ✅ Åbne links i nye faner (standard browseradfærd)

**Hvad vi IKKE gør:**
- ❌ Spore, hvilke links du klikker på
- ❌ Modtage rapporter om din aktivitet
- ❌ Overføre dine data til disse websteder
- ❌ Tilføje sporingsparametre til URL'er
- ❌ Modtage henvisningsprovisioner (ikke affiliatelinks)

**Vigtigt:** Når du klikker på disse links, besøger du eksterne websteder med deres egne privatlivspolitikker. Vi er ikke ansvarlige for deres datapraksis.

### 2. Chrome Web Store-opdateringer (Automatisk)

**Hvad sker der:**
- Chrome tjekker automatisk for udvidelsesopdateringer
- Administreret af Google, ikke af os

**Hvad vi ikke gør:**
- ❌ Kontrollere, hvornår der tjekkes for opdateringer
- ❌ Vide, hvornår du opdaterer
- ❌ Modtage rapporter om installationer
- ❌ Spore opdateringsaktivitet

### 3. Ingen anden netværksaktivitet

**Verifikationsmetoder:**

**Metode 1: Browser DevTools**
1. Åbn EduFocus Pro
2. Tryk på F12 for at åbne DevTools
3. Gå til Network-fanen
4. Brug alle funktioner
5. Observer: Nul netværksanmodninger

**Metode 2: Offline-test**
1. Frakobl fra internettet
2. Brug alle funktioner
3. Observer: Alt virker perfekt

---

## GDPR-overholdelse (Europæiske Union)

EduFocus Pro overholder fuldt ud den Generelle Forordning om Databeskyttelse (GDPR - Forordning 2016/679).

### Dine GDPR-rettigheder

Da vi ikke indsamler personlige data, gælder de fleste GDPR-krav ikke, men her er, hvordan vi håndterer hver ret:

#### Ret til adgang (Artikel 15)
**Hvad det betyder:** Ret til at få adgang til dine data.

**Hvordan vi overholder:**
- Alle dine data er på din enhed og tilgængelige når som helst
- Eksporter dine data: Indstillinger → Eksporter alle data
- Ingen data for os at levere - du har fuld adgang

#### Ret til berigtigelse (Artikel 16)
**Hvad det betyder:** Ret til at rette unøjagtige data.

**Hvordan vi overholder:**
- Du kontrollerer alle data lokalt
- Rediger noter, flashcards, quiz direkte
- Behov ikke at kontakte os

#### Ret til sletning (Artikel 17)
**Hvad det betyder:** Ret til at få dine data slettet.

**Hvordan vi overholder:**
- Indstillinger → Ryd alle data (permanent sletning)
- Eller afinstaller udvidelsen
- Vi har ingen kopier, fordi vi aldrig indsamlede det

#### Ret til dataoverførsel (Artikel 20)
**Hvad det betyder:** Ret til at modtage dine data i et bærbart format.

**Hvordan vi overholder:**
- Indstillinger → Eksporter alle data
- Opretter standard JSON-fil
- Overfør til andre værktøjer eller enheder

#### Ret til at gøre indsigelse (Artikel 21)
**Hvad det betyder:** Ret til at gøre indsigelse mod behandling.

**Hvordan vi overholder:**
- Ikke relevant - ingen ekstern behandling
- Du kan stoppe med at bruge udvidelsen når som helst

### Retsgrundlag for behandling

Vi behandler lokale data baseret på:

**Artikel 6(1)(a) - Samtykke:**
- Du installerer og bruger frivilligt
- Du kan afinstallere når som helst

**Artikel 6(1)(f) - Berettiget interesse:**
- Lokal lagring er nødvendig for, at udvidelsen kan fungere
- Minimal behandling, maksimal privatliv

**Vigtigt:** Da data aldrig forlader din enhed, er dette som at skrive i en fysisk notesbog - ingen databehandling i GDPR-forstand sker hos os.

### Dataansvarlig information

**Dataansvarlig:** Genesis Forge  
**Placering:** Danmark  
**Kontakt:** edufocusbusiness@gmail.com

### Tilsynsmyndighed

**Datatilsynet** (Danske Datatilsyn)  
**Websted:** datatilsynet.dk  
**E-mail:** dt@datatilsynet.dk  
**Telefon:** +45 33 19 32 00

Du har ret til at indgive klager til Datatilsynet eller din lokale databeskyttelsesmyndighed.

---

## Børns privatliv (COPPA & GDPR-K)

EduFocus Pro er designet til studerende i alle aldre, inklusiv børn. Vi tager børns privatliv ekstremt alvorligt.

### COPPA-overholdelse (USA - Under 13)

**Hvordan vi overholder:**

✅ **Ingen dataindsamling**
- COPPA-kompatibel ved design
- Ingen personlige oplysninger indsamlet fra nogen, inklusiv børn

✅ **Ingen forældresamtykke påkrævet**
- Ikke nødvendigt, fordi vi ikke indsamler data
- Ingen registrering eller konti

✅ **Ingen annoncering**
- Ingen annoncer vist
- Ingen adfærdsbaseret annoncering
- Ingen markedsføring til børn

✅ **Ingen sporing**
- Ingen vedvarende identifikatorer
- Ingen brugerprofilering
- Ingen overvågning

✅ **Forældrerettigheder**
- Forældre kan gennemgå alle data (de er på enheden)
- Forældre kan slette alle data (afinstaller eller ryd)
- Forældre kan nægte indsamling (der er ingen)

### GDPR-K-overholdelse (Europæiske Union - Børn)

**Hvordan vi overholder:**

✅ **Ingen forældresamtykke påkrævet**
- Ikke nødvendigt, fordi vi ikke indsamler data
- Børn kan bruge uden autorisation

✅ **Alders passende**
- Klar, simpel grænseflade
- Uddannelsesfokus
- Ingen kommercielt pres

✅ **Ingen profilering**
- Ingen algoritmiske beslutninger
- Ingen målretning
- Ingen adfærdsanalyse

### For forældre & lærere

**Hvordan man inspicerer gemte data:**

**Metode 1: Eksport**
1. Åbn EduFocus Pro
2. Indstillinger → Eksporter alle data
3. Gennemgå JSON-filen i teksteditor

**Metode 2: DevTools**
1. Åbn EduFocus Pro
2. Tryk på F12 → Application → Local Storage
3. Find EduFocus Pro-post
4. Gennemgå alle data (almindelig JSON)

**Hvad du vil se:**
- Noter, flashcards, quiz (læsbar tekst)
- Studiestatistik (tal, datoer)
- Indstillinger (sprog, tema, osv.)

**Hvad du IKKE vil se:**
- Ingen sporings-ID'er
- Ingen brugeridentifikatorer
- Ingen analyser
- Ingen skjulte data

---

## Håndtering af dine data

### Eksporter dine data

**Formål:** Backup eller overførsel til en anden enhed.

**Sådan eksporterer du:**
1. Åbn EduFocus Pro
2. Indstillinger → Eksporter alle data
3. Vælg gemmeplacering
4. JSON-fil downloades

**Hvad er inkluderet:**
- Alle noter, flashcards, quiz
- Studiestatistik og historik
- Indstillinger og præferencer

**Filformat:** Standard JSON (læsbar i teksteditor)

**Brugssager:**
- 💾 Regelmæssige backups (anbefalet!)
- 📱 Overførsel mellem enheder
- 🔍 Se præcis, hvad der er gemt

### Importer dine data

**Sådan importerer du:**
1. Indstillinger → Importer data
2. Vælg JSON-backupfil
3. Bekræft (overskriver eksisterende data)
4. Data gendannes med det samme

⚠️ **Advarsel:** Importering erstatter ALLE nuværende data. Eksporter først, hvis du vil beholde det.

### Slet dine data

**Mulighed 1: Ryd alle data**
- Indstillinger → Ryd alle data
- Bekræfter to gange (forhindrer uheld)
- Alle data slettes permanent
- Udvidelsen forbliver installeret

**Mulighed 2: Afinstaller**
- `chrome://extensions/` → Fjern
- Komplet fjernelse
- Alle data slettes

**Mulighed 3: Selektiv sletning**
- Slet individuelle noter, dæk eller quiz
- Bevar andre data intakte

⚠️ **Sletning er permanent.** Eksporter først, hvis du måske vil have data senere.

---

## Datasikkerhed

Da data gemmes lokalt, afhænger sikkerheden af din enhedssikkerhed.

### Hvad der beskytter dine data

✅ **Chromes krypterede lager**
- Automatisk kryptering af Chrome
- OS-niveau beskyttelse (DPAPI på Windows, Keychain på Mac)

✅ **Enhedssikkerhed**
- Din enheds adgangskode/PIN
- Fuld disk-kryptering (BitLocker, FileVault)
- Antivirussoftware

✅ **Browsersikkerhed**
- Chromes sandboxing
- Udvidelsesisolering
- Regelmæssige sikkerhedsopdateringer

### Sikkerhedsbedste praksis

**For personlige enheder:**
1. Brug stærk enhedsadgangskode
2. Aktiver fuld disk-kryptering
3. Hold Chrome opdateret
4. Lås computer, når du er væk
5. Eksporter regelmæssige backups
6. Brug antivirussoftware

**For delte computere (skole, bibliotek):**
1. Brug separat Chrome-profil
2. Aktiver Chrome-profil-låsning
3. Eksporter backups til personlig USB/cloud
4. Ryd data, før du logger ud
5. Lad aldrig computer være ulåst
6. Gem ikke følsomme oplysninger i noter

### Hvad vi ikke kan beskytte imod

Da data er lokale, kan vi ikke beskytte imod:

❌ **Fysisk enhedsadgang**
- Nogen med adgang til din ulåste enhed kan se dine data
- **Mitigering:** Lås enhed, stærke adgangskoder

❌ **Malware**
- Malware kan få adgang til lokale data
- **Mitigering:** Antivirus, forsigtige downloads

❌ **Tabte/stjålne enheder**
- Data tilgængelige, hvis enheden ikke er krypteret
- **Mitigering:** Fuld disk-kryptering, fjernsletning

### Databrud-respons

**Kan EduFocus Pro blive brudt eksternt?**

Nej. Fordi der ikke er en central database:
- Ingen servere at hacke
- Ingen dataoverførsel at opsnappe
- Ingen "EduFocus Pro database" eksisterer

Din datasikkerhed afhænger fuldstændig af din enhedssikkerhed.

**Hvis din enhed er kompromitteret:**
- Standard sikkerhedspraksis gælder (malwareskan, adgangskodeændringer)
- Vi kan ikke fjernadgang til eller slette dine data
- Du er ansvarlig for enhedssikkerhed

**Rapporter sikkerhedssårbarheder:**
E-mail: edufocusbusiness@gmail.com  
Emne: **SIKKERHEDSSÅRBARHED**

Vi tager sikkerhedsrapporter alvorligt og svarer inden for 24 timer.

---

## Tredjeparts-tjenester

EduFocus Pro integrerer ikke med nogen tredjeparts-tjenester for kernefunktionalitet.

### Eksterne links

Ressource-fanen linker til uddannelseswebsteder. Disse er standard hyperlinks - ingen sporing, ingen datadeling.

**Linkede websteder:**
- Undervisningsministeriet (uvm.dk)
- Khan Academy (da.khanacademy.org)
- Videnskab.dk
- Den Store Danske (lex.dk)
- DR Skole (dr.dk/skole)

Disse websteder har deres egne privatlivspolitikker. Vi er ikke ansvarlige for deres praksis.

### Ingen andre integrationer

Vi bruger **ikke**:
- ❌ Analysetjenester (Google Analytics, osv.)
- ❌ Crash-rapportering (Sentry, osv.)
- ❌ Annoncenetværk
- ❌ Cloud-lager
- ❌ Autentificeringsudbydere
- ❌ Eksterne API'er

**Alt kører lokalt.**

---

## Ændringer i denne politik

Hvis vi opdaterer denne politik:

1. ✅ Opdater "Sidst opdateret" dato
2. ✅ Forøg versionsnummer
3. ✅ Inkluder detaljer i udgivelsesnoter
4. ✅ Vis notifikation i udvidelsen (for store ændringer)

**Vores kerneforpligtelse vil ALDRIG ændre sig: Dine data forbliver på din enhed.**

### Versionhistorik

**v3.0.0 (oktober 2025)** - Nuværende version
- Balanceret detaljer og læsbarhed
- Forbedret klarhed

**v2.0.0 (oktober 2025)**
- Udvidede GDPR/COPPA-sektioner
- Tilføjede tilladelsesdetaljer

**v1.0.0 (Første udgivelse)**
- Oprindelig privatlivspolitik

---

## Kontakt & verifikation

### Kontakt os

**Privatlivsspørgsmål eller bekymringer:**

📧 **E-mail:** edufocusbusiness@gmail.com  
🕐 **Svartid:** Inden for 7 hverdage  
🗣️ **Sprog:** Dansk, engelsk

**For sikkerhedsproblemer:** Brug emne "SIKKERHEDSSÅRBARHED"

### Verificer vores påstande

Stol ikke bare på os - verificer:

**✅ Tjek netværksaktivitet**
1. Åbn EduFocus Pro + DevTools (F12)
2. Network-fane → Brug alle funktioner
3. Se: Nul anmodninger

**✅ Tjek tilladelser**
1. `chrome://extensions/` → EduFocus Pro → Detaljer
2. Se: Kun Lager (+ valgfri Mikrofon)

**✅ Tjek gemte data**
1. Indstillinger → Eksporter alle data
2. Åbn JSON i teksteditor
3. Se: Kun dit indhold

**✅ Test offline**
1. Frakobl internet
2. Brug alle funktioner
3. Se: Alt virker

---

## Jurisdiktion & gældende lov

**Udviklet i:** Danmark 🇩🇰  
**Styret af:** GDPR (Forordning 2016/679) og dansk lov  
**Tilsynsmyndighed:** Datatilsynet (datatilsynet.dk)

For juridiske spørgsmål specifikke for din region, kontakt lokale myndigheder.

---

## Tilgængelige sprog

Denne privatlivspolitik er tilgængelig i:
- 🇬🇧 Engelsk (privacy_en.md)
- 🇩🇰 Dansk (privacy_da.md)
- 🇩🇪 Tysk (privacy_de.md)
- 🇺🇦 Ukrainsk (privacy_uk.md)

Brug for et andet format? E-mail os for store udskrifter, skærmlæser-optimerede eller forenklede versioner.

---

## Hvorfor vi byggede det sådan

**Studerende fortjener privatliv, mens de lærer.**

For mange uddannelsesværktøjer sporer studerende, indsamler data og prioriterer engagement over uddannelse. Vi byggede EduFocus Pro anderledes:

- 📚 **Uddannelsesfokuseret** - Læring, ikke overvågning
- 🔒 **Privatliv-først** - Bygget med privatliv fra dag ét
- 🆓 **Virkelig gratis** - Ingen skjulte omkostninger eller dataindsamling
- 💪 **Brugerkontrolleret** - Dine data, din enhed, dit valg

**Dette er uddannelsessoftware bygget, som den skal være: Privat, sikker og fokuseret på læring.**

---

## Simpel opsummering

**Dine data = Din forretning**

Alt forbliver på din computer. Vi kan ikke se det, vil ikke se det, og designede systemet, så vi ikke kunne se det, selvom vi ville.

### Kerne-løfte
- **Indsaml:** Intet
- **Spor:** Intet
- **Del:** Intet
- **Gem eksternt:** Intet

### For alle

**Studerende:** Studér privat uden overvågning  
**Forældre:** Dit barns data forbliver sikre  
**Lærere:** Anbefal med tillid  
**Alle:** Privatliv uden kompromis

---

**Spørgsmål? E-mail os: edufocusbusiness@gmail.com**

**Denne politik er gældende fra oktober 2025 og gælder for EduFocus Pro v3.5.0 og senere.**

© 2025 Genesis Forge. Licenseret under PROPRIETARY License.

---

**Privatliv er en ret, ikke en privilegie.**

---