# Teste
Só colocando códigos para não esquecer
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="estilo.css">
</head>
<body>

    <ul class="alternada">
        <li>Item 1</li>
        <li>Item 2</li>
        <li>Item 3</li>
        <li>Item 4</li>
        <li>Item 5</li>
    </ul>
    
</body>
</html>

.alternada{
    list-style: upper-alpha;
    font-size: 30px;
    color: indigo;
    width: fit-content;

}
.alternada li:nth-child(odd){
    background-color: lightblue;
}
.alternada li:nth-child(even){
    background-color: rebeccapurple;
}
.alternada li:hover{
    font-weight: bolder;
}
