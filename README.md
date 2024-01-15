<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Workshop P8</title>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Spectral:ital,wght@0,200;0,300;0,400;0,500;0,600;0,700;0,800;1,200;1,300;1,400;1,500;1,600;1,700;1,800&display=swap" rel="stylesheet">
    <style>

body{
    display: flex;
align-items: center;
flex-direction: column;    border: 1px solid black;
}

h1,h2,h3 {
  font-family: "Spectral", serif;
  font-weight: 400;
  font-style: normal;
}

.svg{
    border: 1px solid black;
}

    </style>
</head>
<body>

    <h1>Workshop P8 : Exo 1 - Éléna Luzio/ Mina Leblanc/ Paul-Arthur Lemarquis</h1>
    <h2> Wikidata</h2>

    <iframe class="svg" style="width: 90vw; height: 580vh; border: 1px solid black;" src="https://query.wikidata.org/embed.html#%23defaultView%3ATimeline%0ASELECT%20%3Fastronaut%20%3FastronautLabel%20%3Fdate_of_birth%20%3Fcountry_of_citizenship%20%3Fcountry_of_citizenshipLabel%20WHERE%20%7B%0A%20%20SERVICE%20wikibase%3Alabel%20%7B%20bd%3AserviceParam%20wikibase%3Alanguage%20%22%5BAUTO_LANGUAGE%5D%2Cen%22.%20%7D%0A%20%20%0A%20%20%3Fastronaut%20wdt%3AP106%20wd%3AQ11631.%0A%20%20%3Fastronaut%20wdt%3AP569%20%3Fdate_of_birth.%20%0A%20%20%3Fastronaut%20wdt%3AP27%20%3Fcountry_of_citizenship.%20%0A%7D%0ALIMIT%20100" referrerpolicy="origin" sandbox="allow-scripts allow-same-origin allow-popups"></iframe>
<br>
    <h1>RawGraphs Examples</h1>
    <h2>Astronaut Origin Circular Dendrogram</h2>
    <img class="svg" src="https://hanscastorpus.github.io/Paris8/Svg/dataviz.svg"></img>

    <h2>Astronaut Origin Circle Packing</h2>
    <img class="svg" src="https://hanscastorpus.github.io/Paris8/Svg/QuantityByCountry.svg"></img>

</body>
</html>
