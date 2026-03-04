# Oppimispäiväkirja: Hajautettu git

__Mikä osion tehtävissä oli vaikeaa ja mikä helppoa? Mikä auttoi minua oppimaan? Miten selvitin esteet, jotka vaikuttivat tehtävän suorittamiseen?__

Kävi niin, että luin materiaalit yhtenä päivänä ja jätin harjoituksen toiselle päivälle. Toisaalta huono juttu, sillä olin unohtanut paljon. Toisaalta hyvä, että tuli kerrattua materiaalia.

## Osiossa käyttämäni Git-komennot

| Komento | Kuvaus |
| --------| ------ |

| git remote add origin (linkki) | Määrittää paikallisen repositorion etärepositoiroksi nimeltä origin, jonka osoite on annettu linkki |

| git remote -v | Listaa etärepositoriot |
| git push -u origin master | Puskee paikallisen repositorion master -haaran githubiin |
| git fetch | tuo haaran tiedot paikalliseen repositorioon, mutta ei yhdistä sitä |
| git checkout origin/master | Näyttää  etärepositorion master -haaran sisällön detached HEAD -tilassa |
| git checkout master| Palaa takaisin master -haaraan |
| git status | näyttää paikallisen repositorion nykytilan (onko esim. etärepositoriota jäljessä) |
| git merge origin/master| Yhdistää repositoriot vastaamaan toisiaan |
| git tag harjoitus5 | Lisää viimeisimpään talletukseen tunnisteen harjoitus5 |