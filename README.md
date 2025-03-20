## Máv utastájékoztatás
Ez a projekt egy **HTML** és **CSS** használatával a Máv-nál látható utastéjékoztatásra használt kijelzőkön látható táblázatokat jeleníti meg.

### 📌Funkciók
- 🎫Induló és érkező vonatok táblázatan ábrázolva
- 🚉A vonat célállomását és induló állomását is megjeleníti

### 🕹️ Használat
Egyszerűen nyisd meg a böngészőben ezt a linket https://diak008.github.io/2025_01_30_utastajekoztatas/ és élvezd a látványt.
 
#### ⚔️ Élő demó
A projekt megnyitható itt is: [Máv utastájékoztató](https://diak008.github.io/2025_01_30_utastajekoztatas/)

### 🌐 Alap HTML szerkezet
```html
<!DOCTYPE html>
<html lang="hu">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Máv éprkezőjáratok</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
<table>
    <thead>
        <tr>
            <th></th>
            <th></th>
            <th></th>
            <th></th>
            <th></th>
            <th></th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td></td>
            <td></td>
            <td></td>
            <td></td>
            <td></td>
            <td></td>
        </tr>
        <tr>
            <td></td>
            <td></td>
            <td></td>
            <td></td>
            <td></td>
            <td></td>
        </tr>
        <tr>
            <td></td>
            <td></td>
            <td></td>
            <td></td>
            <td></td>
            <td></td>
        </tr>
        <tr>
            <td></td>
            <td></td>
            <td></td>
            <td></td>
            <td></td>
            <td></td>
        </tr>
        <tr>
            <td></td>
            <td></td>
            <td></td>
            <td></td>
            <td></td>
            <td></td>
        </tr>
    </tbody>
</table>
    
    <a href="index_2.html">Induló járatok</a>
</body>
</html>
```

#### 🌍Alap CSS szerkezet
```CSS
table {
    border: 10px solid;
    background-color: darkblue;
    color: rgb(255, 191, 96); 
    /* betűszín */
    font-family: 'Courier New', Courier, monospace;
    /* betűstílus */
    font-size: 30px;
    /* betűméret */
    border-color: black;
  }
  ```