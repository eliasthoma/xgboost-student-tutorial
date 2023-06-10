# Einbinden des Submodules in das eigene Git-Repository

Eine git-bash im Ordner des Git-Repository öffnen und

```         
git submodule add https://github.com/et1902/xgboost-student-tutorial.git
```

ausführen. Änderungen im Submodule müssen separat commited und gepushed werden. Dazu muss das Submodule als eigenständiges Repository geöffnet und behandelt werden.

Änderung im Submodule werden nicht automatisch übernommen -\> Head Commit muss im Parent Repo geupdated werden.
