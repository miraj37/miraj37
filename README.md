<!DOCTYPE html>
<html lang="bn">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Mynos Bazar - Electronics</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>
  <header>
    <div class="logo">Mynos Bazar</div>
    <input type="text" placeholder="পণ্য খুঁজুন..." />
    <button class="search-btn">খুঁজুন</button>
  </header>

  <nav class="menu">
    <a href="#">হোম</a>
    <a href="#">ফ্ল্যাশ সেল</a>
    <a href="#">ক্যাটাগরি</a>
    <a href="#">লগইন</a>
  </nav>

  <section class="banner">
    <h1>বিশ্বস্ত ইলেকট্রনিক্স বাজার</h1>
    <p>আপনার পছন্দসই পণ্য পান সেরা দামে!</p>
  </section>

  <section class="categories">
    <h2>ক্যাটাগরি</h2>
    <div class="category-list">
      <div class="category">
        <h3>মোবাইল</h3>
        <img src="https://via.placeholder.com/150x150" alt="Mobile" />
      </div>
      <div class="category">
        <h3>ল্যাপটপ</h3>
        <img src="https://via.placeholder.com/150x150" alt="Laptop" />
      </div>
      <div class="category">
        <h3>টিভি</h3>
        <img src="https://via.placeholder.com/150x150" alt="TV" />
      </div>
      <div class="category">
        <h3>গ্যাজেট</h3>
        <img src="https://via.placeholder.com/150x150" alt="Gadget" />
      </div>
    </div>
  </section>

  <section class="products">
    <h2>ফিচারড পণ্য</h2>
    <div class="product-list">
      <div class="product">
        <img src="https://via.placeholder.com/200x150" alt="Product 1" />
        <h3>Samsung Galaxy A15</h3>
        <p>৳17,999</p>
        <button>কার্টে যোগ করুন</button>
      </div>
      <div class="product">
        <img src="https://via.placeholder.com/200x150" alt="Product 2" />
        <h3>Dell Inspiron Laptop</h3>
        <p>৳56,000</p>
        <button>কার্টে যোগ করুন</button>
      </div>
      <div class="product">
        <img src="https://via.placeholder.com/200x150" alt="Product 3" />
        <h3>Smart LED TV</h3>
        <p>৳35,000</p>
        <button>কার্টে যোগ করুন</button>
      </div>
      <div class="product">
        <img src="https://via.placeholder.com/200x150" alt="Product 4" />
        <h3>Wireless Headphones</h3>
        <p>৳5,500</p>
        <button>কার্টে যোগ করুন</button>
      </div>
    </div>
  </section>

  <footer>
    <p>© 2025 Mynos Bazar | সকল অধিকার সংরক্ষিত</p>
  </footer>
</body>
</html>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: 'Arial', sans-serif;
}

header {
  background-color: #004b87;
  color: white;
  padding: 10px;
  text-align: center;
}

header .logo {
  font-size: 28px;
  font-weight: bold;
}

header input {
  padding: 8px;
  width: 70%;
  margin-top: 10px;
  border: none;
  border-radius: 4px;
}

.search-btn {
  background-color: #ff6f00;
  padding: 8px 20px;
  margin-left: 10px;
  border: none;
  border-radius: 4px;
  color: white;
}

nav {
  display: flex;
  justify-content: space-around;
  background-color: #00335e;
  padding: 10px;
}

nav a {
  color: white;
  text-decoration: none;
  font-size: 16px;
}

.banner {
  background-color: #e0f7fa;
  padding: 40px;
  text-align: center;
}

.banner h1 {
  font-size: 28px;
  margin-bottom: 10px;
}

.categories {
  padding: 20px;
  text-align: center;
}

.categories h2 {
  margin-bottom: 20px;
}

.category-list {
  display: flex;
  justify-content: space-around;
  flex-wrap: wrap;
}

.category {
  width: 150px;
  padding: 10px;
}

.category img {
  width: 100%;
  height: auto;
  border-radius: 6px;
}

.products {
  padding: 20px;
}

.products h2 {
  text-align: center;
  font-size: 22px;
  margin-bottom: 20px;
}

.product-list {
  display: flex;
  flex-wrap: wrap;
  gap: 20px;
  justify-content: center;
}

.product {
  background: white;
  padding: 15px;
  width: 200px;
  text-align: center;
  border-radius: 8px;
  box-shadow: 0 2px 5px rgba(0,0,0,0.1);
}

.product img {
  width: 100%;
  height: auto;
  border-radius: 6px;
}

.product h3 {
  font-size: 18px;
  margin: 10px 0;
}

.product p {
  font-size: 16px;
  color: #00796b;
}

.product button {
  margin-top: 10px;
  padding: 8px 15px;
  background-color: #ff6f00;
  color: white;
  border: none;
  border-radius: 4px;
  cursor: pointer;
}

footer {
  background-color: #004b87;
  color: white;
  padding: 10px;
  text-align: center;
  margin-top: 30px;
}
