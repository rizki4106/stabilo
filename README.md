# stabilofont
stabilofont is a python package that serves to provide color, bakcground or style to python text that runs on the terminal / cmd.
When we develop a program sometimes we need to mark important information that we need, so I develop it
<b>stabilofont</b> is to facilitate you and me in developing a program

<h3>Documentation</h3>
To use this package you must first ensure that the python you are using is version> = 3.0 because
This package only works with python version <b> >= 3.0 </b>, after making sure that your python meets the requirements for typing below.
<pre>
pip3 install stabilofont
//## recommended install v0.3 version
pip3 install stabilofont==0.3
</pre>

after completing it please enter into the <b> root </b> folder of your project then import it as follows
<pre>
//#file main.py
from stabilofontfont import *
...
</pre>

to use it is quite easy, you just need to write down the name of the color you want, consider the example below

<pre>
//## main.py

from stabilofont import *

kata = Blue("Awesome")
print(kata)
</pre>
<br/>
<h3>List Colors</h3>
<ol>
  <li>Black=> Black(<i>parameters</i>)</li>
  <li>Red => Red(<i>parameters</i>)</li>
  <li>Green => Green(<i>parameters</i>)</li>
  <li>Blue => Blue(<i>parameters</i>)</li>
  <li>Yellow => Yellow(<i>parameters</i>)</li>
  <li>Purple => Purple(<i>parameters</i>)</li>
  <li>Cyan => Cyan(<i>parameters</i>)</li>
  <li>White => White(<i>parameters</i>)</li>
</ol>

<br/>
Besides the example above, you can also combine it with other styles such as <b>bold</b>
<br/>
<pre>
from stabilofont import *

input = str(input("Apa pendapatmu tentang bahasa python ? : "))

print(Bold(Blue(input)))
</pre>

not only that <b> stabilofont </b> is also able to provide the desired background text for the following examples

<pre>
//## main.py

from stabilofont import *

kata = bgGreen(Blue("Awesome"))
print(kata)
</pre>
<h3>List Background</h3>
<ol>
  <li>Black => bgBlack(<i>parameters</i>)</li>
  <li>Red => bgRed(<i>parameters</i>)</li>
  <li>Green => bgGreen(<i>parameters</i>)</li>
  <li>Blue => bgBlue(<i>parameters</i>)</li>
  <li>Yellow => bgYellow(<i>parameters</i>)</li>
  <li>Purple => bgPurple(<i>parameters</i>)</li>
  <li>Cyan => bgCyan(<i>parameters</i>)</li>
  <li>White => bgWhite(<i>parameters</i>)</li>
</ol>
<br/>
It's not enough just to get here <b> stabilofont </b> is also able to provide text with bold results, custom colors and also the following background colors for example
<br/>

<pre>
//## main.py

from stabilofont import *

kata = bgPurple(Bold(Blue("Awesome")))
print(kata)
</pre>


<br/>
<hr/>
available for works <b>email</b> : rizkimaulana348@gmail.com


