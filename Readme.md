Run in dev mode
-----------
Download project and extract or clone.

> cd /path/to/project

> sbt "run 9000"

Open the http://localhost:9000 on browser

Run in production mode
-------------------

> sbt dist

> unzip  target/universal/scala-play-seed-1.0-SNAPSHOT.zip

> target/universal/scala-play-seed-1.0-SNAPSHOT/bin/scala-play-seed -Dhttp.port=9000

Open the http://localhost:9000 on browser