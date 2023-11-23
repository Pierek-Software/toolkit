# Essential

`code ~/.zshrc` - open zshrc using [Visual Studio Code]("https://code.visualstudio.com/")

# Docker

## Destructive remove all, fresh state

`docker stop $(docker ps -qa); docker rm $(docker ps -qa); docker rmi -f $(docker images -qa); docker volume rm $(docker volume ls -q); docker network rm $(docker network ls -q)`

Bash alias version (docker clean):

`alias docker\ clean='docker stop $(docker ps -qa); docker rm $(docker ps -qa); docker rmi -f $(docker images -qa); docker volume rm $(docker volume ls -q); docker network rm $(docker network ls -q)'`
