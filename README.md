<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Exemplo MathJax no GitHub</title>
  <!-- Inclusão do MathJax via CDN -->
  <script src="https://polyfill.io/v3/polyfill.min.js?features=es6"></script>
  <script id="MathJax-script" async
    src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-mml-chtml.js"></script>
  <style>
    body {
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      background: #f4f7fb;
      color: #333;
      margin: 2rem;
      line-height: 1.6;
    }
    h1 {
      color: #2c3e50;
    }
    .equation {
      background: #fff;
      padding: 1rem;
      border-radius: 8px;
      margin: 1rem 0;
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
      font-size: 1.2rem;
    }
  </style>
</head>
<body>
  <h1>Exemplo de Integral usando MathJax</h1>
  <p>Esta é a notação da integral Gaussiana:</p>
  <div class="equation">
    $$ \int_0^\infty e^{-x^2} \, dx = \frac{\sqrt{\pi}}{2} $$
  </div>
  <p>Você pode editar este arquivo e usar o delimitador <code>$$...$$</code> para escrever suas próprias equações em LaTeX.</p>
</body>
</html>

