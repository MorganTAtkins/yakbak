# yakbak

## Running YakBak

```
docker run -p 7000:7000 --rm -ti -v "$PWD/tapes:/tapes" morgantatkins/yakbak https://www.google.co.uk
```
## What it's doing

1. Exposing local port 7000 to the container port 7000
1. Mounts the container dir "tapes" to the host working directory
1. Adding "https://www.google.co.uk" as the endpoint the calls get forwarded to

