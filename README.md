# Planetiler Transitopia Profile

This Transitopia profile for [Planetiler](https://github.com/onthegomap/planetiler) generates
the following map layers:
  * [Transitopia Cycling Map](https://www.transitopia.org/cycling)

## How to use

You need to have a recent version of Java installed on your system.

Run this command to build the profile and generate the map:

```
./mvnw clean package && java -jar target/planetiler-*-with-deps.jar --force --download
```
