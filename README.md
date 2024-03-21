<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Simulação de Digitação</title>
  <style>
    .container {
      font-family: Arial, sans-serif;
      font-size: 16px;
      margin: 20px auto;
      width: 500px;
    }
    
    .cursor {
      color: red;
      font-weight: bold;
    }
  </style>
</head>
<body>
  <div class="container">
    <span id="frase">Hello! Welcome to my GitHub! My name is Gabriella 💁</span>
    <span id="cursor">|</span>
  </div>
  
  <script>
    const frase = document.getElementById("frase");
    const cursor = document.getElementById("cursor");
    
    let i = 0;
    let interval = setInterval(() => {
      if (i < frase.textContent.length) {
        frase.textContent = frase.textContent.substring(0, i) + frase.textContent.charAt(i);
        cursor.style.display = "none";
      } else {
        clearInterval(interval);
        cursor.style.display = "inline";
      }
      i++;
    }, 100);
  </script>
</body>
</html>


[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=gapashi&layout=donut)](https://github.com/anuraghazra/github-readme-stats)
<br>
![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=gapashi&show_icons=true&theme=radical)
