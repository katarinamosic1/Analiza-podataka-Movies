# Analiza-podataka-Movies

Seminarski rad iz predmeta Uvod u nauku o podacima realizovan u programskom jeziku R. Analizirala sam filmsku industriju koristeći podatke o filmovima proizvedenim od 1980. do 2020. godine, preuzete sa IMDb-a. Cilj analize je bio da se istraži stanje filmske industrije i da se predvidi zarada filmova.

Opis podataka

Dataset movies.csv sadrži informacije o filmovima, uključujući:
    **name**: kategorijska promenljiva koja označava naziv filma
    
    **rating**: kategorijska promenljiva koja označava kategoriju filma (R, PG,..) 
    
    **genre**: kategorijska promenljiva koja označava žanr filma
    
    **year**: numerička promenljiva koja označava godinu objavljivanja filma
    
    **released**: kategorijska promenljiva koja označava datum objavljivanja u formatu (YYYY-MM-DD)
    
    **score**: numerička promenljiva koja označava IMDb ocenu korisnika
    
    **votes**: numerička promenljiva koja označava broj ljudi koji su glasali
    
    **director**: kategorijska promenljiva koja označava direktora filma
    
    **writer**: kategorijska promenljiva koja označava pisca
    
    **star**: kategorijska promenljiva koja označava glumca/glumicu koji je zvezda filma
    
    **country**: kategorijska promenljiva koja označava zemlju porekla filma
    
    **budget**: numerička promenljiva koja označava budžet filma
    
    **gross**: numerička promenljiva koja oznacava prihod filma
    
    **company**: kategorijska promenljiva koja označava produkcijsku kuću
    
    **runtime**: numerička promenljiva koja označava trajanje filma

Cilj projekta: Glavni cilj je predviđanje kolone gross (zarada filmova) i da se otkrije da li filmska industrija propada.

Zaključak: Na osnovu analize grafika i prethodnih zaključaka, mogu da zajljučim da filmska industrija ne pokazuje znakove propadanja, naročito sa znatnim porastom budžeta i prihoda nakon 2010. godine. Podaci su prikupljeni do 2020. godinom pa nemamo uvid u najnovije trendove. Kada je reč o kreiranju modela i predviđanju kolone 'gross', najbolji model koji sam dobila koristi Random Forest pristup, koji objašnjava oko 74% varijanse u podacima.
