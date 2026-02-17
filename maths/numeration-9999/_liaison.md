<!--
link: https://fonts.googleapis.com/css?family=Montserrat:700,400|Fira+Mono&display=swap
    https://cours.relaxmaths.be/styles/lia.css?v14

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

@rm_question_calcul: @0 = [[****************************]] <script>let i=`@input`.replace(/\s+/g, '');@1.split(";").some(ans=>i===ans.replace(/\s+/g, ''))</script>

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

!import[/maths/numeration-9999/Morceaux/je-comprends-decomposition-9999.md]

!import[/maths/numeration-9999/Morceaux/je-lis-et-écris-9999.md]

!import[/maths/numeration-9999/Morceaux/je-comprends-comparer-9999.md]

