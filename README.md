# Gatling

## Maven Archetype
mvn archetype:generate -DarchetypeGroupId=io.gatling.highcharts -DarchetypeArtifactId=gatling-highcharts-maven-archetype

## Sample Site code to test
Gatling fundamentals: https://github.com/james-willett/gatling3-fundamentals
Git: https://github.com/james-willett/VideoGameDB.git
URL: http://localhost:8080/swagger-ui/index.html#/Video_Games
GET: http://localhost:8080/app/videogames


## Sample Script
Run it from the Engine class.
Screenshot 2021-06-02 at 9.12.13 AM<img width="694" alt="Screenshot 2021-06-02 at 9 12 13 AM" src="https://user-images.githubusercontent.com/33754197/120422994-272a0a80-c387-11eb-9fed-b8dbb2bbcb1e.png">

## Gatling maven command
mvn gatling:test -Dgatling.simulationClass=AnalyzerLoginSimulation
