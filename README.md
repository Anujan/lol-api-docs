##Usage
The base URL for all the requests is http://lol-api.herokuapp.com/api, so if you want to get summoner information an example request would be `http://lol-api.herokuapp.com/api/na/summoner/mrquackers`.

**Supported Regions: NA, EUW, EUNE, TR, BR, OCE**

**All requests must be GET requests.**
*There's no rate limit or authentication required but this is subject to change if this service is abused.*

## [/summoner/:summoner_name](https://github.com/anujan/lol-api-docs/summoner.md)
*Returns a summoner's accountId, summonerId, account level, and profile icon id.*

## [/spectator/:summoner_name](https://github.com/anujan/lol-api-docs/spectator.md)
*Returns in-progress game info used for spectating*

## [/rune_pages/:account_id](https://github.com/anujan/lol-api-docs/rune_pages.md)
*Returns the runepages linked with the account ID provided*

## [/recent_games/:account_id](https://github.com/anujan/lol-api-docs/recent_games.md)
*Returns all the games in the summoner's match history*

## [/leagues/:summoner_id](https://github.com/anujan/lol-api-docs/leagues.md)
*Returns the leagues for that summoner*

## [/mastery_pages/:summoner_id](https://github.com/anujan/lol-api-docs/mastery_pages.md)
*Returns the mastery pages linked to the summoner specified*

## [/player_stats/:account_id](https://github.com/anujan/lol-api-docs/player_stats.md)
*Returns a summoner's stats for the current season. This includes Ranked, Normal, Co-Op vs AI, etc.*