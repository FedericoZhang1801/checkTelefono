# checkTelefono
Esercizio checkTelefono

L'esercizio richiede, dati più numeri telefonici in entrata (possibilmente errati) di restituire quello corretto

ho usato delle substring e mi sono servito del metodo .StartsWith per appunto verificare se i numeri telefonici avessero il prefisso corretto

```
        string substringA = "+39";    //dichiarazione substring
        string substringB = "3";
        string substringC = "0039";
```
```
if( stringLength == 10 )          //verifico length e controllo se il numero telefonico ha il prefisso giusto
        {
            if (input.ToString().StartsWith(substringB))
            return numero;
        }
```
