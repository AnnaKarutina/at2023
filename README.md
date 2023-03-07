# Aastategija võistlus 2023 - Veebirakenduse arendaja kutsevõistlus

## Asukoht ja aeg
Võistlus toimub 07.03.2023 08:30-15:40 ja 08.03 08:30-14:00 klassis A411. 

## Probleem

Tarkvaraarendajate õpilaste vastuvõtu katsetesüsteem muutus kasutuskõlblikuks. Tuleb säilitada olemasoleva lahenduse funktsionaalsus, parandades/täiendades olemasolev lahendus või kirjutase selle ümber arvestades ettedefineeritud nõuetega.

## Eeltöö

Alustamiseks sul läheb vaja tutvuda olemasoleva lahendusega, mille leiad [siin](https://github.com/AnnaKarutina/at_eeltoo). Kuna antud lahendus baseerub andmebaasi kasutamisel, sul oleks hea võta kasutusele näidisandmebaasi struktuur koos andmetega, millega sa saad kohe katsetada süsteemi tööd - selle sa leiad [siin](https://raw.githubusercontent.com/AnnaKarutina/at2023/master/db.mysql).

```config.php``` fail ei ole commitimisele lisatav - vaata täpsemalt ```.gitignore``` faili - sisuks oleks vaja panna, kui kasutad minu poolt jagatud andmebaasi dump faili:
```
<?php

// Load default values
require 'system/config.default.php';

// Load local customizations
$cfg['DATABASE_HOSTNAME'] = 'localhost';
$cfg['DATABASE_USERNAME'] = 'root';
$cfg['DATABASE_PASSWORD'] = 'qwerty';
$cfg['DATABASE_DATABASE'] = 'm7iktkhk_aastategija';
```

Tutvu nii projektiga kui ka andmebaasiga ja pane projekt käima ning katseta selle tööd. Administreerimise osa jaoks oleks vaja kasutada kasutaja nimi ja parool - ```admin``` ja ```Murakas112```.

Kujunduse planeerimisel arvesta kooli CVI-ga - brändi raamatuga saab tutvuda [siin](https://drive.google.com/file/d/1TIZNzCwhzIpC3B0OkwNv7VzX0UyO5MPq/view?usp=sharing)

## Projekti dokumentatsiooni nõuded
* Projekti backlogi koostamisel arvesta [nõuetega kasutajalugudele](https://docs.google.com/document/d/1hz_VQ-vfcvWQNvyPyGfJq2QFyqreUQnVhIf0vF8sk4A/edit)
* Koodi jaoks oleks vaja luua meeskonnale ühine GitHub repositoorium ning kindlasti tekitada sinna ```README.md``` fail, kus on kirjas rühma liikmete nimed. Lisaks tuleb panna rühma liikmete juurde kirja nende rollid/ülesanded. Projekti teostamise käigus kindlasti täiendada see osa tarkvaraliste nõuetega ja paigaldamisjuhistega ning muu vajaliku infoga, mis on antud projektiga seotud.
* Eeltöö raames on võimalik tutvuda nii vana visuaaliga kui ka VOCO visuaalse identiteedi materjalidega - sujuva töö teostamiseks oleks hea luua disaini vaade, millega arvestada lahenduse loomisega.

## Väärtuspakkumise täitmiseks tabel
(siin)[https://docs.google.com/document/d/1ZkjphpJMZzW9ZKgpZO-45dE5AvXHproH/edit?usp=share_link&ouid=113634194955509868513&rtpof=true&sd=true]
