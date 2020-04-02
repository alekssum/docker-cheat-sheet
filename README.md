# Docker cheat sheet

## Commands

```
docker rm  $(docker ps -a --filter 'exited=1' --format "{{.ID}}")
```


```
docker image rm $(docker images --filter "dangling=true" --format "{{.ID}}")
```
