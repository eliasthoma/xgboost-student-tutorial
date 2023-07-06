# TODO
* Repository aufräumen
* set.seed() für Reproduzierbarkeit -> https://r-coder.com/set-seed-r/
* ecospat::boice ??
* Metrics::auc ??
* LogLoss gegen N_Samples plotten
* Package Versionen im Text nennen
* Grafiken auf Vollständigkeit prüfen
* Dateipfade als Grafik-Links
* Link zu StatQuest einfügen
* BioClim Layer aussagekräftig benennen
* Paramter Set aufräumen und besser darstellen
* TOC collapse deaktivieren
* Vergleich von GPU vs. CPU
* Shap values darstellen und beschreiben
* Dense/Sparse Matrix efficency erläutern
* Test Daten
* Caret oder Tidymodels als weiterführende Packete für Paramter Tuning
* fix time measurement code

# Einbinden des Submodules in das eigene Git-Repository

Eine git-bash im Ordner des Git-Repository öffnen und

```         
git submodule add https://github.com/et1902/xgboost-student-tutorial.git
```

ausführen. Änderungen im Submodule müssen separat commited und gepushed werden. Dazu muss das Submodule als eigenständiges Repository geöffnet und behandelt werden.

Änderung im Submodule werden nicht automatisch übernommen -\> Head Commit muss im Parent Repo geupdated werden.
