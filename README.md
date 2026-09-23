[//]: # (Author: Christoph P. Neumann)
[//]: # (Title: Awesome Agentic Engineering)
[//]: # (Language: de-DE)
[//]: # (Licence: CC BY 4.0)
[//]: # (Kurztitel: 6GL)
[//]: # (Lemma: 6GL)

# Awesome Sixth-Generation Programming

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) [![Made With Love](https://img.shields.io/badge/Made%20With-Love-pink.svg)](https://github.com/chetanraj/awesome-github-badges) [![Donate via PayPal](https://img.shields.io/badge/Donate-PayPal-blue?logo=paypal)](https://www.paypal.com/donate/?hosted_button_id=QTDJ2JA58ZM9L) [![Support on Ko-fi](https://img.shields.io/badge/Donate-ko--fi-%23FF5E5B?logo=ko-fi&logoColor=white)](https://ko-fi.com/cyberlytics) [![Buy Me A Coffee!](https://img.shields.io/badge/Donate-buymeacoffee-%23FFDD00?logo=buymeacoffee)](https://www.buymeacoffee.com/cyberpetaneuron)

Dies ist sowohl eine Tool-Sammlung als auch ein digitaler Ressourcen-Pool mit kostenlosen Lernmaterialien für **6GL** (Natural Language Programming) und Agentic Engineering (AI-native SDLC / Spec-Driven Development). Entstanden an der [OTH Amberg-Weiden](https://www.oth-aw.de/cpn), welche für ein paar Einträge entsprechend den Kontext bildet.

**Table of Contents**

<!-- toc -->

- [Prelude](#prelude)
- [Agentic Engineering Manifest](#agentic-engineering-manifest)
- [Agentic Education Manifest](#agentic-education-manifest)
- [Lernmaterialien](#lernmaterialien)
- [Vibe Coding Werkzeuge](#vibe-coding-werkzeuge)
- [Prompting Recipies](#prompting-recipies)
- [Agent Context File](#agent-context-file)
- [MCP](#mcp)
- [Agent Skills](#agent-skills)
- [Vibe Testing Werkzeuge](#vibe-testing-werkzeuge)
- [Vibe Hacking Werkzeuge](#vibe-hacking-werkzeuge)
- [Vibe Science Werkzeuge](#vibe-science-werkzeuge)
- [Generative KI Werkzeuge](#generative-ki-werkzeuge)
- [Bildmaterialien Werkzeuge](#bildmaterialien-werkzeuge)
- [Schwesterseiten](#schwesterseiten)
- [Footer](#footer)

<!-- tocstop -->

## Prelude

* **Programmiersprachengenerationen**

  Kennt ihr die Entwicklung von **[1GL bis 5GL](https://en.wikipedia.org/wiki/Programming_language_generations)**? ⭐

  * 4GL (deklarativ) und 5GL (logikbasiert) wurden nie ein Massenphänomen und haben 3GL-Hochsprachen nicht verdrängt.
  * Uncle Bobs Vortrag **„[The Future of Programming](https://www.youtube.com/watch?v=ecIWPzGEbFc)“** ⭐ ist hierzu weiterhin relevant!
  * Interessanterweise hatte bereits [Dijkstra über Natural Language Programming](https://www.cs.utexas.edu/~EWD/transcriptions/EWD06xx/EWD667.html) ⭐ nachgedacht, aber ausnahmsweise irrte er sich hierzu. Allerdings hatte die breite Öffentlichkeit die Fähigkeiten von großen Sprachmodellen vor November 2022 nicht für möglich gehalten.

* **Vibe-Coding-Anpassungsstörungen?**

  Die [aktuelle Zerrissenheit](https://writer.com/blog/enterprise-ai-adoption-survey-results-press-release/) erinnert an frühere Paradigmenwechsel:

  * Dijkstra wurde nicht nur für „[GOTO considered harmful](https://www.perplexity.ai/search/new?q=Wurde+Dijkstra+nicht+nur+gefeiert+für+%22Goto+considered+harmful%22+sondern+auch+angefeindet%3F+Wie+kontrovers+war+die+Modernisierung+zu+seiner+Zeit%3F)“ gefeiert, sondern auch kontrovers diskutiert.
  * GOTO war nicht „falsch“, sondern Teil des 2GL-Programmierstils. Structured Programming und 3GL haben es lediglich im Mainstream verdrängt.
  * Ähnlich dürfte es mit 6GL-Techniken laufen.

  Nebenbemerkung: GOTO wird beispielsweise im Linux-Kernel weiterhin intensiv für Cleanup- und Error-Handling-Muster verwendet; ein Grund könnte allerdings sein, dass sich bessere Alternativen wie ein [defer-Konstrukt](https://www.open-std.org/JTC1/SC22/WG14/www/docs/n3734.pdf) noch im C-Standardisierungsprozess befinden.

* **Vibe Coding als 6GL**

  Vibe Coding kann als **6GL (Sixth-Generation Programming Language)** i.S.v. **Natural Language Programming** bzw. **Spec-Driven Development** verstanden werden.
  * 3GL-Programmierer beherrschen heute meist weder 2GL (Assembly) noch 1GL (Maschinensprache) im Alltag.
  * Jede neue Abstraktion erzeugt eine neue Generation von Entwicklern.
  * **6GL wird die 3GL nicht „ersetzen“, sondern die nächste dominante Abstraktionsebene bilden.** ⭐

* **[AI Exposure](https://www.aiexposure.org/)** misst (Messgrößen u.a. per [OECD](https://www.oecd.org/en/publications/2026/05/the-oecd-ai-exposure-measure_489cfd42.html)), inwieweit künstliche Intelligenz Aufgaben innerhalb eines bestimmten Berufsbereichs unterstützen oder automatisieren kann. (Glauben Sie aber nicht, dass Informatiker durch GenAI überflüssig werden!)

## Agentic Engineering Manifest

\[ aka: Die (merkfähigen) 10 Gebote nach Neumann \]

0. **„KI macht nicht deine Arbeit, sie multipliziert deine Denkqualität.“**
	* (Ein Grundprinzip, daher als 0. Eintrag vorangestellt. Informatikerhumor: Beginne den Index bei 0 und bringe „heimlich“ ein 11. Gebot unter.)
	* KI verstärkt Klarheit, Struktur und Qualität deiner Vorgaben.
	* Human Slop → AI Slop: „Müll rein, Müll raus, nur schneller.“
	* **Nebengesetz:** „KI skaliert nicht nur Produktivität, sie skaliert auch schlechte Entscheidungen.“
	* **Variante:** „Vibe Coding: Where 2 engineers can now create the tech debt of at least 50 engineers.“

1. **„Es liegt stets am Prompt.“**
	* (Als provokantes 1. Gebot notwendig, insbesondere für Einsteiger.)
	* Disclaimer: Obwohl Modellgrenzen existieren, Tooling existiert, Kontext existiert, Retrieval existiert, System Prompts existieren.
	* **Prompt Engineering** ist ein kontinuierlicher Optimierungsprozess aus Hypothese, Test und Verbesserung.
	* Wichtig: Der **Mensch** verantwortet schlechte Fragen/Aufgaben und schlechte Ergebnisse, nicht das Modell.
	* **Nebengesetz:** „Stille Annahmen des Menschen sind keine Instruktionen.“

2. **„Context is King.“**
	* Hintergrund: Schlechte Ergebnisse entstehen meist durch fehlenden, falschen oder unstrukturierten Kontext.
	* **Context Engineering** umfasst neben dem Prompt zusätzlich die System Instructions, Beispiele, Daten, Tools und Regeln sowie den Gesprächsverlauf aus Prompt-Verlauf und Ergebnis-Verlauf.
	* Nochmal: Der **Mensch** verantwortet schlechten Kontext und schlechte Ergebnisse, nicht das Modell.
	* **Nebengesetz**: „Hochwertiger Kontext ist teuer: Daten müssen erzeugt, kuratiert und gepflegt werden.“

3. **„System Prompt vor Modellwahl.“**
	* In derselben Modellklasse und -generation dominiert häufig der [System Prompt](https://github.com/asgeirtj/system_prompts_leaks) die Ergebnisqualität.
	* Ein Modell ohne System Design ist nur Rohintelligenz: Das System definiert (auch „orchestriert“) das Verhalten, nicht das Modell allein.
	* Abgrenzung: Nur Foundation Model Provider konkurrieren primär über Modellqualität und Benchmarks, das allerdings lautstark.
	* Wichtig: Ein durchschnittliches Modell mit gutem System Design kann ein besseres Modell mit schlechtem Kontext schlagen. (vgl. „Modelmaxxing“, u.a. als Gegenkonzept zu „Tokenmaxxing“)
	* **Nebengesetz:** „Modellqualität ≠ Systemqualität“

4. **„Sprachmodelle lieben Rollenspiele.“**
	* Eine definierte Rolle verändert Perspektive, Verhalten und Prioritäten des Modells, denn Rollen definieren Bewertungsmaßstäbe.
	* Wichtig: Methoden wie **[Role Prompting](https://learnprompting.org/docs/advanced/zero_shot/role_prompting)** („Act as ...“) und **Meta Prompting** („Act as a Prompt Engineer ...“) sollten von KI-Benutzern früh ritualisiert werden.
	* **Nebengesetz:** „Die Frage ‚Wer soll denken?‘ ist oft wichtiger als ‚Was soll gedacht werden?‘“

5. **„Format ist Funktion.“**
	* Das gewünschte Ausgabeformat bestimmt maßgeblich die Nutzbarkeit des Ergebnisses.
	* Wichtig: Methoden wie **Output Priming** sollten von KI-Benutzern früh ritualisiert werden.
	* **Nebengesetz:** „Outputqualität folgt Inputstruktur.“

6. **„Kontext ist eine Ressource mit Budget.“**
	* Hintergrund: (1) Kontext verbraucht Tokens und Tokens sind – je nach Abonnement und Modell – durch Budgets (z. B. Wochenbudget, Tagesbudget oder Cool-down-Mechanismen) begrenzt. (2) Das LLM-Kontextfenster ist ebenfalls begrenzt: Es wird sowohl durch den Eingabetext als auch durch die Ausgabe des Modells belegt.
	* Kontext ist die Arbeitsumgebung des Modells.
	* Wichtig: Mehr Kontext bedeutet nicht automatisch besseren Kontext. (Werkzeug: bspw. [Graphify](https://graphify.net/) zur Token-Ökonomie per Knowledge Graph)
	* **Nebengesetz:** „Der beste Kontext ist nicht der vollständigste, sondern der relevanteste.“

7. **„Skills sind Bausteine agentischer Software.“**
	* Hintergrund: Agent Skills sind als [SKILL.md technisch normiert](https://agentskills.io/specification) und bilden ein eigenes Ökosystem.
	* Der Wettbewerb verschiebt sich von der Implementierung einzelner Funktionen zur Gestaltung wiederverwendbarer Fähigkeiten.
	* Im Agentic Programming kapseln **Skills** wiederholbare Entscheidungslogik, Engineering-Prinzipien und technische Umsetzungsmuster.
	* **Nebengesetz:** „Modelle denken, Werkzeuge handeln.“

8.	**„Spezifikation ist die neue Implementierung.“**
	* In der Agenten-Ära wird fachliche und technische Expertise per GenAI zu Software.
	* Entscheidend ist die **zusätzliche** Kompetenz, KI-Systeme zielgerichtet zu orchestrieren.
	* Auf Software-Technik-Ebene verschiebt sich der Schwerpunkt: weniger direkte Syntaxarbeit, mehr Spezifikation, Architektur, Verständnis und Kontrolle.
	* Disclaimer: Auch Hochsprachen-Code ist letztlich „nur“ eine Spezifikation! Erst Compiler, Laufzeitumgebung, Bibliotheken und die Zielplattform formen daraus ein ausführbares System.
	* **Nebengesetz:** „Die nächste Generation von Software wird nicht geschrieben - sie wird beschrieben.“

9.	**„Iteration schlägt Perfektion.“**
	* Prompting ist Exploration. Gute Ergebnisse entstehen selten im ersten Versuch.
	* Wichtig: Prompt Engineering folgt einem wissenschaftlichen Zyklus aus **Hypothese, Experiment, Evaluation und Iteration**.
	* Wann endet der Zyklus? Wenn die Antwort die definierten Qualitätskriterien für den jeweiligen Anwendungsfall erfüllt oder bei **abnehmendem Grenznutzen** weiterer Iterationen, d. h., wenn zusätzliche Versuche keinen wesentlichen Erkenntnis- oder Qualitätsgewinn mehr liefern.
	* Wissenschaftliche Erkenntnis ist grundsätzlich vorläufig: Eine Hypothese gilt so lange, bis sie durch eine andere mit höherer **Erklärungsleistung** (oder Prognosekraft) ersetzt wird. Dasselbe gilt für Prompt und Kontext: sie werden nicht „wahr“, sondern durch bessere Varianten abgelöst.
	* **Nebengesetz:** „Jede LLM-Antwort ist eine Hypothese. LLMs erzeugen Antworten auf Grundlage von Wahrscheinlichkeiten, nicht von Gewissheit.“

10.	**„Agentic Engineering ist anspruchsvolle Informatik.“**
	* Benötigt werden methodische und technische Full-Stack-Kompetenzen.
	* Disclaimer: Der Definition nach handelt es sich bei einem **Informationssystem** schon immer um ein **Mensch-/Aufgabe-/Technik-System**.
	* Dies widerspricht der häufigen Fehlannahme „Jetzt kann jeder Software bauen.“ (= "[AI Exposure](https://www.aiexposure.org/)"-Frage)
	* Für einfache Anwendungen genügen Low-Code-Ansätze, komplexe Software-Anwendungen bleiben eine Engineering-Disziplin.


### Lernpfad

* Erst eine Subscription oder ein [lokales Ollama](https://martinfowler.com/articles/exploring-gen-ai/local-models-for-coding-factors.html).
* Dann [CLAUDE.md](https://github.com/multica-ai/andrej-karpathy-skills/blob/main/CLAUDE.md).
* Dann [ECC](https://github.com/affaan-m/ecc)-analoge Skills.
* Dann All-In. (Mindset!)
* Dann die [richtige Echokammer](https://simonwillison.net/).
* Dann 6GL aka [Natural Language Programming](https://www.cs.utexas.edu/~EWD/transcriptions/EWD06xx/EWD667.html) (Programmier-Ebene)
	- Andrej Karpathy betonte „agentic programming as a tool“, bei der Vibe-Coding-Begriffsbildung
* Dann Spec-Driven Development (SDD) aka Agentic Engineering ⭐ (SW-Technik-Ebene)
	- Further Reading: [spec-kit](https://github.com/github/spec-kit), [SpecDD](https://specdd.ai/) (sowie exemplarisch [kiro](https://kiro.dev/) und [tessl](https://tessl.io/))

Vibe Coding Referenzprojekt für Einsteiger mit kleinen Projekten (ca. 1-wöchige SW-Prototypen)?

* bspw. mein Modul Webanwendungsentwicklung, studentisches Team DeadLock: [CLAUDE.md](https://github.com/CycleByte/WAE-2026SS-TeamBlau-DeadLock/blob/main/CLAUDE.md) ⭐

### Weitere Anmerkungen

* **Welches Modell passt in meine Grafikkarte?** → Nutzt den **[VRAM Calculator](https://apxml.com/tools/vram-calculator)** ⭐
  * (Wer die zugrunde liegenden Infos ebenfalls gelesen hat? Natürlich das freundliche Freibier-Frontier-Modell deiner Wahl, d.h. der Bot berät hierzu ebenfalls zuverlässig.)*

* **„DeepSeek als Alternative zu Claude Code oder GitHub Copilot?“ ist die falsche Fragestellung.**
  Die eigentliche Einordnung ist:

  * **Frontier-Modelle**: 3T+ Parameter, typischerweise Cloud-Modelle der Big-Tech-Anbieter
  * **Mid-Tier-Modelle**: lokal nutzbar mit sehr viel Speicher (z. B. 128+ GB RAM, etwa auf Geräten wie [NVIDIA DGX Spark](https://www.nvidia.com/de-de/products/workstations/dgx-spark/) oder [Ryzen AI 395-Systemen](https://frame.work/de/de/desktop))
  * **Edge-Modelle**: abhängig von verfügbarer Hardware – von Desktop-GPUs bis Smartphones

  NVIDIA DGX Spark bzw. Ryzen AI 395-Systemen könnte man entsprechend auch als **Premium-AI-Edge** bezeichnen.

  [GPT-3](https://arxiv.org/pdf/2005.14165.pdf) war (beschrieben 2020, kommerzieller Durchbruch November 2022) ein **175B-Modell** (deutsche 175 Milliarden). **DeepSeek R1** (Release Januar 2025) war ein **671B-Modell** mit **37B aktiven Parametern durch Mixture-of-Experts (MoE)**. Das große 671B(37B)-DeepSeek R1 ist zwar FOSS Open Weight, läuft aber nicht auf gewöhnlicher Consumer-Hardware. Kleinere Varianten von DeepSeek sind "distilled versions" und basieren faktisch auf Qwen- oder Llama-Architekturen - hinsichtlich Edge-Hardware hier wird es hier also technisch kompliziert. Das französische **Mistral Large 3** (ab Dezember 2025) ist ein FOSS Open Weight 675B-Modell (41B aktiv durch MoE) und ist u.a. auch als 8B oder 14B Edge-Modell verfügbar.
  
  Ein von OpenAI ab Sommer 2025 (zweieinhalb Jahre nach Beginn des ChatGPT-Zeitalters) verfügbares FOSS Open Weight Mid-Tier-Modell für die Premium-AI-Edge (damals 80GB NVIDIA H100) ist **gpt-oss-120b**, ein 117B-Modell mit 5B aktiven Parametern durch MoE, welches im Vergleich zum urpsrünglichen GPT-3 (zur Erinnerung: 175B) und auch zum legacy GPT-3.5-Turbo deutliche Überlegenheit und damit Massentauglichkeit für FOSS-basierte Local-AI demonstrierte.
  
  Weitere nennenswerte FOSS Open Weight Frontier-Modelle sind **[DeepSeek V4 pro](https://huggingface.co/deepseek-ai/DeepSeek-V4-Pro)** mit 1.6T und **[Kimi K3](https://platform.kimi.ai/docs/guide/kimi-k3-quickstart)** mit 2.8T (also deutsche Billionen). Kimi K3 belegt im nativen MXFP4-Format ca. 1½ TB an Speicherplatz und benötigt ein GPU-Cluster mit mindestens 1680GB VRAM. (Ab OpenAI GPT-3.5 sowie für alle Anthropic Claude-Modelle wurden keine offiziellen Anzahlen an Parametern mehr für die Cloud-Modelle der amerikanischen Big-Tech-Anbieter veröffentlicht.)

* **Modelmaxxing als Kostenoptimierung**

  Der bewusste Wechsel zwischen Modellklassen etabliert sich zunehmend als *modelmaxxing*:

  * Planung mit einem High-End-Modell
  * Implementierung mit einem günstigeren Mid-Tier-Modell

  Gerade Studierende profitieren davon, weil Kosten eine zentrale Rolle spielen.


### Vibe Coding Einstiegshinweise

Gutes Preis/Leistungsverhältnis:

* Kostenlos?
	- Für Wissenschaftler mit Zugriff auf nationale Forschungsinfrastruktur: [FAU](https://hpc.fau.de/request-llm-api-key/#models) oder [GDWG](https://docs.hpc.gwdg.de/services/ai-services/chat-ai/models/index.html)
		- Allerdings i.d.R. nur Mid-Tier-Modelle, keine Frontier-Modelle
* Preisgünstig?
	- [Open Code Go](https://opencode.ai/de/go) Subscription (~€10/m)
	- Internationale Subscriptions (bspw. indischen Ursprungs)
		- Warnhinweis: [Ist die regionsübergreifende Weitergabe ein Verstoß gegen die Nutzungsbedingungen der Anbieter?](https://www.perplexity.ai/search/new?q=Beim+Kauf+internationaler+Subscriptions+(bspw.+indischen+Ursprungs)%3A+Ist+eine+reine+regionale+Umgehung+ein+Verstoß+gegen+deutsches+Recht%3F+Ist+es+ein+Verstoß+gegen+Googles+Nutzungsbedingungen%3F+Sind+Googles+Nutzungsbedingungen+in+Deutschland+in+der+bestehenden+Form+überhaupt+rechtswirksam%3F)
		- Angebote u.a. via [driffle](https://driffle.com/de/store?q=Google%20AI%20Pro) oder [kinguin](https://www.kinguin.net/listing?active=1&hideUnavailable=0&type=all&phrase=Google%20AI%20Pro%2018%20months)


Exemplarische **Top-10-Liste** relevanter Slash-Commands, am Beispiel agy / antigravity CLI:

| Top-10 Commands           | Semantics                                                                                 |
| ------------------------- | ----------------------------------------------------------------------------------------- |
| `/model`                  | Switch models without leaving the current session.                                        |
| `/usage`                  | Show quotas and rate limits across models. Check this regularly.                          |
| `/context`                | View token usage by category and manage checkpoints.                                      |
| `/goal`                   | Execute the plan autonomously until completion. Best when you trust the plan.             |
| `/grill-me`               | Ask clarifying questions before taking action. Best for ambiguous or destructive tasks.   |
| `/agent` sowie `/agents`  | Launch a named background subagent or monitor running subagents.                          |
| `/browser`                | Enable web browsing for the current run (scraping, JS-heavy sites, OAuth).                |
| `/config`                 | Configure settings such as model, theme, MCP servers, and Pro upgrade.                    |
| `/export`                 | Export the session to Antigravity 2.0 to continue in the GUI.                             |
| `/schedule`               | Schedule loops, i.e. recurring cron-style runs, or one-time tasks up to 15 minutes ahead. |

Nützliches pwsh Snippet für lokale Automatisierungen (exemplarisch für agy):
```pwsh
agy models |
    Where-Object { $_.Trim() } |
    ForEach-Object {
        "`$Prompt | agy --model `"$($_)`" --dangerously-skip-permissions"
    }
```

## Agentic Education Manifest

\[ aka: 10 nützliche Glaubenssätze nach Neumann \]

**Agentic Education** bedeutet, dass Lernende die aktive Rolle des Agenten übernehmen: Sie setzen Ziele, stellen Fragen, nutzen Werkzeuge (inklusive KI), überprüfen Ergebnisse und steuern ihren eigenen Lernprozess. Dies ist in weiten Teilen nichts neues. So disruptiv sind Sprachmodelle nicht gegenüber der Herausforderung Human Intelligence zu trainieren. Das Manifest mischt traditionelle Glaubenssätze mit modernen Erweiterungen.

1. **„Vertraue nicht auf Talent, vertraue auf Fleiß.“**  → Erfolg im Studium basiert meist auf Ausdauer, Disziplin und Kontinuität  – nicht Genialität.
2. **„Ich lerne für mich, nicht für die Prüfungen.“**  → Nachhaltiges Verstehen schlägt kurzfristiges Bulimie-Lernen.
3. **„Die Qualität deiner Fragen bestimmt die Qualität deines Lernens.“** ⭐ → Neugier ist der Motor echter Bildung. Fragen sind ein Zeichen von Stärke, nicht von Schwäche.
4. **„Kleine Schritte führen weiter als große Vorsätze.“** → Täglich 30 Minuten sind mehr wert als einmal im Monat zehn Stunden..
5. **„Lerne nicht allein – viele kämpfen mit denselben Herausforderungen.“** → Austausch und Gemeinschaft helfen mehr als Einzelkämpfertum (Lerngruppen!)
6. **„Suchmaschinen sind kein Ersatz für Verstehen – aber ein guter Anfang.“**
    * Recherchieren ist eine Kompetenz, kein Trick!
    * Obacht: Das Internet ist teils eine digitale Müllhalde. Und es ist sogar teils monströs.
    * Wichtig: Quellen müssen bewertet, verglichen und kritisch hinterfragt werden.
7. **„Ein Chatbot als KI-Lerntutor ist kein Ersatz für Verstehen – aber ein guter Anfang.“** ⭐
    * Prompting ist eine Kompetenz, kein Trick!
    * Obacht: LLMs teils mit Halluzinationen und Bias / Recherche für Faktencheck weiterhin benötigt.
8. **„LLMs sind (auch) Musterlösungsgeneratoren.“** ⭐
    * Das bloße Lesen einer Musterlösung ist passives Lernen, ohne substanzielle Retention Rate.
    * Zur Erinnerung: Musterlösungen gab es schon immer – in Lehrbüchern, Vorlesungsskripten und Lösungssammlungen.
    * Sprachmodelle erzeugen Musterlösungen schneller, individueller und dialogfähig.
    * Wichtig: Ein LLM kann dir den Lösungsweg zeigen, aber nicht den Lernprozess abnehmen.
9. **„Wer anderen beim Lernen hilft, lernt selbst am tiefsten.“** → Wer etwas wirklich verstanden hat, kann es in eigenen Worten erklären.
    * Referenz: [Feynman-Methode](https://karrierebibel.de/feynman-methode/)
10. **„Bildung bedeutet, selbstständig denken zu können.“** ⭐
    * Ziel des Lernens ist nicht das Sammeln von Fakten, sondern Urteilsfähigkeit.
    * Wissen entfaltet seinen Wert erst durch Anwendung und kritisches Denken.
    * Wichtig: Gute Bildung beantwortet nicht nur Fragen – sie erzeugt bessere Fragen.
    * Nebengesetz: „Der größte Lernerfolg ist geistige Selbstständigkeit.“

### Lernpfad

- Erst: [Effektives Prompting in der Pädagogik](https://promptkatalog.eldshort.de/prompten.html)
- Dann: Agentic Skill [mattpocock teach](https://www.skills.sh/mattpocock/skills/teach)
- Dann: **[The Diamond Age](https://www.amazon.de/dp/0241953197/)** von Neal Stephenson (AI Learning Tutor: „Young Lady's Illustrated Primer: a Propædeutic Enchiridion“)

### Lernphilosophie

* Talentmythos → Growth Mindset
* Prüfungsorientierung → nachhaltiges Lernen
* Fragen → aktive Wissenskonstruktion
* Gewohnheiten → langfristige Entwicklung
* Gemeinschaft → soziale Dimension
* Informationskompetenz  → Recherche & Quellenkritik
* KI-Kompetenz → Die Kunst Fragen zu stellen & kritischer KI-Einsatz
* Lernkompetenz → Urteilsfähigkeit & Kritisches Denken

## Lernmaterialien

- Vor Eintritt in ein Bachelorstudium
	- Prompting-Werkzeuge:
		- **[KI-Campus](https://ki-campus.org/overview/course)** inkl. [Chatbot-Sandbox](https://chat.ki-campus.org/) und [Prompt-Katalog](https://coda.io/@ki-campus/prompt-katalog)
- Generative AI / LLMs:
	- Für Non-Technical Persons (⭐):
		- Webartikel [A jargon-free explanation of **how AI large language models work**](https://arstechnica.com/science/2023/07/a-jargon-free-explanation-of-how-ai-large-language-models-work/) ⭐
		- Podcast [State of Process Automation](https://www.stateofprocessautomation.com/) mit Folge [145 „**Generative KI im Mittelstand**“](https://podcasts.google.com/feed/aHR0cHM6Ly9hbmNob3IuZm0vcy80ZWMwMDhjMC9wb2RjYXN0L3Jzcw/episode/M2M4ZDhmZDMtMThlNS00ODYwLWJhZmEtMDhjZmM0MWFiNjUy)
		- Zur Leistungsfähigkeit von LLMs: [A **GPT-4 Capability** Forecasting Challenge](https://nicholas.carlini.com/writing/llm-forecast/question/Capital-of-Paris) ⭐
	- Einstieg für Technical Persons:
		- Einstieg LLM = Large Language Models ⭐:
			- [How to Build ChatGPT From Scratch: **Understanding LLMs Step by Step**](https://nextweekai.com/blog/build-chatgpt-from-scratch-guide/) ⭐
			- **[What are Large Language Models](https://www.analyticsvidhya.com/blog/2023/03/an-introduction-to-large-language-models-llms/)** ⭐
		- Videokurs freeCodeCamp [Learn Generative AI for Developers](https://www.freecodecamp.org/news/learn-generative-ai-for-developers/)
		- Einstieg GAN = Generative Adversarial Networks:
			- Einordnung: GANs vor den Transformern; Bilder erzeugen; Methodisch: Generator vs. Discriminator; GANs sind **nicht** Teil der GPTs
			- [**Generative Adversarial Networks**: Build Your First Models](https://realpython.com/generative-adversarial-networks/) | [Tensorflow GAN](https://www.tensorflow.org/tutorials/generative/dcgan)
			- Google Course [GAN](https://developers.google.com/machine-learning/gan)
	- Chatbot (Text-to-Text):
		- Einstieg: KDnuggets [ChatGPT: Everything You **Need to Know**](https://www.kdnuggets.com/2023/01/chatgpt-everything-need-know.html) | KDnuggets [ChatGPT as a **Python Programming Assistant**](https://www.kdnuggets.com/2023/01/chatgpt-python-programming-assistant.html)
		- Webartikel: **[GPT-3's family tree](https://www.truthm.com/gpt-3s-family-tree/)** | Paper **[Attention Is All You Need](https://arxiv.org/abs/1706.03762)** (2017) von Vasvani et al. (auch als das [**Transformer**-Paper von Google](https://arxiv.org/abs/1706.03762) bekannt)
		- Milestone Papers: [Liste per Awesome-LLM](https://github.com/Hannibal046/Awesome-LLM#milestone-papers)
		- Nennenswerte Webartikel: Leseliste per [Great thoughts about LLM](https://github.com/Hannibal046/Awesome-LLM#great-thoughts-about-llm)
		- Unsensored Models:
			- Methode "uncensoring": von [Eric Hartford](https://erichartford.com/uncensored-models) (on [ollama](https://ollama.com/search?q=Eric%20Hartford))
			- Methode "abliteration": von [Arditi et al.](https://www.lesswrong.com/posts/jGuXSZgv6qfdhMCuJ/refusal-in-llms-is-mediated-by-a-single-direction), zzgl. [Uncensor any LLM with abliteration](https://huggingface.co/blog/mlabonne/abliteration), auch für Text-to-Image ([am Bsp. Flux.1](https://medium.com/@aloshdenny/uncensoring-flux-1-dev-abliteration-bdeb41c68dff))
			- Models in HuggingFace: ["eric hartford"](https://huggingface.co/search/full-text?q=eric+hartford&type=model), ["abliterate"](https://huggingface.co/search/full-text?q=abliterate&type=model), ["unsensored"](https://huggingface.co/search/full-text?q=_uncensored&type=model)
		- Zulässigkeit von Generative AI als Werkzeug zur Erstellung wiss. Publikationen? vgl. **[ACM Policy on Authorship](https://www.acm.org/publications/policies/new-acm-policy-on-authorship)**
		- **LLM-Evaluation**: [LLM Evaluation Metrics: The Ultimate LLM Evaluation Guide](https://www.confident-ai.com/blog/llm-evaluation-metrics-everything-you-need-for-llm-evaluation)
		- Text-to-Code: [Top Open Source (Free) Text to Code Generator models on the market](https://www.edenai.co/post/top-free-code-generation-tools-apis-and-open-source-models)
		- Weiterführende Referenz: [Awesome OpenAI](https://github.com/Jaykef/awesome-openAI)
	- Image Generator: [Awesome Text-to-Image](https://github.com/Yutong-Zhou-cv/Awesome-Text-to-Image)
	- Tools für Text-to-X: Im unteren [Werkzeuge-Unterabschnitt](#generative-ki-werkzeuge) (Text-zu-Bild, Text-zu-Video, Text-zu-Präsentation, Text-zu-Quiz, Text-zu-Sprache, Text-zu-Sound)
	- Europäische Ebene: **[LEAM](https://leam.ai/)**
	- Datensets: vgl. [Tools-Seite BDCC, Abschnitt Data Science](https://github.com/cyberlytics/awesome-bdccai-tools#data-science)
	- Weiterführende Quellen: [Awesome Generative AI](https://github.com/steven2358/awesome-generative-ai) | [Awesome Generative Deep Art](https://github.com/filipecalegario/awesome-generative-deep-art), [Awesome MVS](https://github.com/walsvid/Awesome-MVS)
- Prompt Engineering: [Google Prompting Essentials](https://www.coursera.org/learn/google-prompting-essentials)
	- ChatBot/Text-zu-Text:
		- Einstieg: [Prompt Engineering 101 - Introduction and resources](https://www.linkedin.com/pulse/prompt-engineering-101-introduction-resources-amatriain) | [Prompt Engineering 101](https://humanloop.com/blog/prompt-engineering-101) | roadmap.sh [Prompt Engineering Roadmap](https://roadmap.sh/prompt-engineering)
		- Use Cases: [The 14 Best ChatGPT Prompts on GitHub](https://www.makeuseof.com/best-chatgpt-prompts-on-GitHub/) (2023) von J. Luansing
		- Data Science: KDnuggets [ChatGPT-**for-Data-Science**-Cheatsheet](https://www.kdnuggets.com/publications/sheets/ChatGPT_for_Data_Science_Cheat_Sheet_KDnuggets.pdf), KDnuggets [ChatGPT-**Cheatsheet**](https://www.kdnuggets.com/publications/sheets/ChatGPT_Cheatsheet_Costa.pdf)
		- IT-Security: [ChatGPT4 – Potential Scenarios For Accelerated Cybercrime](https://blog.checkpoint.com/2023/03/15/check-point-research-conducts-initial-security-analysis-of-chatgpt4-highlighting-potential-scenarios-for-accelerated-cybercrime/)
	- Text-zu-Bild: [The Ultimate **Stable Diffusion Prompt Guide**](https://prompthero.com/stable-diffusion-prompt-guide) von PromptHero | [Prompting **Adobe Firefly**](https://torybarber.com/prompting-adobe-firefly/) (2023) von Tory Barber
		- Webartikel [How to Use ChatGPT to Write Prompts & Prompt Templates for Adobe Firefly & Midjourney](https://www.downloadsource.net/how-to-use-chatgpt-to-write-prompts-prompt-templates-for-adobe-firefly-midjourney/n/22511/) (2023) von Jascha Luca | analog [Adobe Firefly prompt generator](https://flowgpt.com/prompt/UjVmU4bSLor1cpBxx5veq) Vorlage für GPT
	- Agentic:
		- OpenAI [Chain of Command](https://model-spec.openai.com/)
			- Levels of authority: Root » System Prompt » Developer Prompt » User Prompt » Guideline Prompt » Message Prompt
			- AI Agent Levels of Authority: Instruction Prompt » Message Prompt (however: agent instructions are also known as agent system prompt!)
	- Weiterführende Quellen: roadmap.sh [Prompt Engineering](https://roadmap.sh/prompt-engineering), [Awesome Prompt Engineering](https://github.com/promptslab/Awesome-Prompt-Engineering) | reddit-Liste [Useful Prompt Engineering tools and resources](https://www.reddit.com/r/StableDiffusion/comments/xcrm4d/useful_prompt_engineering_tools_and_resources/) | lablab [AI Tutorials](https://lablab.ai/t) | [Awesome Text-to-Image](https://github.com/Yutong-Zhou-cv/Awesome-Text-to-Image)
- Vibe Coding:
	- Wegbereiter:
		- Begriff: [Andrej Karpathy](https://x.com/karpathy/status/1886192184808149383) (Feb. 2025)
		- Technik: "[Cursor](https://www.cursor.com/) [Composer](https://cursor101.com/article/cursor-composer) (i.e., multi-file editing), backed with Claude [Sonnet](https://www.anthropic.com/claude/sonnet)" (insb. wegen Claude Sonnets großem Kontextfenster von 200K+)
	- Video [The End of Software Engineering (as we know it)](https://www.youtube.com/watch?v=j0XukGlEUTc) von Jan Bosch (zzgl. [blog article](https://janbosch.com/blog/index.php/2017/10/06/the-end-of-system-architects/))
	- State-of-the-Art: [AI Unified Process](https://unifiedprocess.ai/) (Einstieg: [software-architektur.tv](https://software-architektur.tv/2026/01/16/folge298.html), [Video](https://tube.tchncs.de/w/mUmkL5mEFzYXD8dY4ixrTY)) mit Querbezug zu [Self-contained Systems](https://scs-architecture.org/) (SCS) von Innoq
	- Weiterführende Quellen: roadmap.sh [Vibe Coding](https://roadmap.sh/vibe-coding) sowie [AI Product Builder](https://roadmap.sh/ai-product-builder) (und allg. [Product Design](https://roadmap.sh/product-design))
- AI Engineering
	- vgl. Schwesterseite [awesome-basics](https://github.com/cyberlytics/awesome-basics) zu Machine Learning und Generative AI / LLMs
	- Weiterführende Quellen: roadmap.sh [AI Agents](https://roadmap.sh/ai-agents) sowie [AI Engineering](https://roadmap.sh/ai-engineer)

## Vibe Coding Werkzeuge

\[ OBACHT: Gilt für eine akademische Abschlussarbeit ggf. als Unterschleif i.S.v. High-Tech-Plagiarism. Hochschulrecht ist anders als reines Urheberrecht. \]

- RAD: vgl. Schwesterseite [awesome-software-engineering-tools » Rapid Application Development](https://github.com/cyberlytics/awesome-software-engineering-tools#rapid-application-development)
- Low Code: vgl. Schwesterseite [awesome-bdccai-tools » Low-Code / No-Code](https://github.com/cyberlytics/awesome-bdccai-tools#low-code--no-code)
- Übersicht/Einstieg: indiehackers [Vibe Coding Tools](https://www.indiehackers.com/vibe-coding-tools) ([free ones](https://www.indiehackers.com/vibe-coding-tools?tags=Free))
- Vibe Coding via Agentic AI (Full-Stack-Engineering Assistants)
	- Marktführer CLIs: 
		- Anthropic **[Claude Code CLI](https://docs.anthropic.com/en/docs/claude-code/overview)** \[**npm install -g @anthropic-ai/claude-code**\]
		- OpenAI [Codex CLI](https://openai.com/codex/) \[**npm i -g @openai/codex**\]
		- Google [Gemini CLI](https://github.com/google-gemini/gemini-cli) \[**npm install -g @google/gemini-cli**\]
		- GitHub [Copilot CLI](https://github.com/github/copilot-cli) \[**npm install -g @github/copilot**\]
	- Open Source CLIs:
		- [cline](https://cline.bot/) ([github](https://github.com/cline/cline)) \[**npm install -g cline**\]
			- [Roo Code](https://github.com/RooCodeInc/Roo-Code) as fork from cline
			- [Kilo Code](https://kilocode.ai/) ([github](https://github.com/Kilo-Org/kilocode)) = merged features from Roo Code and Cline plus own features
		- ollama-based CLIs:
			- [ollama code cli](https://github.com/vigyatgoel/ollama-code-cli) \[pip install ollama-code-cli\]
			- [tlm CLI](https://github.com/yusufcanb/tlm) \[irm https://raw.githubusercontent.com/yusufcanb/tlm/1.2/install.ps1 | iex\]
		- [LocalAGI](https://github.com/mudler/LocalAGI)
		- [aider](https://aider.chat/): AI pair programming \[**pip install aider-install && aider-install\]
		- [tgpt](https://github.com/aandrew-me/tgpt) (= Terminal GPT) \[**choco install tgpt**\]
	- Desktop (u.a. VS Code Extensions):
		- **[Cursor](https://www.cursor.com/)** \[**choco install cursoride**\]
		- **[Windsurf](https://windsurf.com/)** (formerly Codeium) \[**choco install windsurf**\]
		- **[TRAE IDE](https://www.trae.ai/)** (zzgl. [TRAE Solo](https://www.trae.ai/solo))
		- More: **[Void](https://voideditor.com/)**, [Tabby](https://www.tabbyml.com/), [Qodo Command](https://www.qodo.ai/products/qodo-command/)/[Qodo Gen](https://www.qodo.ai/products/qodo-gen/)
		- ReactJS/UI-centric: [Onlook](https://onlook.com/)
		- UI-Design: [SuperDesign.Dev](https://www.superdesign.dev/)
	- VS Code Extensions:
		- **[TabNine](https://www.tabnine.com/install/vs-code/)** (kostenlos ist nur die Short-Code-Completion)
		- GitHub [Copilot VS Code Extension](https://marketplace.visualstudio.com/items?itemName=GitHub.copilot)
		- OpenAI Codex als VS Code Extension: **[Code GPT](https://marketplace.visualstudio.com/items?itemName=DanielSanMedium.dscodegpt)**)
		- [Kudo](https://www.kodu.ai/)
	- Cloud:
		- Universal: [replit](https://replit.com/), Google [jules](https://jules.google/), Google [AI Studio](https://aistudio.google.com)
		- Web&Mobile in General: [bolt](https://bolt.new/), [biela.dev](https://biela.dev/), [shelbula.dev](https://shelbula.dev/), [JDoodle.ai](https://www.jdoodle.ai/)
		- ReactJS: [loveable](https://lovable.dev/), [Tempo](https://www.tempo.new)
		- Next.js: [v0](https://v0.dev/chat) (UI-centric)
		- GitHub **[Copilot](https://github.com/copilot/)**
		- Weiterführende Liste: [AI Tools Club](https://aitoolsclub.com/top-50-ai-vibe-coding-tools-for-everyone-in-2025/)
	- Game Engineering:
		- Unity ⭐ (C#): mit In-Editor AI Assistant, MCP Server, Agent Plugin, Skills
		- Unreal Engine 😲 (C/C++): erst experimentell / eher nur MCP-basiert
		- Godot ⭐ (v.a. GDScript): AI Agent [ziva](https://ziva.sh/) sowie [Godot-MCP](https://github.com/IvanMurzak/Godot-MCP) mit Skills oder [godot-agent](https://github.com/aigengame/godot-agent)
		- Und dabei nicht übersehen: Web-basierte Spiele! Sehr gutes Vibe Coding!
	- AR/VR:
		- Cross-Plattform AR/VR: WebXR, bspw. mittels Three.js! Sehr gutes Vibe Coding!
		- AR per Smartphone, bpsw. Unity wegen dessen Cross-Plattform/Mobile-Stärken und Vibe-Coding-Stärken! ([Beispiel](https://ilearn.ar-action.com/))
		- VR per Unity (C#) + OpenXR + PICO OpenXR SDK  + PICO 4 Ultra
			- Bestes AR/VR-Headset für Eigenentwicklungen/Einstieg? Das chinesiche [PICO](https://www.picoxr.com/de) Headset ⭐, wegen der niedrigen Nebenkosten bei der App-Entwicklung. Insbesondere für das Enterprise-Umfeld!
		- Educational Technology als AV/VR-Trainings? Per No-Code! Deutsches [3spin Learning](https://www.3spin-learning.com/de/) sowie niederländisches [Warp VR](https://www.warpvr.com/) (mit [kostenloser Edu-Lizenzoption](https://www.warpvr.com/pricing))
	- Nennenswerte weitere Ansätze:
		- [MetaGPT](https://github.com/FoundationAgents/MetaGPT): Multi-Agent Framework that assigns different roles to GPTs to form a collaborative entity for complex tasks ([Docs](https://docs.deepwisdom.ai/main/en/guide/get_started/introduction.html))
			- MetaGPT X (= Spin-off product by MetaGPT inventors): [MGX](https://mgx.dev/)
- Cheat Sheets
	- [Claude Code Cheat Sheet](https://awesomeclaude.ai/code-cheatsheet)
	- [Antigravity CLI (agy) Cheat Sheet #1](https://agentpedia.codes/blog/antigravity-cheat-sheet), [Antigravity CLI (agy) Cheat Sheet #2](https://toolsbase.dev/en/reference/antigravity-cli-commands)
- Für SQL (KI-gestützte SQL Code-Completion)
	- Open-Source **[NSQL](https://huggingface.co/NumbersStation)** mit [Begleitartikel](https://www.numbersstation.ai/post/introducing-nsql-open-source-sql-copilot-foundation-models)
	- Kostenpflichtig (€): **[Cogram](https://www.cogram.com/)**
- Vibe Coding via Prompting
	- Tutorials: [loveable](https://docs.lovable.dev/tips-tricks/prompting-one), [VibeCoding](https://github.com/cpjet64/vibecoding/tree/main), [bolters.io Knowledge Base](https://bolters.io/)
	- Prompt Generators: [TinyToolStack](https://tinytoolstack.com/app/vibecodingpromptgenerator?ref=producthunt), PromptHub [Prompt Iterator](https://www.prompthub.us/prompt-enhancers/prompt-iterator), [Bolt Prompter](https://chatgpt.com/g/g-tozliiBeO-bolt-prompter)
- Supporting Tools
	- Pack your codebase into AI-friendly formats: [Repomix](https://repomix.com)
- Weiterführende Referenzen: [Awesome Vibe Coding](https://github.com/filipecalegario/awesome-vibe-coding), [Awesome Vibe Coding Tools](https://github.com/furudo-erika/awesome-vibe-coding-tools?tab=readme-ov-file) 

## Prompting Recipies

\[ aka Prompt-Katalog / Prompts Directory \]

- Prompting Cheat Sheets: [20 ChatGPT Prompts](https://images.app.goo.gl/7LqXi96XaQABWpRY6), [All-in-one AI Cheat Sheet](https://images.app.goo.gl/uvfr5XsuUdHD2gRYA), [Prompt Engineering Mistakes](https://images.app.goo.gl/ANUTJHrRc6QzM1ak6)
	- Edu: Ulrich Ivens [Effektives Prompting in der Pädagogik](https://promptkatalog.eldshort.de/prompten.html)
- ChatBot/Text-to-Text Kataloge:
	- Free/Open: [prompts.chat](https://prompts.chat/), [Agentic Workers](https://www.agenticworkers.com/library), GPTBot [Prompts Library](https://gptbot.io/chatgpt-prompts), Alexandria [Prompt Library](https://aiexandria.com/), Temaniaga [Prompt Hub for Business](https://www.temaniaga.com/apps/ai-prompt-hub/), [Awesome ChatGPT Prompts](https://github.com/f/awesome-chatgpt-prompts)
	- Commercial (€): [GodOfPrompt](https://www.godofprompt.ai/prompt-library), [Business Prompts](https://businessaiprompts.com/PromptLibrary)
	- Vendors: OpenAI [Cookbook](https://cookbook.openai.com/), Microsoft [Copilot Promptkatalog](https://m365.cloud.microsoft/copilot-prompts)
	- Edu: [KI-Campus Prompt-Katalog](https://coda.io/@kic/prompt-katalog), [Josh Cavalier](https://joshcavalier.notion.site/), [Microsoft Prompts for Edu](https://github.com/microsoft/prompts-for-edu)
- Text-to-Image Kataloge: [PromptHero](https://prompthero.com/ai-prompts), [chatgptprompt.in](https://chatgptprompt.in/)
- Text-to-Video Kataloge: [PromptHero](https://prompthero.com/video), [chatgptprompt.in](https://chatgptprompt.in/prompts?category=video)
- Vibe Coding Kataloge: [loveable](https://docs.lovable.dev/prompting/prompting-library), [cursor.directory](https://cursor.directory/rules), Examples by [VibeCodex](https://vibecodex.io/#prompts)
- System Prompts: [System Prompts Leaks](https://github.com/asgeirtj/system_prompts_leaks)

## Agent Context File

\[ aka CLAUDE.md / AGENT.md / META.md / ... \]

- [Karpathy-Inspired CLAUDE.md](https://github.com/multica-ai/andrej-karpathy-skills)
- Further Reading: [Awesome Claude.md](https://github.com/josix/awesome-claude-md), 

## MCP

\[ = Model Context Protocol \]

- [MCP **Standardization**](https://modelcontextprotocol.io)
- Repos: [MCP Market](https://mcpmarket.com/), [smithery.ai](https://smithery.ai/)
- Further Reading: [Awesome MCP Servers](https://github.com/punkpeye/awesome-mcp-servers)

## Agent Skills

- [Agent Skills **Standardization**](https://agentskills.io/home)
- Cross Agent Tools: [npx skills](https://github.com/vercel-labs/skills)
- Coding
	- [Everything Claude Code (ECC)](https://github.com/affaan-m/ecc) (funkioniert auch mit anderen AI coding assistants)
	- [Antigravity Awesome Skills](https://github.com/sickn33/antigravity-awesome-skills) (funkioniert auch mit anderen AI coding assistants)
	- [Superpowers](https://github.com/obra/superpowers)
	- Repos: [Open Agent Skills Ecosystem](https://www.skills.sh/), [SkillsLLM](https://skillsllm.com/), [Awesome Skills](https://awesome-skills.com/)
	- Further Reading: [Awesome Claude Skills #1](https://github.com/travisvn/awesome-claude-skills), [Awesome Claude Skills #2](https://github.com/ComposioHQ/awesome-claude-skills), [Awesome Claude Code Subagents](https://github.com/VoltAgent/awesome-claude-code-subagents), [Official Claude Plugins Marketplace](https://claude.com/plugins)
- MS Office
	- Anthropic: [pdf](https://www.skills.sh/anthropics/skills/pdf), [pptx](https://www.skills.sh/anthropics/skills/pptx), [docx](https://www.skills.sh/anthropics/skills/docx), [xslx](https://www.skills.sh/anthropics/skills/xlsx)
	- [ppt-master](https://www.skills.sh/hugohe3/ppt-master/ppt-master)
- Entscheidungsfindung / Steel-Man the Opposition
	- [the-fool](https://www.skills.sh/jeffallan/claude-skills/the-fool), [dissent](https://www.skills.sh/open-horizon-labs/skills/dissent), [devils-advocate](https://www.skills.sh/majesticlabs-dev/majestic-marketplace/devils-advocate), [gpt-taste](https://www.skills.sh/leonxlnx/taste-skill/gpt-taste), [reasoning personas](https://clawhub.ai/artyomx33/skills/reasoning-personas)
- Informatiker-Humor
	- [gilfoyle](https://www.skills.sh/axiomhq/gilfoyle/gilfoyle), [bmad](https://www.skills.sh/bmad-code-org/bmad-method/bmad-review-adversarial-general), [caveman](https://www.skills.sh/juliusbrussee/caveman/caveman)
- Science
	- [Awesome Science Skills](https://github.com/K-Dense-AI/scientific-agent-skills) (i.a., Research Methodology & Planning, Scientific Writing, Data Analysis & Visualization)
	- [mattpocock teach](https://www.skills.sh/mattpocock/skills/teach)
	- Further Reading: [Awesome Scientific Skills](https://github.com/InternScience/Awesome-Scientific-Skills)

- Token Efficiency / Cost Optimization
	- [Graphify](https://graphify.net/)


## Vibe Testing Werkzeuge

- [RobotFramework](https://robotframework.org/) als Testökosystem, da dessen Testbeschreibungen sehr natürlichsprachlich sind
- [Harness AI Test Automation](https://www.harness.io/products/ai-test-automation)
- [testRigor](https://testrigor.com/) (free for public open source)
- Teilaspekt von [Qodo Gen](https://www.qodo.ai/products/qodo-gen/)
- Java-centric: [diffblue](https://www.diffblue.com/)
- Webartikel: Vibe Testing [with Playwright](https://timdeschryver.dev/blog/vibe-testing-with-playwright)

## Vibe Hacking Werkzeuge

- Vibe Pentesting
	- Local/CLI: [vulnhuntr](https://github.com/protectai/vulnhuntr)
	- Cloud/GUI: [Vibe Coding Penetration Tester](https://github.com/firetix/vibe-coding-penetration-tester) (cf. [vibehack.io](http://vibehack.io/)), [ZeroThreat](https://zerothreat.ai/)

## Vibe Science Werkzeuge

- [K-Dense BYOK](https://github.com/K-Dense-AI/k-dense-byok)

## Generative KI Werkzeuge

Selbst wenn de Verwendung von generativer KI zur Text-Erstellung Ihrer Abschlussarbeit Ihnen ggf. untersagt sein sollte: Dennoch können Sie sich die diversen Werkzeuge zu Nutzen machen, bspw. als persönlicher KI Tutor.

- Chatbots (aka Answer-Engines, in Ggbst. zu Search-Engines):
	- Empfohlen: [**perplexity**.ai](https://www.perplexity.ai/) ⭐ (mit „Focus: Academic“)
	- Weitere Nennenswerte: Anthropic **[Claude](https://www.anthropic.com)**, Google [Gemini](https://gemini.google.com/), OpenAI [ChatGPT](https://openai.com/blog/chatgpt/), Meta [Llama](https://llama.meta.com/), [HuggingChat](https://huggingface.co/chat/), Opera [Aria](https://www.opera.com/features/aria), [character.ai](https://beta.character.ai/), …
	- KI-Suche (Hybirdform von LLMs und Search-Engines)
		- [**you**.com](https://you.com/), [Andi](https://andisearch.com), Microsoft [Bing](https://bing.com/new), OpenAI [SearchGPT](https://openai.com/index/searchgpt-prototype/), …
- AI-enabled Browser: Perplexity [Comet](https://comet.perplexity.ai/), [Sigma](https://www.sigmabrowser.com/), [Fellou](https://fellou.ai/), Arc [Max](https://arc.net/max), Opera [Aria](https://www.opera.com/de/features/aria), Microsoft Edge+Copilot
	- Mac-only: [Dia](https://www.diabrowser.com/)
	- Disbling AI features in Browsers: [Just the Browser](https://justthebrowser.com/)
- Als Extension:
	- in Browsern:
		- Grammatik: [LanguageTool](https://languagetool.org/de/chrome)
		- LLM u.a. für GMail: [Halist AI](https://chromewebstore.google.com/detail/halist-ai/fbpfkdadaghhgfcnaljbkjmfaaclohdb)
		- Weitere Referenzen: [Tooltivity-Liste](https://tooltivity.com/categories/ai)
	- in Thunderbird:
		- [ThunderAI](https://addons.thunderbird.net/en-US/thunderbird/addon/thunderai/)
- Desktop-Apps / AI Tool Installer:
	- Universell: **[pinokio](https://pinokio.computer/)** ⭐, [SEAIT](https://github.com/diStyApps/seait/)
- Text-to-Text:
	- LLM Model-Benchmark: [What LLM Provider](https://whatllm.vercel.app/) | [Open LLM Leaderboard](https://huggingface.co/spaces/open-llm-leaderboard/open_llm_leaderboard) ([Method](https://huggingface.co/docs/leaderboards/open_llm_leaderboard/about)) sowie [MTEB Leaderboard](https://huggingface.co/spaces/mteb/leaderboard)
		- LLM Modelle mit DE-Unterstützung: [Webartikel](https://medium.com/@oledawidzinski/deutschsprachige-open-source-llms-als-alternative-zu-chatgpt-und-co-8ecbcf6ab96d) (u.a. Mistral-Nemo-Instruct-2407, DiscoLM_German_7b_v1, SauerkrautLM, …, Qwen2-7B-Instruct, Llama3-DiscoLeo-Instruct-8B, …)
		- Long-Term Context LLM / Personalized AI: [MemGPT](https://memgpt.ai/)
		- Agent AI: **[Letta](https://github.com/letta-ai/letta)**
	- Desktop/Local/Offline: **[Msty](https://msty.app/)** ⭐, **[LM Studio](https://lmstudio.ai/)** ⭐ \[**choco install lm-studio**\], **[Witsy](https://witsyai.com/)** ⭐ \[**choco install witsy**\], [AnythingLLM](https://anythingllm.com/), Nomic [gpt4all](https://github.com/nomic-ai/gpt4all) \[**choco install gpt4all**\], [Jan AI](https://jan.ai) \[**choco install jan**\] und andere
		- Local [OpenAI-compatible API](https://platform.openai.com/docs/api-reference/chat) Server: [LM Studio OpenAI-compatible API server](https://lmstudio.ai/docs/api/openai-api), [vLLM OpenAI-compatible API Server](https://docs.vllm.ai/en/latest/serving/openai_compatible_server.html), [Msty Local AI Service](https://docs.msty.app/how-to-guides/make-local-ai-service-available-on-the-network), [gpt4all API Server](https://docs.gpt4all.io/gpt4all_api_server/home.html), [Jan.ai Cortex Local API Server](https://cortex.so/docs/quickstart/) ([API](https://cortex.so/api-reference/))
			- Docker: [LocalAI](https://localai.io/): Local family AI, full-stack = All-in-One: LLMs, Text to Speech, Speech to Text, Function calling, Image generation, Embedding server
		- Let LLMs run code locally: [Open Interpreter](https://github.com/OpenInterpreter/open-interpreter)
	- WebUI/Local/Offline:
		- **[Open WebUI](https://openwebui.com/)** ⭐
		- [Text Generation WebUI](https://github.com/hermannklie/text-generation-webui)
	- Embedded/Local/Offline: [vLLM](https://github.com/vllm-project/vllm)
	- Desktop/Cloud-only/Online: **[Noi](https://github.com/lencx/Noi)**
	  - Single Vendor: Unofficial **[ChatGPT Desktop](https://github.com/lencx/ChatGPT)** \[**choco install chatgpt**\], Official **[Claude Desktop](https://claude.ai/download)** \[**choco install claude**\], Official **[Perplexity Windows App](https://apps.microsoft.com/detail/xp8jnqfbqh6pvf)** (sowie Unofficial Inulute [Perplexity AI Desktop](https://pplx.inulute.com/download/))
	- more: [basran](https://github.com/hyperonym/basaran), [LocalAI](https://github.com/mudler/LocalAI), [Xorbits Inference](https://github.com/xorbitsai/inference) 
	- Data Science
		- [**WolframAlpha** Chat Notebooks in der Wolfram Cloud](https://www.wolframcloud.com/) ⭐ ([Anleitung](https://writings.stephenwolfram.com/2023/06/introducing-chat-notebooks-integrating-llms-into-the-notebook-paradigm/))
	- Summarizer
		- Ask your Document: [AskYourPDF](https://askyourpdf.com), [ChatPDF](https://www.chatpdf.com/), [PDF.ai](https://pdf.ai/), …
		- DIY-Helfer
			- Prompt Splitter: [chatgpt-**prompt-splitter**](https://chatgpt-prompt-splitter.jjdiaz.dev) für großen Text-Input (derzeit sind nur Chunks von jeweils ein paar Tausend Zeichen erlaubt)
			- Text-Extraktion aus PDF: **pdftotext** aus den [xpdf-utils](http://www.xpdfreader.com) \[**choco install xpdf-utils**\]
		- YouTube Summarizer (mittels GPT): **[Glasp](https://glasp.co/youtube-summary)**
- Text-to-…: ([Auswahlhilfe](https://llmselector.vercel.app/))
	- Text-to-Code:
		- Dev/FOSS-Models: Facebook [Llama](https://www.llama.com/llama-downloads/), OpenAI [gpt-oss](https://openai.com/index/introducing-gpt-oss/), Google [gemma](https://huggingface.co/google), [DeepSeek](https://huggingface.co/deepseek-ai), xAI [grok](https://huggingface.co/xai-org), [Qwen](https://huggingface.co/Qwen), [Mistral](https://huggingface.co/mistralai) (Mistral [Commercial vs. OSS](https://docs.mistral.ai/getting-started/models)), TII [Falcon](https://huggingface.co/tiiuae), BigScience [BLOOM](https://huggingface.co/bigscience/bloom)
			- AI-Coder Model-Benchmark: [Eval Plus](https://evalplus.github.io/leaderboard.html)
		- Desktop/Local/Offline: **[Msty](https://msty.app/)** ⭐, **[LM Studio](https://lmstudio.ai/)** ⭐
		- WebUI/Local/Offline: [bolt.diy](https://github.com/stackblitz-labs/bolt.diy), [autogpt](https://agpt.co/)
		- Cloud/freemium: [DeepSeek Chat](https://chat.deepseek.com/), Online [Eden AI](https://www.edenai.co/), [uvm.](https://codesubmit.io/blog/ai-code-tools/)
		- Nennenswerte andere Dev-Tools: [dir-assistant](https://github.com/curvedinf/dir-assistant)
		- Weiterführende Referenzen: [Awesome AI-Powered Developer Tools](https://github.com/jamesmurdza/awesome-ai-devtools) | [Awesome Code-AI](https://github.com/sourcegraph/awesome-code-ai)
	- Text-to-SQL:
		- Foundational Models: [DuckDB NSQL](https://github.com/NumbersStationAI/DuckDB-NSQL)
		- Tutorials: AWS Machine Learning [Build a robust text-to-SQL solution ](https://aws.amazon.com/de/blogs/machine-learning/build-a-robust-text-to-sql-solution-generating-complex-queries-self-correcting-and-querying-diverse-data-sources/), LlamaIndex [Text-to-SQL Guide with Jupyter](https://docs.llamaindex.ai/en/stable/examples/index_structs/struct_indices/SQLIndexDemo/), IBM Watson [Generating SQL from text with LLMs](https://developer.ibm.com/tutorials/awb-text-to-sql-using-llms/)
	- Text-to-Image:
		- AI-Image-Generator Model-Benchmark: Artificial Analysis [Image AI Model & Provider Leaderboard](https://artificialanalysis.ai/text-to-image) | [Benchmarking-Awesome-Diffusion-Models](https://github.com/Schuture/Benchmarking-Awesome-Diffusion-Models)
		- Dev/FOSS Models: **[Stable Diffusion](https://github.com/CompVis/stable-diffusion)**, **[FLUX.1](https://github.com/black-forest-labs/flux)**
		- Desktop/Local/Offline: Lykos **[Stability Matrix](https://lykos.ai/downloads)** ⭐ (Tutorial: [Using FLUX.1 locally](https://www.kdnuggets.com/using-flux-1-locally))
			- Stability Matrix ist ein 1-Stop-Shop für alle anderen Werkzeuge wie bspw.: Stable Diffusion WebUI [Forge](https://github.com/lllyasviel/stable-diffusion-webui-forge) bzw. [reForge](https://github.com/Panchovix/stable-diffusion-webui-reForge), [ComfyUI](https://github.com/comfyanonymous/ComfyUI)
			- Disclaimer: Manche Text-to-Image Werkzeuge benötigen (Stand 2025) eine NVidia RTX als Hardware-Voraussetzung
			- Bonus-Hinweis: Für Stable Diffusion WebUI, und dessen Derivate, kann man dessen REST-API (aka **sdapi**) mit dessen Kommandozeilenparameter `--api` aktivieren
				- Diesen `--api` Parameter kann man auch in Stability Matrix (unter dessen `Launch Options` für Stable Diffusion WebUI) leicht ergänzen (per `Extra Launch Arguments`)
				- Die aktivierte **sdapi** läuft dann bspw. unter http://127.0.0.1:7860/sdapi/v1/txt2img
		- WebUI/Local/Offline: [MFLUX-WWebUI](https://github.com/CharafChnioune/MFLUX-WEBUI)
		- Cloud/freemium-with-API: [Playground](https://playground.com/design/pricing), [PicoGen](https://picogen.io/), [Pollinations AI](https://pollinations.ai/)
		- Cloud/freemium: [Deep Dream Generator](https://deepdreamgenerator.com/) ([old version](https://deepdreamgenerator.com/generator?old-tools=1)), [Dezgo](https://dezgo.com/text2image/sdxl), [Stable Diffusion Online](https://stablediffusionweb.com/) (10img/d; mit Wasserzeichen), [NightCafe](https://creator.nightcafe.studio/), [WPimages](https://www.wpimagines.com/), [AI Image Generator](https://www.aiimagegenerator.org/), [uvm.](https://easywithai.com/best-free-ai-image-generators/)
		- Cloud/€€€/Subscriptions: **[OpenArt](https://openart.ai/create)** ⭐, [fal](https://fal.ai/), [dreamina](https://dreamina.capcut.com/ai-tool/home/?type=image), OpenAI [**DALL·E** 2](https://labs.openai.com/waitlist), **[Midjourney](https://www.midjourney.com/)**, [craiyon](https://www.craiyon.com/) (früher: „DALL·E mini“), Google [Imagen](https://imagen.research.google/), Adobe [Firefly](https://www.adobe.com/products/firefly.html) …
	- Text-to-Video: [synthesia](https://www.synthesia.io), [dreamina](https://dreamina.capcut.com/ai-tool/home/?type=video), [kaiber.ai](https://kaiber.ai), … , China: [Kling](https://kling.kuaishou.com/en)
		- WebUI/Local/Offline: [CogStudio](https://github.com/pinokiofactory/cogstudio), [FramePack](https://github.com/lllyasviel/framepack), [FP-Studio](https://docs.framepackstudio.com/), [Wan](https://wan.video/)
	- Text-to-Slides: **[Gamma](https://gamma.app/)** ⭐, [Felo Slides](https://felo.ai/agents/felo-slides-qP4dLw7kMv9ZuG5FnX8cH1), [SlidesPilot](https://www.slidespilot.com/), [SlideSpeak](https://slidespeak.co/), [ChatBA](https://www.chatba.com/), [Presentation Intelligence](https://www.pi.inc/), [Slidesgo](https://slidesgo.com/), …
		- Academic: [ChatSlide](https://chatslide.ai/) (formerly: DrLambda)
		- Local: «tbd» ([AutoPresent](https://github.com/para-lost/AutoPresent))
	- Text-to-Visuals (for presentations): [Napkin AI](https://app.napkin.ai/)
	- Text-to-Quiz: [Quizalize](https://app.quizalize.com/pricing), …
	- Text-to-Speach (TTS): [NaturalReader](https://www.naturalreaders.com/online/), [TTSMaker](https://ttsmaker.com/), [Murf.AI](https://murf.ai/text-to-speech), …
	- Text-to-Sound:
		- Cloud: [boomy](https://boomy.com/), [Suno AI](https://app.suno.ai/), [Vocaloid](https://www.vocaloid.com/en/vocaloid6/), Google [Instrument Playground](https://artsandculture.google.com/experiment/instrument-playground/8QFo2oQr2uT3pg?hl=en), …
		- WebUI/Local/Offline: [ACE-Step](https://github.com/ace-step/ACE-Step), [YuE](https://github.com/multimodal-art-projection/YuE)
	- Text-to-3D / Image-to-3D: [csm.ai](https://www.csm.ai) (zzgl. €: [3D AI Studio](https://www.3daistudio.com))
	- AI-Suites/API-centric/Pay-as-you-Go: **[Fireworks AI](https://fireworks.ai/)**, [Replicate](https://replicate.com/)
	- Weiterführende Referenzen: [There is an AI for that](https://theresanaiforthat.com/most-saved/) | [There's an AI](https://theresanai.com/)
- IT-Security:
	- [WormGPT](https://thehackernews.com/2023/07/wormgpt-new-ai-tool-allows.html)
- Prompt Builder:
	- Cloud: gptforwork [OpenAI GPT prompt generator](https://gptforwork.com/tools/prompt-generator)
- Prompting Desktop Integration:
	- [Razer AI Launcher](https://mysupport.razer.com/app/answers/detail/a_id/15016) (Benötigt Razer Maus; Prompt Launcher ist dann Teil von **Synapse**)
	- [Logi AI Prompt Builder](https://www.logitech.com/software/logi-ai-prompt-builder.html) (Benötigt Logitech Maus; Prompt Builder ist dann Teil von **Logi Options+**)
	- Weiterführende Quellen: [Awesome **ChatGPT Prompts**](https://github.com/f/awesome-chatgpt-prompts)
- Weiterführende Quellen
	- Werkzeugsammlungen: **[FutureTools](https://www.futuretools.io)** | [Awesome AI Tools](https://tools.awesomechatgpt.com) #1 | [Awesome AI Tools](https://github.com/mahseema/awesome-ai-tools) #2 | Altern [Awesome AI Tools](https://github.com/mahseema/awesome-ai-tools) #3 | [Awesome Generative AI](https://github.com/steven2358/awesome-generative-ai) #1 | [Awesome Generative AI](https://github.com/filipecalegario/awesome-generative-ai) #2 | [Awesome AGI](https://github.com/EmbraceAGI/Awesome-AGI) | [Awesome GPT](https://github.com/formulahendry/awesome-gpt) | [Awesome GPT-4](https://gpt4.tools) | [Awesome Bots](https://github.com/DopplerHQ/awesome-bots)

## Bildmaterialien Werkzeuge

- Kostenlose bzw. lizenzfreundliche Bildmaterialien: vgl. Schwesterseite [awesome-thesis-tools » Bildmaterialien](https://github.com/cyberlytics/awesome-thesis-tools#bildmaterialien)
- AI-rendered Illustrations/Art:
	- Prompt Galleries (Prompts und deren AI-generierten Bilder): **[PromptHero](https://prompthero.com/)**, **[Playground AI](https://playgroundai.com/)**
	- Unterstützung bei der Prompt Generation: **[NightCafe](https://nightcafe.studio/)**, **[promptoMANIA](https://promptomania.com/prompt-builder/)**
	- Von Unternehmen mit Marktführerschaften: [**Adobe** Firefly](https://firefly.adobe.com/), [**Microsoft** Designer](https://designer.microsoft.com/), ([**Google** Imagen](https://imagen.research.google/) in Vorbereitung)
	- Open Source: **[OpenArt](https://openart.ai/create)** ⭐ ([github](https://github.com/OpenArt-AI)), **[Stable Diffusion](https://huggingface.co/spaces/stabilityai/stable-diffusion)** als free cloud UI via Huggingface Space (eigentliches [KI-Modell](https://github.com/CompVis/stable-diffusion) auf GitHub) by [stability.ai](https://stability.ai/) + [runway](https://runwayml.com/) sowie darauf basierend **[Lexica](https://lexica.art/)**
		- Kommandozeilenwerkzeug: **[imaginAIry](https://github.com/brycedrennan/imaginAIry)**
	- Closed Source: **[craiyon](https://www.craiyon.com/)** (früher: „DALL·E mini“), per Warteliste: [OpenAI DALL·E 2](https://labs.openai.com/waitlist)
		- (€:) **[Midjourney](https://www.midjourney.com/)** ([Anleitung](https://docs.midjourney.com/docs/midjourney-discord); benötigt [Discord](https://discord.com/download); [Pricing](https://docs.midjourney.com/docs/plans))
	- Other: **[artbreeder](https://www.artbreeder.com/)** (formerly known as GANbreeder), **[Lensa](https://play.google.com/store/apps/details?id=com.lensa.app)** (u.a. für AI-Avatare)
	- Stark limitierte kostenlose Angebote: [stockimg.ai](https://stockimg.ai/), [runway](https://runwayml.com/)
	- Disclaimer: [Rule 34](https://en.wikipedia.org/wiki/Rule_34) zzgl. Kürzelkunde [NSFW](https://en.wikipedia.org/wiki/Not_safe_for_work)
	- Weiterführende Quellen: [TopAi.tools](https://topai.tools/) | [Prompt-Werkzeug-Liste auf reddit](https://www.reddit.com/r/StableDiffusion/comments/xcrm4d/useful_prompt_engineering_tools_and_resources/)
- AI-rendered Infographics (mit Texten!):
	- [Ideogram](https://ideogram.ai/)
- AI Image Upscaler
	- **[upscayl](https://upscayl.org/)** ⭐ ([github](https://github.com/upscayl/upscayla)) basierend auf ESRGAN/Real-ESRGAN

## Schwesterseiten

Es gibt von mir weitere Schwesterseiten im Kontext Informatik/KI: [Digitaler Ressourcen-Pool](https://github.com/cyberlytics/awesome-basics), [Werkzeuge » Abschlussarbeiten](https://github.com/cyberlytics/awesome-thesis-tools), [Werkzeuge » Software-Engineering](https://github.com/cyberlytics/awesome-software-engineering-tools) und [Werkzeuge » Big Data und Cloud Computing für AI](https://github.com/cyberlytics/awesome-bdccai-tools).


## Footer

### Future Work

I plan to translate this awesome list from German into English at some point.

### Contribute

What did I miss? Anything you recommend?

Contributions are most welcome, please adhere to the contribution guidelines and ensure your pull request adheres to the following guidelines:

- Make an individual pull request for each suggestion.
- Keep descriptions short and simple.
- Check your spelling and grammar.
- Make sure your text editor is set to remove trailing whitespace.
- Try to make your Pull request and title as descriptive as possible.
- New categories or improvements to the existing categorization are welcome.

Thank you for your suggestions!

### Backers

Thank you to all our supporters! 🙏

_Please, consider supporting my work as a lot of effort takes place to generate this list! Thanks a lot._

[![Buy Me A Coffee please!](https://cdn.buymeacoffee.com/buttons/default-orange.png)](https://www.buymeacoffee.com/cyberpetaneuron)

### License

[![Creative Commons License](http://i.creativecommons.org/l/by/4.0/88x31.png)](http://creativecommons.org/licenses/by/4.0/)

This work is licensed under Creative Commons [CC BY 4.0](http://creativecommons.org/licenses/by/4.0/) .
