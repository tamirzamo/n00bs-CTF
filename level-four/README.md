so the hint is "HTTP means Hypertext Transfer Protocol"</br>
so in curl manpage https://curl.haxx.se/docs/manpage.html.</br>
we see curl -I gives the http header.</br>
![alt text](  https://github.com/tamirzamo/n00bs-CTF/blob/master/level-four/4a.png  )

then you get the header and see a suspicious cookie. </br>

 then need to decrypt the coockie content with https://www.dcode.fr/rot-13-cipher and get the flag.</br>
![alt text](  https://github.com/tamirzamo/n00bs-CTF/blob/master/level-four/4b.png  )
