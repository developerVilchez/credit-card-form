## Funciones globales: 1
#### función global con respecto al contexto de ejecución document y con respecto al contexto de ejecución window es una función local.
* funcion anónima:
$(document).ready(function() {};

## Variables globales: 6
##### con respecto al contexto de ejecución document, siendo locales para el contexto de ejecución global del objeto window
* $inputCard
* $inputMonth
* $inputYear
* $buttonNext
* regexOnlyNumbers
* labelErrorOrSuccessMessages

## Funciones locales: 5
* function activeButton() {}
* function desactiveButton() {}
* function longitud(input) {}
* function soloNumeros(input) {}
* function isValidCreditCar(numberCard){}
### Funciones callback:
* isValidCreditCard($(this).val().trim());
* activeButton();
* desactiveButton();
### Expresions statement:

### Clousure:
* var arr = [];
* var sumaTotal = 0;
### Scope:
* $(document).ready(function() {};
* $inputCard.on('input', function() {}
* function activeButton() {}
* function desactiveButton() {}
* function longitud(input) {}
* if (input.trim().length === 16) {}
* function soloNumeros(input) {}
* if (regex.test(input)) {}
* function isValidCreditCard(numberCard) {}
* if (creditCardNumber !== undefined) {}
* for (var index = creditCardNumber.length - 1; index >= 0; index--) {}
* for{} arr[index] = arr[index] * 2;
* if{} arr[index] = arr[index] - 9;
* for{} sumaTotal = sumaTotal + parseInt(arr[index]);
* if{}  console.log('Es una tarjeta valida');
* else{} console.log('No es un numero valido');
* console.log('Verifique el numero de su tarjeta'); 



## Contextos de ejecucion:
##### Hay dos contextos de ejecución 
* Entorno de contexto de ejecución del Obejto Windows.
* Entorno de contexto de ejecución del Document.


### Funciones que forman parte de la PILA:
* function longitud(input) {}
* function soloNumeros(input) {} 
### Funciones que forman parte de la COLA:
* activeButton();
* desactiveButton();
* function isValidCreditCard(numberCard) 
