# Los Balkan Anticheat Launcher Bypass

### Trenutna podržana verzija: Los Balkan Launcher 1.2

```
 __   ________ _____   _      ______      ________  _____   _      ____  
 \ \ / /  ____/ ____| | |    / __ \ \    / /  ____|/ ____| | |    |  _ \ 
  \ V /| |__ | |  __  | |   | |  | \ \  / /| |__  | (___   | |    | |_) |
   > < |  __|| | |_ | | |   | |  | |\ \/ / |  __|  \___ \  | |    |  _ < 
  / . \| |___| |__| | | |___| |__| | \  /  | |____ ____) | | |____| |_) |
 /_/ \_\______\_____| |______\____/   \/   |______|_____/  |______|____/ 
                                                                         
```                                                                         
                                                                         
### Kreirao Xegzg - http://github.com/xegzg
### Antivirus scan: https://www.virustotal.com/#/file/35670e244d0c1a7b395e21d488987ba7ceaee5fd9f045ab117c581fcca466be1/detection
                          
### Opcenite informacije:
Ovaj anticheat bypass ili ti ga (crack ako je nekom lakse shvatit) ce biti updatean sa svakom novom verzijom LB Anticheat-a.
Kada pokrenete Anticheat Bypass pise koju trenutno verziju LB AC-a podržava.
Svaki update mozete pronaci na gore navedenom github linku.


### Upute:

* 1.) Dodajte 'datum_kreiranja.lbac' i 'datum_modificiranja.lbac' u vas GTA folder
* 2.) Otvorite oba filea koja ste ubacili pomocu notepada te promjenite datum iz razloga sto bi u protivnom svi korisnici Bypassa imali isti datum.
    - Datum modificiranja moze biti isti ili veci od kreiranja (nemojte stavit manji, koristite mozak..)
    Pri editu datuma zamjenite samo brojke nemojte dirat '.' i ':' da nebi rezultiralo drugacijim sintaksama od LB clienta trenutno je sve namjesteno kao i tamo.
    Koristite brojeve bez 0 ispred npr. pisite 1 umjesto 01..
* 3.) Spojite se na SAMP server (LB) i automatski ste spojeni u sistemu kao da ste kliknuli 'Aktiviraj' na original clientu.
    Kada izadete iz SA:MPa mozete ostaviti Bypass upaljen te dok god je on upaljen u SA:MP mozete ulazit sigurno bez da ga ponovo palite.
* 4.) Upalite LB Anticheat Bypass (LBACxeg.exe) te se zabavite ;)!

### Kako ovo radi?!
Koristi isti princip spajanja na LB server kao i ogirinalan anticheat, i pruza iste funckije kao i pravi anticheat samo što blokiramo neželjene fileove od pojavlivanja adminima
koji koriste komande za provjeru. (/getfiles, /procinfo, /dirinfo - Vjerojatno ce ih profi skripter Conti kasnije zamjenit no to nije ni bitno?!)
Bitno je da ste sigurni.

Original LB anticheat radi na sistemu kad ga upalite i udete u igru, odete stisnete "Aktiviraj" te saljete doznanja serveru da koristite Anticheat.
Kada ste nekom adminu sumnjivi on na vama iskoristi jednu od gore navedenih komandi da provjeri vaš folder, procese i datum kreiranja/modificiranja foldera.
Te mu izbaci popis svih fileova koji se nalaze u vasem GTA folderu, ukoliko imate CLEO izbacit ce mu CLEO folder i zna da imate cheat. 
Tu dolazi u korist ovaj Bypass koji blokira prikaz svih fileova vezanih uz mod s0beit i CLEO 4 te ce adminu izgledati kao da imate fresh installan GTA folder koji nikad cheatove nije vidio :)
