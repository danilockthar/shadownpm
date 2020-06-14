# what is this   

Inserta sombras en las imagenes.

# installation

`npm i --save shadowMonster` 

Then ...

```
import {shadowMonster} from 'shadowMonster';

shadowMonster({
    shadow_type: 'soft',
    padding: true
});
```
## options

shadowMonster soporta dos parametros opcionales:

* *shadow_type* - _hard | soft_ (Default to soft)
* *padding* - _boolean_ (Default to false)