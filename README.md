A template form-ban felvett új könyv címe kerüljön be az app.component books tömbjébe egy Output
emitter segítségével

Készítsetek új űrlapot, amely egy felhasználó felvételét intézi az alábbi értékekkel:
- usernév
- emailcím
- jelszó
- születési dátum
(ügyeljetek rá, hogy ezek mindegyikének van saját input mező formátuma)
(hozzatok is létre egy User interfészt vagy osztályt)
- a user objektumok egy Outputon keresztül jussanak vissza a szülő osztályhoz, mely írassa ki őket a
console-ra és tárolja el őket egy tömbben