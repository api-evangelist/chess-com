# Chess.com (chess-com)

Chess.com is the world's largest online chess platform, serving 250+ million members with play, training, lessons, puzzles, live event broadcasts, streamers, and a community of clubs and tournaments. The Chess.com Published Data API (PubAPI) exposes a free, unauthenticated, JSON-LD REST surface covering players, monthly game archives (with PGN download), clubs, daily and live team matches, Swiss and round-robin tournaments, titled-player lists, country rosters, the daily puzzle, the streamer list, and live leaderboards.

**URL:** [Visit APIs.json](https://raw.githubusercontent.com/api-evangelist/chess-com/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags

 - Chess, Gaming, Online Games, Sports, Community, Education

## Timestamps

- **Created:** 2026-05-25
- **Modified:** 2026-05-25

## At a Glance

| Property | Value |
|---|---|
| Base URL | `https://api.chess.com/pub/` |
| Auth | None (public) |
| Format | JSON-LD (gzip, ETag, Last-Modified, JSONP) |
| Rate limit | Serial unlimited; parallel requests get `429` |
| Refresh cadence | At most every 12-24 hours |
| Documentation | [Published Data API](https://www.chess.com/news/view/published-data-api) |

## APIs

### Chess.com Published Data API
Public, unauthenticated REST API exposing player profiles, monthly game archives (with PGN download), club rosters, daily and live team matches, Swiss and round-robin tournaments, titled players, country rosters, the daily puzzle, the streamer list, and live leaderboards.

**Human URL:** [https://www.chess.com/news/view/published-data-api](https://www.chess.com/news/view/published-data-api)

- [Documentation](https://www.chess.com/news/view/published-data-api)
- [Help Center](https://support.chess.com/en/articles/9650547-published-data-api)
- [OpenAPI](openapi/chess-com-published-data-api-openapi.yml)
- [JSON Schema - Player](json-schema/chess-com-player-schema.json)
- [JSON Schema - Game](json-schema/chess-com-game-schema.json)
- [JSON Schema - Club](json-schema/chess-com-club-schema.json)
- [JSON-LD Context](json-ld/chess-com-context.jsonld)
- [Naftiko Capability - Players](capabilities/players-players.yaml)
- [Naftiko Capability - Games](capabilities/games-games.yaml)
- [Naftiko Capability - Clubs](capabilities/clubs-clubs.yaml)
- [Naftiko Capability - Tournaments](capabilities/tournaments-tournaments.yaml)
- [Naftiko Capability - Matches](capabilities/matches-matches.yaml)
- [Naftiko Capability - Countries](capabilities/countries-countries.yaml)
- [Naftiko Capability - Puzzles](capabilities/puzzles-puzzles.yaml)
- [Naftiko Capability - Leaderboards](capabilities/leaderboards-leaderboards.yaml)
- [Naftiko Capability - Streamers](capabilities/streamers-streamers.yaml)

## Resource Coverage

| Resource | Endpoints |
|---|---|
| Players | `/player/{username}`, `/stats`, `/is-online`, `/clubs`, `/matches`, `/tournaments`, `/titled/{title}` |
| Games | `/games`, `/games/to-move`, `/games/archives`, `/games/{YYYY}/{MM}`, `/games/{YYYY}/{MM}/pgn` |
| Clubs | `/club/{url-ID}`, `/members`, `/matches` |
| Tournaments | `/tournament/{url-ID}`, `/{round}`, `/{round}/{group}` |
| Team Matches | `/match/{ID}`, `/match/{ID}/{board}`, `/match/live/{ID}`, `/match/live/{ID}/{board}` |
| Countries | `/country/{iso}`, `/players`, `/clubs` |
| Puzzles | `/puzzle`, `/puzzle/random` |
| Streamers | `/streamers` |
| Leaderboards | `/leaderboards` |

## Common Properties

- [Portal - chess.com](https://www.chess.com)
- [Documentation - Published Data API](https://www.chess.com/news/view/published-data-api)
- [Documentation - Help Center PubAPI](https://support.chess.com/en/articles/9650547-published-data-api)
- [Pricing - Premium Membership](https://www.chess.com/membership)
- [AboutUs](https://www.chess.com/about)
- [PrivacyPolicy](https://www.chess.com/legal/privacy)
- [TermsOfService](https://www.chess.com/legal)
- [Blog - News](https://www.chess.com/news)
- [Blog - Articles](https://www.chess.com/article)
- [Forum](https://www.chess.com/forum)
- [LinkedIn](https://www.linkedin.com/company/chess-com)
- [Twitter / X](https://twitter.com/chesscom)
- [YouTube](https://www.youtube.com/chess)
- [Twitch](https://www.twitch.tv/chess)
- [GitHub Organization](https://github.com/chess)
- [Streamers](https://www.chess.com/streamers)
- [Leaderboards](https://www.chess.com/leaderboard)
- [SDK - chess-web-api (Node.js)](https://github.com/andyruwruw/chess-web-api)
- [SDK - chess-web-api on npm](https://www.npmjs.com/package/chess-web-api)
- [SDK - chess.com (Python)](https://github.com/sarartur/chess.com)
- [SDK - chess-com-api (async Python)](https://github.com/Stupidoodle/chess-com-api)
- [SDK - chess-com-pubapi-java-wrapper (Java)](https://github.com/sornerol/chess-com-pubapi-java-wrapper)
- [SDK - chess-pub-api-client (Ruby)](https://github.com/chrismaltais/chess-pub-api-client)

## Artifacts

### OpenAPI

- [Chess.com Published Data API](openapi/chess-com-published-data-api-openapi.yml)

### JSON Schema

- [Player](json-schema/chess-com-player-schema.json)
- [Game](json-schema/chess-com-game-schema.json)
- [Club](json-schema/chess-com-club-schema.json)

### JSON Structure

- [Player Structure](json-structure/chess-com-player-structure.json)

### JSON-LD

- [Chess.com Context](json-ld/chess-com-context.jsonld)

### Capabilities (Naftiko)

- [Players](capabilities/players-players.yaml)
- [Games](capabilities/games-games.yaml)
- [Clubs](capabilities/clubs-clubs.yaml)
- [Tournaments](capabilities/tournaments-tournaments.yaml)
- [Team Matches](capabilities/matches-matches.yaml)
- [Countries](capabilities/countries-countries.yaml)
- [Puzzles](capabilities/puzzles-puzzles.yaml)
- [Leaderboards](capabilities/leaderboards-leaderboards.yaml)
- [Streamers](capabilities/streamers-streamers.yaml)

### Examples

- [Get Player Profile](examples/chess-com-get-player-profile-example.json)
- [Get Monthly Archive](examples/chess-com-get-monthly-archive-example.json)
- [Get Daily Puzzle](examples/chess-com-get-daily-puzzle-example.json)

### Spectral Ruleset

- [Chess.com API rules](rules/chess-com-rules.yml)

### Vocabulary

- [Chess.com Vocabulary](vocabulary/chess-com-vocabulary.yml)

### Commercial artifacts

- [Plans / Pricing](plans/chess-com-plans-pricing.yml)
- [Rate Limits](rate-limits/chess-com-rate-limits.yml)
- [FinOps Definition](finops/chess-com-finops.yml)

## Notes for Consumers

- Send a recognizable User-Agent header containing your contact email or URL — generic agents may be blocked.
- Use `If-Modified-Since` and `If-None-Match` to revalidate cached responses with `304 Not Modified`.
- Serialize requests against the host. Parallel callers get `429 Too Many Requests`.
- Lowercase the username before constructing player URLs; the API normalizes accordingly.
- Game archives are immutable once a month rolls over — cache aggressively.

## Maintainers

**FN:** Kin Lane

**Email:** info@apievangelist.com
