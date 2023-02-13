# 280 Zeichen Relevanz: Wie Twitter zur Plattform für Ideen - und Egos - wurde

Twitter besteht aus seinen prominenten Nutzern. Ein Porträt der Plattform anhand vier Power-NutzerInnen aus Journalismus, Unterhaltung, Wissenschaft und Politik.


## 0 Checkliste

- **These formulieren:** Persönliche Twitter-Daten von Power-NutzerInnen illustrieren deren Twitterhistorie. Man kann unterschieden, wie erratisch doer strategisch jemand Twitter nutzt, und wie persönliche oder gesellschaftliche Ereignisse die Nutzung beinflussen. 
- **These checken: Relevanz? Neu? Aufwand/Ertrag?** Wegen anhaltender Debatten um Twitter relevant. Neu. Aufwand akzeptabel, 4-5 AT
- **Knackpunkt bestimmen:** Bekomme ich die Daten? Welche Darstellungen/Analysen sind ein Mehrwert 
- **Briefing Person konsultieren** Mit Stephanie Lahrtz und Gioia da Silva überlegt, welche Personen interessant wären. Mit Joana Kelén überlegt, welche Insights interessieren könnten: Dinge wie Corona - wann am Tag jemand etwas macht. Häufige Themen. Wie die Geburt eines Kindes die Nutzung verändert.
- **Daten beschaffen/reinigen/analysieren/visualisieren**
- **Ergänzen durch klassische Recherche** Interviews mit allen Beteiligten
- **Dokumentieren Code und statistische Annahmen**
- **Link auf Publikation**
- **Aufwandslogbuch**



## 1 Daten-Quelle

Nach Gesprächen die persönlichen Twitter-Archiv-Datensätze von Patrizia Laeri, Patrick Karpiczenko, Emma Hardcroft, und Andri Silberschmidt bekommen - ohne die privaten Teile wie Nachrichten, gelöschte Tweets, etc. Die Ordner sind lokal gespeichert und json Files. 

Eine weitere Datenquelle, nötig für Follwers/Following, ist die Twitter-API.

## 2 Analyse

Eine deskriptive Analyse der Twitter-Aktivitäten. 


- Wie aktiv sind diese Power-Nutzer über die Jahre? Tweeten sie mehr selbst, oder retweeten sie? Wofür haben sie am meisten Likes und Retweets bekommen?
- An welchen Wochentagen und zu welcher Uhrzeit sind die Accounts aktiv? Wie veränderte sich das über die Jahre durch Ereignisse wie: Pandemiebeginn, Geburt eines Kindes, andere, persönliche Ergeignisse?
- Welche Wörter und Hashtags erwähnt der Account besonders oft? Was lässt sich über die Themen schliessen?
  Wie haben sich die Top-Wörter über die Jahre verändert?
- Welche User erwähnt der Account besonders oft? 
  &rarr; Werden immer diesselben Personen erwähnt, oder viele verschiedene?

[Link zum Notebook](https://github.com/ruthf9/DDJ_project_twitter_analysis/blob/main/Twitter_Archiv_Analyse.ipynb).

- Wer folgt diesem Account - und wem folgt er?
  &rarr; *Ausbaumöglicheit: Auswertung nach Geschlecht*
  
[Link zum Notebook](https://github.com/ruthf9/DDJ_project_twitter_analysis/blob/main/Twitter_API_for_Github.ipynb) - zum Ausführen ist ein Access Token notwendig



## 3 Vorgehen bisher
- Vier interessante Personen identifiziert, per Mail oder Telefon Kontakt aufgenommen, Projekt erklärt, Daten erhalten
- Mit Patrizia Laeri bereits das Interview geführt. Mit Emma Hodcroft hat meine Kollegin S. Lahrtz bereits das Interview geführt
- Die anderen beiden Interviews, sowie Rückfragen nach der Analyse sind ausständig

- Twitter-Archiv-Analyse: Guten Beispielcode gefunden, daran selbstständig weitergearbeitet, um die wichtigsten Daten zu sammeln über die Tweetaktivität
- Erstes Gespräch mit Briefing-Person Joana Kelén, die für den Artikel die Visualisierungen machen wird: Herausgearbeitet, dass nicht alle Details bei allen Accounts spannend sind, sondern jeweils spannende Aspekte gezeigt werden sollen. Einige Hypothesen nach dem Gespräch: 
  -  Wie Patrizia Laeri strategisch Hashtags nutzt für Frauen-Anliegen.
  -  Wie der Komiker Karpi anders twittert, seit er Vater wurde - ob sich seine Sucht belegen lässt
  -  Welche Dynamik die Twitter-Aktivitäten von der Virologin Hodcroft während Corona hatten
  -  Wie bei Silberschmidt die Karriere als Politiker die Themen verändert hat und der Account professioneller und erwachsener wurde
Manches könnte man auch vergleichen, etwa: Wie viel twittern diese Leute? Wie viel twittern sie ausserhalb der Arbeitszeit? Verbreiten diese Accounts vor allem Eigenwerbung (taggen sich selbst) - oder verbreiten sie auch fremden Content?

- Viele Varianten von Plots erstellt für einen besseren Eindruck zu diesen Themen
- parallel: inhaltliche Auswertung von Tweets begonnen - Wörter, Hashtags und Mentions sammeln
- Einarbeiten in Twitter-API, weil mich das generell interessiert, für später. Und für eine systematischere Darstellung von Followers/Following. Begonnen mit: Folgen sich diese 4 Personen gegenseitig? 

- zweites Gespräch mit Briefing-Person, was wäre noch interessant:
  -  Bei den Top Hashtags und Mentions ist noch Recherche nötig, zum inhaltliche Dinge aufzeichen
  -  Bei Silberschmidt zeitlich schauen, wann Wahlkampf
  -  Zusammenhang Lockdown-Twitter



*Was noch fehlt*:
- letzte Analysen
- zwei Interviews, Rückfragen bei den bereits Interviewten
- Inputs geben für Illustrationen/Infografiken
- Text fertig schreiben


## 4 Aufwands Logbuch

Recherche:
- Daten akquirieren, Interviews führen: 0,5 Tage 
- *Schätzung weiterer Aufwand 1,5 Tage*

Coding:
- Twitter-Archiv verstehen, Daten extrahieren: 0,5 Tage
- Code schreiben für Analysen und Plots der Twitter-Daten 2 Tage
- Twitter-API machen und einarbeiten: 1 Tag
- Twitter-API-Analyse 0,5 Tage
- *Schätzung weiterer Aufwand: 0,5 Tage*

In Summe etwa 4,5 Tage bereits daran gearbeitet, datenjournalistisch fehlt wenig, weitere Recherche und Schreiben fehlen noch



