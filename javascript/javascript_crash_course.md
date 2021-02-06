
# Javascript Basics Crash Course for Beginners 


## background 
you just need to know html and css to style up a page to utilize them to change the effects or the appearance of things on a webpage 
you swatted on those two areas it is time to get cracking with javascript 


html -- controls the structure of your website 
css -- controls the presentation/design 
javascript -- adds behaviours and interactivity 


javascript is a scripting language 
intentionally limited 
does not have the same features as other programming languages 
cannot communicate directly with a database , or file system on a computer, 
however its intended purpose is great at manipulating webpages 


javascript is a client side language 
client/browser <- server 
html/css/js.      php 

do not rely on javascript 
javascript should enhance your audience's experience only 
do not rely on js to add core functionality to your website 
the official name of js is ECMAscript, jumped on that bandwagon 


embed javascript into html web page 
annoying pop-up box 
```javascript 
<script>
window.alert("hello");

</script>
``` 
they have been putting javascript for a long time, it is a big step up, the learning curve is not that steep , introduce yourself softly into js 



## where to put your javascript? 

just paste at the bottom of your content before the closing body tag in some circumstance you are going to find links at the top here and there are occassions when that is absolutely find when the javascript is asynchronous and it loads in conjunction with your html page 


you put it in an external file so it does not meess up your content page in your html 

it is neater and it keeps things in a logical place 

link that file to the external file 
```javascript
<script src="xxx.js"> </script>
```
externalize it and put it in separate file and then link that file at the bottom of the page using script reference 




### google chrome developer tools 

right click -> resources 
console tab -> We can type in javascript in the browser so it can test things out , it can throw errors that it may have when it comes to js 



### syntax 

it is beneficial before we write any code 
1 javascript is case sensitive , case sensitive 
```javascript 
function myFunction(){}
myFunction();

```
2 statement ends with semicolon 
carried on now technically speaking 

3 whitespace is not sensitive generally they are performanicing the same tasks 

4 comments similar to css, ```javascript //   /*  */```

5 run from top to bottom follow particular order 

### variable 
1 they can contain letters, numbers underscores 
2 have a specific naming contention 
3 we do not have to specify the type of the variable when we initalize it 


outdated: 
```javascript 
var Variable = value;
console.log(Variable);
```
we can change value or type of variables , name your variable in logical way 
this is what is known dynamic types , in other languages, you will have to specify the types of variable when you initialize it 
the takeaway points are that we initalize variables with the var keyword and we can set them to empower you in the same statement 

I would advise you not to do that !!!!! 




### mathematical operators 
= + - / * 





```javascript 
4 * "hello"
NaN
```
this makes no sense so javascript returns a NaN
javascript concatenates strings with numeric values or strings 
you can only do is add a number to a string and that is concatenate 

```javascript 
value + 2
3
value + 5 
6
value * 3 
3
value - 2 
-1
value / 2 
0.5
value % 2 
1

```



### mathmatical shorthand methods 
= + - / * 
```javascript 
var value = 3; 
value += 2;
5
value -= 2;
3
value *= 2;
6
value /= 2;
3
value %/ = 2
value %= 2;
1
var value = 3;
value + "hello";
"3hello"
```


### logging to the console 
show you a couple of techniques that are used to test certain things including writing message or variables or values to console 
write out to the document 

```javascript 
var value = 100;
document.write(value);
console.log(value);
```

these two different ways of writing the console 



### booleans 
a boolean is a value either represents true or false 
it is used to evaluate certain circumstances 

```javascript 
var value = true;
console.log(value);
```
















