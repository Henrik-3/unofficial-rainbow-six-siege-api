# unofficial-rainbow-six-siege-api (v.1.0-beta1)
Unofficial R6 API by scraping data from the r6stats page

# Status
See the current status of the API here: https://status.henrikdev.xyz/

# Authentication and Rate Limits
All rate limits are the same for every endpoint, so in general you have **250 Requests every 2.5 Minutes**. Your rate limit is based on your IP so you don't need an API Key for authentication.
If you exceed rate limit you will get following JSON with 429 Status Code:
```json
{
    "status": "429",
    "message": "You reached your Rate Limit, please try again later"
}
```
# Documentation
The documention for the API is available under https://docs.henrikdev.xyz/r6-api.html

# Endpoints
- The base url is https://api.henrikdev.xyz
- Platforms available: pc, xbox, ps4
- Available profile/player endpoints will be for the initial release:
  - /r6/v1/profile/{platform}/{name} ⚠️
  - /r6/v1/profile/{platform}/{name}/season ⚠️
  - /r6/v1/profile/{platform}/{name}/operator ⚠️

⚠️== Beta | ❌ == Deprecated, will result in 410 Error
  
# Projects using this API
- Currently none, text me if you use it and want to be linked here

# Usage
- N.A

# Contributors
- N.A

# Other Stuff
Also would be happy if you give the project a star and give credit when you use it. If you wanna help me to pay the server (15€ per month), you can help us over the donation link from my hoster: [Link](https://spenden.pp-h.eu/7cca1276-84ee-446f-9b07-47c668eaddfe).

- Other API's
  - https://github.com/Henrik-3/unofficial-valorant-api
  - https://github.com/Henrik-3/unofficial-splitgate-api


If you have any questions write on Discord: Henrik3#1451. 
