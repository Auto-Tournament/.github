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

| Repository | What it is |
|---|---|
| [auto-tournament](https://github.com/Auto-Tournament/auto-tournament) | The platform: web app, API and database, shipped as one Docker image. Formerly MatchZy Auto Tournament. |
| [auto-tournament-cs2](https://github.com/Auto-Tournament/auto-tournament-cs2) | Auto Tournament CS2 (formerly MatchZy Enhanced): the CS2 server plugin that runs matches and reports every event to Auto Tournament. |
| [cs2-server-manager](https://github.com/Auto-Tournament/cs2-server-manager) | CLI that installs and runs several CS2 servers on one Linux machine. |
| [docs](https://github.com/Auto-Tournament/docs) | Source for [docs.autotournament.gg](https://docs.autotournament.gg). |

[Documentation](https://docs.autotournament.gg) · [Discord](https://discord.gg/n7gHYau7aW)

<sub>The Auto Tournament, Auto Tournament CS2 and CS2 Server Manager logos were generated with an AI image model (ChatGPT) and then cleaned up and recoloured by hand.</sub>
