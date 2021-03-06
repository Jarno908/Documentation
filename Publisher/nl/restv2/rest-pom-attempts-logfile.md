# REST API: Algemene Marketing Suite informatie

Elk bericht dat wordt verstuurd via Marketing Suite wordt opgeslagen in de 
cdm-attempts logfiles. Je kunt deze downloaden in CSV, JSON of XML formaat.
Instructies hiervoor kun je vinden onder "Meer informatie over logfiles", 
of je kunt ze via het dashboard downloaden. De logfiles bevatten de volgende 
informatie. 

| Data         | Omschrijving                                  |
| ------------ | --------------------------------------------- |
| id           | ID van het bericht                            |
| time         | Tijdstip van verzending                       |
| mailingid    | ID van de mailing                             |
| profileid    | ID van het profiel van de ontvanger           |
| subprofileid | ID van het subprofiel van de ontvanger        |
| databaseid   | ID van de database                            |
| collectionid | ID van de collectie                           |
| senderdomain | Domein van de verzender                       |
| templateid   | ID van de template                            |
| tags         | Tags van de email, gescheiden met puntkomma's |
| email        | Email van de ontvanger                        |

## Andere logfiles

** [Marketing suite algemeen log](./rest-cdm-attempts-logfile)
* [Marketing suite misbruik log](./rest-cdm-abuse-logfile)
* [Marketing suite click log](./rest-cdm-click-logfile)
* [Marketing suite ontvangst log](./rest-cdm-delivery-logfile)
* [Marketing suite error log](./rest-cdm-error-logfile)
* [Marketing suite impressies log](./rest-cdm-impression-logfile)
* [Marketing suite herzendingen log](./rest-cdm-retry-logfile)
* [Marketing suite uitschrijvingen log](./rest-cdm-unsubscribe-logfile)
* [Publisher misbruik log](./rest-pom-abuse-logfile)
* [Publisher clicks (nieuwe stijl) log](./rest-pom-clicks-logfile)
* [Publisher clicks (oude stijl) log](./rest-pom-clicks-logfile)
* [Publisher ontvangst log](./rest-pom-delivery-logfile)
* [Publisher error log](./rest-pom-error-logfile)
* [Publisher impressies log](./rest-pom-impression-logfile)
* [Publisher herzendingen log](./rest-pom-retry-logfile)
* [Publisher uitschrijvingen log](./rest-pom-unsubscribe-logfile)


## Meer informatie over log files

* [Overzicht van alle API calls](rest-api)
* [Vraag namen van logfiles op](rest-get-logfiles-names)
* [Een logfile downloaden in JSON formaat](./rest-get-logfiles-json.md)
* [Een logfile downloaden in CSV formaat](./rest-get-logfiles-csv.md)
* [Een logfile downloaden in XML formaat](./rest-get-logfiles-xml.md)
