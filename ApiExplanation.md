# 1

### Api Calls

|Route|Verb|Beskrivning|Returnerad data|
|---|---|---|---|
|/notes|get|alla anteckningar hämtas|"4":{"title":"hej", "content":"detta är en note", "id":4}, "5":{"title":"hej", "content":"detta är nästa note", "id":5}|
|/notes/id|get|specifik anteckning hämtas|{"title":"note 3", "content":"detta är endast 1 note", "id":3}|
|/notes/id|delete|specifik anteckning raderas|note: 2 deleted|
|/notes|post|anteckning skapas|new note added|
|/notes/id|put|specifik anteckning ändras|note: 1 changed. Skulle kunna visa ändringen|

### Data object definition

|Data object|Definition|
|---|---|
|res|data som webbläsaren skickar tillbaka|
|req|förfrågan som användaren skickar till webbläsaren|
|err|errormeddelanden som skickas med när filen läses in|
|data|data som skickas från en specifik fil|

### Namngivning

Jag tycker de flesta namn är tydliga\
dataPath, otydlig eftersom den inte beskriver vilken data som hämtas med filvägen

# 2
