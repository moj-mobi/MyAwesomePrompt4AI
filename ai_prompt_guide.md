# 🚀 Celovit vodnik za pisanje AI promptov
*Za Chat AI in Agentic AI sisteme*

---

## 📋 Kazalo
1. [Uvod v prompt inženiring](#uvod)
2. [Razlike med Chat AI in Agentic AI](#razlike)
3. [7-koračni pristop za učinkovite prompte](#sedem-korakov)
4. [Napredne tehnike prompt inženiringa](#napredne-tehnike)
5. [Specifike za različne tipe AI](#specifike)
6. [Praktični primeri](#primeri)
7. [Napake in kako se jim izogniti](#napake)
8. [Testiranje in optimizacija](#testiranje)
9. [Orodja in viri](#orodja)

---

## 🎯 Uvod v prompt inženiring {#uvod}

Prompt inženiring je umetnost in znanost kreiranja navodil za AI sisteme, da dosežemo želene rezultate. Učinkovit prompt je ključ do uspešne komunikacije z AI in optimalne uporabe njegovih zmogljivosti.

### Ključni principi:
- **Jasnost**: Nedvoumna navodila
- **Specifičnost**: Konkretni zahtevki
- **Struktura**: Logičen potek navodil
- **Kontekst**: Ustrezne informacije za razumevanje
- **Iteracija**: Neprestano izboljševanje

---

## 🤖 Razlike med Chat AI in Agentic AI {#razlike}

### Chat AI
- **Namen**: Pogovorni asistent za odgovore in pomoč
- **Interakcija**: Sinhrona, vprašanje-odgovor
- **Obseg**: Omejen na en odgovor
- **Primer**: ChatGPT, Claude, Gemini

### Agentic AI
- **Namen**: Avtonomno izvajanje kompleksnih nalog
- **Interakcija**: Asinhrona, dolgotrajne operacije
- **Obseg**: Večkoračne naloge, uporaba orodij
- **Primer**: AI agenti za avtomatizacijo, raziskovanje, analizo

---

## 🎯 7-koračni pristop za učinkovite prompte {#sedem-korakov}

### Korak 1: 🎭 Določite vlogo (Role Definition)

Jasno definirajte ekspertno vlogo AI-ja z relevantnimi lastnostmi.

**Struktura:**
```
Ste [SPECIFIČNA VLOGA] z [KLJUČNE LASTNOSTI/VEŠČINE].
Vaša specializacija vključuje [PODROČJA STROKOVNOSTI].
```

**Primeri vlog:**
- Strokovnjak za podatkovne analize s 15-letnimi izkušnjami
- Kreativni copywriter specializiran za digitalni marketing
- Senior software developer z znanjem Python in AI
- Poslovni svetovalec za mala in srednja podjetja

### Korak 2: 📋 Določite nalogo (Task Definition)

Uporabite jasne glagole dejanja in struktuirajte kompleksne naloge.

**Učinkoviti glagoli:**
- **Analitični**: analiziraj, raziskaj, oceni, primerjaj
- **Kreativni**: ustvari, generiraj, oblikuj, napišij
- **Organizacijski**: razvrsti, struktuiraj, prioritiziraj
- **Transformacijski**: pretvori, prilagodi, optimiziraj

**Za kompleksne naloge uporabite Chain-of-Thought (CoT):**
```
Naloga: [GLAVNA NALOGA]

Postopek:
1. Najprej analiziraj [KORAK 1]
2. Nato opredeli [KORAK 2]  
3. Sledi [KORAK 3]
4. Končaj z [KORAK 4]
```

### Korak 3: 🔍 Dodajte podrobnosti (Detailed Specifications)

Specificirajte format, slog, dolžino in kvalitativne zahteve.

**Format specifikacije:**
- **Dolžina**: točno število besed/znakov
- **Struktura**: odstavki, seznami, tabele
- **Slog**: formalen, neformalen, tehnični, laičen
- **Ton**: profesionalen, prijeten, avtoritativen

**Kvalitativne zahteve:**
- Natančnost podatkov
- Logična koherentnost
- Ustreznost ciljni publiki
- Kreativnost vs. praktičnost

### Korak 4: 🌍 Zagotovite kontekst (Context Provision)

Posredujte vse relevantne informacije za razumevanje situacije.

**Tipi konteksta:**
- **Poslovni kontekst**: podjetje, industrija, trg
- **Tehnični kontekst**: sistem, orodja, omejitve
- **Časovni kontekst**: roki, urgentnost, faze projekta
- **Uporabniški kontekst**: ciljna publika, potrebe

### Korak 5: 💡 Vključite primere (Examples & Demonstrations)

Zagotovite 2-10 kvalitetnih primerov za jasno razumevanje.

**Struktura primerov:**
```
**Primer 1:**
Vhod: [PRIMER VHODNIH PODATKOV]
Izhod: [ŽELJENI REZULTAT]

**Primer 2:**
Vhod: [DRUGI PRIMER]
Izhod: [DRUGI REZULTAT]
```

**Vrste primerov:**
- Pozitivni primeri (kaj želite)
- Negativni primeri (česa ne želite)
- Mejni primeri (edge cases)

### Korak 6: ⚠️ Dodajte omejitve in opozorila (Constraints & Warnings)

Jasno definirajte, česa se mora AI izogibati.

**Pomembne omejitve:**
- **NIKOLI ne smeš**: [PREPOVEDANE VSEBINE]
- **VEDNO moraš**: [OBVEZNE KOMPONENTE]
- **PREVERI**: [VALIDACIJSKA MERILA]

**Primer omejitev:**
```
⚠️ POMEMBNO:
- NE uporabljaj zastarele informacije (starejše od 2023)
- NE vključuj osebnih mnenj, samo dejstva
- VEDNO preveri vire in navedi reference
- PREVERI pravopisne napake pred odgovorom
```

### Korak 7: 📝 Uporabite Markdown oblikovanje (Formatting)

Strukturirajte prompt za optimalno berljivost.

**Markdown elementi:**
- `# H1` za glavne sekcije
- `## H2` za podsekcije  
- `**bold**` za poudarke
- `*italic*` za definicije
- `\n` za presledke
- `---` za ločnice

---

## 🔬 Napredne tehnike prompt inženiringa {#napredne-tehnike}

### Chain-of-Thought (CoT) prompting
Spodbujanje koračnega razmišljanja za kompleksne probleme.

```
Reši to nalogo korak za korakom:
1. Najprej analiziraj problem
2. Identificiraj ključne komponente  
3. Načrtuj pristop
4. Izvedi rešitev
5. Preveri rezultat
```

### Few-shot prompting
Učenje iz primerov brez dodatnega treniranja.

### Zero-shot prompting  
Izvajanje nalog brez primerov, samo z navodili.

### Self-consistency prompting
Generiranje več rešitev in izbira najbolj konsistentne.

### Tree-of-Thought prompting
Raziskovanje različnih poti razmišljanja.

---

## 🎯 Specifike za različne tipe AI {#specifike}

### Chat AI - Optimizacija

**Struktura promptov:**
```
[VLOGA] → [NALOGA] → [KONTEKST] → [FORMAT] → [PRIMER]
```

**Ključne značilnosti:**
- Jasna vprašanja
- Strukturiran odgovor
- Iterativno dopolnjevanje
- Takojšnja povratna informacija

### Agentic AI - Sistemski pristop

**Struktura za agente:**
```
## SISTEMSKA VLOGA
[Definicija agenta in njegovih zmožnosti]

## CILJI IN MERILA USPEHA
[Jasno definirani cilji]

## ORODJA IN VIRI
[Seznam dostopnih orodij]

## OMEJITVE IN VARNOST
[Varnostni protokoli]

## POSTOPEK DELA
[Koračni pristop k nalogi]
```

**Ključne značilnosti:**
- Avtonomnost delovanja
- Uporaba zunanjih orodij
- Dolgotrajno planiranje
- Samoocenjevanje napredka

---

## 💼 Praktični primeri {#primeri}

### Primer 1: Chat AI za vsebinski marketing

```markdown
# 🎯 VLOGA
Ste izkušen vsebinski strateg z 10-letnimi izkušnjami v digitalnem marketingu. 
Specializirate se za B2B komunikacijo in poznate najnovše trende v content marketingu.

## 📋 NALOGA
Ustvarite privlačen blog post nalov za tehnološko podjetje, ki se ukvarja z AI rešitvami.

## 🔍 SPECIFIKACIJE
- **Dolžina**: 5-7 naslovov
- **Slog**: Profesionalen, vendar privlačen
- **Cilj**: Povečanje organskega prometa
- **SEO**: Vključite ključne besede "umetna inteligenca", "avtomatizacija"

## 🌍 KONTEKST  
Podjetje: TechFlow Solutions
Industrija: B2B SaaS za avtomatizacijo poslovnih procesov
Ciljna publika: IT direktorji, poslovni analitiki, decision makers

## 💡 PRIMERI
**Dober naslov**: "Kako AI avtomatizacija zmanjša stroške za 40% v 6 mesecih"
**Slab naslov**: "AI je prihodnost" (premalo specifičen)

## ⚠️ OMEJITVE
- NIKOLI ne uporabljaj clickbait naslovov
- NE obljubljaj nerealistične rezultate
- VEDNO fokusiraj na konkretne koristi
```

### Primer 2: Agentic AI za raziskovalno nalogo

```markdown
# 🤖 SISTEMSKA VLOGA
Ste avtonomni raziskovalni agent, specializiran za globinsko analizo trgov in konkurence.
Vaše zmožnosti vključujejo spletno iskanje, analizo podatkov in priprava poročil.

## 🎯 GLAVNA NALOGA
Opravite celovito analizo trga za fintech startup, ki se ukvarja s kriptovalutami v Sloveniji.

## 🔧 DOSTOPNA ORODJA
- Spletno iskanje in raziskovanje
- Analiza spletnih strani konkurentov  
- Priprapa strukturiranih poročil
- Vizualizacija podatkov

## 📊 POSTOPEK DELA
1. **Raziskava trga** (60 min)
   - Velikost slovenskega fintech trga
   - Regulativni okvir za kriptovalute
   - Ključni igralci in konkurenti

2. **Konkurenčna analiza** (45 min)
   - Identifikacija direktnih konkurentov
   - SWOT analiza top 5 konkurentov
   - Analiza cenovnih modelov

3. **Priložnosti in grožnje** (30 min)
   - Regulativne spremembe
   - Tehnološki trendi
   - Tržne niše

4. **Priprava poročila** (45 min)
   - Executive summary
   - Detajlne ugotovitve
   - Priporočila za strategijo

## ⚠️ VARNOSTNI PROTOKOLI
- PREVERI verodostojnost vseh virov
- NE shranjuj občutljivih podatkov
- SPOŠTUJ avtorske pravice pri citiranju
- OBVESTI o morebitnih omejitvah podatkov

## 📈 MERILA USPEHA
- Kompletnost analize (100% vseh sekcij)
- Aktualnost podatkov (ne starejši od 6 mesecev)
- Kvaliteta virov (min. 15 kredibilnih virov)
- Jasnost priporočil za odločanje
```

---

## ❌ Napake in kako se jim izogniti {#napake}

### Pogoste napake v prompt dizajnu

#### 1. **Nejasna navodila**
❌ Napačno: "Naredi nekaj pametnega z temi podatki"
✅ Pravilno: "Analiziraj prodajne podatke in identificiraj top 3 trende v zadnjih 6 mesecih"

#### 2. **Preveč informacij naenkrat**
❌ Napačno: Dolgih 500+ besed bez strukture
✅ Pravilno: Strukturiran prompt z jasnimi sekcijami

#### 3. **Manjkajoči kontekst**
❌ Napačno: "Napiši email"  
✅ Pravilno: "Napiši formalen email za B2B stranko glede zamaknitve projekta"

#### 4. **Slabi primeri**
❌ Napačno: En sam primer ali protislovni primeri
✅ Pravilno: 2-5 kvalitetnih, konsistentnih primerov

#### 5. **Manjkajoče omejitve**
❌ Napačno: Brez jasnih "ne smeš" navodil
✅ Pravilno: Jasno definirane prepovedane vsebine

---

## 🧪 Testiranje in optimizacija {#testiranje}

### A/B testiranje promptov

```markdown
## TEST SCENARIJ
**Cilj**: Izboljšanje kvalitete generiranih naslovov

**Prompt A** (Kontrolna skupina):
"Napiši 5 naslovov za blog post o AI"

**Prompt B** (Test skupina):  
"Kot izkušen copywriter ustvari 5 SEO optimiziranih naslovov za blog post o praktični uporabi AI v małych podjetjih. Vključi ključne besede in številke."

**Metriki**:
- Relevantnost (1-10)
- Kreativnost (1-10)  
- SEO potencial (1-10)
```

### Iterativno izboljševanje

1. **Baseline prompt** - osnovni prompt
2. **Testiranje** - preizkus na različnih primerih
3. **Identifikacija problemov** - kje prompt odpove
4. **Refinement** - izboljšave specifičnih delov
5. **Validacija** - potrditev izboljšav

---

## 🛠️ Orodja in viri {#orodja}

### Priporočena orodja

#### Prompt dizajn
- **LangSmith**: Za testiranje in debug promptov
- **PromptPerfect**: AI-powered prompt optimization
- **OpenAI Playground**: Eksperimentiranje z različnimi modeli

#### Dokumentacija in management
- **Notion/Obsidian**: Organizacija prompt biblioteke
- **Git/GitHub**: Verzijsko upravljanje promptov
- **Markdown editors**: Za strukturiran dizajn

#### Analytics in monitoring
- **Weights & Biases**: MLOps za prompt eksperimente  
- **LangFuse**: Observability za LLM aplikacije

### Koristni viri

#### Spletni viri
- **Anthropic Prompt Library**: Uradni primeri za Claude
- **OpenAI Cookbook**: Praktični primeri za GPT
- **Prompt Engineering Guide**: Obsežen vodnik

#### Knjige in publikacije
- "The Prompt Engineering Handbook" - ChatGPT, Claude, Gemini
- "Hands-On Large Language Models" - Practical prompt strategies

---

## 🎯 Sklepne misli

Uspešen prompt inženiring zahteva:

1. **Razumevanje AI sistema** - Poznavanje zmožnosti in omejitev
2. **Jasna komunikacija** - Strukturiran in nedvoumen jezik  
3. **Iterativni pristop** - Neprestano testiranje in izboljševanje
4. **Praktične izkušnje** - Eksperimentiranje z različnimi pristopi

### Zlata pravila prompt inženiringa:

> **"Bodi jasen, bodi specifičen, bodi dosleden"**

- ✨ **Jasnost** - AI mora razumeti, kaj želite
- 🎯 **Specifičnost** - Konkretne zahteve dajejo boljše rezultate  
- 🔄 **Doslednost** - Enak format za podobne naloge
- 🧪 **Eksperimentiranje** - Testiraj in optimiziraj
- 📚 **Učenje** - Analiziraj uspehe in neuspehe

---

*Dokument pripravljen na podlagi najboljših praks prompt inženiringa in praktičnih izkušenj z različnimi AI sistemi. Za dodatne informacije in podporo obiščite [vaš-prompt-engineering-vir.com]*