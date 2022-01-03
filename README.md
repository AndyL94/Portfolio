# Exercice Portfolio
---------------
[Afficher le portfolio](https://andyl94.github.io/Portfolio/)
# HTML
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portfolio - Andy LOUIS</title>
    <link rel="stylesheet" href="./css/style.css">
    <link rel="icon" type="image/png" sizes="32x32" href="./favicon/icon-page.jpg   ">
</head>
```
---------------
# CSS
```css
/* Reset */
html{ 
    font-size: 62.5%;  
}
body{
    font: 1.6rem sans-serif; 
    margin: 0;  
}
h1,h2,h3,h4,p,ol,ul,figure,dd{
    margin: 0;
    padding: 0;
    list-style-type: none;
}
h1,h2,h3,h4{
    font-weight: normal;
}

:root{
    --color-primary: rgb(96, 170, 219);
    --color-secondary: #fff;
    --color-main: #d9d9dd9c;
}


body{
    background-image: url("../asset/img-background1.png");
    background-size: cover;
    background-repeat: no-repeat;
    background-position: center center;
    background-attachment: fixed;
}

footer{
    max-width: 60.0rem;
    margin: 3rem auto 2rem;
    background-color: var(--color-main);
    box-shadow: 0 0 2.0rem rgb(96, 170, 219);
    padding: 1rem;
}

.logos{
    width: 10.0rem;
    height: 10.0rem;
}
   

header h1 {
    text-align: center;
    padding-top: 1.4rem;
    padding-bottom: 1.4rem;
    padding-right: 5rem;
    margin-bottom: 0.1rem;
}
```