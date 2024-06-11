# Laborübung für Studienarbeit über Fuzz-Testing

Dieses Repository beihnaltet eine Laborübung für Studierende, die im Rahmen der Studienarbeit bei Herrn Prof. Dr.-Ing. Falko Michael Kötter an der DHBW Stuttgart für den B.Sc. Informatik verfasst wurde.  
Die Laborübung soll Studierenden Fuzzing nahebringen und ein Verständnis für die Technik vermitteln.

## Start-Anleitung

Repository klonen:

```plaintext
git clone https://github.com/evabecks/fuzztesting_studienarbeit_labor.git
```

In den _fuzztesting_studienarbeit_labor_ Ordner navigieren.  
Docker-Container starten:

```plaintext
docker compose up
```

Um das Notebook zu öffnen: [127.0.0.1/tree](http://127.0.0.1:8888/tree).  
Python Notebook öffnen und _Run All Cells_ wählen.

Um das Notebook zurückzusetzen muss der Docker-Container neu gestartet werden:

```plaintext
docker compose down
docker compose up
```
