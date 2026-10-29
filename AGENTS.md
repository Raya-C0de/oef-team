Maak in de root van deze repo een bestand AGENTS.md met precies twee secties:

## Project
## Stack & constraints

Werkwijze:
- Onderzoek eerst de repo: README, package-manifests (package.json, pyproject.toml,
  go.mod, Cargo.toml e.d.), lockfiles, configbestanden, CI-workflows, Dockerfiles,
  .env.example en de mappenstructuur.
- Schrijf alleen feiten die je in de repo kunt aanwijzen. Geen regels, conventies,
  adviezen of instructies: geen "altijd", "nooit", "moet", "gebruik", "vermijd".
- Wat je niet zeker weet, laat je weg. Gok niet en vul niets aan uit algemene kennis.

Inhoud Project:
- Wat het project is en doet, in 2–4 zinnen.
- Voor wie of waarvoor het bedoeld is (alleen als dat uit de repo blijkt).
- Globale opbouw: de belangrijkste mappen en wat erin staat.

Inhoud Stack & constraints:
- Talen en versies (zoals vastgelegd in config of lockfiles).
- Frameworks en belangrijkste libraries, met versies.
- Package manager, build-tool, testframework, linter/formatter.
- Runtime- en deploydoel (bv. Node 20, Docker, Vercel, AWS Lambda).
- Databases en externe services/API's waarvan de repo afhankelijk is.
- Vastgelegde beperkingen die in de config staan, zoals engine-versies,
  ondersteunde browsers of platformen, en verplichte environment-variabelen
  (alleen de namen, nooit waarden).

Vorm:
- Korte bullets, geen inleiding of afsluiting, geen andere secties.
- Houd het onder de ~60 regels.
- Laat me na afloop per bullet weten op welk bestand die gebaseerd is,
  maar zet die bronnen niet in AGENTS.md zelf.