# Dodge

Dodgessa tarkoituksena on ohjata pelaajaa tekoälyllä.
  - Pelin idea:
      a) pelaajan tulee säilyä elossa mahdollisimman pitkään
          - pelaaja menettää hp:tä osuessaan dangeriin
          - 2s kuolemattomuus osuman jälkeen
      b) saavuttaa maali mahdollisimman lyhyessä ajassa
      
Ohjelman rakenne
  - Pelaaja
    - kuutio
    - ohjattavissa ulkoisella AI:lla tai näppiksellä
  - Danger
    - kuutio
    - ohjelman oma AI ohjaa
  - Wall
    - kuutio
    - estää pelaajan kulkemisen läpi
    - levelin generointi taulukosta
