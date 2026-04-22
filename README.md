# 🏪 Mapa Comercial de Catalunya

Mapa interactiu dels establiments comercials dels 947 municipis de Catalunya, amb indicadors com l'Índex d'Atracció Comercial (IAC) i l'Índex de Dotació Comercial (IDC).

## 🔗 [Veure el mapa en viu](https://EL-TEU-USUARI.github.io/mapa-comerc-catalunya/)

## Indicadors disponibles

| Indicador | Descripció |
|-----------|------------|
| **Establiments** | Nombre total d'establiments comercials |
| **Densitat / 1000h** | Establiments per cada 1.000 habitants |
| **Diversitat** | Índex Shannon normalitzat de diversitat comercial |
| **Superfície** | Metres quadrats comercials totals |
| **IAC** | Índex d'Atracció Comercial — pes del comerç no quotidià |
| **IDC** | Índex de Dotació Comercial — establiments per habitant |

Filtratge addicional per categories: Hostaleria, Alimentació, Tèxtil, Salut i Serveis Professionals.

## Tecnologia

- [Leaflet.js](https://leafletjs.com/) per al mapa interactiu
- Geometries municipals oficials de l'ICGC
- Classificació Smart Breaks (quantils + arrodoniment "pretty")
- Fitxer HTML únic, sense dependències de servidor

## Estat

⚠️ **Les dades comercials són simulades** — El projecte utilitza geometries reals dels municipis de Catalunya però les dades d'establiments són generades algorítmicament per demostració. L'objectiu és connectar-hi dades reals del CCAM.

## Llicència

Dades cartogràfiques: [ICGC](https://www.icgc.cat/) — CC BY 4.0
