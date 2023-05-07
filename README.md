Download Link: https://assignmentchef.com/product/solved-lab-3
<br>
<ol>

 <li>Inside <strong>lab3.js</strong>, you will <strong>export</strong> a class named <strong>lab3</strong>. In this class you will implement the following functions:</li>

 <li><strong>testDefaultParamters</strong>The function takes <strong>two parameters</strong>, and the <strong>second parameter is</strong> <strong>defaulted to 100</strong></li>

 <li>The function returns a <strong>json</strong> object containing two attributes: ‘<strong>first’</strong> and ‘<strong>second’</strong>The<strong> ‘first’ attribute</strong> of the return object is defined as the<strong> first parameter </strong>of the function</li>

 <li>The ‘<strong>second’ attribute</strong> of the return object is defined as the <strong>second parameter</strong> of the function</li>

 <li><strong>testTemplateLiterals</strong>The function takes <strong>three parameters</strong>, a <strong>firstName</strong>, <strong>middleName</strong>, and <strong>lastName</strong></li>

 <li>The function returns a string with the <strong>three parameters separated by commas</strong>The parameters should be concatenated using ES6 string templates, not ES5 string addition!</li>

 <li><strong>testMultilineStrings</strong>The function takes <strong>no parameters</strong></li>

 <li>The function returns a <strong>multi-line string that is at least 4 lines long</strong>The content of the string is up to you!</li>

 <li><strong>testSortWithArrowFunction</strong>The function takes an <strong>array of numbers as a parameter</strong></li>

 <li>The function returns the <strong>array sorted with a custom comparator</strong> that sorts the numbers <strong>descending</strong></li>

 <li>Use the .sort function of the array and pass in a custom comparatorThe comparator should be implemented as an arrow function using ES6 syntax</li>

</ol>

<pre class="ql-syntax"><span class="hljs-class"><span class="hljs-keyword">class</span> <span class="hljs-title">lab3</span></span>{    <span class="hljs-function"><span class="hljs-keyword">function</span> <span class="hljs-title">testDefaultParamters</span>(<span class="hljs-params">a,b=<span class="hljs-number">100</span></span>)</span>{      <span class="hljs-keyword">return</span>  json={      <span class="hljs-string">'first'</span>:a         <span class="hljs-string">'second'</span>:b};}    <span class="hljs-function"><span class="hljs-keyword">function</span> <span class="hljs-title">testTemplateLiterals</span>(<span class="hljs-params">firstName,middleName,lastName</span>)</span>{      <span class="hljs-keyword">return</span> myName=<span class="hljs-string">'${firstName},${middleName},${lastName}'</span>;}    <span class="hljs-function"><span class="hljs-keyword">function</span> <span class="hljs-title">testMultilineStrings</span></span>{  <span class="hljs-keyword">return</span>   mySpell= <span class="hljs-string">`Uh-bare-toe.   AK-ee-oh.   AH-gwah-MEN-tee.   A-LAR-tey.`</span>;}<span class="hljs-function"><span class="hljs-keyword">function</span> <span class="hljs-title">testSortWithArrowFunction</span>(<span class="hljs-params">a</span>)</span>{ <span class="hljs-keyword">return</span> a.sort(<span class="hljs-function">(<span class="hljs-params">m,n</span>)=&gt;</span>n-m);}}<span class="hljs-keyword">export</span> {lab3}</pre>