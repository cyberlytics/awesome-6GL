[//]: # (Author: Christoph P. Neumann)
[//]: # (Title: Awesome Agentic Engineering)
[//]: # (Language: de-DE)
[//]: # (Licence: CC BY 4.0)
[//]: # (Kurztitel: 6GL)
[//]: # (Lemma: 6GL)

# Awesome 6GL

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) [![Made With Love](https://img.shields.io/badge/Made%20With-Love-pink.svg)](https://github.com/chetanraj/awesome-github-badges) [![Donate via PayPal](https://img.shields.io/badge/Donate-PayPal-blue?logo=paypal)](https://www.paypal.com/donate/?hosted_button_id=QTDJ2JA58ZM9L) [![Support on Ko-fi](https://img.shields.io/badge/Donate-ko--fi-%23FF5E5B?logo=ko-fi&logoColor=white)](https://ko-fi.com/cyberlytics) [![Buy Me A Coffee!](https://img.shields.io/badge/Donate-buymeacoffee-%23FFDD00?logo=buymeacoffee)](https://www.buymeacoffee.com/cyberpetaneuron)

Dies ist mein digitaler Ressourcen-Pool für 6GL (Natural Language Programming) und Agentic Engineering (AI-native SDLC / Spec-Driven Development). Entstanden an der [OTH Amberg-Weiden](https://www.oth-aw.de/cpn), welche für ein paar Einträge entsprechend den Kontext bildet.

Es gibt von mir weitere Schwesterseiten im Kontext Informatik/KI: [Digitaler Ressourcen-Pool](https://github.com/cyberlytics/awesome-basics), [Werkzeuge » Abschlussarbeiten](https://github.com/cyberlytics/awesome-thesis-tools), [Werkzeuge » Software-Engineering](https://github.com/cyberlytics/awesome-software-engineering-tools) und [Werkzeuge » BDCC/AI](https://github.com/cyberlytics/awesome-bdccai-tools).

**Table of Contents**

<!-- toc -->

- [Heading TODO](#heading-todo)
- [Footer](#footer)
  - [Future Work](#future-work)
  - [Contribute](#contribute)
  - [Backers](#backers)
  - [License](#license)

<!-- tocstop -->

## Vibe Coding

\[OBACHT: Gilt für eine akademische Abschlussarbeit ggf. als Unterschleif i.S.v. High-Tech-Plagiarism. Hochschulrecht ist anders als reines Urheberrecht.\]

- Übersicht/Einstieg: indiehackers [Vibe Coding Tools](https://www.indiehackers.com/vibe-coding-tools) ([free ones](https://www.indiehackers.com/vibe-coding-tools?tags=Free))
- Wegbereiter:
	- Begriff: [Andrej Karpathy](https://x.com/karpathy/status/1886192184808149383) in February 2025
	- Technik: "[Cursor](https://www.cursor.com/) [Composer](https://cursor101.com/article/cursor-composer) (i.e., multi-file editing), backed with Claude [Sonnet](https://www.anthropic.com/claude/sonnet) (i.a., due to its large context window of 200K+), talked to via [SuperWhisper](https://superwhisper.com/)"
- Methodisches State-of-the-Art:
	- [AI Unified Process](https://unifiedprocess.ai/) (Einstieg: [software-architektur.tv](https://software-architektur.tv/2026/01/16/folge298.html), [Video](https://tube.tchncs.de/w/mUmkL5mEFzYXD8dY4ixrTY)) mit Querbezug zu [Self-contained Systems](https://scs-architecture.org/) (SCS) von Innoq
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
	- Nennenswerte weitere Ansätze:
		- [MetaGPT](https://github.com/FoundationAgents/MetaGPT): Multi-Agent Framework that assigns different roles to GPTs to form a collaborative entity for complex tasks ([Docs](https://docs.deepwisdom.ai/main/en/guide/get_started/introduction.html))
			- MetaGPT X (= Spin-off product by MetaGPT inventors): [MGX](https://mgx.dev/)
- Cheat Sheets
	- [Claude Code Cheat Sheet](https://awesomeclaude.ai/code-cheatsheet)
	- [Antigravity CLI (agy) Cheat Sheet #1](https://agentpedia.codes/blog/antigravity-cheat-sheet), [Antigravity CLI (agy) Cheat Sheet #2](https://toolsbase.dev/en/reference/antigravity-cli-commands)
- CLAUDE.md / META.md templates
	- [Karpathy-Inspired CLAUDE.md](https://github.com/multica-ai/andrej-karpathy-skills)
	- Further Reading: [Awesome Claude.md](https://github.com/josix/awesome-claude-md), 
- [MCP](https://modelcontextprotocol.io)
	- Repos: [MCP Market](https://mcpmarket.com/), [smithery.ai](https://smithery.ai/)
	- Further Reading: [Awesome MCP Servers](https://github.com/punkpeye/awesome-mcp-servers)
- [Agent Skills](https://agentskills.io/home)
	- Cross Agent Tools: [npx skills](https://github.com/vercel-labs/skills)
	- Coding
		- [Everything Claude Code (ECC)](https://github.com/affaan-m/ecc) (funkioniert auch mit anderen AI coding assistants)
		- [Antigravity Awesome Skills](https://github.com/sickn33/antigravity-awesome-skills) (funkioniert auch mit anderen AI coding assistants)
		- [Superpowers](https://github.com/obra/superpowers)
		- Repos: [Open Agent Skills Ecosystem](https://www.skills.sh/), [SkillsLLM](https://skillsllm.com/), [Awesome Skills](https://awesome-skills.com/)
		- Further Reading: [Awesome Claude Skills #1](https://github.com/travisvn/awesome-claude-skills), [Awesome Claude Skills #1](https://github.com/ComposioHQ/awesome-claude-skills), [Awesome Claude Code Subagents](https://github.com/VoltAgent/awesome-claude-code-subagents), [Official Claude Plugins Marketplace](https://claude.com/plugins)
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
- Für SQL (KI-gestützte SQL Code-Completion)
	- Open-Source **[NSQL](https://huggingface.co/NumbersStation)** mit [Begleitartikel](https://www.numbersstation.ai/post/introducing-nsql-open-source-sql-copilot-foundation-models)
	- Kostenpflichtig (€): **[Cogram](https://www.cogram.com/)**
- Vibe Testing
	- [RobotFramework](https://robotframework.org/) als Testökosystem, da dessen Testbeschreibungen sehr natürlichsprachlich sind
	- [Harness AI Test Automation](https://www.harness.io/products/ai-test-automation)
	- [testRigor](https://testrigor.com/) (free for public open source)
	- Teilaspekt von [Qodo Gen](https://www.qodo.ai/products/qodo-gen/)
	- Java-centric: [diffblue](https://www.diffblue.com/)
	- Webartikel: Vibe Testing [with Playwright](https://timdeschryver.dev/blog/vibe-testing-with-playwright)
- Vibe Hacking / Vibe Pentesting
	- Local/CLI: [vulnhuntr](https://github.com/protectai/vulnhuntr)
	- Cloud/GUI: [Vibe Coding Penetration Tester](https://github.com/firetix/vibe-coding-penetration-tester) (cf. [vibehack.io](http://vibehack.io/)), [ZeroThreat](https://zerothreat.ai/)
- Vibe Coding via Prompting
	- Tutorials: [loveable](https://docs.lovable.dev/tips-tricks/prompting-one), [VibeCoding](https://github.com/cpjet64/vibecoding/tree/main), [bolters.io Knowledge Base](https://bolters.io/)
	- Prompting Recipies: Prompting Library by [loveable](https://docs.lovable.dev/prompting/prompting-library), [cursor.directory](https://cursor.directory/rules), Examples by [VibeCodex](https://vibecodex.io/#prompts), OpenAI Academy [Prompt Packs](https://academy.openai.com/public/tags/prompt-packs-6849a0f98c613939acef841c)
	- Prompt Generators: [TinyToolStack](https://tinytoolstack.com/app/vibecodingpromptgenerator?ref=producthunt), PromptHub [Prompt Iterator](https://www.prompthub.us/prompt-enhancers/prompt-iterator), [Bolt Prompter](https://chatgpt.com/g/g-tozliiBeO-bolt-prompter)
- Supporting Tools
	- Pack your codebase into AI-friendly formats: [Repomix](https://repomix.com)
- Vibe Science
	- [K-Dense BYOK](https://github.com/K-Dense-AI/k-dense-byok)
- Weiterführende Referenzen: [Awesome Vibe Coding](https://github.com/filipecalegario/awesome-vibe-coding), [Awesome Vibe Coding Tools](https://github.com/furudo-erika/awesome-vibe-coding-tools?tab=readme-ov-file) 

## Agentic Engineering Manifest

\[aka: Die (merkfähigen) 10 Gebote nach Neumann\]

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
	* Hintergrund: Agent Skills sind im Format [technisch normiert](https://agentskills.io/specification) (SKILL.md) und bilden ein eigenes Ökosystem.
	* Der Wettbewerb verschiebt sich von der Implementierung einzelner Funktionen zur Gestaltung wiederverwendbarer Fähigkeiten.
	* Im Agentic Programming kapseln **Skills** wiederholbare Entscheidungslogik, Engineering-Prinzipien und technische Umsetzungsmuster.
	* **Nebengesetz:** „Modelle denken, Werkzeuge handeln.“

8.	**„Spezifikation ist die neue Implementierung.“**
	* In der Agenten-Ära wird fachliche und technische Expertise generativ zu Software.
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
	* Dies widerspricht der häufigen Fehlannahme „Jetzt kann jeder Software bauen.“
	* Für einfache Anwendungen genügen Low-Code-Ansätze, komplexe Software-Anwendungen bleiben eine Engineering-Disziplin.


### Lernpfad

* Erst eine Subscription oder ein [lokales Ollama](https://martinfowler.com/articles/exploring-gen-ai/local-models-for-coding-factors.html).
* Dann [CLAUDE.md](https://github.com/multica-ai/andrej-karpathy-skills/blob/main/CLAUDE.md).
* Dann [ECC](https://github.com/affaan-m/ecc)-analoge Skills.
* Dann All-In. (Mindset!)
* Dann die [richtige Echokammer](https://simonwillison.net/).
* Dann 6GL aka [Natural Language Programming](https://www.cs.utexas.edu/~EWD/transcriptions/EWD06xx/EWD667.html) (Programmier-Ebene)
	- Andrej Karpathy betonte „agentic programming as a tool“, bei der Vibe-Coding-Begriffsbildung
* Dann Spec-Driven Development (SDD) aka Agentic Engineering (SW-Technik-Ebene)
	- Further Reading: [spec-kit](https://github.com/github/spec-kit), [SpecDD](https://specdd.ai/) (sowie exemplarisch [kiro](https://kiro.dev/) und [tessl](https://tessl.io/))

Vibe Coding Referenzprojekt für Einsteiger mit kleinen Projekten (ca. 1-wöchige SW-Prototypen)?

* Mein Modul Webanwendungsentwicklung, studentisches Team DeadLock: [CLAUDE.md](https://github.com/CycleByte/WAE-2026SS-TeamBlau-DeadLock/blob/main/CLAUDE.md)

### Weitere Hinweise

* **Welches Modell passt in meine Grafikkarte?** → Nutzt den **[VRAM Calculator](https://apxml.com/tools/vram-calculator)** ⭐
  * (Wer die zugrunde liegenden Infos ebenfalls gelesen hat? Natürlich das freundliche Freibier-Frontier-Modell deiner Wahl. Der Bot berät dazu ebenfalls.)*

* **„DeepSeek als Alternative zu Claude Code oder GitHub Copilot?“ ist die falsche Fragestellung.**
  Die eigentliche Einordnung ist:

  * **Frontier-Modelle**: 1T+ Parameter, typischerweise Cloud-Modelle der Big-Tech-Anbieter
  * **Mid-Tier-Modelle**: lokal nutzbar mit sehr viel Speicher (z. B. 128+ GB RAM, etwa auf Geräten wie NVIDIA DGX Spark oder Ryzen AI 395-Systemen)
  * **Edge-Modelle**: abhängig von verfügbarer Hardware – von Desktop-GPUs bis Smartphones

  NVIDIA DGX Spark könnte man entsprechend auch als **Premium-AI-Edge** bezeichnen.

  DeepSeek R1 (Release Januar 2025) war ein **671B-Modell** mit **37B aktiven Parametern durch Mixture-of-Experts (MoE)**. Die lokal auf Laptops und PCs genutzten DeepSeek-Varianten sind dagegen typischerweise **3B/7B/9B-Modelle**. Das große 671B(37B)-Modell ist Open Source, läuft aber nicht auf gewöhnlicher Edge-Hardware.

* **Modelmaxxing als Kostenoptimierung**

  Der bewusste Wechsel zwischen Modellklassen etabliert sich zunehmend als *modelmaxxing*:

  * Planung mit einem High-End-Modell
  * Implementierung mit einem günstigeren Mid-Tier-Modell

  Gerade Studierende profitieren davon, weil Kosten eine zentrale Rolle spielen.

* **Vibe-Coding-Anpassungsstörungen?**

  Die [aktuelle Zerrissenheit](https://writer.com/blog/enterprise-ai-adoption-survey-results-press-release/) erinnert an frühere Paradigmenwechsel:

  * Dijkstra wurde nicht nur für „[GOTO considered harmful](https://www.perplexity.ai/search/new?q=Wurde+Dijkstra+nicht+nur+gefeiert+für+%22Goto+considered+harmful%22+sondern+auch+angefeindet%3F+Wie+kontrovers+war+die+Modernisierung+zu+seiner+Zeit%3F)“ gefeiert, sondern auch kontrovers diskutiert.
  * GOTO war nicht „falsch“, sondern Teil des 2GL-Programmierstils. Structured Programming und 3GL haben es lediglich im Mainstream verdrängt.
  * Ähnlich dürfte es mit 6GL-Techniken laufen.

  Nebenbemerkung: GOTO wird beispielsweise im Linux-Kernel weiterhin intensiv für Cleanup- und Error-Handling-Muster verwendet; ein Grund könnte allerdings sein, dass sich bessere Alternativen wie ein [`defer`-Konstrukt](https://www.open-std.org/JTC1/SC22/WG14/www/docs/n3734.pdf) noch im C-Standardisierungsprozess befinden.

* **Programmiersprachengenerationen**

  Kennt ihr die Entwicklung von **[1GL bis 5GL](https://en.wikipedia.org/wiki/Programming_language_generations)**?

  * 4GL (deklarativ) und 5GL (logikbasiert) wurden nie ein Massenphänomen und haben 3GL-Hochsprachen nicht verdrängt.
  * Uncle Bobs Vortrag **„[The Future of Programming](https://www.youtube.com/watch?v=ecIWPzGEbFc)“** ist hierzu weiterhin relevant.

* **Vibe Coding als 6GL**

  Vibe Coding kann als **6GL: Natural Language Programming bzw. Spec-Driven Development** verstanden werden.

  * 3GL-Programmierer beherrschen heute meist weder 2GL (Assembly) noch 1GL (Maschinensprache) im Alltag.
  * Jede neue Abstraktion erzeugt eine neue Generation von Entwicklern.
  * Die 6GL wird die 3GL nicht einfach „ersetzen“, sondern die nächste dominante Abstraktionsebene bilden.


## Vibe Coding Einstiegshinweise

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
