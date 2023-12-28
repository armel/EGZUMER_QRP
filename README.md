# EGZUMER QRP
EGZUMER V0.21 QRP

# Installation

Cloner le repository ou télécharger le ou les firmwares qui vous intéressent (_download raw file_). Ensuite, il vous suffit d'utiliser le [flasheur](https://egzumer.github.io/uvtools/) en ligne. C'est tout.

# Ventilation des puissances en fonction des firmwares

| Nom |	Description | Low | Mid | High |
| --------- | ------------ | ------------ | ------------ | ------------ |
| firmware.packed.bin | EGZUMER V0.21 + ENABLE_REDUCE_LOW_MID_TX_POWER :=1 | ~100mW | ~500mW | ~4W|
| firmware.0.25_2.0_4.0 | EGZUMER V0.21 + F4HWN | ~250mW | ~2W | ~4W |
| firmware.0.5_2.0_4.0 | EGZUMER V0.21 + F4HWN | ~500mW | ~2W | ~4W |
| firmware.1.0_2.0_4.0 | EGZUMER V0.21 + F4HWN | ~1W | ~2W | ~4W |

# Vidéos sur Youtube

[Partie 1](https://www.youtube.com/watch?v=aueOkAnnEcM)

[Partie 2](https://www.youtube.com/watch?v=INs5kHHVxII)

# Informations complémentaires

Dans les videos, j'utilise un simple SWRMètre Diamond. Je me suis amusé à refaire les mesures de puissance à l'aide du TinySA Ultra. Je vous livre les résultats :

| Nom |	Description | Low | Mid | High |
| --------- | ------------ | ------------ | ------------ | ------------ |
| firmware.0.25_2.0_4.0 | EGZUMER V0.21 + F4HWN | ~150mW | ~1.7W | ~4.3W |
| firmware.0.5_2.0_4.0 | EGZUMER V0.21 + F4HWN | ~400mW | ~1.7W | ~4.3W |
| firmware.1.0_2.0_4.0 | EGZUMER V0.21 + F4HWN | ~750W | ~1.7W | ~4.3W |

J'aurais tendance à penser que le TinySA Ultra donne des résultats plus précis. Mais globalement, à 100mW ~ 200mW pret, les mesures sont similiares à celles effectuées à l'aide du SWRMètre Diamond (modulo les erreurs de mesures inévitables, les pertes d'insertion, etc.). 

Gardez toujours en tête que la __métrologie (la science des mesures) est un art et que l'outil de mesures idéal n'existe pas__ ! Et je n'ai pas la prétention d'en maitriser toutes les subtilités. Je tente juste de faire au mieux en étant le plus méticuleux possible. 