# Ionic app to demonstrate automated tests #

<br>

Dieses Repository enthält eine Ionic-App, die Angular und Capacitor verwendet. 
Der Zweck der App besteht darin, zu demonstrieren, wie automatische Tests für Ionic-Apps geschrieben werden können.

Die App ermöglicht die Abfrage von IATA-Codes (International Air Transport Association), insbesondere 
[Flughafen-Codes](https://en.wikipedia.org/wiki/IATA_airport_code) und [Fluglinien-Codes](https://en.wikipedia.org/wiki/Airline_codes). 
Allerdings sind nur wenige Flughäfen und Fluggesellschaften tatsächlich in der App "gespeichert" (d.h. fest im Code hinterlegt), 
siehe [Klasse IatadbService](src/app/iatadb.service.ts).

<br>

Der Autor dieser App steht in keinerlei Verbindung zur IATA.

<br>

----

## Screenshot ##

<br>

![Screenshot 1](screenshot_1.png) &nbsp; ![Screenshot 2](screenshot_2.png)

![Screenshot 3](screenshot_3.png) &nbsp; ![Screenshot 4](screenshot_4.png)

<br>

----

## Running the tests ##

<br>

Enter the following command to run the tests with the [Karma testrunner](http://karma-runner.github.io/latest/index.html):

```
npm test
```

The unit tests are defined in the files with suffix `.spec.ts` under folder [src/app/](src/app/) .

<br>

----

## License ##

<br>

See the [LICENSE file](LICENSE.md) for license rights and limitations (BSD 3-Clause License) for the files in this repository.

<br>
