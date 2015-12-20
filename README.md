# formularz

<!DOCTYPE html>

<html lang="pl">
<head>
    <meta charset="utf-8">
    <meta name="description" content="simple example of html">
    <meta name="author" content="infoShare Academy">
    <meta name="keywords" content="infoshare, academy">
    <title>cw-css-04</title>
    <link rel="shortcut icon" href="images/favicon.ico" type="image/x-icon" />

    <link rel="stylesheet" href="styles/cw-css-04.css" />
</head>
<body>
<p>Paragraf pierwszy</p>
<p style="color: red;">Paragraf drugi</p>
<p>Paragraf trzeci</p>
<p style="color: blue !important;">Paragraf 22</p>
</body>
<form>
    <label for="nasz-form-01"> NAZWA UZYTKOWNIKA: </label>

    <br>

    <fieldset>
        <legend>wyb plec </legend>
    <label for="plec-1">K:</label><input id="plec-1" name="plec"  type="radio" value="K"/>
    <br>
    <label for="plec-2">M:</label><input id="plec-2" name="plec" type="radio" value="K"/>
    </fieldset>

   
<br>
        <input type="password">
        <br>
        <input type="button" value="Dodaj do koszyka">
        <br>
        <input type="submit">
    <input id="nasz-form-01" value=""type="text" name="jjjj">
    <br>
    <input type="checkbox"/>

    <br>

    <select name="" id="">
        <option value="1"> opcja pierwsza</option>
        <option value="2">opcja druga</option>

    </select>
</form>

</html>
