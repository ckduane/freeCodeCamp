---
id: bad87fee1348bd9aec908848
title: Create Bootstrap Wells
challengeType: 0
videoUrl: ''
localeTitle: Создать бутстрап-колодцы
---

## Description
<section id="description"> У Bootstrap есть класс, который называется <code>well</code> который может создать визуальное ощущение глубины для ваших столбцов. Гнездо один <code>div</code> элемент с классом <code>well</code> в каждом из ваших <code>col-xs-6</code> <code>div</code> элементов. </section>

## Instructions
undefined

## Tests
<section id='tests'>

```yml
tests:
  - text: Добавьте <code>div</code> элемент с классом <code>well</code> внутри каждого из <code>div</code> элементов с классом <code>&quot;col-xs-6&quot;</code>
    testString: 'assert($("div.col-xs-6").not(":has(>div.well)").length < 1, "Add a <code>div</code> element with the class <code>well</code> inside each of your <code>div</code> elements with the class <code>"col-xs-6"</code>");'
  - text: ''
    testString: 'assert($("div.row > div.col-xs-6").length > 1, "Nest both of your <code>div</code> elements with the class <code>"col-xs-6"</code> within your <code>div</code> element with the class <code>"row"</code>.");'
  - text: ''
    testString: 'assert(code.match(/<\/div>/g) && code.match(/<div/g) && code.match(/<\/div>/g).length === code.match(/<div/g).length, "Make sure all your <code>div</code> elements have closing tags.");'

```

</section>

## Challenge Seed
<section id='challengeSeed'>

<div id='html-seed'>

```html
<div class="container-fluid">
  <h3 class="text-primary text-center">jQuery Playground</h3>
  <div class="row">
    <div class="col-xs-6">

    </div>
    <div class="col-xs-6">

    </div>
  </div>
</div>

```

</div>



</section>

## Solution
<section id='solution'>

```js
// solution required
```
</section>
