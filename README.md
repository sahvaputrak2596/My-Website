<!DOCTYPE html>
<html lang="id">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Tindak Pond</title>
    <link rel="stylesheet" href="styles.css" />
  </head>
  <body>
    <div class="header">
      <h1>Tindak Pond</h1>
    </div>

    <div class="profile">
      <img src="new_profile1.jpg" alt="Foto Profil" />
      <div class="bio">
        <h2>Percetakan_Tindak_Pond</h2>
        <p>Solusi cetak mencetak Anda!
            Cetak Box cover, Food Packaging, Paperbag, Undangan, Kalender
            Admin : 085609413125.</p>
      </div>
    </div>

    <div class="gallery">
      <div class="photo" onclick="openWhatsApp('Product 1')">
        <img src="new_product 1.jpg" alt="Produk 1" />
      </div>
      <div class="photo" onclick="openWhatsApp('Product 2')">
        <img src="new_product2.jpg" alt="Produk 2" />
      </div>
      <div class="photo" onclick="openWhatsApp('Product 3')">
        <img src="new_product3.jpg" alt="Produk 3" />
      </div>
      <div class="photo" onclick="openWhatsApp('Product 4')">
        <img src="new_product4.jpg" alt="Produk 4" />
      </div>
      <div class="photo" onclick="openWhatsApp('Product 5')">
        <img src="new_product5.jpg" alt="Produk 5" />
      </div>
      <div class="photo" onclick="openWhatsApp('Product 6')">
        <img src="new_product6.jpg" alt="Produk 6" />
      </div>
      <div class="photo" onclick="openWhatsApp('Product 7')">
        <img src="new_product7.jpg" alt="Produk 7" />
      </div>
      <div class="photo" onclick="openWhatsApp('Product 8')">
        <img src="new_product8.jpg" alt="Produk 8" />
      </div>
    </div>
    <!-- Tambahkan lebih banyak foto sesuai kebutuhan -->

    <script>
      function openWhatsApp(product) {
        const phoneNumber = "085609413125";
        const message = `Hello, saya ingin memesan: ${product}`;
        window.open(
          `https://wa.me/${phoneNumber}?text=${encodeURIComponent(message)}`,
          "_blank"
        );
      }
    </script>
  </body>
</html>
