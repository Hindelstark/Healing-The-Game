<HTML>
  <HEAD>
    <TITLE>A game by Hindelstark</TITLE>
 </HEAD>
  
 <BODY> 
  
  <center>
  <iframe width="560" height="315" src="https://www.youtube.com/embed/aB2UD0k5CFE" frameborder="0" allowfullscreen></iframe>
  </center>
  
  <SCRIPT type="text/JavaScript"> 
  <!-- // Cache ce qui suit aux navigateurs qui ne supportent pas JavaScript 
  
  // Vérifiez que l'utilisateur est prêt à jouer !
 
 function monJeu()
{
confirm("Prêt pour l'aventure ?");
var age = prompt("Quel est votre âge ?");
    if(age<13) {
    console.log("Vous êtes un peu jeune pour ça, non ?");
}
    else   // "autrement"
{
confirm("A vous de jouer !");
}
confirm("Vous êtes une douce petite princesse, en pleine promenade au bord d'une fontaine, dans la mystérieuse forêt de Paimpont...");

confirm("Soudain, un crapaud sort de l'eau et vous interpelle : Bonjour mademoiselle je suis un prince victime d'un affreux mauvais sort...");

var reponseUtilisateur = prompt("Voudriez-vous m'embrasser?");
    if (reponseUtilisateur==="oui"){
        confirm("En un baiser, le crapaud se change en Meven, le prince geek qui passe sa soirée à faire des jeux vidéo");
}
    else {
        confirm("Oh non ! Le crapaud dépité s'enfuit en un plongeon !");
}
var retour = prompt("Notez ce jeu de 0 à 10 :");
    if (retour>8){
    confirm("Merci ! A très vite")
  }
    else{
    confirm("Je vais continuer à m'entraîner à coder alors !")
}
return false;
}

  //--> // Fin de la partie cachée </SCRIPT> 
  
  <a href=# onclick=return monJeu();>Launch the Game !</a>

 </BODY> 

</HTML>
