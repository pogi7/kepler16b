# Kepler 16b

This is an example Oml project for a hypothetical mission called Kepler 16b.

## Clone

Clone this repo to your machine
   ```
     git clone https://gitlab.com/melaasar/kepler16b.git
   ```
## Build
   
Build the repo by invoking the gradle build script
   ```
   cd kepler16b
   ./gradlew build
   ```
   >NOTE: If you are on Windows, replace ./gradlew with gradlew.bat (also in the instructions below)

## Analyze

Start Fuseki Server
   ```
   ./gradlew startFuseki
   ```
   
Run the provided sparql queries
   ```
   ./gradlew owlQuery
   ```
   
Stop Fuseki Server
   ```
   ./gradlew stopFuseki
   ```

Generate the website with reports
   ```
   ./gradlew generateWebsite
   ```

