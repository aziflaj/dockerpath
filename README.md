# Docker Path

My journey through [X-Team's Docker path](http://paths.x-team.com/docker)

## Novice

A simple container running a Hello World application in Sinatra. You can run the app by executing:

```bash
$ docker build -t dockerpath/novice .
$ docker run -d -p 3000:3000 dockerpath/novice
```

The application should be running on [http://localhost:3000/](http://localhost:3000/).
