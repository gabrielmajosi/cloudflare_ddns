# cloudflare_ddns

## config.yml guide

Get your global api key from [here](https://dash.cloudflare.com/profile/api-tokens).
Put your email that you signed up with in `email`.
`zones` are the sites you want, go into your overview for your desired site and scroll down to zone id, and one or multiple to the list.
`query_every_seconds` is how often you want to check for IP changes (in seconds).

A systemd unit is **strongly** recomended.
