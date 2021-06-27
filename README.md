# animals-dogshow
<ul>
      <li>Adjective ending in "st": <input type="text" id="adjst1"></li>
      <li>Dog Breed: <input type="text" id="breed1"></li>
      <li>Food: <input type="text" id="food1"></li>
      <li>Verb: <input type="text" id="verb1"></li>
      <li>Verb:<input type="text" id="verb2"></li>
      <li>Food: <input type="text" id="food2"></li>
      <li>Verb: <input type="text" id="verb3"></li>
      <li>Dog Breed: <input type="text" id="breed2"></li>
      <li>Verb: <input type="text" id="verb4"></li>
      <li>Adjective ending in "st": <input type="text" id="adjst2"></li>
      <li>Food: <input type="text" id="food3"></li>
</ul>
    
<button id="clicker">Lib it!</button>
    
<p>Generated story: <span id = "story"></span> </p>

<script>
var clicker = document.getElementById("clicker")
var onlibitClick = function(){
    var adjst1 = document.getElementById("adjst1")
    var breed1 = document.getElementById("breed1")
    var food1 = document.getElementById("food1")
    var verb1 = document.getElementById("verb1")
    var verb2 = document.getElementById("verb2")
    var food2 = document.getElementById("food2")
    var verb3 = document.getElementById("verb3")
    var breed2 = document.getElementById("breed2")
    var verb4 = document.getElementById("verb4")
    var adjst2 = document.getElementById("adjst2")
    var food3 = document.getElementById("food3")
    var storyDiv = document.getElementById("story")
    story.innerHTML = "Every year, the local dog shelter hosts a dog show to find the " + adjst1 + " dog in the town. This time, I entered my " + breed1 + ", " + food1
+ ". I've trained him to " + verb1 + " and to " + verb2 + " on command. Every time he does a trick right, I give him a " + food2 + ". At the dog show, he ran out in front of the judges and started to " + verb3 + ". The crowd went wild and a big " + breed2 + " behind " + food1 + "started to " + verb4 + ". He didn't win the big prize, but he was awarded the prize for " + adjst2 + " in show. We got a HUGE trophy shaped like a " + food3 + ". I can't wait for the dog show next year!" 

}
clicker.addEventListener("click", onlibitClick)
</script>