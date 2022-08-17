# one-line-of-code

## Responsive Font size using css

1rem = 16px so we make it to 1rem = 10px <br /> 
how to do it see below: <br />
### Solution:<br />
Convert px into % <br />
100% = 16px <br />
if 1px = 6.25% <br />
then 10px = 62.5% 
<br /><br />
=> font-size: 62.5%; | 10px | 1rem  
therefore <br />
html{ font-size: 62.5%; } <br />
now use px to rem on everywhere of website then see the result and chill...<br /><br />

### For medium devices<br />
@media(max-width:998px){<br />
html{
font-size: 55%: | 8.8px
}<br />
}<br /><br />
### For mobile <br />
@media(max-width:768px){<br />
html{
font-size: 45%; | 7.2px
}<br />
}
