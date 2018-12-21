# discord-image-downloader-go
[forked from here](https://github.com/Seklfreak/discord-image-downloader-go)

## Discord SelfBots are forbidden!
[Official Statement](https://support.discordapp.com/hc/en-us/articles/115002192352-Automated-user-accounts-self-bots-)
### You have been warned.

## Changes
* commented out updateDiscordStatus()
* xurls.Strict.FindAllString(...) -> xurls.Strict().FindAllString(...) ([see here](https://github.com/Seklfreak/discord-image-downloader-go/issues/45#issuecomment-347247349))

## Build
1. set $GOPATH to install dir
2. go get *repo*
3. cd to where the code was downloaded
4. go build && go install
