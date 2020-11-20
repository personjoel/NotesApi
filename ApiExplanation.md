# Api Calls

|Route|Verb|Beskrivning|Returnerad data|
|---|---|---|---|
|/notes|get|alla anteckningar hämtas|"4":{"title":"hej", "content":"detta är en note", "id":4}, "5":{"title":"hej", "content":"detta är nästa note", "id":5}|
|/notes/id|get|specifik anteckning hämtas|{"title":"note 3", "content":"detta är endast 1 note", "id":3}|
|/notes/id|delete|specifik anteckning raderas|note: 2 deleted|
|/notes|post|anteckning skapas|new note added|
|/notes/id|put|specifik anteckning ändras|note: 1 changed. Skulle kunna visa ändringen|
