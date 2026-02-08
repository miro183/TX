<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="utf-8" />
    <title>Главная</title>
    <link rel="stylesheet" href="site.css" />
</head>
<body>
    <div class="top-strip">
        языки программирования
        <div class="TwoDiv">
            <div class="uu"> <a class="uu"  href="1 str.html" >C++</a></div>
            <div class="uu"><a class="uu" href="2 str.html"id="myElement" >C#</a></div>
            <div class="uu"><a class="uu" href="3 str.html"id="myElement">Java</a></div>
            <div class="uu"><a class="uu" href="4 str.html"id="myElement">JavaScript</a></div>
            <div class="uu"><a class="uu" href="5 str.html"id="myElement">Python</a></div>
            <div class="uu"><a class="uu" href="6 str.html"id="myElement">Kotlin</a></div>
        </div>
    </div>
    <script>
        const elements = document.querySelectorAll('.uu');
        elements.forEach((el) => {
            el.addEventListener('mouseenter', () => {
                el.style.color = 'red';
            });
            el.addEventListener('mouseleave', () => {
                el.style.color = '';
            });
        });
    </script>
</body>
</html>
