# Einstein-AI Code examples
Antes de poder desplegar estos fuentes, seguir los siguientes pasos en la org:

Activar Einstein desde Setup > Einstein
Activar Copilot : Setup > Einstein Copilots : On


Caso de uso 2 - OBtener nombre de ciudad a partir de zipcode: 
Ejecutar de forma anónima: 
list<integer> zipcode = new List<integer>{29400};
System.debug('Ciudad: '+ZipCodeName.getCityForZipCode(zipcode));

1. Creacion de copilot action sobre apex Class ZipCodeName
    1.1 Informar input y output instructions:
   
        1.1.1 Input: the zipcode value for which city name needs to be find
   
        1.1.2 Output: Show the name of the city to the user
   
    1.2 Seleccionar required input para la entrada y show in conversation para la salida
