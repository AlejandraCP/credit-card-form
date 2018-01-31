# Credit Card Form

## Identificación de funciones

#### Función global - Función Callback
~~~js
$(document).ready(function()
)};
~~~~  

#### Funciones Locales - Funciones Statement

~~~js

function activeButton()   
function desactiveButton()   
function longitud(input)  
function soloNumeros(input)  
function isValidCreditCard(numberCard)  
$inputCard.on('input', function() {
});
~~~

## Identificación de Variables


#### Variables locales dentro de evento ready
~~~js
var $inputCard
var $inputMonth
var $inputYear
var $buttonNext 
var regexOnlyNumbers
var labelErrorOrSuccessMessages
~~~

#### Variables locales dentro de función isValidCreditCard

~~~js
var creditCardNumber;
var arr;
var sumaTotal;
var index;
~~~  

## Stack Execution  

Inicia en linea 3

~~~js
console.log('Probar con el numero valido 4544164785372342'); 
function activeButton()  
function desactiveButton()  
function longitud(input)  
function soloNumeros(input)  
function isValidCreditCard(numberCard)  
~~~ 