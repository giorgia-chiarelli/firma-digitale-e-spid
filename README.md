<!--
author:   Giorgia Chiarelli, Rabia Akter, Ommyshahbe Ali,Luo Kaishan


email:    giorgia.chiarelli@savoiabenincasa.it      rabia.akter@savoiabenicasa.it     ommyshahbe.ali@savoiabenincasa.it     kaishan.luo@savoiabenincasa.it


version:  0.0.1


language: it


narrator: IT italian femmine


comment:  


-->


# La firma digitale


La firma digitale è l'equivalente della firma scritta su carta ed ha pari valore legale. 



![](https://www.altalex.com//~/media/Images/Lex/Informatica/firma-digitale%20jpg.jpg)


![](https://trasformazionedigitale.bit4id.com/wp-content/uploads/2023/02/firma-digitale-remota.jpg)

## Cos'è lo SPID


__SPID__ (Sistema Pubblico per la gestione dell’Identità Digitale):
framework per la gestione dell’Identità Digitale e viene utilizzato per ilo riconoscimento della frima digitale. 
Il framework facilita lo sviluppo del software. 


__Utenti__, sono persone fisiche giuridiche che sono associate a uno o piùaccounbtcontenenti informazioni personali.
__Identity Provider__ (IdP), creano e gestiscono gli account e sono dei soggetti pubblici.
__Attribute Authorities__ (o Provider),persone con il compito di certificare.
__Service Provider__ (SP), organizzazioni pubbliche o private che forniscono un servizio agli utenti utilizzati
un servizio agli utenti autorizzati.
__ Una terza parte fidata__ (TTP), garantisce i livelli standard di sicurezza richiesti dallo SPID.




Lo SPID è stato inventato per servizzi che hanno diversi livelli di criticità. 

In base al tipo di sevizio si può richiedere l'autenticazione didiverso livello. 

Abbiamo 3 livelli di robustezza, SPIDL1, SPIDL2, SPIDL3. 

## Markdown


You can use common [Markdown](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet) syntax to create your course, such as:


1. Lists
2. ordered or


   * unordered
   * ones ...




| Header 1   | Header 2   |
| :--------- | :--------- |
| Item 1     | Item 2     |




Images:


![images](https://farm2.static.flickr.com/1618/26701766821_7bea494826.jpg)




### Extensions


     --{{0}}--
But you can also include other features such as spoken text.


      --{{1}}--
Insert any kind of audio file:


       {{1}}
?[audio](https://bigsoundbank.com/UPLOAD/mp3/1068.mp3)




     --{{2}}--
Even videos or change the language completely.


       {{2-3}}
!?[video](https://www.youtube.com/watch?v=bICfKRyKTwE)




      --{{3 Russian Female}}--
Первоначально создан в 2004 году Джоном Грубером (англ. John Gruber) и Аароном
Шварцем. Многие идеи языка были позаимствованы из существующих соглашений по
разметке текста в электронных письмах...




    {{3}}
Type "voice" to see a list of all available languages.




### Styling


<!-- class = "animated rollIn" style = "animation-delay: 2s; color: purple" -->
The whole text-block should appear in purple color and with a wobbling effect.
Which is a **bad** example, please use it with caution ...
~~ only this is red ;-) ~~ <!-- class = "animated infinite bounce" style = "color: red;" -->


## Charts


Use ASCII-Art to draw diagrams:


                                    Multiline
    1.9 |    DOTS
        |                 ***
      y |               *     *
      - | r r r r r r r*r r r r*r r r r r r r
      a |             *         *
      x |            *           *
      i | B B B B B * B B B B B B * B B B B B
      s |         *                 *
        | *  * *                       * *  *
     -1 +------------------------------------
        0              x-axis               1


## Quizzes




### A Textquiz


What did the **fish** say when he hit a **concrete wall**?


    [[dam]]


### Multiple Choice


Just add as many points as you wish:


    [[X]] Only the **X** marks the correct point.
    [[ ]] Empty ones are wrong.
    [[X]] ...


### Single Choice


Just add as many points as you wish:


    [( )] ...
    [(X)] <-- Only the **X** is allowed.
    [( )] ...


## Executable Code


A drawing example, for demonstrating that any JavaScript library can be used, also for drawing.


```javascript
// Initialize a Line chart in the container with the ID chart1
new Chartist.Line('#chart1', {
  labels: [1, 2, 3, 4],
  series: [[100, 120, 180, 200]]
});


// Initialize a Line chart in the container with the ID chart2
new Chartist.Bar('#chart2', {
  labels: [1, 2, 3, 4],
  series: [[5, 2, 8, 3]]
});
```
<script>@input</script>


<div class="ct-chart ct-golden-section" id="chart1"></div>
<div class="ct-chart ct-golden-section" id="chart2"></div>




### Projects


You can make your code executable and define projects:


``` js     -EvalScript.js
let who = data.first_name + " " + data.last_name;


if(data.online) {
  who + " is online"; }
else {
  who + " is NOT online"; }
```
``` json    +Data.json
{
  "first_name" :  "Sammy",
  "last_name"  :  "Shark",
  "online"     :  true
}
```
<script>
  // insert the JSON dataset into the local variable data
  let data = @input(1);


  // eval the script that uses this dataset
  eval(`@input(0)`);
</script>


## More


Find out what you can even do more with quizzes:


https://liascript.github.io/course/?https://raw.githubusercontent.com/liaScript/docs/master/README.md
https://liascript.github.io/LiveEditor/?/edit/BDHWYDYCWAOySVkPYW7TNGDI


