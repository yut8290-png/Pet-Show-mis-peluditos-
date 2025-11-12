# Pet-Show-mis-peluditos-
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Pet Show Mis Peluditos</title>
  <style>
    body {
      font-family: 'Poppins', sans-serif;
      margin: 0;
      background-color: #fffaf2;
      background-image: url('https://images.unsplash.com/photo-1601758123840-230c66a06d5c?auto=format&fit=crop&w=1400&q=80');
      background-size: cover;
      background-repeat: no-repeat;
      background-position: center;
      color: #333;
    }
    header {
      background: linear-gradient(135deg, rgba(255,182,193,0.8), rgba(147,112,219,0.8));
      text-align: center;
      padding: 50px 20px 30px 20px;
      color: white;
    }
    header p { font-size: 1.2em; margin-top: 10px; font-weight: 500; }
    .logo-container { text-align: center; margin-bottom: 15px; }
    .logo-container svg { width: 180px; height: 180px; }
    .logo-container h2 { font-family: 'Comic Sans MS', cursive, sans-serif; font-size: 2em; margin-top: 10px; color: white; }
    nav { background-color: rgba(255,204,112,0.9); padding: 12px; text-align: center; }
    nav a { text-decoration: none; color: #333; margin: 0 15px; font-weight: bold; font-size: 1.1em; }
    nav a:hover { color: #ff6600; }
    section { padding: 30px 20px; text-align: center; background-color: rgba(255, 250, 242, 0.85); margin: 20px auto; border-radius: 15px; width: 90%; max-width: 1200px; }
    .productos { display: flex; flex-wrap: wrap; justify-content: center; gap: 25px; }
    .card { background: #fff; width: 260px; border-radius: 20px; box-shadow: 0 6px 10px rgba(0,0,0,0.15); padding: 15px; transition: transform 0.3s; }
    .card:hover { transform: translateY(-5px); }
    .card img { width: 100%; border-radius: 12px; object-fit: cover; height: 200px; }
    .card h3 { margin: 12px 0 6px; }
    .precio { color: #ff4500; font-weight: bold; }
    .whatsapp-btn { display: inline-block; margin-top: 20px; background-color: #25d366; color: white; padding: 14px 22px; border-radius: 30px; text-decoration: none; font-weight: bold; font-size: 1.1em; box-shadow: 0 4px 6px rgba(0,0,0,0.2); transition: background-color 0.3s; }
    .whatsapp-btn:hover { background-color: #20b858; }
    footer { background-color: rgba(255,184,77,0.9); color: white; text-align: center; padding: 18px; margin-top: 40px; border-radius: 0 0 15px 15px; }
  </style>
</head>
<body>

<header>
  <div class="logo-container">
    <svg viewBox="0 0 150 150">
      <path d="M50,75 C30,20 70,20 50,75" fill="none" stroke="#FF69B4" stroke-width="4"/>
      <path d="M100,75 C120,20 80,20 100,75" fill="none" stroke="#8A2BE2" stroke-width="4"/>
      <circle cx="55" cy="60" r="3" fill="#FF69B4"/>
      <circle cx="95" cy="60" r="3" fill="#8A2BE2"/>
    </svg>
    <h2>Pet Show Mis Peluditos</h2>
  </div>
  <p>Todo para el cuidado y amor de tus mascotas</p>
</header>

<nav>
  <a href="#inicio">Inicio</a>
  <a href="#productos">Productos</a>
  <a href="#desparasitantes">Desparasitantes</a>
  <a href="#contacto">Contacto</a>
</nav>

<section id="inicio">
  <h2>Bienvenidos</h2>
  <p>En <strong>Pet Show Mis Peluditos</strong> encontrarás lo mejor para tus amigos peludos: comida, accesorios, medicamentos y mucho amor 💕.</p>
</section>

<section id="productos">
  <h2>Nuestros Productos</h2>
  <div class="productos">
    <div class="card">
      <img src="https://images.unsplash.com/photo-1601758123927-30e9f6e9f7e5?auto=format&fit=crop&w=250&h=200&q=80" alt="Comida para gatos">
      <h3>Comida para Gatos</h3>
      <p>Marcas: Mirringo, Q-ida Cat, Monello y Don Kat</p>
    </div>
    <div class="card">
      <img src="https://images.unsplash.com/photo-1592194996308-7b43878e84a6?auto=format&fit=crop&w=250&h=200&q=80" alt="Comida para perros">
      <h3>Comida para Perros</h3>
      <p>Monello, Dog Show, Ringo, Chunky, Dogourmet y Alpo</p>
    </div>
  </div>
</section>

<section id="desparasitantes">
  <h2>Desparasitantes</h2>
  <div class="productos">
    <div class="card">
      <img src="https://images.unsplash.com/photo-1600206110965-7e563a147f09?auto=format&fit=crop&w=250&h=200&q=80" alt="Canbest">
      <h3>Canbest</h3>
      <p>2 ml <span class="precio">$6.000</span><br>5 ml <span class="precio">$7.000</span></p>
    </div>
    <div class="card">
      <img src="https://images.unsplash.com/photo-1588776814546-d45c8d353264?auto=format&fit=crop&w=250&h=200&q=80" alt="Phamocan">
      <h3>Phamocan</h3>
      <p>2 ml <span class="precio">$6.500</span><br>5 ml <span class="precio">$7.500</span></p>
    </div>
    <div class="card">
      <img src="https://images.unsplash.com/photo-1583241208487-6f189ec86be1?auto=format&fit=crop&w=250&h=200&q=80" alt="Paracanis">
      <h3>Paracanis</h3>
      <p>10 ml <span class="precio">$12.000</span></p>
    </div>
  </div>
  <a class="whatsapp-btn" href="https://wa.me/573175354808?text=Hola%20Pet%20Show%20Mis%20Peluditos!%20Quiero%20comprar%20desparasitantes%20para%20mi%20mascota." target="_blank">💬 Escríbenos por WhatsApp</a>
</section>

<section id="contacto">
  <h2>Contáctanos</h2>
  <p>📍 Dirección: Calle Principal, Ciudad</p>
  <p>📞 WhatsApp: +57 317 5354808</p>
  <p>📧 Email: petshowmis@peluditos.com</p>
</section>

<footer>
  <p>© 2025 Pet Show Mis Peluditos | Hecho con amor para tus mascotas 🐶🐱</p>
</footer>

</body>
</html>

