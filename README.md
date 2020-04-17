# Tagesschau-API
Documentation for APH's Tagesschau API

## Endpoints
| Name     | Description                                                                    | URL            |
|----------|--------------------------------------------------------------------------------|----------------|
| news     | The latest 40 Articles published on the Tagesschau Website                     | /news          |
| article (removed) | Response with an Article depending on what Value you pass along with it (0-39)  | /news/article |

## Open Endpoints
Open endpoints require no Authentication.
* News : `GET /news`

**Example**
```json
[
  {
    "title": "Coronavirus-Einschränkungen: Sommerferien wohl eher daheim",
    "description": "Können wir den Sommerurlaub abhaken? Die Tourismus-Industrie leidet sehr unter dem Corona-Shutdown. Auch die Debatte, die Sommerferien zu verkürzen, ist nicht hilfreich. Wie das Virus unser Reiseverhalten verändern könnte. Von Angela Ulrich.",
    "url": "http://www.tagesschau.de/inland/sommerferien-corona-103.html",
    "pubDate": "Sat, 18 Apr 2020 01:37:44 +0200",
    "image": "http://www.tagesschau.de/multimedia/bilder/sommerurlaub-101~_v-mittel16x9.jpg"
  },
  {
    "title": "\"Alan Kurdi\": Flüchtlinge gehen auf Fähre in Quarantäne",
    "description": "Seit Wochen verweigern Italien und Malta dem deutschen Flüchtlingsschiff \"Alan Kurdi\" das Einlaufen. Heute wurden die Flüchtlinge an Bord einer italienischen Fähre genommen. Dort sollen sie in Corona-Quarantäne gehen. Von E. Trapp.",
    "url": "http://www.tagesschau.de/ausland/alan-kurdi-157.html",
    "pubDate": "Fri, 17 Apr 2020 20:38:24 +0200",
    "image": "http://www.tagesschau.de/multimedia/bilder/sendungsbild-586907~_v-mittel16x9.jpg"
  },
  {
    "title": "Anklage gegen Attentäter von Halle",
    "description": "Der Prozess gegen den Attentäter von Halle beginnt in einigen Wochen in Magdeburg. Der Generalbundesanwalt erhob Anklage gegen den 28-jährigen Rechtsextremisten. Er hatte die Tat aus Judenhass geplant.",
    "url": "http://www.tagesschau.de/inland/anklage-attentat-halle-101.html",
    "pubDate": "Fri, 17 Apr 2020 20:28:08 +0200",
    "image": "http://www.tagesschau.de/multimedia/bilder/anklage-halle-103~_v-mittel16x9.jpg"
  },
  {
    "title": "\"Corona-Anwältin\" Bahner: Eine Juristin gibt Rätsel auf",
    "description": "Die Anwältin Beate Bahner galt zunächst als eine Art Schutzheilige der Kritiker der Corona-Maßnahmen. Inzwischen irritiert sie Gegner wie Anhänger - und entwickelt sich zu einem tragischen Fall. Von Wulf Rohwedder.",
    "url": "http://www.tagesschau.de/faktenfinder/corona-beate-b-103.html",
    "pubDate": "Fri, 17 Apr 2020 20:09:22 +0200",
    "image": "http://www.tagesschau.de/corona-massnahmen-119~_v-mittel16x9.jpg"
  },
  {
    "title": "Corona-Soforthilfen: Auch in Sachsen Fake-Portal entdeckt",
    "description": "Kriminelle haben nun auch in Sachsen versucht, mit einem gefälschten Antragsportal an Corona-Soforthilfegelder zu kommen. Nach NDR-Informationen wurde die Fakeseite erneut in der Slowakei registriert. Von Peter Hornung.",
    "url": "http://www.tagesschau.de/investigativ/ndr/corona-hilfe-fakeseiten-101.html",
    "pubDate": "Fri, 17 Apr 2020 20:03:17 +0200",
    "image": "http://www.tagesschau.de/multimedia/bilder/computer-tastatur-107~_v-mittel16x9.jpg"
  },
  {
    "title": "1000 Seeleute auf \"Charles de Gaulle\" infiziert",
    "description": "Mehr als 1000 französische Marinesoldaten haben sich an Bord des Flugzeugträgers \"Charles de Gaulle\" mit dem Coronavirus infiziert. Die Quelle der Infektion ist unklar. Die Regierung untersucht den Fall.",
    "url": "http://www.tagesschau.de/ausland/corona-frankreich-flugzeugtraeger-101.html",
    "pubDate": "Fri, 17 Apr 2020 19:38:31 +0200",
    "image": "http://www.tagesschau.de/multimedia/bilder/corona-flugzeugtraeger-103~_v-mittel16x9.jpg"
  },
  {
    "title": "Corona-Liveblog: ++ Trump heizt Proteste gegen Schutzmaßnahmen an ++",
    "description": "\"Befreit Michigan\" - US-Präsident Trump hat Proteste gegen strenge Schutzmaßnahmen auf Twitter angeheizt. Die ersten US-Bundesstaaten wollen die Schutzmaßnahmen lockern. Laut RKI bleibt die Ansteckungsrate auf niedrigem Nivenau. Die Entwicklungen im Liveblog.",
    "url": "http://www.tagesschau.de/newsticker/liveblog-coronavirus-freitag-103.html",
    "pubDate": "Fri, 17 Apr 2020 23:32:55 +0200",
    "image": "http://www.tagesschau.de/multimedia/bilder/usa-trump-175~_v-mittel16x9.jpg"
  },
  {
    "title": "Kirche und Corona: Gottesdienste wieder ab Mai?",
    "description": "In der Corona-Krise sind Zusammenkünfte in Kirchen, Moscheen und Synagogen verboten. Nach Beratungen im Bundesinnenministerium haben Religionsvertreter jedoch die Hoffnung, dass sich das ändern könnte. Von Janina Lückoff.",
    "url": "http://www.tagesschau.de/inland/corona-kirche-101.html",
    "pubDate": "Fri, 17 Apr 2020 18:36:24 +0200",
    "image": "http://www.tagesschau.de/multimedia/bilder/kirche-corona-107~_v-mittel16x9.jpg"
  },
  {
    "title": "Pharmahersteller Gilead: Der hässliche Hoffnungsträger",
    "description": "Der US-Pharmakonzern Gilead testet derzeit das wohl aussichtsreichste Medikament gegen die Coronavirus-Erkrankung. Doch wie sauber hat das Unternehmen in der Vergangenheit gearbeitet? Von F. Barth, F. Farken und M. Grill.",
    "url": "http://www.tagesschau.de/investigativ/ndr-wdr/gilead-105.html",
    "pubDate": "Fri, 17 Apr 2020 18:00:52 +0200",
    "image": "http://www.tagesschau.de/multimedia/bilder/gilead-101~_v-mittel16x9.jpg"
  },
  {
    "title": "Corona: Altmaier will Wirtschaft nur langsam normalisieren",
    "description": "Wirtschaftsminister Altmaier hat Forderungen der Wirtschaft nach einer schnellen Normalisierung zurückgewiesen. Er versprach, konkrete Vorschläge vorzulegen. Branchenverbände warnen vor einer schweren Krise und Insolvenzen.",
    "url": "http://www.tagesschau.de/wirtschaft/altmaier-corona-wirtschaft-101.html",
    "pubDate": "Fri, 17 Apr 2020 17:40:33 +0200",
    "image": "http://www.tagesschau.de/multimedia/bilder/peter-altmaier-115~_v-mittel16x9.jpg"
  },
  {
    "title": "Dramatischer Appell - \"Wir brauchen Europa, um zu überleben\"",
    "description": "Aus dem Flüchtlingslager Moria auf der Insel Lesbos kommt ein dramatischer Appell der Bewohner. Europa müsse helfen, denn das Coronavirus sei wie ein Todesurteil für Alte und Kranke.",
    "url": "http://www.tagesschau.de/ausland/moria-fluechtlinge-hilferuf-101.html",
    "pubDate": "Fri, 17 Apr 2020 16:40:51 +0200",
    "image": "http://www.tagesschau.de/multimedia/bilder/moria-hilferuf-101~_v-mittel16x9.jpg"
  },
  {
    "title": "Eltern bekommen Entschädigung nach weiteren Schließungen",
    "description": "Gerade mit den ganz Kleinen ist an arbeiten Zuhause oft nicht zu denken. Durch die langen Kitaschließungen können viele Eltern in finanzielle Nöte geraten. Welche Ansprüche stehen ihnen zu? Von Iris Marx.",
    "url": "http://www.tagesschau.de/inland/kinderbetreuung-verdienstausfall-entschaedigung-101.html",
    "pubDate": "Fri, 17 Apr 2020 15:33:30 +0200",
    "image": "http://www.tagesschau.de/multimedia/bilder/schulausfall-homeschooling-105~_v-mittel16x9.jpg"
  },
  {
    "title": "Gottesdienstverbot soll schrittweise gelockert werden",
    "description": "Religiöse Zusammenkünfte sind näher gerückt: Die Religionsgemeinschaften sollen Konzepte vorlegen, wie in Kirchen, Synagogen und Moscheen sicher Gottesdienste gestaltet werden können. Derweil geht Sachsen einen Sonderweg.",
    "url": "http://www.tagesschau.de/inland/gottesdienst-corona-kirche-101.html",
    "pubDate": "Fri, 17 Apr 2020 15:32:14 +0200",
    "image": "http://www.tagesschau.de/multimedia/bilder/koeln-kirche-101~_v-mittel16x9.jpg"
  },
  {
    "title": "Opposition fordert mehr Parlamentsbeteiligung",
    "description": "Die Opposition will bei der Umsetzung von Corona-Maßnahmen nicht mehr nur Zuschauer sein. Mehrere Politiker forderten eine stärkere Beteiligung der Parlamente. Man wünsche sich mehr Transparenz und Information.",
    "url": "http://www.tagesschau.de/inland/corona-oppositionskritik-101.html",
    "pubDate": "Fri, 17 Apr 2020 15:20:44 +0200",
    "image": "http://www.tagesschau.de/multimedia/bilder/opposition-corona-101~_v-mittel16x9.jpg"
  },
  {
    "title": "Debatte über kürzere Sommerferien: \"Geboten\" oder \"unnötig\"?",
    "description": "Bundestagspräsident Schäubles Vorschlag, die Sommerferien zu verkürzen, schlägt hohe Wellen. Während einige Experten und Parteikollegen ihn unterstützen, lehnen Tourismusbranche und Lehrerverband den Vorstoß ab.",
    "url": "http://www.tagesschau.de/inland/sommerferien-corona-101.html",
    "pubDate": "Fri, 17 Apr 2020 15:09:20 +0200",
    "image": "http://www.tagesschau.de/multimedia/bilder/menschenleerer-strand-101~_v-mittel16x9.jpg"
  },
  {
    "title": "Atemwegs-Krankschreibung: Untersuchung beim Arzt wieder nötig",
    "description": "Die Krankschreibung per Telefon ist passé: Eine Ausnahmeregelung für Patienten mit leichten Atemwegsbeschwerden endet kommende Woche. Eine Untersuchung vom Arzt wird wieder erforderlich. Praxisärzte kritisieren dies.",
    "url": "http://www.tagesschau.de/inland/krankschreibung-arztbesuch-101.html",
    "pubDate": "Fri, 17 Apr 2020 15:06:01 +0200",
    "image": "http://www.tagesschau.de/multimedia/bilder/arztpraxis-111~_v-mittel16x9.jpg"
  },
  {
    "title": "Coronavirus: Das Problem mit der Sterblichkeitsrate",
    "description": "In Deutschland sind anscheinend bislang weniger Corona-Erkrankte gestorben als in anderen Ländern. Woran liegt das? Ist das Gesundheitssystem besser gewappnet - oder wird hier nur anders gezählt? Von Christian Baars.",
    "url": "http://www.tagesschau.de/faktenfinder/hintergrund/sterblichkeit-corona-101.html",
    "pubDate": "Fri, 17 Apr 2020 21:03:54 +0200",
    "image": "http://www.tagesschau.de/multimedia/bilder/coronavirus-zelle-101~_v-mittel16x9.jpg"
  },
  {
    "title": "Loveparade: Staatsanwaltschaft stimmt Prozess-Einstellung zu",
    "description": "Knapp zehn Jahre nach dem Loveparade-Unglück mit 21 Toten und mehr als 650 Verletzten stimmten die Staatsanwaltschaft Duisburg und die Angeklagten heute der Einstellung des Strafprozesses zu.",
    "url": "http://www.tagesschau.de/regional/nordrheinwestfalen/loveparade-prozess-139.html",
    "pubDate": "Fri, 17 Apr 2020 12:30:00 +0200",
    "image": "http://www.tagesschau.de/multimedia/bilder/loveparade-prozess-109~_v-mittel16x9.jpg"
  },
  {
    "title": "Wer über Identität täuscht, soll schwerer Pass erhalten",
    "description": "Ausländer, die bei der Einreise falsche Angaben zu Namen oder Herkunftsland gemacht haben, sollen künftig schwerer Deutsche werden können. Der Gesetzentwurf könnte auch Auswirkungen auf die Kinder der \"Identitätstäuscher\" haben.",
    "url": "http://www.tagesschau.de/inland/bundesinnenministerium-einbuergerung-101.html",
    "pubDate": "Fri, 17 Apr 2020 12:59:29 +0200",
    "image": "http://www.tagesschau.de/multimedia/bilder/einbuergerung-101~_v-mittel16x9.jpg"
  },
  {
    "title": "Galeria Karstadt Kaufhof klagt auf Öffnung der Filialen in NRW",
    "description": "Möbelhäuser dürfen in NRW ab nächster Woche öffnen, Kaufhäuser nicht: Aus Sicht von Galeria Karstadt Kaufhof ist das eine Ungleichbehandlung. Der Konzern hat daher Klage gegen die Corona-Sonderregel des Landes eingereicht.",
    "url": "http://www.tagesschau.de/wirtschaft/galeria-karstadt-kaufhof-101.html",
    "pubDate": "Fri, 17 Apr 2020 12:57:55 +0200",
    "image": "http://www.tagesschau.de/multimedia/bilder/galeria-kaufhof-105~_v-mittel16x9.jpg"
  },
  {
    "title": "World Press Photo: \"Symbol der Hoffnung\"",
    "description": "Ein junger sudanesischer Demonstrant rezitiert im Dunklen inbrünstig ein Gedicht - erhellt nur vom Handylicht der Umstehenden. Diese Aufnahme des japanischen Fotografen Yasuyoshi Chiba ist Welt-Pressefoto des Jahres.",
    "url": "http://www.tagesschau.de/ausland/world-press-photo-award-101.html",
    "pubDate": "Fri, 17 Apr 2020 11:28:03 +0200",
    "image": "http://www.tagesschau.de/multimedia/bilder/worldpressphoto-117~_v-mittel16x9.jpg"
  },
  {
    "title": "Fernsehjournalist Ulrich Kienzle ist tot",
    "description": "Legendär waren die Wortduelle mit Co-Moderator Hauser. Und auch als Ex-\"Frontal\"-Moderator und Nahost-Experte schrieb Kienzle Fernsehgeschichte, so ZDF-Chefredakteur Frey. Nun ist der Journalist mit 83 Jahren gestorben.",
    "url": "http://www.tagesschau.de/inland/ulrich-kienzle-101.html",
    "pubDate": "Fri, 17 Apr 2020 11:26:17 +0200",
    "image": "http://www.tagesschau.de/multimedia/bilder/kienzle-101~_v-mittel16x9.jpg"
  },
  {
    "title": "RKI-Chef Wieler: \"Bekämpfungsstrategie zeigt Erfolge\"",
    "description": "Die Corona-Einschränkungen in Deutschland sind massiv, wirken aber offenbar: Laut RKI-Chef Wieler ist die Reproduktionszahl weiter gesunken - auf 0,7. Er sprach von einem \"wirklich guten Zwischenergebnis\".",
    "url": "http://www.tagesschau.de/inland/wieler-spahn-pressekonferenz-101.html",
    "pubDate": "Fri, 17 Apr 2020 12:24:39 +0200",
    "image": "http://www.tagesschau.de/multimedia/bilder/wieler-131~_v-mittel16x9.jpg"
  },
  {
    "title": "Corona-Maßnahmen: Wie setzen die Bundesländer die Beschlüsse um?",
    "description": "Die Länderchefs haben mit der Kanzlerin zwar Eckpunkte für Regeln zur Eindämmung der Corona-Pandemie beschlossen. Doch bei der Umsetzung nutzt jedes Bundesland eigene Spielräume. Eine Übersicht von Iris Marx.",
    "url": "http://www.tagesschau.de/inland/bund-laender-beschluss-uebersicht-101.html",
    "pubDate": "Fri, 17 Apr 2020 11:12:59 +0200",
    "image": "http://www.tagesschau.de/multimedia/bilder/bundeslaender-101~_v-mittel16x9.jpg"
  },
  {
    "title": "Corona in Nicaragua: Kleinreden und aussitzen",
    "description": "Mehr als einen Monat war Präsident Ortega aus der Öffentlichkeit verschwunden. Zeit, um einen Plan gegen das Coronavirus zu entwickeln, meinten manche. Nun zeigt sich: Diese Hoffnung war vergeblich. Von Anne-Katrin Mellmann.",
    "url": "http://www.tagesschau.de/ausland/nicaragua-corona-103.html",
    "pubDate": "Fri, 17 Apr 2020 10:08:03 +0200",
    "image": "http://www.tagesschau.de/multimedia/bilder/nicaragua-ortega-103~_v-mittel16x9.jpg"
  },
  {
    "title": "Corona-Maßnahmen: Die Kirchen werden unruhig",
    "description": "Manche Geschäfte dürfen nächste Woche wieder öffnen, Gottesdienste sind aber weiter verboten. Aus Sicht der Kirchen muss darüber noch mal geredet werden. Heute treffen sich Vertreter der Religionen mit der Bundesregierung.",
    "url": "http://www.tagesschau.de/inland/coronakrise-kirchen-101.html",
    "pubDate": "Fri, 17 Apr 2020 12:51:04 +0200",
    "image": "http://www.tagesschau.de/multimedia/bilder/kirche-161~_v-mittel16x9.jpg"
  },
  {
    "title": "Corona-Pandemie in China: 50 Prozent mehr Tote in Wuhan",
    "description": "Die chinesische Stadt Wuhan hat die Zahl der Corona-Toten um 1290 Fälle nach oben korrigiert. Dafür nannten die Behörden eine Vielzahl von Gründen. Schon länger wurden die Angaben Pekings bezweifelt.",
    "url": "http://www.tagesschau.de/ausland/china-wuhan-109.html",
    "pubDate": "Fri, 17 Apr 2020 09:14:10 +0200",
    "image": "http://www.tagesschau.de/multimedia/bilder/china-coronavirus-147~_v-mittel16x9.jpg"
  },
  {
    "title": "Corona-Krise: Chinas Wirtschaft bricht deutlich ein",
    "description": "Im ersten Quartal 2020 ist das chinesische Bruttoinlandsprodukt um fast sieben Prozent geschrumpft. Durch das Coronavirus lag die Produktion teils brach. Das Land hofft darauf, wieder aufholen zu können. Von Axel Dorloff.",
    "url": "http://www.tagesschau.de/wirtschaft/china-wirtschaft-einbruch-101.html",
    "pubDate": "Fri, 17 Apr 2020 07:43:43 +0200",
    "image": "http://www.tagesschau.de/multimedia/bilder/china-industrie-fertigung-105~_v-mittel16x9.jpg"
  },
  {
    "title": "Ein Jahr Busunglück auf Madeira: Erinnerungen an eine Tragödie",
    "description": "Vor einem Jahr stürzte auf Madeira ein Bus mit deutschen Touristen eine Böschung hinunter. 29 Menschen starben. Die Staatsanwaltschaft macht den Busfahrer dafür verantwortlich. Oliver Neuroth hat mit Überlebenden gesprochen.",
    "url": "http://www.tagesschau.de/ausland/ein-jahr-nach-madeira-busunglueck-101.html",
    "pubDate": "Fri, 17 Apr 2020 07:09:25 +0200",
    "image": "http://www.tagesschau.de/multimedia/bilder/madeira-113~_v-mittel16x9.jpg"
  },
  {
    "title": "Folgen der Corona-Krise: Autoindustrie droht Absatzeinbruch",
    "description": "Langsam fahren die Autohersteller die Produktion wieder hoch. Doch wann die Konjunktur wieder in Gang kommt, ist unklar. Es droht ein massiver Absatzeinbruch. Zehntausende Jobs sind in Gefahr. Von Notker Blechner.",
    "url": "http://www.tagesschau.de/wirtschaft/boerse/autoindustrie-coronakrise-101.html",
    "pubDate": "Fri, 17 Apr 2020 06:45:00 +0200",
    "image": "http://www.tagesschau.de/multimedia/bilder/autoindustrie-105~_v-mittel16x9.jpg"
  },
  {
    "title": "Corona-Auflagen: Was Sie über Schutzmasken wissen müssen",
    "description": "Es gibt noch keine bundesweite Maskenpflicht, aber die \"dringende Empfehlung\", in bestimmten Bereichen \"Alltagsmasken\" zu tragen. Was bedeutet das? Wo sollen sie getragen werden? Wo bekommt man sie? Ein Überblick von Dominik Lauck.",
    "url": "http://www.tagesschau.de/faktenfinder/hintergrund/masken-faq-101.html",
    "pubDate": "Fri, 17 Apr 2020 15:20:10 +0200",
    "image": "http://www.tagesschau.de/multimedia/bilder/corona-maske-103~_v-mittel16x9.jpg"
  },
  {
    "title": "Corona in Ägypten: \"Wir überlassen das dem lieben Gott\"",
    "description": "Offiziell gibt es in Ägypten weniger als 3000 Covid-19-Infizierte. Weniger als 200 Menschen sind den Angaben zufolge gestorben. Wer etwas anderes behauptet, wird bestraft. Im Alltag ergeben sich die Ägypter in ihr Schicksal. Von Anne Allmeling.",
    "url": "http://www.tagesschau.de/ausland/corona-aegypten-101.html",
    "pubDate": "Fri, 17 Apr 2020 05:04:58 +0200",
    "image": "http://www.tagesschau.de/multimedia/bilder/corona-aegypten-103~_v-mittel16x9.jpg"
  },
  {
    "title": "Trockenheit: Droht ein neuer Dürresommer?",
    "description": "Zwei Sommer hintereinander haben Landwirte mit extremer Trockenheit und Rekordtemperaturen gekämpft. Wie sieht es in diesem Jahr aus? Steht erneut eine Dürreperiode bevor? Von O. Lambrecht und J. Lange.",
    "url": "http://www.tagesschau.de/faktenfinder/inland/duerresommer-101.html",
    "pubDate": "Fri, 17 Apr 2020 05:01:53 +0200",
    "image": "http://www.tagesschau.de/multimedia/bilder/duerre-deutschland-101~_v-mittel16x9.jpg"
  },
  {
    "title": "Landgericht sieht unzulässige Abschalteinrichtung bei BMW",
    "description": "Das Düsseldorfer Landgericht hat als erstes Gericht BMW zur Rücknahme eines Diesel-PKW verurteilt. Die Begründung: Der Autobauer habe eine unzulässige Abschalteinrichtung eingesetzt. Von A. Meyer-Fünffinger und J. Steule.",
    "url": "http://www.tagesschau.de/investigativ/br-recherche/bmw-diesel-101.html",
    "pubDate": "Fri, 17 Apr 2020 10:53:17 +0200",
    "image": "http://www.tagesschau.de/bmw-x1-101~_v-mittel16x9.jpg"
  },
  {
    "title": "Kommentar: Trumps \"Big Bang\" bleibt aus. Gut so!",
    "description": "Trotz Trumps Bombast - am Ende haben sich bei den Plänen des US-Präsidenten zur \"Wiederbelebung\" Amerikas die Gesundheitsexperten und Gouverneure durchgesetzt. Zum Glück, meint Katrin Brand.",
    "url": "http://www.tagesschau.de/kommentar/trump-lockerungen-coronavirus-101.html",
    "pubDate": "Fri, 17 Apr 2020 04:33:22 +0200",
    "image": "http://www.tagesschau.de/multimedia/bilder/usa-trump-177~_v-mittel16x9.jpg"
  },
  {
    "title": "Bolsonaro entlässt Gesundheitsminister nach Corona-Streit",
    "description": "Der brasilianische Präsident hat das Coronavirus mehrfach als \"kleine Grippe\" abgetan, während sein Gesundheitsminister Mandetta sich für strikte Ausgangsbeschränkungen stark machte. Jetzt muss der Minister gehen.",
    "url": "http://www.tagesschau.de/ausland/bolsonaro-gesundheitsminister-coronavirus-101.html",
    "pubDate": "Fri, 17 Apr 2020 03:13:25 +0200",
    "image": "http://www.tagesschau.de/multimedia/bilder/bolsonaro-gesundheitsminister-brasilien-101~_v-mittel16x9.jpg"
  },
  {
    "title": "Trump will USA in drei Phasen wieder öffnen",
    "description": "US-Präsident Trump hat einen Fahrplan vorgestellt, wie die Bundesstaaten ab morgen mit Lockerungen der Corona-Beschränkungen beginnen können. Dies solle in drei Phasen geschehen - die Entscheidung läge bei den Gouverneuren.",
    "url": "http://www.tagesschau.de/ausland/trump-richtlinien-corona-lockerungen-101.html",
    "pubDate": "Fri, 17 Apr 2020 02:14:45 +0200",
    "image": "http://www.tagesschau.de/multimedia/bilder/trump-coronavirus-115~_v-mittel16x9.jpg"
  },
  {
    "title": "DeutschlandTrend: Union erreicht höchsten Wert seit August 2017",
    "description": "Auf 38 Prozent würde die Union laut DeutschlandTrend derzeit kommen - der höchste Wert seit August 2017. Die AfD wäre erstmals seit fast drei Jahren einstellig. Zwei Drittel fühlen sich durch die Corona-Regeln nur wenig belastet.",
    "url": "http://www.tagesschau.de/inland/deutschlandtrend-2183.html",
    "pubDate": "Thu, 16 Apr 2020 23:55:43 +0200",
    "image": "http://www.tagesschau.de/multimedia/bilder/deutschlandtrend-149~_v-mittel16x9.jpg"
  },
  {
    "title": "\"Rambo\"-Star Dennehy ist tot",
    "description": "Golden-Globe-Gewinner Brian Dennehy ist im Alter von 81 Jahren gestorben. Er wurde als der Gegenspieler von Sylvester Stallone in \"Rambo\" bekannt und übernahm zahlreiche Rollen in US-Fernsehserien.",
    "url": "http://www.tagesschau.de/ausland/dennehy-101.html",
    "pubDate": "Thu, 16 Apr 2020 21:40:53 +0200",
    "image": "http://www.tagesschau.de/ausland/dennehy-105~_v-mittel16x9.jpg"
  },
  {
    "title": "UN-Generalsekretär: Hunderttausende Kinder in Gefahr",
    "description": "Hunderttausende Kinder sind wegen der Folgen der Corona-Pandemie weltweit in akuter Gefahr. Laut UN-Generalsekretär Guterres könnten sie in ihren Familien nicht mehr richtig versorgt werden.",
    "url": "http://www.tagesschau.de/ausland/kindersterblichkeit-corona-101.html",
    "pubDate": "Thu, 16 Apr 2020 20:56:32 +0200",
    "image": "http://www.tagesschau.de/multimedia/bilder/kinder-corona-103~_v-mittel16x9.jpg"
  }
]
```
