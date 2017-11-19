# Summary
Based of Alpine 3.6 with a minimal install of just the bind-tools package, will perform and output the results of a dig on the given domain name.

# Usage
`docker run danstreeter/dig {dig parameters} domainname.com`

_dig parameters_ are whatever you can run within the standard 'dig' command

![danstreeter/whois example](http://www.danstreeter.co.uk/g/docker-dig-example.gif)

# Alias Helper
You can also install an alias in your profile or alias file to reduce your command to just `dig` as follows:
```
alias dig="docker run --rm -it danstreeter/dig"
```
_Note: You may need to prepend the docker command in the alias above with `winpty` for usage on some windows based terminals (Git-Bash for example)_

# Docker Hub
https://hub.docker.com/r/danstreeter/dig/
