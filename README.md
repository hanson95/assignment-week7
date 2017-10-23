# assignment-week7

Hanson Cress
10/22/2017


Exploits in the 4.2 version of wordpress
1.
XSS vulneralbility
the first vulneralbility I found was in the reply box on a post where a hacker could inject a script into the text box.
Patched in 4.2.1
To do this attack use the <script></script> tags inside the text box
gif: https://imgur.com/a/57J4s

2.
XSS vulneralbility
the next vulneralbility i found was when you upload somethign to the site in the description of the file you can inject
script code in the title and when you try to create the title it executes.
Patched in 4.2.1
to do this attack place your <script> in the title of an uploaded item.
gif: https://imgur.com/a/G6uo1

3.
XSS vulneralbility
the last one i found was when you upload a file and change the title of the file to be a malicious script and save the file.The script will execute. This attack is similiar to #2 but this one is in the title of a file.
patched in 4.2.1
to do this attack place you <script> in the title of an uploaded item.
gif: https://imgur.com/a/CLMmA



