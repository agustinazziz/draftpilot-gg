# Riot Production API Key — application text for DraftPilot

Paste these into the Riot Developer Portal application (developer.riotgames.com → Register Product →
Production API Key). Adjust the bracketed parts. Keep the framing: **analysis / coaching on
player-visible information and public data; no automation; no game modification; no information
advantage.**

---

## Product name

DraftPilot

## Product URL

https://draftpilot.gg   (replace with your real domain once the landing page is live)

## Short description (1–2 sentences, for short fields)

DraftPilot is an analysis and coaching tool for the League of Legends champ select phase. It reads the
draft state already shown in the player's client and, combined with public champion statistics,
recommends which champion to pick and how to play the game.

## Full description

DraftPilot helps players make better decisions during the League of Legends pick/ban phase.

During champ select it reads the information already visible to the player — allied picks, enemy picks,
bans, and the player's own assigned role (including autofill) — and produces:

- a recommended pick for the player's role, drawn from a champion pool the player configures plus the
  strongest options outside it, adjusted to the enemy composition, the player's own team composition
  (damage type balance, engage, frontline), the lane matchup, and current-patch win and pick rates;
- a short explanation of why that pick fits the draft;
- an early / mid / late game plan tailored to the specific enemy champions;
- ultimate-usage guidance against the main enemy threats;
- an optional AI-generated natural-language read of the draft, with an alternative-picks list, for
  players who want a deeper analysis.

**Scope and behavior.** DraftPilot is strictly read-only and advisory. It does not pick, ban, accept
queues, script inputs, automate any part of gameplay, modify game files or memory, or interact with the
game in any way. It uses only information that is already on the player's screen during champ select,
plus publicly available champion statistics. It provides no information that other players in the lobby
do not also have.

**Distribution.** DraftPilot is being built for the Overwolf platform and will be distributed through
the Overwolf Appstore as an overlay that is active only during champ select.

**Monetization.** Freemium. A free tier provides the heuristic recommendations and win-rate data. An
optional paid subscription ("Pro") unlocks the AI coach and additional matchup detail. No sale of
in-game currency or items; no implication of Riot Games endorsement.

**Riot API usage.** Version 1 sources live draft data through Overwolf's Game Events API and uses Riot's
Data Dragon for static champion assets (names, icons, roles). We are requesting a production key to stay
compliant and to support planned features that would compute our own aggregate champion statistics from
public match data (e.g. MATCH-V5, LEAGUE-V4) rather than relying on third-party statistics sites. If a
production key is not appropriate for this usage level, please advise which key type we should hold.

**Compliance.** DraftPilot will display the standard non-endorsement notice, will not use Riot logos or
trademarks in its branding, will not claim to be official, and will follow Riot's developer policies and
in-game advertising rules (no advertising shown during active gameplay). A privacy policy and terms of
service are published on the product site.

## Category

Companion app / third-party tool (champ select assistant)

## Team / company

[Your name or company], [Country]. Solo developer / small team.

## Disclaimer to include on all surfaces

DraftPilot isn't endorsed by Riot Games and doesn't reflect the views or opinions of Riot Games or
anyone officially involved in producing or managing Riot Games properties. Riot Games, and all
associated properties are trademarks or registered trademarks of Riot Games, Inc.
