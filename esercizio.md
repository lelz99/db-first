Modellizzare la struttura di una tabella per memorizzare tutti i dati riguardanti delle auto usate messe in vendita da un concessionario.


Colonne | Tipi | Attributi|
---|---|---|
Targa | char(7) | Primary_key unique | oppure
id | bigint | Primary_key auto increment  | 
Color | char(6) | not null
km_percorsi | medium int | not null
doppie_chiavi | bool/int | not null default('no')
marca | varchar(50) | not null 
modello | varchar(100) | not null 
anno | year | not null
immatricolazione | datetime | not null
alimentazione | char(1) | not null