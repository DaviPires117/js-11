
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Minha Página</title>
</head>
<body>

  <script>
    
    window.alert("Bem-vindo à minha página!");

    document.title = "Minha Página - Boas-vindas";

    var sectionElement = document.createElement("section");

    var sectionTitleElement = document.createElement("h1");
    sectionTitleElement.textContent = "Título da Section";

    var sectionParagraphElement = document.createElement("p");
    sectionParagraphElement.textContent = "Este é um parágrafo dentro da section.";
  sectionElement.appendChild(sectionTitleElement);
    sectionElement.appendChild(sectionParagraphElement);

 document.body.appendChild(sectionElement);
  </script>

</body>
</html>
