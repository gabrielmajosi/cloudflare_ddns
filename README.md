# cloudflare_ddns


### Install
`git clone https://github.com/sheepsushis/cloudflare_ddns.git`

### Usage

Rename `example.config.json` to `config.json`, open the file.

`email` - the email you used to sign up on Cloudflare  
`api_key` - go to [here](https://dash.cloudflare.com/profile/api-tokens) and get your "global api key" from the bottom of the page  
`zones` - go to your site, go to overview, and scroll down to "Zone ID" on the right side. Copy it, and place it in the list  
`query_every_seconds` - how often you want to check if the DNS is valid  

A systemd unit is **strongly** recomended.
