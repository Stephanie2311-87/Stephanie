# Stephanie
Candles
<!DOCTYPE html>
<html lang="el">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Just Silent</title>
  <style>
    body {
      margin: 0;
      font-family: 'Arial', sans-serif;
      background-color: #e8f5e9;
      color: #333;
    }
    header {
      background: url('header-image.jpg') no-repeat center center/cover;
      height: 300px;
      display: flex;
      align-items: center;
      justify-content: center;
      text-align: center;
      color: white;
      font-size: 2em;
      font-weight: bold;
      text-shadow: 1px 1px 5px rgba(0,0,0,0.7);
    }
    main {
      padding: 20px;
    }
    .products {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
    }
    .product {
      background: white;
      border-radius: 10px;
      overflow: hidden;
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
      text-align: center;
      padding: 15px;
    }
    .product img {
      width: 100%;
      height: 200px;
      object-fit: cover;
    }
    .product h2 {
      font-size: 1.2em;
      margin: 10px 0;
    }
    .product p {
      color: #666;
    }
    footer {
      text-align: center;
      padding: 20px;
      background-color: #c8e6c9;
      font-size: 0.9em;
    }
  </style>
</head>
<body>

<header>
  Just silent - relax for a moment
</header>

<main>
  <h1 style="text-align:center;">Τα προϊόντα μας</h1>
  <div class="products">

    <div class="product">
      <img src="product1.jpg" alt="Κερί 100% φυσικό κερί σόγιας 250ml">
      <h2>Κερί φυσικό σόγιας 250ml</h2>
      <p>Τιμή: €10</p>
    </div>

    <div class="product">
      <img src="product2.jpg" alt="Κερί σόγιας για μασάζ 250ml">
      <h2>Κερί σόγιας για μασάζ 250ml</h2>
      <p>Τιμή: €12</p>
    </div>

    <div class="product">
      <img src="product3.jpg" alt="Κερί παραφίνης 250ml">
      <h2>Κερί παραφίνης 250ml</h2>
      <p>Τιμή: €8</p>
    </div>

    <!-- Εδώ μπορείς να προσθέσεις και τα υπόλοιπα προϊόντα με τον ίδιο τρόπο -->

  </div>
</main>

<footer>
  Πληρωμές με Revolut διαθέσιμες. Ευχαριστούμε που μας προτιμάτε!
</footer>

</body>
</html>
