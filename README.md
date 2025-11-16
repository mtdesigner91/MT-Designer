[realisations.html](https://github.com/user-attachments/files/23567807/realisations.html)
<!DOCTYPE html>
<html lang="fr">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Nos réalisations - MT Designer</title>[a-propos.html](https://github.com/user-attachments/files/23567809/a-propos.html)<!DOCTYPE html>
<html lang="fr">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>À propos - MT Designer</title>
<link rel="stylesheet" href="assets/style.css">
</head>
<body>
<div class="container">

<header>
  <div class="logo"><img src="images/logo.jpg" alt="Logo MT Designer">MT <span style="color:var(--highlight)">Designer</span></div>
  <button class="menu-toggle">☰</button>
  <nav>
    <a href="index.html">Accueil</a>
    <a href="a-propos.html">À propos</a>
    <a href="realisations.html">Nos réalisations</a>
    <a href="contact.html">Contact</a>
  </nav>
</header>

<section>
  <h1>À propos de MT Designer</h1>
  <img src="images/logo.jpg" alt="Logo MT Designer">
  <p>Basée à <strong>Morangis</strong>, MT Designer est une entreprise spécialisée dans les travaux de construction et de rénovation. Notre mission est d’accompagner nos clients à chaque étape de leur projet.</p>
  <p>Nous plaçons la <strong>qualité</strong>, la <strong>fiabilité</strong> et la <strong>transparence</strong> au cœur de chacune de nos interventions.</p>
  <p>MT Designer, c’est avant tout une équipe à taille humaine, soucieuse du détail et à l’écoute de vos besoins.</p>
  <p><strong>MT Designer</strong> — parce que votre projet mérite le meilleur savoir-faire.</p>
</section>

<footer>
  <div class="social-links">
    <a href="https://www.instagram.com/mtdesignneer" target="_blank" title="Instagram MT Designer">
      <img src="https://cdn-icons-png.flaticon.com/512/174/174855.png" alt="Instagram">
    </a>
    <a href="https://wa.me/33768048703" target="_blank" title="WhatsApp MT Designer">
      <img src="https://cdn-icons-png.flaticon.com/512/733/733585.png" alt="WhatsApp">
    </a>
  </div>
  <p>© 2025 MT Designer - Tous droits réservés</p>
  <p>📍 Morangis | 📞 Tel: +33 7 68 04 87 03 | ✉️ Mail: mtdesigner@yahoo.com</p>
</footer>

</div>
<script src="assets/script.js"></script>
</body>
</html>


<link rel="stylesheet" href="assets/style.css">

<style>
/* === GALERIE === */
.gallery {
  display: grid;[contact.html](https://github.com/user-attachments/files/23567808/contact.html)<!DOCTYPE html>
<html lang="fr">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Contact & Devis - MT Designer</title>
<link rel="stylesheet" href="assets/style.css">
</head>
<body>
<div class="container">

<header>
  <div class="logo"><img src="images/logo.jpg" alt="Logo MT Designer">MT <span style="color:var(--highlight)">Designer</span></div>
  <button class="menu-toggle">☰</button>
  <nav>
    <a href="index.html">Accueil</a>
    <a href="a-propos.html">À propos</a>
    <a href="realisations.html">Nos réalisations</a>
    <a href="contact.html">Contact</a>
  </nav>
</header>

<section>
  <h1>Contact & Demande de Devis</h1>
  <p>Remplissez le formulaire ci-dessous pour obtenir un devis gratuit ou contactez-nous directement sur WhatsApp.</p>
  <form action="https://formspree.io/f/your-form-id" method="POST" enctype="multipart/form-data">
    <label for="name">Nom complet</label>
    <input type="text" id="name" name="name" required>

    <label for="email">Adresse e-mail</label>
    <input type="email" id="email" name="_replyto" required>

    <label for="phone">Téléphone</label>
    <input type="tel" id="phone" name="phone">

    <label for="project">Type de projet</label>
    <select id="project" name="project">
      <option>Construction</option>
      <option>Rénovation</option>
      <option>Décoration</option>
      <option>Autre</option>
    </select>

    <label for="message">Message / Description</label>
    <textarea id="message" name="message" rows="5" required></textarea>

    <label for="file">Joindre un fichier (optionnel)</label>
    <input type="file" id="file" name="file">

    <button type="submit">📩 Envoyer ma demande</button>
  </form>

  <a href="https://wa.me/33768048703?text=Bonjour%20MT%20Designer,%20je%20souhaite%20obtenir%20un%20devis." class="whatsapp-btn" target="_blank">💬 Contacter sur WhatsApp</a>
</section>

<footer>
  <div class="social-links">
    <a href="https://www.instagram.com/mtdesignneer" target="_blank" title="Instagram MT Designer">
      <img src="https://cdn-icons-png.flaticon.com/512/174/174855.png" alt="Instagram">
    </a>
    <a href="https://wa.me/33768048703" target="_blank" title="WhatsApp MT Designer">
      <img src="https://cdn-icons-png.flaticon.com/512/733/733585.png" alt="WhatsApp">
    </a>
  </div>
  <p>© 2025 MT Designer - Tous droits réservés</p>
  <p>📍 Morangis | 📞 Tel: +33 7 68 04 87 03 | ✉️ Mail: mtdesigner@yahoo.com</p>
</footer>

</div>
<script src="assets/script.js"></script>
</body>
</html>


  grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
  gap: 20px;
  margin-top: 40px;
  padding: 0 20px;
}

.gallery img {
  width: 100%;
  border-radius: 12px;
  box-shadow: 0 4px 15px rgba(0, 0, 0, 0.1);
  transition: transform 0.3s ease, box-shadow 0.3s ease;
  cursor: pointer;
}

.gallery img:hover {
  transform: scale(1.05);
  box-shadow: 0 6px 25px rgba(0, 0, 0, 0.15);
}

/* === LIGHTBOX === */
.lightbox {
  display: none;
  position: fixed;
  z-index: 999;
  left: 0;
  top: 0;
  width: 100%;
  height: 100%;
  background-color: rgba(0, 0, 0, 0.85);
  justify-content: center;
  align-items: center;
  padding: 20px;
}

.lightbox-content {
  max-width: 90%;
  max-height: 90%;
  border-radius: 12px;
}

.lightbox .close {
  position: absolute;
  top: 30px;
  right: 50px;
  color: #fff;
  font-size: 40px;
  font-weight: bold;
  cursor: pointer;
}
</style>
</head>

<body>
<div class="container">

<header>
  <div class="logo">
    <img src="images/logo.jpg" alt="Logo MT Designer" style="height:60px;vertical-align:middle;margin-right:10px;">
    MT <span style="color:var(--highlight)">Designer</span>
  </div>
  <button class="menu-toggle">☰</button>
  <nav>
    <a href="index.html">Accueil</a>
    <a href="a-propos.html">À propos</a>
    <a href="realisations.html" class="active">Nos réalisations</a>
    <a href="contact.html">Contact</a>
  </nav>
</header>

<section>
  <h1>Nos réalisations</h1>
  <p>Découvrez nos projets de rénovation, de construction et d’aménagement réalisés pour nos clients.</p>

  <!-- === GALERIE AUTO === -->
  <div class="gallery" id="gallery"></div>

</section>

<!-- === LIGHTBOX === -->
<div id="lightbox" class="lightbox">
  <span class="close">&times;</span>
  <img class="lightbox-content" id="lightbox-img" alt="">
</div>

<footer>
  <div class="social-links">
    <a href="https://www.instagram.com/mtdesignneer" target="_blank">
      <img src="https://cdn-icons-png.flaticon.com/512/174/174855.png" alt="Instagram">
    </a>
    <a href="https://wa.me/33768048703" target="_blank">
      <img src="https://cdn-icons-png.flaticon.com/512/733/733585.png" alt="WhatsApp">
    </a>
  </div>
  <p>© 2025 MT Designer - Tous droits réservés</p>
  <p>📍 Morangis | 📞 +33 7 68 04 87 03 | ✉️ mtdesigner@yahoo.com</p>
</footer>

</div>

<script>
// === GALERIE AUTO ===
// indique combien d’images existent au maximum
const totalImages = 300;
const gallery = document.getElementById("gallery");

for (let i = 1; i <= totalImages; i++) {
  const img = document.createElement("img");
  img.src = `filesrealisations/realisation${i}.jpg`;
  img.alt = `Réalisation ${i}`;

  // supprime l'image si elle n'existe pas
  img.onerror = () => img.remove();

  // ajout à la galerie
  gallery.appendChild(img);
}

// === LIGHTBOX ===
const lightbox = document.getElementById("lightbox");
const lightboxImg = document.getElementById("lightbox-img");
const closeBtn = document.querySelector(".lightbox .close");

document.addEventListener("click", e => {
  if (e.target.closest(".gallery img")) {
    lightbox.style.display = "flex";
    lightboxImg.src = e.target.src;
  }
});

closeBtn.addEventListener("click", () => {
  lightbox.style.display = "none";
});

lightbox.addEventListener("click", e => {
  if (e.target === lightbox) {
    lightbox.style.display = "none";
  }
});
</script>

</body>
</html>
