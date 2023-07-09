# Hosting

For serving this as a webpage you need to copy

* xgboost.html
* style.css
* images/

onto your webserver. Maybe you need to rename xgboost.html to index.html which should be no problem.

# TODO
* Package Versionen im Text nennen
* Link zu StatQuest einfügen
* Paramter Set aufräumen und besser  - Paramter set in jetztiger Form bleibt nicht bestehen.
* Vergleich von GPU vs. CPU - Nur im Text erwähnen nicht genauer analysieren
* Test Daten - zu aufwendig zu implementieren, als TODO für zukünftige Gruppe schreiben
* Caret oder Tidymodels als weiterführende Packete für Paramter Tuning
* Explain logloss - Logloss wurde durch AUC ersetzt

# Einbinden des Submodules in das eigene Git-Repository

Eine git-bash im Ordner des Git-Repository öffnen und

```         
git submodule add https://github.com/et1902/xgboost-student-tutorial.git
```

ausführen. Änderungen im Submodule müssen separat commited und gepushed werden. Dazu muss das Submodule als eigenständiges Repository geöffnet und behandelt werden.

Änderung im Submodule werden nicht automatisch übernommen -\> Head Commit muss im Parent Repo geupdated werden.
