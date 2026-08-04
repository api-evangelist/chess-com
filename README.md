# Chess.com (chess-com)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/chess-com/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/chess-com/refs/heads/main/apis.yml)

## Scope

- **Access:** 3rd-Party

## Tags

- Chess
- Gaming
- Online Games
- Sports
- Community
- Education

## Timestamps

- **Created:** 2026-05-25
- **Modified:** 2026-05-25

## APIs

### Chess.com Published Data API

Public, unauthenticated REST API exposing player profiles, monthly game archives (with PGN download), club rosters, daily and live team matches, Swiss/round-robin tournaments, titled players, country rosters, the daily puzzle, the streamer list, and live leaderboards across daily, blitz, bullet, rapid, tactics, lessons, and chess variants. JSON-LD response shape with ETag, Last-Modified, gzip, and JSONP support; data refreshes at most every 12-24 hours.

- **Human URL:** [https://www.chess.com/news/view/published-data-api](https://www.chess.com/news/view/published-data-api)
- **Base URL:** `https://api.chess.com/pub/`

#### Tags

- Chess
- Gaming
- Players
- Public Data

#### Properties

- [Documentation](https://www.chess.com/news/view/published-data-api)
- [Documentation](https://support.chess.com/en/articles/9650547-published-data-api)
- [OpenAPI](openapi/chess-com-published-data-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/chess-com-published-data-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/chess-com-published-data-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/chess-com-player-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/chess-com-game-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/chess-com-club-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON-LD](json-ld/chess-com-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)

## Common Properties

- [Portal](https://www.chess.com)
- [Documentation](https://www.chess.com/news/view/published-data-api)
- [Documentation](https://support.chess.com/en/articles/9650547-published-data-api)
- [Pricing](https://www.chess.com/membership)
- [Privacy Policy](https://www.chess.com/legal/privacy)
- [Terms of Service](https://www.chess.com/legal)
- [About Us](https://www.chess.com/about)
- [Blog](https://www.chess.com/news)
- [Blog](https://www.chess.com/article)
- [Forum](https://www.chess.com/forum)
- [LinkedIn](https://www.linkedin.com/company/chess-com)
- [Twitter](https://twitter.com/chesscom)
- [YouTube](https://www.youtube.com/chess)
- [Twitch](https://www.twitch.tv/chess)
- [GitHub Organization](https://github.com/chess)
- [Support](https://www.chess.com/coaches)
- [Documentation](https://www.chess.com/streamers)
- [Documentation](https://www.chess.com/leaderboard)
- [SDK](https://github.com/andyruwruw/chess-web-api)
- [SDK](https://www.npmjs.com/package/chess-web-api)
- [SDK](https://github.com/sarartur/chess.com)
- [SDK](https://github.com/Stupidoodle/chess-com-api)
- [SDK](https://github.com/sornerol/chess-com-pubapi-java-wrapper)
- [SDK](https://github.com/chrismaltais/chess-pub-api-client)
- [Plans](plans/chess-com-plans-pricing.yml)
- [Rate Limits](rate-limits/chess-com-rate-limits.yml)
- [Fin Ops](finops/chess-com-finops.yml)
- [Vocabulary](vocabulary/chess-com-vocabulary.yml)

## Maintainers

**FN:** Kin Lane
**Email:** info@apievangelist.com
