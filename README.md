<div id="digitação">
  <span id="frase">Hello! I'm Gapashi! Welcome to my GitHub!</span>
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


[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=gapashi&layout=donut)](https://github.com/anuraghazra/github-readme-stats)
<br>
![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=gapashi&show_icons=true&theme=radical)
