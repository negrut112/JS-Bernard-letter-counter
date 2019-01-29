# JS-Bernard-letter-counter

<p>Bernard is a bot that can count a specific letter from a wrote sentence.</p>
<p>I invite you to see how it works on: <a href="https://negrut112.github.io/JS-Bernard-letter-counter/">https://negrut112.github.io/JS-Bernard-letter-counter/</a> press F5 to repeat.</p>
<img src="https://i.imgur.com/dioUeL3.jpg">
## JavaScript

<p>I made a <b>function</b> that is asking for a sentence to analise using the <b>prompt</b> command that is stored in a <b>var</b> named <i>askfor</i> and asking for the letter who would you like to count using same method.<br>
  
I declared a <b>var</b> named <i>letter</i>, wich will be our “letter counter”.</p>

<pre><code>function bernardTheLetterCounter () {<br>
var askfor = prompt(‘Write a sentence to analise.’);<br>
var freq = prompt(‘The frequency of wich letter would you like to count?’);<br>
var letter = 0;</pre></code>

<p>Below we have an if condition inside a for loop that’s giving us the length of the sentence from where we extract the letter to count. After this letter++ comand will loop as many times, the asked letter appears.</p>

<pre><code>for (i = 0; i &lt;= askfor.length; i++) {<br>
if (askfor.charAt(i) == freq ) {<br>
letter++;<br>
 };<br>
};</pre></code>

<p>Alert comand will display the following string:</p>
<pre><code>alert(‘The letter ’ + freq + ’ appears ’ + letter + ’ times in this sentence.’);<br>
return; // closing the loop<br>
};<br>
bernardTheLetterCounter(); // run the function</pre></code>
