---
order: 9
title: Selectors
---

Dans l'utilisation de jQuery, le choix du sélecteur est l'un des points les plus importants. En effet, il existe de nombreuses façons pour sélectionner un élément du DOM, mais cela ne signifie pas qu'ils ont forcément les mêmes performances, vous pouvez sélectionner un élément en utilisant les classes, les ID ou les méthodes comme `find()`, `children()`.

Parmi toutes les possibilités, la solution la plus rapide reste la sélection de l’ID car elle est basée sur une opération de DOM native.

```js
$("#foo");
```

*[> Results on JSPerf](http://jsperf.com/browser-diet-jquery-selectors)*
