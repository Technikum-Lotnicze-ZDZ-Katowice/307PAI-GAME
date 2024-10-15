# 307PAI-GAME
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <button onClick="mojaFunkcja()">Click</button>

    <script>
        function mojaFunkcja(){
            console.log('Kliknąłeś');
        }
    </script>
</body>
</html>
```


```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>    
    <script>
        window.onload = function () {

            const mybtn = document.querySelector('#btn1');
            
            mybtn.addEventListener('click',mojaFunkcja)
            
            function mojaFunkcja(){
                console.log('Kliknąłeś');
            }
        }
    </script>
</head>
<body>
    <button id="btn1">Click</button>
</body>
</html>
```

```js
            if(co === 'YES'){
                console.log('Kliknąłeś TAK');
            } else {
                console.log('Kliknąłeś NIE');
            }

//ternary operator

            let what = co === 'YES' ? 'TAK' : 'NIE';

            console.log('kliknąłeś', what);
```


```js
        const mojaTablica = [
            'Ala',
            'ma',
            'kota'
        ]
        function mojaFunkcja(){
            let = tekst = '';
            for(let i=0;i < mojaTablica.length;i++){
                tekst += mojaTablica[i];
                if(i < mojaTablica.length - 1){
                    tekst += ' ';
                } else {
                    tekst += '!';
                }
            }

            console.log(tekst);
        }
```
