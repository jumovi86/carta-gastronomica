<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Elýsa Gourmet — Carta Gastronómica</title>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Fraunces:ital,opsz,wght@0,9..144,400;0,9..144,600;1,9..144,500&family=Work+Sans:wght@400;500;600&display=swap" rel="stylesheet">
<style>
  :root{
    --forest: #1F3B2C;  
    --forest-deep: #16291F;
    --ivory: #F6F1E4;
    --paper: #FBF8F1;
    --gold: #B98D34;
    --ink: #2A2620;
    --ink-soft: #5B5548;
    --rule: rgba(42,38,32,0.14);
  }

  *{ box-sizing: border-box; }

  html, body{
    margin: 0;
    padding: 0;
    background: var(--paper);
    color: var(--ink);
    font-family: 'Work Sans', sans-serif;
  }

  .hero{
    background: var(--forest);
    background-image: radial-gradient(circle at 50% -10%, var(--forest-deep), var(--forest) 70%);
    color: var(--ivory);
    text-align: center;
    padding: 4.5rem 1.5rem 3.5rem;
  }

  .emblem{
    width: 74px;
    height: 74px;
    margin: 0 auto 1.6rem;
    border: 1.5px solid rgba(246,241,228,0.55);
    border-radius: 50%;
    display: flex;
    align-items: center;
    justify-content: center;
    font-family: 'Fraunces', serif;
    font-size: 1.6rem;
    font-weight: 600;
    letter-spacing: 0.02em;
  }

  .hero h1{
    font-family: 'Fraunces', serif;
    font-weight: 600;
    font-size: clamp(2.4rem, 6vw, 3.4rem);
    letter-spacing: 0.01em;
    margin: 0 0 0.6rem;
  }

  .hero .sub{
    font-size: 0.8rem;
    text-transform: uppercase;
    letter-spacing: 0.22em;
    color: rgba(246,241,228,0.75);
    margin: 0 0 1.6rem;
  }

  .hero .tagline{
    font-family: 'Fraunces', serif;
    font-style: italic;
    font-weight: 500;
    font-size: 1.15rem;
    color: var(--gold);
    margin: 0;
  }

  main{
    max-width: 680px;
    margin: 0 auto;
    padding: 3.2rem 1.5rem 5rem;
  }

  .category{
    margin-bottom: 3.4rem;
  }

  .category:last-child{
    margin-bottom: 0;
  }

  .category-title{
    font-family: 'Fraunces', serif;
    font-weight: 600;
    font-size: 1.5rem;
    color: var(--forest);
    margin: 0 0 1.6rem;
    padding-bottom: 0.7rem;
    border-bottom: 1.5px solid var(--forest);
  }

  .dish{
    display: grid;
    grid-template-columns: 1fr auto;
    column-gap: 1rem;
    align-items: baseline;
    padding: 1.15rem 0;
    border-bottom: 1px solid var(--rule);
  }

  .category > .dish:last-child{
    border-bottom: none;
  }

  .dish-name{
    font-family: 'Fraunces', serif;
    font-weight: 600;
    font-size: 1.05rem;
    color: var(--ink);
    line-height: 1.3;
  }

  .dish-price{
    font-family: 'Fraunces', serif;
    font-weight: 500;
    font-size: 1.05rem;
    color: var(--gold);
    white-space: nowrap;
  }

  .dish-desc{
    grid-column: 1 / -1;
    font-size: 0.92rem;
    line-height: 1.55;
    color: var(--ink-soft);
    margin-top: 0.35rem;
    max-width: 56ch;
  }

  footer{
    text-align: center;
    padding: 2.2rem 1.5rem 3rem;
    background: var(--forest);
    color: rgba(246,241,228,0.7);
    font-size: 0.82rem;
    letter-spacing: 0.03em;
  }

  footer strong{
    color: var(--ivory);
    font-family: 'Fraunces', serif;
    font-weight: 600;
    font-style: italic;
  }

  @media (max-width: 480px){
    .dish{ grid-template-columns: 1fr; row-gap: 0.2rem; }
    .dish-price{ font-size: 0.98rem; }
  }
</style>
</head>
<body>

<div class="hero">
  <div class="emblem">EG</div>
  <h1>Elýsa Gourmet</h1>
  <p class="sub">Carta gastronómica</p>
  <p class="tagline">"¡Esto no se cuenta&hellip; se prueba!"</p>
</div>

<main>

  <section class="category">
    <h2 class="category-title">Antojos</h2>

    <div class="dish">
      <span class="dish-name">Canastas de plátano verde (3 unidades)</span>
      <span class="dish-price">$ 18.900</span>
      <p class="dish-desc">Crujientes canastas preparadas artesanalmente con plátano verde, generosamente rellenas de tierna carne desmechada o pollo en su propio jugo.</p>
    </div>

    <div class="dish">
      <span class="dish-name">Totopos con fondue de quesos y guacamole</span>
      <span class="dish-price">$ 22.000</span>
      <p class="dish-desc">Tortillas de maíz tostadas acompañadas de una exquisita selección de quesos fundidos, guacamole fresco y pico de gallo tradicional.</p>
    </div>

    <div class="dish">
      <span class="dish-name">Antojo especial de la casa</span>
      <span class="dish-price">$ 16.500</span>
      <p class="dish-desc">Crujientes totopos de maíz complementados con pollo desmenuzado, maíz tierno, queso costeño rallado y nuestra salsa fina especial.</p>
    </div>

    <div class="dish">
      <span class="dish-name">Tequeños artesanales (6 unidades)</span>
      <span class="dish-price">$ 15.000</span>
      <p class="dish-desc">Bastones de masa dorada crujiente rellenos de queso fresco fundido, servidos con una suave reducción de piña acaramelada.</p>
    </div>

    <div class="dish">
      <span class="dish-name">Patacones tradicionales con hogao y queso</span>
      <span class="dish-price">$ 14.000</span>
      <p class="dish-desc">Deliciosos medallones de plátano verde aplanados y dorados, cubiertos con sofrito criollo de la casa y auténtico queso costeño.</p>
    </div>

    <div class="dish">
      <span class="dish-name">Hamburguesa Elýsa Gourmet</span>
      <span class="dish-price">$ 28.500</span>
      <p class="dish-desc">Exquisita carne de res seleccionada, pan artesanal brioche, queso cheddar fundido, tocineta crujiente y nuestra salsa exclusiva.</p>
    </div>

    <div class="dish">
      <span class="dish-name">Sándwich de pollo al pesto</span>
      <span class="dish-price">$ 24.000</span>
      <p class="dish-desc">Pechuga de pollo a la parrilla marinada en pesto de albahaca fresca, queso fundido y tomate fresco en pan especial.</p>
    </div>

    <div class="dish">
      <span class="dish-name">Wrap crujiente de ave</span>
      <span class="dish-price">$ 21.000</span>
      <p class="dish-desc">Trocitos de pollo en costra crujiente con lechuga fresca, maíz dulce y aderezo César, envueltos delicadamente en tortilla de trigo.</p>
    </div>

    <div class="dish">
      <span class="dish-name">Picada personal Elýsa</span>
      <span class="dish-price">$ 32.000</span>
      <p class="dish-desc">Selección especial de carnes finas, cerdo, chorizo artesanal, arepas asadas, yuca crujiente y patacón acompañado de hogao.</p>
    </div>

    <div class="dish">
      <span class="dish-name">Alitas glaseadas en salsa barbacoa (8 unidades)</span>
      <span class="dish-price">$ 26.000</span>
      <p class="dish-desc">Alitas de pollo horneadas y bañadas en salsa barbacoa ahumada.</p>
    </div>
  </section>

  <section class="category">
    <h2 class="category-title">Repostería y pastelería</h2>

    <div class="dish">
      <span class="dish-name">Porción de pastel de chocolate fino</span>
      <span class="dish-price">$ 12.000</span>
      <p class="dish-desc">Bizcocho húmedo de cacao con una suave cobertura de chocolate fudge de alta intensidad.</p>
    </div>

    <div class="dish">
      <span class="dish-name">Porción de tarta Red Velvet</span>
      <span class="dish-price">$ 13.500</span>
      <p class="dish-desc">Delicado pastel aterciopelado con un sutil toque de cacao y una cremosa cobertura de queso.</p>
    </div>

    <div class="dish">
      <span class="dish-name">Selección de mini rosquillas horneadas (6 unidades)</span>
      <span class="dish-price">$ 16.000</span>
      <p class="dish-desc">Mini donas horneadas con baño de arequipe artesanal, cobertura de chocolate y decoraciones festivas.</p>
    </div>

    <div class="dish">
      <span class="dish-name">Cupcake de autor (unidad)</span>
      <span class="dish-price">$ 7.500</span>
      <p class="dish-desc">Ponqué tradicional de vainilla o chocolate coronado con una suave crema dulce de mantequilla batida.</p>
    </div>

    <div class="dish">
      <span class="dish-name">Galleta fina con chispas de chocolate</span>
      <span class="dish-price">$ 6.500</span>
      <p class="dish-desc">Galleta crujiente horneada en su punto exacto, enriquecida con finas pepitas de chocolate que se funden delicadamente al paladar.</p>
    </div>
  </section>

  <section class="category">
    <h2 class="category-title">Bebidas y refrescos</h2>

    <div class="dish">
      <span class="dish-name">Limonada de panela y hierbabuena</span>
      <span class="dish-price">$ 8.500</span>
      <p class="dish-desc">Refrescante bebida de limón combinada con reducción de panela natural y hojas frescas de hierbabuena.</p>
    </div>

    <div class="dish">
      <span class="dish-name">Jugos naturales de la estación (maracuyá / lulo / mango)</span>
      <span class="dish-price">$ 8.000</span>
      <p class="dish-desc">Jugos preparados al momento con fruta fresca seleccionada en agua.</p>
    </div>

    <div class="dish">
      <span class="dish-name">Soda artesanal de frutos rojos</span>
      <span class="dish-price">$ 11.000</span>
      <p class="dish-desc">Agua carbonatada combinada con concentrado artesanal de frutos del bosque y hielo templado.</p>
    </div>

    <div class="dish">
      <span class="dish-name">Café latte de especialidad</span>
      <span class="dish-price">$ 7.500</span>
      <p class="dish-desc">Selección de café colombiano de origen con una delicada emulsión de leche cremosa.</p>
    </div>

    <div class="dish">
      <span class="dish-name">Malteada artesanal de arequipe</span>
      <span class="dish-price">$ 13.500</span>
      <p class="dish-desc">Helado de vainilla batido con dulce de leche artesanal, acompañado de crema chantilly y un barquillo crujiente.</p>
    </div>
  </section>

</main>

<footer>
  Elýsa Gourmet &middot; <strong>Esto no se cuenta&hellip; ¡Se prueba!</strong>
</footer>

</body>
</html>
