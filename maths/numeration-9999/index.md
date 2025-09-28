
<!--
link: https://fonts.googleapis.com/css?family=Montserrat:700,400|Fira+Mono&display=swap
    https://cours.relaxmaths.be/styles/lia.css?v5

version:  2.0.0

author:   RelaxMaths

email:    relaxmaths@naturavie.be

comment:  La numération 9999 ...

logo:    https://cours.relaxmaths.be/images/bannière_relax_maths_cropped.png

language: fr
narrator: French Female

dark:     false

mode: manual

date:     30/08/2025

sharing: false

@style

.lia-btn.lia-quiz__resolve {
    visibility: hidden;
    display: none;
}

output.lia-script {
    cursor: default !important;
    padding: 0 !important; 
}
.lia-script {
    background-color: transparent !important;
    border-radius: 0 !important;
}

@end

@rm_lire: {!>}{@0}
@rm_lire_inv: {!>}{<span style="visibility:hidden;display:inline-flex">@0</span>}

@rm_bleu: <db>@0</db>
@rm_jaune: <dj>@0</dj>
@rm_rouge: <dr>@0</dr>
@rm_vert: <dv>@0</dv>
@rm_nombre
<script>
function afficher_nombre(N) {
    let mille = Math.floor(N / 1000);
    let cent = Math.floor((N % 1000) / 100);
    let dix = Math.floor((N % 100) / 10);
    let un = N % 10;
    let htmlLigne = "<tr class='lia-table__header text-center'>";
    // Générer chaque colonne d'image pour la ligne des images
    for (let i = 0; i < mille; i++) {
        htmlLigne += `<th style="text-align:center;"><img src="https://cours.relaxmaths.be/images/numeration/1000.svg" alt="1000" /></th>`;
    }
    for (let i = 0; i < cent; i++) {
        htmlLigne += `<th style="text-align:center;"><img src="https://cours.relaxmaths.be/images/numeration/100.svg" alt="100" /></th>`;
    }
    for (let i = 0; i < dix; i++) {
        htmlLigne += `<th style="text-align:center;"><img src="https://cours.relaxmaths.be/images/numeration/10.svg" alt="10" /></th>`;
    }
    for (let i = 0; i < un; i++) {
        htmlLigne += `<th style="text-align:center;"><img src="https://cours.relaxmaths.be/images/numeration/1.svg" alt="1" /></th>`;
    }
    htmlLigne += "</tr>";

    // Retourner le tableau HTML complet
    let tableHTML = `<div class="lia-table-responsive has-thead-sticky"><table class="lia-table"><thead class="lia-table__head">${htmlLigne}</thead></table></div>`;
    send.html(tableHTML);
}

// Appelle la fonction avec le paramètre transmis ("@0")
afficher_nombre(parseInt("@0"));
</script>
@end
-->

# Numération 9999

<div>
<columns>

<button_column>

@rm_lire_inv(`Tu vas maintenant partir à la découverte des nombres jusqu'à neuf-mille-neuf-cent-nonante-neuf. Ces nombres sont très utiles dans la vie de tous les jours; notamment pour compter de grandes quantités, lire des années, payer certaines sommes d'argent, ou encore, calculer des distances. Pour commencer; voici une vidéo te permettant d'apprendre à lire et à écrire les nombres de 1000 à neuf-mille-neuf-cent-nonante-neuf. Tu peux bien sûr y revenir à tout moment.`)
</button_column>

<column>

Tu vas maintenant partir à la découverte des nombres jusqu'à __9999__.

Ces nombres sont très utiles dans la vie de tous les jours, notamment pour compter de grandes quantités, lire des années, payer certaines sommes d'argent ou encore calculer des distances...

Pour commencer, voici une vidéo te permettant d'apprendre à lire et à écrire les nombres de 1000 à 9999. Tu peux bien sûr y revenir à tout moment.

</column>

</columns>

!?[Lire et écrire les nombres de 1000 à 9999](https://www.youtube.com/watch?v=qpNKsGeQpBM)

<!-- class="qr_150" -->
[qr-code](https://www.youtube.com/watch?v=qpNKsGeQpBM) 

</div>

## Je comprends la décomposition des nombres jusqu'à 9999

<exercice>
<!-- data-type="none" data-sortable="false" -->
| MILLE | CENTAINE | DIZAINE | UNITÉ |
| :------: | :------: | :------: | :------: |
| <dr>M</dr> | <db>C</db> | <dv>D</dv> | <dj>U</dj> |
| ![](https://cours.relaxmaths.be/images/numeration/1000.svg) | ![](https://cours.relaxmaths.be/images/numeration/100.svg) | ![](https://cours.relaxmaths.be/images/numeration/10.svg) | ![](https://cours.relaxmaths.be/images/numeration/1.svg) |
| 1000 | 100 | 10 | 1 |
</exercice>

### Effectuer des additions simples de milliers

<exercice>
<!-- data-type="none" data-sortable="false" -->
| ![](https://cours.relaxmaths.be/images/numeration/1000.svg) | ![](https://cours.relaxmaths.be/images/numeration/1000.svg) | ![](https://cours.relaxmaths.be/images/numeration/1000.svg) | ![](https://cours.relaxmaths.be/images/numeration/1000.svg) | ![](https://cours.relaxmaths.be/images/numeration/1000.svg) |
| :------: | :------: | :------: | :------: | :------: |

<!-- class="calcul" -->
= <dr>1000</dr> + <dr>1000</dr> + <dr>1000</dr> + <dr>1000</dr> + <dr>1000</dr>

<!-- class="calcul"  -->
= <dr>5000</dr>
</exercice>

<exercice>
<!-- data-type="none" data-sortable="false" -->
| ![](https://cours.relaxmaths.be/images/numeration/1000.svg) | ![](https://cours.relaxmaths.be/images/numeration/1000.svg) |
| :------: | :------: |

<!-- class="calcul" -->
= [[1000]] + [[1000]]

<!-- class="calcul"  -->
= [[2000]]
</exercice>

<exercice>
<!-- data-type="none" data-sortable="false" -->
| ![](https://cours.relaxmaths.be/images/numeration/1000.svg) | ![](https://cours.relaxmaths.be/images/numeration/1000.svg) | ![](https://cours.relaxmaths.be/images/numeration/1000.svg) |
| :------: | :------: | :------: |

<!-- class="calcul" -->
= [[1000]] + [[1000]] + [[1000]]

<!-- class="calcul"  -->
= [[3000]]
</exercice>

<exercice>
<!-- data-type="none" data-sortable="false" -->
| ![](https://cours.relaxmaths.be/images/numeration/1000.svg) | ![](https://cours.relaxmaths.be/images/numeration/1000.svg) | ![](https://cours.relaxmaths.be/images/numeration/1000.svg) | ![](https://cours.relaxmaths.be/images/numeration/1000.svg) |
| :------: | :------: | :------: | :------: |

<!-- class="calcul" -->
= [[1000]] + [[1000]] + [[1000]] + [[1000]]

<!-- class="calcul"  -->
= [[4000]]
</exercice>

<exercice>
<!-- data-type="none" data-sortable="false" -->
| ![](https://cours.relaxmaths.be/images/numeration/1000.svg) | ![](https://cours.relaxmaths.be/images/numeration/1000.svg) | ![](https://cours.relaxmaths.be/images/numeration/1000.svg) | ![](https://cours.relaxmaths.be/images/numeration/1000.svg) | ![](https://cours.relaxmaths.be/images/numeration/1000.svg) | ![](https://cours.relaxmaths.be/images/numeration/1000.svg) |
| :------: | :------: | :------: | :------: | :------: | :------: |

<!-- class="calcul" -->
= [[1000]] + [[1000]] + [[1000]] + [[1000]] + [[1000]] + [[1000]]

<!-- class="calcul"  -->
= [[6000]]
</exercice>

### Effectuer des additions simples M, C, D et U avec aide visuelle
@rm_lire(`Complète suivant l'exemple donné.`)

<exercice>
@rm_nombre(2324)

<!-- class="calcul"  -->
= <dr>2000</dr> + <db>300</db> + <dv>20</dv> + <dj>4</dj>

<!-- class="calcul"  -->
= <dr>2</dr><db>3</db><dv>2</dv><dj>4</dj>
</exercice>

<exercice>
@rm_nombre(5121)

<!-- class="calcul"  -->
= [[5000]] + [[100]] + [[20]] + [[1]]

<!-- class="calcul"  -->
= [[5121]]
</exercice>

<exercice>
@rm_nombre(1112)

<!-- class="calcul"  -->
= [[1000]] + [[100]] + [[10]] + [[2]]

<!-- class="calcul"  -->
= [[1112]]
</exercice>

<exercice>
@rm_nombre(3414)

<!-- class="calcul"  -->
= [[3000]] + [[400]] + [[10]] + [[4]]

<!-- class="calcul"  -->
= [[3414]]
</exercice>

<exercice>
@rm_nombre(1521)

<!-- class="calcul"  -->
= [[1000]] + [[500]] + [[20]] + [[1]]

<!-- class="calcul"  -->
= [[1521]]
</exercice>

<exercice>

@rm_nombre(4163)

<!-- class="calcul"  -->
= [[4000]] + [[100]] + [[60]] + [[3]]

<!-- class="calcul"  -->
= [[4163]]
</exercice>

<h4>POUR ALLER PLUS LOIN...</h4>

<columns>

<button_column>

@rm_lire_inv(`Déplace les bons nombres aux bons endroits, puis clique sur valider en-bas de l'écran.`)

</button_column>

<column>

Déplace les bons nombres aux bons endroits, puis clique sur "Valider" en-bas de l'écran.

</column>

</columns>

[<div><img alt src="https://cours.relaxmaths.be/images/numeration/combien_de_cubes.png" loading="lazy" /></div>](https://soutien67.fr/math/activites/compter_9999/Compter-9999-E1/index.html)

<!-- class="qr_150" -->
[qr-code](https://soutien67.fr/math/activites/compter_9999/Compter-9999-E1/index.html) 

### Effectuer des additions simples M, C, D et U dans l'ordre

@rm_lire(`Effectue les additions suivantes en te référant à l'exemple.<br/> Tu obtiendras <u>un nombre à 4 chiffres</u> dans lequel tu placeras TOUJOURS le chiffre des milles en premier, PUIS celui des centaines, PUIS celui des dizaines, et enfin celui des unités`)

<exercice>
<!-- class="calcul centrer"  -->
<dr>9000</dr> + <db>500</db> + <dv>40</dv> + <dj>7</dj> = <dr>9</dr><db>5</db><dv>4</dv><dj>7</dj>

<!-- data-type="none" data-sortable="false" -->
|<dr>M</dr>|<db>C</db>|<dv>D</dv>|<dj>U</dj>|
| :------: | :------: | :------: | :------: |
|<dr>9</dr>|<db>5</db>|<dv>4</dv>|<dj>7</dj>|
</exercice>

<exercice>
<!-- class="calcul"  -->
4000 + 600 + 30 + 5 = [[4635]]
</exercice>

<exercice>
<!-- class="calcul"  -->
2000 + 800 + 70 + 9 = [[2879]]
</exercice>

<exercice>
<!-- class="calcul"  -->
7000 + 300 + 80 + 1 = [[7381]]
</exercice>

<exercice>
<!-- class="calcul"  -->
5000 + 200 + 90 + 6 = [[5296]]
</exercice>

<exercice>
<!-- class="calcul"  -->
8000 + 400 + 50 + 3 = [[8453]]
</exercice>

<exercice>
<!-- class="calcul"  -->
2000 + 900 + 60 + 8 = [[2968]]
</exercice>

<exercice>
<!-- class="calcul"  -->
7000 + 100 + 20 + 4 = [[7124]]
</exercice>

### Effectuer rapidement des additions simples M, C, D et U dans le désordre

@rm_lire(`Effectue les additions suivantes en te référant à l'exemple.<br/> Tu obtiendras <u>un nombre à 4 chiffres</u> dans lequel tu placeras TOUJOURS le chiffre des mille en premier, PUIS celui des centaines, PUIS celui des dizaines, et enfin, celui des unités.`)

<exercice>
<!-- class="calcul centrer"  -->
<dr>3000</dr> + <db>500</db> + <dj>9</dj> + <dv>60</dv> = <dr>3000</dr> + <db>500</dr> + <dv>60</dv> + <dj>9</dj> =  <dr>3</dr><db>5</db><dv>6</dv><dj>9</dj>


<!-- data-type="none" data-sortable="false" -->
| <dr>M</dr> | <db>C</db> | <dv>D</dv> | <dj>U</dj> |
| :--------: | :--------: | :--------: | :--------: |
| <dr>3</dr> | <db>5</db> | <dv>6</dv> | <dj>9</dj> | 
</exercice>

<exercice>
<!-- class="calcul"  -->
200 + 3000 + 70 + 5 = [[3275]]
</exercice>

<exercice>
<!-- class="calcul"  -->
40 + 4000 + 9 + 300 = [[4349]]
</exercice>
<exercice>
<!-- class="calcul"  -->
900 + 4000 + 60 + 7 = [[4967]]
</exercice>

<exercice>
<!-- class="calcul"  -->
80 + 2000 + 300 + 5 = [[2385]]
</exercice>

<exercice>
<!-- class="calcul"  -->
20 + 7000 + 800 + 3 = [[7823]]
</exercice>

<exercice>
<!-- class="calcul"  -->
600 + 5000 + 4 + 90  = [[5694]]
</exercice>

<exercice>
<!-- class="calcul"  -->
70 + 8000 + 200 + 6 = [[8276]]
</exercice>

<exercice>
<!-- class="calcul"  -->
700 + 2000 + 50 + 9 = [[2759]]
</exercice>

<exercice>
<!-- class="calcul"  -->
400 + 6000 + 30 + 8 = [[6438]]
</exercice>

<h4>POUR ALLER PLUS LOIN...</h4>


<div class="lia-iframe-wrapper">
  <iframe src="https://soutien67.fr/math/activites/compter_9999/Compter-9999-E2/index.html"
    allowfullscreen="true"
    webkitallowfullscreen="true"
    mozallowfullscreen="true"
    frameborder="0"></iframe>
</div>

<!-- class="qr_150" -->
[qr-code](https://soutien67.fr/math/activites/compter_9999/Compter-9999-E2/index.html) 

### Effectuer des additions simples de M, C et D

@rm_lire(`Effectue les additions suivantes en te référant à l'exemple.<br/> Tu obtiendras <u>un nombre à 4 chiffres</u> dans lequel tu placeras TOUJOURS le chiffre des mille en premier, PUIS celui des centaines, PUIS celui des dizaines, et enfin, celui des unités.`)

<exercice>
<!-- class="calcul centrer"  -->
<dr>8000</dr> + <db>500</db> + <dv>50</dv> = <dr>8</dr><db>5</db><dv>5</dv><dj>0</dj>

<!-- data-type="none" data-sortable="false" -->
| <dr>M</dr> | <db>C</db> | <dv>D</dv> | <dj>U</dj> |
| :--------: | :--------: | :--------: | :--------: |
| <dr>8</dr> | <db>5</db> | <dv>5</dv> | <dj>0</dj> | 
</exercice>

<exercice>
<!-- class="calcul"  -->
40 + 3000 + 500 = [[3540]]
</exercice>

<exercice>
<!-- class="calcul"  -->
6000 + 90 + 200 = [[6290]]
</exercice>

<exercice>
<!-- class="calcul"  -->
2000 + 900 + 60  = [[2960]]
</exercice>

<exercice>
<!-- class="calcul"  -->
5000 + 80 + 200 = [[5280]]
</exercice>

<exercice>
<!-- class="calcul"  -->
4000 + 500 + 40 = [[4540]]
</exercice>

<exercice>
<!-- class="calcul"  -->
7000 + 30 + 900 = [[7930]]
</exercice>

<exercice>
<!-- class="calcul"  -->
50 + 9000 + 600 = [[9650]]
</exercice>

<exercice>
<!-- class="calcul"  -->
6000 + 30 + 400 = [[6430]]
</exercice>

<exercice>
<!-- class="calcul"  -->
8000 + 40 + 700 = [[8740]]
</exercice>

### Effectuer des additions simples de M, C et U

@rm_lire(`Effectue les additions suivantes en te référant à l'exemple.<br/> Tu obtiendras <u>un nombre à 4 chiffres</u> dans lequel tu placeras TOUJOURS le chiffre des mille en premier, PUIS celui des centaines, PUIS celui des dizaines, et enfin, celui des unités.`)

<exercice>
<!-- class="calcul centrer"  -->
<dr>7000</dr> + <db>800</db> + <dj>4</dj> = <dr>7</dr><db>8</db><dv>0</dv><dj>4</dj>

<!-- data-type="none" data-sortable="false" -->
| <dr>M</dr> | <db>C</db> | <dv>D</dv> | <dj>U</dj> |
| :--------: | :--------: | :--------: | :--------: |
| <dr>7</dr> | <db>4</db> | <dv>0</dv> | <dj>8</dj> | 
</exercice>

<exercice>
<!-- class="calcul"  -->
7000 + 200 + 1 = [[7201]]
</exercice>

<exercice>
<!-- class="calcul"  -->
3 + 8000 + 900 = [[8903]]
</exercice>

<exercice>
<!-- class="calcul"  -->
600 + 9000 + 9 = [[9609]]
</exercice>

<exercice>
<!-- class="calcul"  -->
9 + 5000 + 800 = [[5809]]
</exercice>

<exercice>
<!-- class="calcul"  -->
800 + 3000 + 3 = [[3803]]
</exercice>

<exercice>
<!-- class="calcul"  -->
6 + 2000 + 500 = [[2506]]
</exercice>

<exercice>
<!-- class="calcul"  -->
400 + 9000 + 9 = [[9409]]
</exercice>

<exercice>
<!-- class="calcul"  -->
2 + 6000 + 700 = [[6702]]
</exercice>

<exercice>
<!-- class="calcul"  -->
100 + 8000 + 2 = [[8102]]
</exercice>

### Effectuer des additions simples de M, D et U

@rm_lire(`Effectue les additions suivantes en te référant à l'exemple.<br/> Tu obtiendras <u>un nombre à 4 chiffres</u> dans lequel tu placeras TOUJOURS le chiffre des mille en premier, PUIS celui des centaines, PUIS celui des dizaines, et enfin, celui des unités.`)

<exercice>
<!-- class="calcul centrer"  -->
<dr>3000</dr> + <dv>80</dv> + <dj>4</dj> = <dr>3</dr><db>0</db><dv>8</dv><dj>4</dj>

<!-- data-type="none" data-sortable="false" -->
| <dr>M</dr> | <db>C</db> | <dv>D</dv> | <dj>U</dj> |
| :--------: | :--------: | :--------: | :--------: |
| <dr>3</dr> | <db>0</db> | <dv>8</dv> | <dj>4</dj> | 
</exercice>

<exercice>
<!-- class="calcul"  -->
9000 + 4 + 30 = [[9034]]
</exercice>

<exercice>
<!-- class="calcul"  -->
7 + 2000 + 80 = [[2087]]
</exercice>

<exercice>
<!-- class="calcul"  -->
60 + 3000 + 5 = [[3065]]
</exercice>

<exercice>
<!-- class="calcul"  -->
2000 + 9 + 70 = [[2079]]
</exercice>

<exercice>
<!-- class="calcul"  -->
8 + 4000 + 20 = [[4028]]
</exercice>

<exercice>
<!-- class="calcul"  -->
9000 + 60 + 2 = [[9062]]
</exercice>

<exercice>
<!-- class="calcul"  -->
5 + 7000 + 40 = [[7045]]
</exercice>

<exercice>
<!-- class="calcul"  -->
3000 + 7 + 50 = [[3057]]
</exercice>

<exercice>
<!-- class="calcul"  -->
6 + 2000 + 90 = [[2096]]
</exercice>

<exercice>
<!-- class="calcul"  -->
30 + 6000 + 8 = [[6038]]
</exercice>

<h4>POUR ALLER PLUS LOIN...</h4>

@rm_lire(`Coche le __niveau 3__ puis réalise l'exercice proposé.`)

[<div><img src="https://cours.relaxmaths.be/images/numeration/recomposition_de_nombres.png" loading="lazy" /></div>](https://www.logicieleducatif.fr/jeu/recomposition-de-nombres-avec-zero)


<!-- class="qr_150" -->
[QR-CODE](https://www.logicieleducatif.fr/jeu/recomposition-de-nombres-avec-zero)

### Effectuer des décompositions de nombres

@rm_lire(`Décompose les nombres donnés en milliers, centaines, dizaines et unités.<br/> Aide-toi de l'exemple ci-dessous.`)


<exercice>
<!-- class="calcul centrer"  -->
2547 = <dr>2000</dr> + <db>500</db> + <dv>40</dv> + <dj>7</dj>
</exercice>

<exercice>
<!-- class="calcul"  -->
3805 = [[3000 + 800 + 5]]
</exercice>

<exercice>
<!-- class="calcul"  -->
4623 = [[4000 + 600 + 20 + 3]]
</exercice>

<exercice>
<!-- class="calcul"  -->
5178 = [[5000 + 100 + 70 + 8]]
</exercice>

<exercice>
<!-- class="calcul"  -->
3290 = [[3000 + 200 + 90]]
</exercice>

<exercice>
<!-- class="calcul"  -->
1845 = [[1000 + 800 + 40 + 5]]
</exercice>

<exercice>
<!-- class="calcul"  -->
4762 = [[4000 + 700 + 60 + 2]]
</exercice>

<exercice>
<!-- class="calcul"  -->
2934 = [[2000 + 900 + 30 + 4]]
</exercice>

<exercice>
<!-- class="calcul"  -->
2040 = [[2000 + 40]]
</exercice>

<exercice>
<!-- class="calcul"  -->
3170 = [[3000 + 100 + 70]]
</exercice>


<h4> POUR ALLER PLUS LOIN </h4>

<div class="lia-iframe-wrapper">
  <iframe src="https://learningapps.org/view29465907"
    allowfullscreen="true"
    webkitallowfullscreen="true"
    mozallowfullscreen="true"
    frameborder="0"></iframe>
</div>

<!-- class="qr_150" -->
[QR-CODE](https://learningapps.org/view29465907)

## Je lis et j'écris les nombres jusqu'à 9999

!?[Lire et écrire les nombres de 1000 à 9999](https://www.youtube.com/watch?v=qpNKsGeQpBM)

<!-- class="qr_150" -->
[QR-CODE](https://www.youtube.com/watch?v=qpNKsGeQpBM)

<columns>

<button_column>

@rm_lire_inv(`Un moyen visuel pour retenir comment lire et écrire un nombre de 1000 à neuf mille neuf cent nonante-neuf facilement. Un nombre de 1000 à neuf mille neuf cent nonante-neuf comporte toujours 4 chiffres : les millie, les centaines, les dizaines et les unités. Tu lis d'abord le premier chiffre et ajoute le mot "__MILLE__" derrière. Ensuite, tu lis les trois derniers chiffres ensemble comme tu avais l'habitude de le faire pour les nombres jusqu'à 999.`)
</button_column>

<column>

Un moyen visuel pour retenir comment lire et écrire un nombre de 1000 à 9999 facilement.<br/> 1. Un nombre de 1000 à 9999 comporte toujours 4 chiffres : <dr>M</dr><db>C</db><dv>D</dv><dj>U</dj><br/> 2. Tu lis le premier chiffre et ajoute le mot <i>"MILLE"</i> derrière.<br/> 3. Ensuite, tu lis <i> les trois derniers chiffres ensemble </i> comme tu avais l'habitude de le faire pour les nombres jusqu'à 999.
</column>

</columns>

<exercice>
<!-- data-type="none" data-sortable="false" -->
| <dr>M</dr> | <db>C</db> | <dv>D</dv> | <dj>U</dj> |
| :-------:| :--------: | :-------: | :-------: |
|2|3|4|5|
</exercice>

@rm_lire(`Cet exemple se lit : "2 mille 345" - deux mille trois cent quarante-cinq.`)

### Associer des nombres dictés à leur écriture mathématique

<div class="lia-iframe-wrapper">
  <iframe src="https://learningapps.org/watch?v=pfej9vya324"
    allowfullscreen="true"
    webkitallowfullscreen="true"
    mozallowfullscreen="true"
    frameborder="0"></iframe>
</div>

<!-- class="qr_150" -->
[QR-CODE](https://learningapps.org/watch?v=pfej9vya324)

<hr>

<div class="lia-iframe-wrapper">
  <iframe src="https://learningapps.org/watch?v=payedb9wc24"
    allowfullscreen="true"
    webkitallowfullscreen="true"
    mozallowfullscreen="true"
    frameborder="0"></iframe>
</div>

<!-- class="qr_150" -->
[QR-CODE](https://learningapps.org/watch?v=payedb9wc24)

### Écrire des nombres dictés en écriture mathématique
@rm_lire(Écoute les nombres qui te sont dictés et écris ta réponse ci-dessous.)

<exercice>
1. @rm_lire_inv(`5837`)
[[5837]]
</exercice>

<exercice>
2. @rm_lire_inv(`7613`)
[[7613]]
</exercice>

<exercice>
3. @rm_lire_inv(`4395`)
[[4395]]
</exercice>

<exercice>
4. @rm_lire_inv(`9275`)
[[9275]]
</exercice>

<exercice>
5. @rm_lire_inv(`3187`)
[[3187]]
</exercice>

<exercice>
6. @rm_lire_inv(`6543`)
[[6543]]
</exercice>

<exercice>
7. @rm_lire_inv(`8729`)
[[8729]]
</exercice>

<exercice>
8. @rm_lire_inv(`5916`)
[[5916]]
</exercice>

<exercice>
9. @rm_lire_inv(`7365`)
[[7365]]
</exercice>

<exercice>
10. @rm_lire_inv(`4159`)
[[4159]]
</exercice>

@rm_lire(`Pour les exercices suivants, la consigne reste la même mais ATTENTION car les nombres comportent un 0 soit au niveau des centaines, des dizaines ou des unités...`)

<exercice>
11. @rm_lire_inv(`3057`)
[[3057]]
</exercice>

<exercice>
12. @rm_lire_inv(`4708`)
[[4708]]
</exercice>

<exercice>
13. @rm_lire_inv(`5820`)
[[5820]]
</exercice>

<exercice>
14. @rm_lire_inv(`6209`)
[[6209]]
</exercice>

<exercice>
15. @rm_lire_inv(`5043`)
[[5043]]
</exercice>

<exercice>
16. @rm_lire_inv(`5910`)
[[5910]]
</exercice>

<exercice>
17. @rm_lire_inv(`7290`)
[[7290]]
</exercice>

<exercice>
18. @rm_lire_inv(`8602`)
[[8602]]
</exercice>

<exercice>
19. @rm_lire_inv(`5803`)
[[5803]]
</exercice>

<exercice>
20. @rm_lire_inv(`4310`)
[[4310]]
</exercice>

<h4>POUR ALLER PLUS LOIN...</h4>
@rm_lire(`Configure l'application selon l'image ci-dessous, puis réalise les exercices.`)

[<div><img src="https://cours.relaxmaths.be/images/numeration/nombres_9999.png" loading="lazy" /></div>](https://www.logicieleducatif.fr/jeu/nombres-en-chiffres)

<!-- class="qr_150" -->
[QR-CODE](https://www.logicieleducatif.fr/jeu/nombres-en-chiffres)

### Lire des nombres

@rm_lire(`Lis à ton professeur la suite de nombres ci-dessous :`)

<exercice>
* 4820
* 7305
* 6094
* 5813
* 9407
* 3206
* 8751
* 5603
* 4308
* 2179
* 7012
* 6509
* 8702
* 2908
* 4701
* 2045
</exercice>



## Je comprends comment comparer des nombres entre eux jusqu'à 9999

!?[](https://www.youtube.com/watch?v=FV-uBVGKIbI)

<!-- class="qr_150" -->
[QR-CODE](https://www.youtube.com/watch?v=FV-uBVGKIbI)

### Écrire le nombre qui vient juste avant celui donné

@rm_lire(`Dans chaque exercice, écris le nombre qui vient juste avant celui donné.`)

<exercice>
[[2185]] 
< 2186
</exercice>

<exercice>
<!-- class="calcul"  -->
[[3228]]  
< 3229
</exercice>

<exercice>
<!-- class="calcul"  -->
[[4357]]  
< 4358
</exercice>

<exercice>
<!-- class="calcul"  -->
[[5472]]  
< 5473
</exercice>

<exercice>
<!-- class="calcul"  -->
[[6890]] 
< 6891
</exercice>

<exercice>
<!-- class="calcul"  -->
[[7659]] 
< 7660
</exercice>

<exercice>
<!-- class="calcul"  -->
[[8698]] 
< 8699
</exercice>

<exercice>
<!-- class="calcul"  -->
[[7575]] 
< 7576
</exercice>

<exercice>
<!-- class="calcul"  -->
[[8900]] 
< 8901
</exercice>

<exercice>
<!-- class="calcul"  -->
[[8798]] 
< 8799
</exercice>

<exercice>
<!-- class="calcul"  -->
[[9839]]  
< 9840
</exercice>

<exercice>
<!-- class="calcul"  -->
[[9500]] 
< 9501
</exercice>

<exercice>
<!-- class="calcul"  -->
[[7299]] 
< 7300
</exercice>

<exercice>
<!-- class="calcul"  -->
[[5099]] 
< 5100
</exercice>

<exercice>
<!-- class="calcul"  -->
[[6249]] 
< 6250
</exercice>

### Écrire le nombre qui vient juste après celui donné

@rm_lire(`Dans chaque exercice, écris le nombre qui vient juste après celui donné.`)

<exercice>
<!-- class="calcul"  -->
2187 < [[2188]]
</exercice>

<exercice>
<!-- class="calcul"  -->
3256 < [[3257]]
</exercice>

<exercice>
<!-- class="calcul"  -->
4440 < [[4441]]
</exercice>

<exercice>
<!-- class="calcul"  -->
4305 < [[4306]]
</exercice>

<exercice>
<!-- class="calcul"  -->
2178 < [[2179]]
</exercice>

<exercice>
<!-- class="calcul"  -->
6845 < [[6846]]
</exercice>

<exercice>
<!-- class="calcul"  -->
7700 < [[7701]]
</exercice>

<exercice>
<!-- class="calcul"  -->
7510 < [[7511]]
</exercice>

<exercice>
<!-- class="calcul"  -->
8607 < [[8608]]
</exercice>

<exercice>
<!-- class="calcul"  -->
9669 < [[9670]]
</exercice>

<exercice>
<!-- class="calcul"  -->
2199 < [[2200]]
</exercice>

<exercice>
<!-- class="calcul"  -->
9979 < [[9980]]
</exercice>

<exercice>
<!-- class="calcul"  -->
7499 < [[7500]]
</exercice>

<exercice>
<!-- class="calcul"  -->
8879 < [[8880]]
</exercice>

<exercice>
<!-- class="calcul"  -->
5099 < [[5100]]
</exercice>

### Encadrer les nombres donnés à l'unité

@rm_lire(`Dans chaque exercice, encadre le nombre donné par le nombre qui vient juste avant et celui qui vient juste après.`)

<exercice>
<!-- class="calcul"  -->
[[3216]] 
< 3217 < [[3218]]
</exercice>

<exercice>
<!-- class="calcul"  -->
[[4581]] 
< 4582 < [[4583]]
</exercice>

<exercice>
<!-- class="calcul"  -->
[[6824]] 
< 6825 < [[6826]]
</exercice>

<exercice>
<!-- class="calcul"  -->
[[7912]] 
< 7913 < [[7914]]
</exercice>

<exercice>
<!-- class="calcul"  -->
[[6606]] 
< 6607 < [[6608]]
</exercice>

<exercice>
<!-- class="calcul"  -->
[[8739]] 
< 8740 < [[8741]]
</exercice>

<exercice>
<!-- class="calcul"  -->
[[3350]] 
< 3351 < [[3352]]
</exercice>

<exercice>
<!-- class="calcul"  -->
[[8409]] 
< 8410 < [[8411]]
</exercice>

<exercice>
<!-- class="calcul"  -->
[[4160]] 
< 4161 < [[4162]]
</exercice>

<exercice>
<!-- class="calcul"  -->
[[6469]] 
< 6470 < [[6471]]
</exercice>

<exercice>
<!-- class="calcul"  -->
[[7878]] 
< 7879 < [[7880]]
</exercice>

<exercice>
<!-- class="calcul"  -->
[[8905]] 
< 8906 < [[8907]]
</exercice>

<exercice>
<!-- class="calcul"  -->
[[4499]] 
< 4500 < [[4501]]
</exercice>

<exercice>
<!-- class="calcul"  -->
[[8999]] 
< 9000 < [[9001]]
</exercice>

<exercice>
<!-- class="calcul"  -->
[[9998]] 
< 9999 < [[10000]]
</exercice>

### Indiquer le nombre le plus petit

@rm_lire(`Coche le nombre le plus petit dans chaque exercice.`)

<exercice>
1. 
- [(x)] 4169
- [( )] 5284
</exercice>

<exercice>
2. 
- [(x)] 3025
- [( )] 4182
</exercice>

<exercice>
3. 
- [( )] 6600
- [(x)] 5499
</exercice>

<exercice>
4. 
- [( )] 7899
- [(x)] 5853
</exercice>

<exercice>
5. 
- [(x)] 3203
- [( )] 6501
</exercice>

<exercice>
6. 
- [(x)] 4690
- [( )] 5964
</exercice>

<exercice>
7. 
- [(x)] 6548
- [( )] 6584
</exercice>

<exercice>
8. 
- [( )] 6608
- [(x)] 4408
</exercice>

<exercice>
9. 
- [( )] 7720
- [(x)] 4322
</exercice>

<exercice>
10. 
- [(x)] 6800
- [( )] 7901
</exercice>

### Indiquer le nombre le plus grand
@rm_lire(`Coche le nombre le plus grand dans chaque exercice.`)

<exercice>
1. 
- [(x)] 6648
- [( )] 5284
</exercice>

<exercice>
2. 
- [(x)] 7366
- [( )] 5184
</exercice>

<exercice>
3. 
- [( )] 5500
- [(x)] 9999
</exercice>

<exercice>
4. 
- [( )] 6699
- [(x)] 9953
</exercice>

<exercice>
5. 
- [( )] 3208
- [(x)] 6506
</exercice>

<exercice>
6. 
- [(x)] 7799
- [( )] 5999
</exercice>

<exercice>
7. 
- [(x)] 7100
- [( )] 6014
</exercice>

<exercice>
8. 
- [(x)] 9902
- [( )] 5499
</exercice>

<exercice>
9. 
- [( )] 4320
- [(x)] 4322
</exercice>

<exercice>
10. 
- [(x)] 9700
- [( )] 9699
</exercice>

### Classer des nombres du plus petit au plus grand (ordre croissant)

@rm_lire(`Classe les nombres suivants du plus petit au plus grand.`)

<exercice>
<!-- class="calcul centrer"  -->
4253 - 4224 - 4232 - 4258 - 4201 - 4275 - 4299 - 4228

<!-- class="centrer"  -->
[[4201]] 
[[4224]] 
[[4228]]
[[4232]]
[[4253]]
[[4258]]
[[4275]]
[[4299]]
</exercice>

<exercice>
<!-- class="calcul centrer"  -->
6674 - 6012 - 6528 - 6147 - 6795 - 6283 - 6461 - 6050

<!-- class="centrer"  -->
[[6012]] 
[[6050]] 
[[6147]]
[[6283]]
[[6461]]
[[6528]]
[[6674]]
[[6795]]
</exercice>

<exercice>
<!-- class="calcul centrer"  -->
5639 - 3158 - 7204 - 2346 - 6090 - 8571 - 6400 - 4783

<!-- class="centrer"  -->
[[2346]] 
[[3158]] 
[[4783]]
[[5639]]
[[6090]]
[[6400]]
[[7204]]
[[8571]]
</exercice>

<exercice>
<!-- class="calcul centrer"  -->
4271 - 9362 - 8516 - 2957 - 1849 - 8000 - 4723 - 6080

<!-- class="centrer"  -->
[[1849]] 
[[2957]] 
[[4271]]
[[4723]]
[[6080]]
[[8000]]
[[8516]]
[[9362]]
</exercice>

<exercice>
<!-- class="calcul centrer"  -->
4683 - 8519 - 5274 - 2498 - 3127 - 7002 - 5671 - 9000

<!-- class="centrer"  -->
[[2498]] 
[[3127]] 
[[4683]]
[[5274]]
[[5671]]
[[7002]]
[[8519]]
[[9000]]
</exercice>

<exercice>
<!-- class="calcul centrer"  -->
6842 - 7815 - 2364 - 5197 - 3951 - 8427 - 6000 - 4572

<!-- class="centrer"  -->
[[2364]] 
[[3951]] 
[[4572]]
[[5197]]
[[6000]]
[[6842]]
[[7815]]
[[8427]]
</exercice>

<h4>POUR ALLER PLUS LOIN...</h4>
@rm_lire(Coche l'étoile __Personnalisé__ puis règle le jeu comme sur l'image pour réaliser l'exercice proposé.)

[<div><img src="https://cours.relaxmaths.be/images/numeration/ordre_croissant_perso.png" loading="lazy" /></div>](https://www.logicieleducatif.fr/jeu/rangement-en-ordre-croissant)

<!-- class="qr_150" -->
[QR-CODE](https://www.logicieleducatif.fr/jeu/rangement-en-ordre-croissant)

### Classer des nombres du plus grand au plus petit (ordre décroissant)

@rm_lire(`Classe les nombres suivants du plus grand au plus petit.`)

<exercice>
<!-- class="calcul centrer"  -->
4510 - 4562 - 4548 - 4501 - 4587 - 4596 - 4563 - 4512

<!-- class="centrer" --> 
[[4596]] 
[[4587]] 
[[4563]] 
[[4562]] 
[[4548]] 
[[4512]] 
[[4510]] 
[[4501]] 
</exercice>

<exercice>
<!-- class="calcul centrer"  -->
8927 - 8814 - 8843 - 8856 - 8872 - 8891 - 8880 - 8835

<!-- class="centrer"  -->
[[8927]] 
[[8891]] 
[[8880]] 
[[8872]] 
[[8856]] 
[[8843]] 
[[8835]] 
[[8814]] 
</exercice>

<exercice>
<!-- class="calcul centrer"  -->
5824 - 4300 - 6384 - 7212 - 8009 - 8456 - 9501 - 9000 - 7653 - 6542

<!-- class="centrer"  -->
[[9501]] 
[[9000]] 
[[8456]] 
[[8009]] 
[[7653]] 
[[7212]] 
[[6542]] 
[[6384]] 
[[5824]] 
[[4300]] 
</exercice>

<exercice>
<!-- class="calcul centrer"  -->
7812 - 8820 - 9000 - 9522 - 8010 - 7000 - 6541 - 6000 - 5821 - 4300

<!-- class="centrer"  -->
[[9522]] 
[[9000]] 
[[8820]] 
[[8010]] 
[[7812]] 
[[7000]] 
[[6541]] 
[[6000]] 
[[5821]] 
[[4300]] 
</exercice>

<exercice>
<!-- class="calcul centrer"  -->
7821 - 4087 - 6548 - 2740 - 5999 - 6319 - 2250 - 4250

<!-- class="centrer"  -->
[[7821]] 
[[6548]] 
[[6319]] 
[[5999]] 
[[4250]] 
[[4087]] 
[[2740]] 
[[2250]] 
</exercice>

<exercice>
<!-- class="calcul centrer"  -->
9170 - 4017 - 8240 - 4322 - 4089 - 6358 - 2319 - 7508

<!-- class="centrer"  -->
[[9170]] 
[[8240]] 
[[7508]] 
[[6358]] 
[[4322]] 
[[4089]] 
[[4017]] 
[[2319]] 
</exercice>

<h4>POUR ALLER PLUS LOIN...</h4>
@rm_lire(Coche l'étoile __Personnalisé__ puis règle le jeu comme sur l'image pour réaliser l'exercice proposé.)

[<div><img src="https://cours.relaxmaths.be/images/numeration/ordre_croissant_perso.png" loading="lazy" /></div>](https://www.logicieleducatif.fr/jeu/rangement-en-ordre-decroissant)


<!-- class="qr_150" -->
[QR-CODE](https://www.logicieleducatif.fr/jeu/rangement-en-ordre-decroissant)





