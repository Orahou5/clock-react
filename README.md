# clock-react

04.2 Exercice Clock

Faites cet exercice dans un fichier index_horloge_clock.html

    Définir un composant <Clock /> et essayez d'implémenter une horologe. Faites en sorte que dans le DOM l'horloge se mette à jour et affiche les secondes, minutes et heures qui passent.

Remarques : vous pouvez utiliser un setInterval JavaScript pour re-lancer le rendu manuellement. Exemple :

const root = ReactDOM.createRoot(document.getElementById('root'));

// React va re-render le composant <Clock /> dans #root toute les secondes
setInterval(() => root.render(<Clock />) , 1000);

Résultat souhaité (avec un affichage dynamique) :

  10h 25m 30s
