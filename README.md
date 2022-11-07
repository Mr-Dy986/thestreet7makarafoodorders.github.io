<!DOCTYPE html>
<html lang="en">

  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <script src="https://telegram.org/js/telegram-web-app.js"></script>
    <title>ផ្លូវ-The Street</title>
    <link rel="icon" type="image/x-icon" href="./images/favicon.ico" />
    <link rel="stylesheet" href="./src/style.css" />
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.1.1/css/all.min.css"
      integrity="sha512-KfkfwYDsLkIlwQp6LFnl8zNdLGxu9YAA1QvwINks4PhcElQSvqcyVLLD9aMhXd13uQjoXtEKNosOWaZqXgel0g=="
      crossorigin="anonymous" referrerpolicy="no-referrer" />
  </head>

  <body>
    <!-- Navbar -->
    <div class="navbar">
      <div class="navbar__content">
        <a href="index.html"><span>ផ្លូវ-The Street</span></a>
        <a href="cart.html">
          <div class="cart">
            <i class="fa-solid fa-cart-shopping"></i>
            <div class="cartCounter">0</div>
          </div>
        </a>
      </div>
    </div>

    <!-- Shop -->
    <section class="container content-section">
      <section class="shop-items">
        <section class="shop__grid" id="shop"></section>
      </section>
    </section>
  </body>

  <script src="https://kit.fontawesome.com/602cd2a7a9.js" crossorigin="anonymous"></script>
  <script src="./src/dummyData.js"></script>
  <script src="./src/main.js"></script>

</html>
