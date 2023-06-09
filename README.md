# CJ Scott - Midterm
My name is Ian C.J. Scott. I'm a Junior majoring in Economics and History and minoring in Political Science, Constitutional Democracy, and Ancient Mediterranean Studies. I'm taking this class as an elective for Economics. I love apple pie and butter pecan ice cream. I have an Xbox Series X and a PC. I built my pc exactly 3 years ago this time in 2020 and I built it primarily to play [Mount and Blade II: Bannerlord](https://www.taleworlds.com/en/Games/Bannerlord/) at the time. I now play a massive whole heap of games
 
I'm a massive _Game of Thrones_ Fan and for my midterm project I wanted to do something fun. So I decided to do a summary of the War of the 5 Kings from the perspective of the Books.

![Lord Robert Baratheon and Prince Rhaegar Targaryen at the Trident](https://th.bing.com/th/id/R.b3d5752d5dc8cd2706071c11800c9187?rik=6gjlIlU3hm4XyQ&riu=http%3a%2f%2fimages2.fanpop.com%2fimages%2fphotos%2f3400000%2fRobert-vs-Rhaegar-a-song-of-ice-and-fire-3420624-936-685.jpg&ehk=LdRQcZHJpaHuyBpx9URZqRXdOIga26laRFifPes5odk%3d&risl=&pid=ImgRaw&r=0)
## **Lord Robert Baratheon and Prince Rhaegar fighting at the Battle of the Trident 283 A.C.**
# The War of the Five Kings - Context
>_“When you play the game of thrones, you win or you die.” - Cersei Lannister_  
>
  >The year is 297 A.C. It has been 14 years since [Robert's Rebellion.](https://awoiaf.westeros.org/index.php/Robert%27s_Rebellion) [Jon Arryn](https://awoiaf.westeros.org/index.php/Jon_Arryn) Hand of the King and Lord of the Vale has been assassinated. For 14 years bar the [Greyjoy Rebellion](https://awoiaf.westeros.org/index.php/Greyjoy%27s_Rebellion), there has been peace. In the following year 298, A.C. [King Robert](https://awoiaf.westeros.org/index.php/Robert_I_Baratheon) traveled to The North to ask his friend [Lord Eddard Stark](https://awoiaf.westeros.org/index.php/Eddard_Stark) to be the new Hand of the King. At [Winterfell](https://awoiaf.westeros.org/index.php/Winterfell), [Bran Stark](https://awoiaf.westeros.org/index.php/Bran_Stark) son of Eddard has a mysterious accident and tensions begin to boil between Lannisters and Starks. Eddard (Ned) Stark acceps King Robert's offer and travels south to the capital, Kings Landing to assume his position as Hand of the King. Upon reaching the capital, Ned immediately begins investigating the death of Jon Arryn and arrives at two conclusions: Jon Arryn was likely murdered and that King Robert’s legitimate children, [Joffrey](https://awoiaf.westeros.org/index.php/Joffrey_Baratheon), [Myrcella](https://awoiaf.westeros.org/index.php/Myrcella_Baratheon) and [Tommen](https://awoiaf.westeros.org/index.php/Tommen_Baratheon) are illegitimate children. King Robert’s children were born of [Queen Cersei's](https://awoiaf.westeros.org/index.php/Cersei_Lannister) twin brother Ser [Jaime Lannister](https://awoiaf.westeros.org/index.php/Jaime_Lannister). Once Ned realizes this truth he warns Queen Cersei out of a sense of honor and for the security of her children. Cersei ignores Ned’s warning and has King Robert killed before anything could happen. Cersei swiftly crowns her son Joffery, as king. Ned protests this, as [Stannis Baratheon](https://awoiaf.westeros.org/index.php/Stannis_Baratheon), Robert’s younger brother, is the rightful monarch. Ned is imprisoned and eventually executed, sparking war between the Lannisters and the Starks. Stannis seeking his rightful throne, declares his claim for the throne. [Renly Baratheon](https://awoiaf.westeros.org/index.php/Renly_Baratheon), younger brother of Robert and Stannis declares his claim and allies with the [Tyrells](https://awoiaf.westeros.org/index.php/House_Tyrell). Sensing unease, [Balon Greyjoy](https://awoiaf.westeros.org/index.php/Balon_Greyjoy) declares himself King again and revolts against the Iron throne. [Robb Stark](https://awoiaf.westeros.org/index.php/Robb_Stark), son of Ned declares himself King of the North and Westeros finds itself at war once again. 

## **The Five Kings**
* [King Joffery Baratheon](Joffery.md)
* [King Robb Stark](Robb.md)
* [King Stannis Baratheon](Stannis.md)
* [King Renly Baratheon](Renly.md)
* [King Balon Greyjoy](Balon.md)


[Here is your image](https://www.bing.com/images/search?view=detailV2&ccid=TnjQfLo3&id=32441C46D7AEA509D32103FE7E4FBF76B960EB11&thid=OIP.TnjQfLo3KVxqcg4-7tbNqgHaEK&mediaurl=https%3a%2f%2fi.ytimg.com%2fvi%2faBP3Fv0zpa4%2fmaxresdefault.jpg&cdnurl=https%3a%2f%2fth.bing.com%2fth%2fid%2fR.4e78d07cba37295c6a720e3eeed6cdaa%3frik%3dEetguXa%252fT37%252bAw%26pid%3dImgRaw%26r%3d0&exph=720&expw=1280&q=rick+rolled&simid=608013876208301294&FORM=IRPRST&ck=6596E1DE2A6FF348FDB4E92F73AAAD29&selectedIndex=2&ajaxhist=0&ajaxserp=0)

Here lies your code
<!DOCTYPE html>
<html>
<head>
<meta charset="UTF-8">
<title>Fizz Buzz</title>
<script>

function fizzbuzz() {
	var display = document.getElementById('display');
	var displayHTML = "";
	for (i = 0; i < 100; i++) {
		displayHTML += "<p>" + i + "</p>";
	}
	display.innerHTML = displayHTML
}
function fizzbuzz() {
  var display = document.getElementById('display');
  var divisible = "";
  var displayHTML = "";

  for (i = 1; i < 101; i++) {
    if (i % 3 === 0 && i % 5 === 0) {
      divisible = "FizzBuzz";
    } else if (i % 5 === 0) {
      divisible = "Buzz";
    } else if (i % 3 === 0) {
      divisible = "Fizz";
    } else {
      divisible = "";
    }

    displayHTML += "<p>" + i + ":" + divisible + "</p>";
  }
  display.insertAdjacentHTML('afterend', displayHTML); 
}

fizzbuzz();
</script>

</head>

<body onload="fizzbuzz()">
<div id="display">

</div>
</body>

</html>
