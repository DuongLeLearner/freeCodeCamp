---
id: 587d7b89367417b2b2512b4a
title: Use Destructuring Assignment to Assign Variables from Nested Objects
challengeType: 1
videoUrl: ''
localeTitle: Use Destructuring Assignment para atribuir variáveis ​​de objetos aninhados
---

## Description
<section id="description"> Podemos similarmente desestruturar objetos <em>aninhados</em> em variáveis. Considere o seguinte código: <blockquote> const a = { <br> início: {x: 5, y: 6}, <br> end: {x: 6, y: -9} <br> }; <br> const {início: {x: startX, y: startY}} = a; <br> console.log (startX, startY); // 5, 6 </blockquote> No exemplo acima, a variável <code>start</code> recebe o valor de <code>a.start</code> , que também é um objeto. </section>

## Instructions
<section id="instructions"> Use a atribuição de desestruturação para obter o <code>max</code> de <code>forecast.tomorrow</code> e atribuí-lo a <code>maxOfTomorrow</code> . </section>

## Tests
<section id='tests'>

```yml
tests:
  - text: <code>maxOfTomorrow</code> é igual a <code>84.6</code>
    testString: 'assert(getMaxOfTmrw(LOCAL_FORECAST) === 84.6, "<code>maxOfTomorrow</code> equals <code>84.6</code>");'
  - text: desestruturação aninhada foi usada
    testString: 'getUserInput => assert(getUserInput("index").match(/\{\s*tomorrow\s*:\s*\{\s*max\s*:\s*maxOfTomorrow\s*\}\s*\}\s*=\s*forecast/g),"nested destructuring was used");'

```

</section>

## Challenge Seed
<section id='challengeSeed'>

<div id='js-seed'>

```js
const LOCAL_FORECAST = {
  today: { min: 72, max: 83 },
  tomorrow: { min: 73.3, max: 84.6 }
};

function getMaxOfTmrw(forecast) {
  "use strict";
  // change code below this line
  const maxOfTomorrow = undefined; // change this line
  // change code above this line
  return maxOfTomorrow;
}

console.log(getMaxOfTmrw(LOCAL_FORECAST)); // should be 84.6

```

</div>



</section>

## Solution
<section id='solution'>

```js
// solution required
```
</section>
