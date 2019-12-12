# Riker Docker Management Tool

Riker is a replacement for Wharf. Wharf has returned to his homeland is no longer relavent. Riker is his updated replacement. This is a better written Python version of the same tool.

## Commands Supported

While one can use docker or docker-compose the run the same commands, riker automates the some of the tasks putting routine tasks together and simplifying the commands.

| Command | Description |
|---------|-------------------------------------------------------------------------------------------|
| build | Builds a container refered to in the current directory by the .wharf or .riker files        |
| rebuild | ReBuilds a container ignoring the cache (forced rebuild )        |
| rm | Builds a container refered to in the current directory by the .wharf or .riker files        |
| new | Creates a new .wharf, Dockerfile, and docker-compose.yaml based on defaults |
| info | Reports the current repo and image tag        |
| logs | Displays the current docker log        |
| flogs | Displays the current docker log with the tail -f option (continuously displays the log)       |
| deploy |  Does a git fetch, docker pull, and docker run on the container |
| release | Does a git push, docker build, and docker push on the container |
| run | Instantiate the container and starts it (up -d) |
| start | Alias to run |
| ps | Does a docker ps on the container |
| stop | Stops the container |
| kill | Stops and removes the container |
| pull | Pulls the container set |
| push | Pushs the container set |
| readme | Runs docker-readme on the container |
| tag | Updates the tag in the .riker file and associated tags on the compose, etc files |
| bash | Runs bash inside the running container |











