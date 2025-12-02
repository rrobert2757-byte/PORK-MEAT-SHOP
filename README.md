<!DOCTYPE html>
<html lang='en'>
<head>
<meta charset='UTF-8'>
<meta name='viewport' content='width=device-width, initial-scale=1.0'>
<title>Fresh Pork Meat Shop</title>

<!-- Google Font -->
<link href='https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&display=swap' rel='stylesheet'>

<style>
body {
  margin: 0;
  font-family: 'Poppins', sans-serif;
  background: #fafafa;
  color: #222;
}

/* Header / Navigation */
header {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 15px 25px;
  background: #ffffff;
  position: sticky;
  top: 0;
  z-index: 1000;
  box-shadow: 0 2px 10px rgba(0,0,0,0.1);
}
header img.logo {
  height: 55px;
}
nav a {
  text-decoration: none;
  margin-left: 20px;
  color: #333;
  font-weight: 600;
  transition: .3s;
}
nav a:hover {
  color: #e63946;
}

/* Hero Section */
.hero {
  position: relative;
  height: 70vh;
  background: url('https://images.pexels.com/photos/65175/pexels-photo-65175.jpeg') center/cover no-repeat;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
  color: #fff;
}
.hero::after {
  content: '';
  position: absolute;
  width: 100%;
  height: 100%;
  background: rgba(0,0,0,0.55);
  top: 0;
  left: 0;
}
.hero-content {
  position: relative;
  max-width: 700px;
  animation: fadeInUp 1.3s ease-out;
}
.hero h1 {
  font-size: 45px;
  font-weight: 700;
  margin-bottom: 15px;
}
.hero p {
  font-size: 18px;
  margin-bottom: 25px;
}
.btn-primary {
  padding: 12px 25px;
  background: #e63946;
  color: #fff;
  border-radius: 6px;
  text-decoration: none;
  font-weight: 600;
}

/* Products Section */
.products {
  padding: 60px 20px;
  text-align: center;
}
.products h2 {
  font-size: 32px;
  margin-bottom: 30px;
}
.product-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
  gap: 25px;
}
.product {
  background: #fff;
  padding: 20px;
  border-radius: 10px;
  box-shadow: 0 4px 15px rgba(0,0,0,0.1);
}
.product img {
  width: 100%;
  border-radius: 10px;
  margin-bottom: 15px;
}

/* WhatsApp Button */
.whatsapp-btn {
  position: fixed;
  bottom: 20px;
  right: 20px;
  background: #25d366;
  color: white;
  padding: 15px 18px;
  border-radius: 50px;
  font-size: 18px;
  font-weight: 600;
  text-decoration: none;
  z-index: 999;
}

/* Footer */
footer {
  text-align: center;
  padding: 30px;
  background: #222;
  color: #fff;
  margin-top: 50px;
}

/* Animation */
@keyframes fadeInUp {
  from { opacity: 0; transform: translateY(30px); }
  to { opacity: 1; transform: translateY(0); }
}
</style>
</head>

<body>

<header>
  <img src='https://upload.wikimedia.org/wikipedia/commons/thumb/0/0b/Pig_icon.png/600px-Pig_icon.png' class='logo'>
  <nav>
    <a href='#home'>Home</a>
    <a href='#products'>Products</a>
    <a href='#contact'>Contact</a>
  </nav>
</header>

<section class='hero' id='home
