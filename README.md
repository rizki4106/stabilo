# stabilofont
stabilofont merupakan sebuah package python yang berfungsi untuk memberikan warna, bakcground ataupun style pada teks python yang berjalan di terminal / cmd.
Saat kita mengembangkan sebuah program kadang kala kita perlu menandai informasi penting yang kita perlukan oleh karena itu saya mengembangkan
<b>stabilofont</b> ini untuk mempermudah kalian dan juga saya dalam mengembangkan sebuah program

<h3>Dokumentasi</h3>
Untuk menggunakan package ini pertama - tama kalian harus memastikan bahwa python yang kalian gunakan sudah versi >= 3.0 karena
package ini hanya berfungsi pada python versi <b>>= 3.0</b>, Setelah memastikan bahwa python kalian sudah memenuhi syarat ketikan perintah dibawah ini
<pre>
pip3 install stabilofont
//## disarankan install versi ketiga
pip3 install stabilofont==0.3
</pre>

setelah setelah selesai silahkan masukan ke dalam <b>root</b> folder dari project kalian kemudian import dengan cara sebagai berikut
<pre>
//#file main.py
from stabilofontfont import *
...
</pre>

untuk menggunakannya cukup mudah yakni kalian hanya tinggal Menuliskan nama warna yang kalian inginkan perhatikan contoh dibawah ini

<pre>
//## main.py

from stabilofont import *

kata = Blue("Awesome")
print(kata)
</pre>
<br/>
<h3>List Warna</h3>
<ol>
  <li>Hitam => Black(<i>parameters</i>)</li>
  <li>Merah => Red(<i>parameters</i>)</li>
  <li>Hijau => Green(<i>parameters</i>)</li>
  <li>Biru => Blue(<i>parameters</i>)</li>
  <li>Kuning => Yellow(<i>parameters</i>)</li>
  <li>Ungu => Purple(<i>parameters</i>)</li>
  <li>Cyan => Cyan(<i>parameters</i>)</li>
  <li>Putih => White(<i>parameters</i>)</li>
</ol>

<br/>
Selain contoh diatas kalian juga bisa mengkombinasikannya dengan style lain seperti <b>bold</b>
<br/>
<pre>
from stabilofont import *

input = str(input("Apa pendapatmu tentang bahasa python ? : "))

print(Bold(Blue(input)))
</pre>

bukan hanya itu <b>stabilofont</b> ini juga mampu memberikan background pada text yang diinginkan berikut contohnya

<pre>
//## main.py

from stabilofont import *

kata = bgGreen(Blue("Awesome"))
print(kata)
</pre>
<h3>List Background</h3>
<ol>
  <li>Hitam => bgBlack(<i>parameters</i>)</li>
  <li>Merah => bgRed(<i>parameters</i>)</li>
  <li>Hijau => bgGreen(<i>parameters</i>)</li>
  <li>Biru => bgBlue(<i>parameters</i>)</li>
  <li>Kuning => bgYellow(<i>parameters</i>)</li>
  <li>Ungu => bgPurple(<i>parameters</i>)</li>
  <li>Cyan => bgCyan(<i>parameters</i>)</li>
  <li>Putih => bgWhite(<i>parameters</i>)</li>
</ol>
<br/>
Tidak cukup hanya sampai disini <b>stabilofont</b> ini juga mampu memberikan teks dengan hasil tebal, warna custom dan juga terdapat warna background berikut contohnya
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


