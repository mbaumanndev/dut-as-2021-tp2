TP 2
====

Pour cet exercice, un template de page web vous est fourni. Un problème cependant, le JavaScript n'a pas été réalisé !

Votre tâche est de dynamiser les éléments suivants :
- La modale (Section 5)
- Ouvrir/fermer les menus du header au click
  - Un click en dehors des menus doit les fermer également
- Retirer la banner du DOM quand on clique sur close (Section 2)
- La vérification du formulaire (champs non vide) (Section 4)

Nous ne tiendrons compte que de la version PC de la page, ne ous attardez pas sur la version mobile.

Vous trouverez dans le code des sections semblables à celle-ci :

```html
<!--
    Background overlay, show/hide based on modal state.

    Entering: "ease-out duration-300"
    From: "opacity-0"
    To: "opacity-100"
    Leaving: "ease-in duration-200"
    From: "opacity-100"
    To: "opacity-0"
-->
<div class="hidden fixed inset-0 bg-gray-500 bg-opacity-75 transition-opacity md:block" aria-hidden="true"></div>
```

Ces sections vous donnent des indications sur les changements à faire dans le HTML et sur des directives à faire en JS sur les classes des éléments pour que les composants aient le bon comportement.
