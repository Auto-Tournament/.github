<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/at-wordmark-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="assets/at-wordmark-light.svg">
  <img src="assets/at-wordmark-light.svg" alt="Auto Tournament" height="56">
</picture>

Self-hosted tournament platform. You create the tournament; Auto Tournament
loads each match onto your game servers, tracks the score and moves the
bracket on by itself.

CS2 is the built-in game today. From 3.0, games and tournament formats plug in
as modules.

| Repository | What it is | License |
|---|---|---|
| [auto-tournament](https://github.com/Auto-Tournament/auto-tournament) | The platform: web app, API and database, shipped as one Docker image. Formerly MatchZy Auto Tournament. | PolyForm Noncommercial |
| [ready-up](https://github.com/Auto-Tournament/ready-up) | Ready Up: the new native CS2 match plugin, with no Metamod or CounterStrikeSharp needed. A MatchZy / Get5 alternative that survives CS2 updates. | PolyForm Noncommercial |
| [cs2-plugin](https://github.com/Auto-Tournament/cs2-plugin) | MatchZy Enhanced (now named Auto Tournament CS2): the CounterStrikeSharp plugin that runs matches and reports every event to Auto Tournament. | MIT |
| [cs2-server-manager](https://github.com/Auto-Tournament/cs2-server-manager) | CLI that installs and runs several CS2 servers on one Linux machine. | PolyForm Noncommercial |
| [packs](https://github.com/Auto-Tournament/packs) | Game packs for the platform's game catalog. | PolyForm Noncommercial |
| [docs](https://github.com/Auto-Tournament/docs) | Source for [docs.autotournament.gg](https://docs.autotournament.gg). | PolyForm Noncommercial |

Free for personal and non-commercial use. If you earn money from running the tools, a commercial license is priced per server: see [pricing](https://autotournament.gg/pricing).

[Website](https://autotournament.gg) · [Documentation](https://docs.autotournament.gg) · [Pricing](https://autotournament.gg/pricing) · [Discord](https://discord.gg/n7gHYau7aW)

<sub>The Auto Tournament, Auto Tournament CS2 and CS2 Server Manager logos were generated with an AI image model (ChatGPT) and then cleaned up and recoloured by hand.</sub>
