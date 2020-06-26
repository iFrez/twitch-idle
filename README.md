Twitch Idle is a simple CLI to pretend watching streams you follow.
This allows you to 'farm' currencies in various streams. This works for Snusbot, StreamElements,
and a whole lot of other bots tracking your time spent watching the stream.

## Usage

### Prerequisites:

- A valid Node installation (including npm)

### Installation

- Clone this repository
- Install dependencies via `npm install`
- Fill in all required data inside config.json

Variable | Description
------------ | -------------
clientId | [Twitch Application Client ID](https://dev.twitch.tv/)
userName | Twitch Username
userAuth | Oauth token from [Twitch Chat OAuth Password Generator](https://twitchapps.com/tmi/)
token | Token generated especially to your clientId. [Read more here.](https://dev.twitch.tv/docs/authentication/getting-tokens-oauth) Example url to get app token: `https://id.twitch.tv/oauth2/authorize?response_type=token&client_id=<Your clientId>&redirect_uri=http://localhost&scope=viewing_activity_read&state=<Some salt (Random string)>`

- Run the script via `npm run build`