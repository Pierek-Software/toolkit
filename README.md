# Essential

`code ~/.zshrc` - open zshrc using [Visual Studio Code]("https://code.visualstudio.com/")

# Terminal

`alias ls='ls -a'`

# Chrome Extensions

_uBlock_ - block ads
_SponsorBlock_ - skip YouTube non interested part of video, skip
sponsors, intro, outro
_JSON Formatter_ - nice looking JSON
_Bookmarks clean up_ - remove bookmarks duplication</li>
_SEO META in 1 CLICK_ - All SEO information in one extension</li>
_Poper Blocker_ - block pop ups, cookie consent</li>

# Docker

## Destructive remove all, fresh state

`docker stop $(docker ps -qa); docker rm $(docker ps -qa); docker rmi -f $(docker images -qa); docker volume rm $(docker volume ls -q); docker network rm $(docker network ls -q)`

Bash alias version (docker clean):

`alias docker\ clean='docker stop $(docker ps -qa); docker rm $(docker ps -qa); docker rmi -f $(docker images -qa); docker volume rm $(docker volume ls -q); docker network rm $(docker network ls -q)'`
