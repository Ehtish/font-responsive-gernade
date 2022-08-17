# one-line-of-code

Responsive font size
<br />
1rem = 16px so we make it to 1rem = 10px 

how to do it see below:
<br />
step1: convert px into % 100% = 16px
1px = 6.25%
then 	10px = 62.5%

font-size 62.5%; | 10px | 1rem 
therefore
html{
font-size: 62.5%;
}

now use px to rem on everywhere of website then see the result and chill...
 
@media(max-width:998px){
html{
font-size: 55%; | 8.8px
}
}
@media(max-width:768px){
html{
font-size: 45%; | 7.2px
}
}
