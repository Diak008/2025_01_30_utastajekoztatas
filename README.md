## Máv utastájékoztatás
Ez a projekt egy **HTML** és **CSS** használatával a Máv-nál látható utastéjékoztatásra használt kijelzőkön látható táblázatokat jeleníti meg.

### 📌Funkciók
- 🎫Induló és érkező vonatok táblázatan ábrázolva
- 🚉A vonat célállomását és induló állomását is megjeleníti

### 🕹️ Használat
Egyszerűen nyisd meg a böngészőben ezt a linket https://diak008.github.io/2025_01_30_utastajekoztatas/ és élvezd a látványt.
 
#### ⚔️ Élő demó
A projekt meg nyizható ittt is: [Máv utastájékoztató](https://diak008.github.io/2025_01_30_utastajekoztatás/)

### 🌐 Alap HTML szerkezet
˙˙˙html
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
                <th>8:43:13</th>
                <th colspan="4">Máv érkező járatok</th>
                <th> <img id="kep" src="mav_logo.png" alt="máv logó" title="Máv logó"></th>  
            </tr>
            <tr>
                <th>Tervezett érkezés</th>
                <th>Érkezés</th>
                <th>Vonat</th>
                <th>Honnan</th>
                <th>Hova</th>
                <th>Vágány</th>  
            </tr>
        </thead>    
        <tbody>
            <tr>
                <td id="eredeti">8:30</td>
                <td id="keses">8:42</td>
                <Td>IC</Td>
                <Td>Szeged</Td>
                <Td>Szatymaz-Kistelek</Td>
                <Td>5</Td>
            </tr>
            <tr>
                <td class="elsö_oszlop">9:22</td>
                <td>  </td>
                <Td>Sz</Td>
                <Td>Szentes</Td>
                <Td>Csongrád</Td>
                <Td>2</Td>
            </tr>
            <tr>
                <td class="elsö_oszlop">9:22</td>
                <td> </td>
                <Td>IC</Td>
                <Td>Szeged</Td>
                <Td>Szatymaz-Kistelek</Td>
                <Td>4</Td>
            </tr>
            <tr>
                <td class="elsö_oszlop">9:24</td>
                <td> </td>
                <Td>Sz</Td>
                <Td>Lakitelek</Td>
                <Td>Tiszaalpár</Td>
                <Td>1</Td>
            </tr>
            <tr>
                <td class="elsö_oszlop">9:27</td>
                <td> </td>
                <Td>IC</Td>
                <Td>Nyugati**Budapest</Td>
                <Td>Cegléd-Kecskemét</Td>
                <Td>5</Td>
            </tr>
            <tr>
                <td class="elsö_oszlop">9:30</td>
                <td> </td>
                <Td>Ic</Td>
                <Td>Szeged</Td>
                <Td>Szatymaz-Kistelek</Td>
                <Td>3</Td>
            </tr>
        </tbody>
    </table>
    <a href="index_2.html">Induló járatok</a>
</body>
</html>