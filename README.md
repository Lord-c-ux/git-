# git-
<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8">
  <title>Titre de la page</title>
</head>
<body>
  <p>
    Ceci est le premier paragraphe du corps de la page. Il sert d'exemple pour montrer comment ajouter du contenu textuel dans la section <code>&lt;body&gt;</code> d'un document HTML.
  </p>
  <!-- Contenu de la page -->
</body><!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8">
  <title>Mini Calculatrice</title>
  <style>
    body {
      background: #fff;
      color: #000;
      font-family: Arial, sans-serif;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
    }
    .calculatrice {
      width: 8.5cm;
      padding: 1cm;
      border: 2px solid #000;
      border-radius: 10px;
      background: #fff;
      box-shadow: 2px 2px 8px #0002;
      text-align: center;
    }
    .calculatrice input[type="number"] {
      width: 3cm;
      padding: 0.2cm;
      margin: 0.2cm 0;
      font-size: 1em;
      border: 1px solid #000;
      background: #fff;
      color: #000;
    }
    .calculatrice button {
      width: 4cm;
      padding: 0.3cm;
      margin-top: 0.5cm;
      font-size: 1em;
      background: #000;
      color: #fff;
      border: none;
      border-radius: 5px;
      cursor: pointer;
    }
    .calculatrice button:hover {
      background: #222;
    }
    #resultat {
      margin-top: 0.7cm;
      font-size: 1.1em;
      font-weight: bold;
      color: #000;
    }
  </style>
</head>
<body>
  <div class="calculatrice">
    <h2>Mini Calculatrice</h2>
    <form id="calculatrice">
      <input type="number" id="nombre1" name="nombre1" step="any" placeholder="Nombre 1" required>
      <br>
      <input type="number" id="nombre2" name="nombre2" step="any" placeholder="Nombre 2" required>
      <br>
      <button type="submit">Additionner</button>
    </form>
    <div id="resultat"></div>
  </div>
  <script>
    const form = document.getElementById('calculatrice');
    const resultat = document.getElementById('resultat');

    form.addEventListener('submit', function(event) {
      event.preventDefault();
      const x = parseFloat(document.getElementById('nombre1').value);
      const y = parseFloat(document.getElementById('nombre2').value);
      const somme = x + y;
      resultat.textContent = `La somme de ${x} et ${y} est : ${somme}`;
    });
  </script>
</body>
</html>
</html>
<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8">
  <title>Titre de la page</title>
</head>
<body>
  <h1>Calculatrice de nombres relatifs</h1>
  <p>
    Ceci est le premier paragraphe du corps de la page. Il sert d'exemple pour montrer comment ajouter du contenu textuel dans la section <code>&lt;body&gt;</code> HTML.
  </p>
  <p>
    Ceci est le second paragraphe du corps de la page. Il continue l'exemple en ajoutant plus de texte pour illustrer la structure d'une page HTML.
  </p>

  <!-- Variables pour la calculatrice de nombres relatifs -->
  <form id="calculatrice">
    <label for="nombre1">Nombre 1 :</label>
    <input type="number" id="nombre1" name="nombre1" step="any" required>
    <br>
    <label for="nombre2">Nombre 2 :</label>
    <input type="number" id="nombre2" name="nombre2" step="any" required>
    <br>
    <button type="submit">Calculer</button>
  </form>
  <div id="resultat"></div>

  <script>
  </style>
</head>
<body>
  <div class="calculatrice">
    <h2>Mini Calculatrice</h2>
    <form id="calculatrice">
      <input type="number" id="nombre1" name="nombre1" step="any" placeholder="Nombre 1" required>
      <br>
      <input type="number" id="nombre2" name="nombre2" step="any" placeholder="Nombre 2" required>
      <br>
      <button type="submit">=</button>
    </form>
    <div id="resultat"></div>
  </div>
  <script>
    const form = document.getElementById('calculatrice');
    const resultat = document.getElementById('resultat');

    form.addEventListener('submit', function(event) {
      event.preventDefault();
      const x = parseFloat(document.getElementById('nombre1').value);
      const y = parseFloat(document.getElementById('nombre2').value);
      const somme = x + y;
      resultat.textContent = `La somme de ${x} et ${y} est : ${somme}`;
    });
  </script>
</body>
</html>
<!-- Exemple de déclaration de variables pour l'addition d'entiers -->
<script>
  // Déclaration des variables entières pour l'addition
  let a = 7;
  let b = 12;

  // Calcul de la somme
  let somme = a + b;

  // Affichage du résultat dans la console
  console.log("La somme de " + a + " et " + b + " est : " + somme);

  // Affichage du résultat dans la page HTML (si un élément avec id="resultat" existe)
  // document.getElementById('resultat').innerText = "La somme de " + a + " et " + b + " est : " + somme;
</script><!-- Exemple de déclaration de variables pour la soustraction d'entiers et code complet -->
<script>
  // Déclaration des variables entières pour la soustraction
  let a = 15;
  let b = 8;

  // Calcul de la différence
  let difference = a - b;

  // Affichage du résultat dans la console
  console.log("La différence entre " + a + " et " + b + " est : " + difference);

  // Affichage du résultat dans la page HTML (si un élément avec id="resultat" existe)
  // document.getElementById('resultat').innerText = "La différence entre " + a + " et " + b + " est : " + difference;
</script><!-- Exemple de déclaration de variables pour la multiplication de deux ou plusieurs nombres -->
<script>
  // Multiplication de deux nombres
  let a = 4;
  let b = 6;
  let produit2 = a * b;

  // Multiplication de plusieurs nombres
  let c = 3;
  let d = 2;
  let produitN = a * b * c * d;

  // Affichage des résultats dans la console
  console.log("Le produit de " + a + " et " + b + " est : " + produit2);
  console.log("Le produit de " + a + ", " + b + ", " + c + " et " + d + " est : " + produitN);

  // Affichage dans la page HTML (si un élément avec id="resultat" existe)
  // document.getElementById('resultat').innerText = "Le produit de " + a + ", " + b + ", " + c + " et " + d + " est : " + produitN;
</script><!-- Exemple de déclaration de variables pour la division de nombres entiers -->
<script>
  // Déclaration des variables pour la division
  let a = 20;
  let b = 4;

  // Calcul du quotient
  let quotient = a / b;

  // Affichage du résultat dans la console
  console.log("Le quotient de " + a + " divisé par " + b + " est : " + quotient);

  // Affichage du résultat dans la page HTML (si un élément avec id="resultat" existe)
  // document.getElementById('resultat').innerText = "Le quotient de " + a + " divisé par " + b + " est : " + quotient;
</script><!-- Exemple de déclaration de variable pour la fonction cosinus -->
<script>
  // Déclaration de la variable en radians
  let angle = Math.PI / 3; // 60 degrés en radians

  // Calcul du cosinus
  let cosinus = Math.cos(angle);

  // Affichage du résultat dans la console
  console.log("Le cosinus de l'angle (en radians) " + angle + " est : " + cosinus);

  // Affichage dans la page HTML (si un élément avec id="resultat" existe)
  // document.getElementById('resultat').innerText = "Le cosinus de l'angle " + angle + " radian est : " + cosinus;
</script>
