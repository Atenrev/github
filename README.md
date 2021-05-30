# musical-instruments-recognition
Repositori d'un treball de l'assignatura de Visió per Computador de la [Universitat Autònoma de Barcelona](https://www.uab.cat) en el qual s'estudia l'ús de diferents espectrogrames per al reconeixement de diferents instruments d'un àudio.

## Abstract
En aquest projecte s'estudia la classificació d'àudios a partir dels instruments musicals que hi apareixen, mitjançant tècniques de visió per computador. Amb aquest propòsit, s'han estudiat diferents maneres de representar un so a partir d'imatges, de manera que es representin les freqüències sonores en un eix de la imatge, el temps en l'altre, i la intensitat de cada freqüència es representi mitjançant el color. Alguns dels tipus de gràfics considerats són els espectrogrames, els *mel-spectrogram* o els *tonnetz*.

Posteriorment, s'ha estudiat quin és el millor model basat en xarxes convolucionals que permet classificar els àudios musicals a partir d'aquests gràfics. Per a fer-ho, el model haurà de tenir en consideració els elements físics del so inherents a un instrument musical, com el timbre, que apareixerà en l'eix vertical dels espectrogrames. Al mateix temps, el model ha de ser capaç de no tenir en consideració els canvis produïts per propietats més pròpies de la melodia, com el to.

S'ha trobat que el millor model classifica a partir d'una combinació de diferents gràfics, i tot i que les mètriques obtingudes per a aquest model són acceptables, no són especialment altes, com ja passava en l'estat de l'art d'aquest problema.
