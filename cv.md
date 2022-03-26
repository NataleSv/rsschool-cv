# Natalia Sorokina

 *Junior Frontend Developer*
<hr>

## *Contacts*

Telegram: NataleSv  
github: [NataleSv](https://github.com/NataleSv)  
discord: NataleSv#6370  


## *Education*

### University

2010 - 2015  
Marketing  
***Nizhny Novgorod State University of Architecture, Building and Civil Engineering (NNSUABCE or NNGASU)***  

### Courses

2020 - 2021  
Development and Promotion of Web Projects  
***Computer Academy STEP***  

2021  
Basics of frontend development  
***Innopolis University***  


## *Skills*
- Git
- HTML5
- CSS3, SASS/SCSS
- Bootstrap
- JavaScript
- React
- PHP 
- Laravel 
- SQL 

- *VS Code, IntelliJ IDEA, Figma, Adobe Photoshop, Illustrator, Adobe XD*


## *Languages*
 - Russian - native speaker
 - English - A2 (B1 in process)


## *Code example*

```
let color = document.getElementById('color').value;
let span = document.getElementsByClassName('span');
let arr = [];
let regexp = /^([a-z]+)$/i; 

if (arr.includes(color)) {  
         message(span[0], 'already exists')
      } else if (validate(regexp, color)) {
         message(span[0], '')
      } else {
         message(span[0], 'use latin letters')
      }
      
function validate(regexp, inp) {
   return regexp.test(inp);
}

function message( el, mess) {
   el.innerHTML = mess;
}
```
