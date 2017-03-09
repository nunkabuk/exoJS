```javascript
//REVISIONS
// Declarez une variable nommée "boucler" contenant true
var boucler=true;

// Declarez un tableau members contenant Aida67, lapie002, anneserrano, Jennysmille, nunkabuk, RCosson, kaonb-ax, FerEmilie, crazychouwi, KiluaZoldyc, patatobeur, Sam11360, elo062, hermeline, Biciclet,
var members =["Aida67", "lapie002", "anneserrano", "Jennysmille", "nunkabuk", "RCosson", "kaonb-ax", "FerEmilie", "crazychouwi", "KiluaZoldyc", "patatobeur", "Sam11360", "elo062", "hermeline", "Biciclet",
];
document.getElementById("check").addEventListener("click",function(){
// SI la variable boucler vaut true ALORS

if (boucler){
  // Bouclez sur le tableau que vous avez déclaré ci-dessus
    for (var i = 0; i<= members.length; i++){



  // Mettre un switch pour qu'au moment où la boucle se trouve sur votre pseudo cela ajoute "Affiche " devant votre pseudo dans la console et sur l'écran et par defaut seulement le pseudo des autres
var pseudo = members[i];
  switch (pseudo) {
case "nunkabuk":
 var divcheck = document.getElementById("check");
 var new div = document.createElement("div");
 newdiv.innerHTML= "<p>Affiche"+pseudo+ "</p>"
 divcheck.appendChild(newdiv);
 console.log("affiche"+pseudo);

 break;
 default:

 var divcheck = document.getElementById("check");
 var newdiv = document.CreateElement("div");
 newdiv.innerHTML= "<p>"+pseudo+ "</p>"
 divcheck.appendChild(newdiv);
 console.log(pseudo);
    }
   }
  }

// FIN REVISIONS
});


```
