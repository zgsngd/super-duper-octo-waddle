body {
  font-family: Arial, sans-serif;
  background-color: #f4f4f4;
  margin: 0;
  padding: 0;
  display: flex;
  justify-content: center;
  align-items: center;
  height: 100vh;
}

.container {
  background-color: #fff;
  padding: 20px;
  box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
  width: 80%;
  max-width: 600px;
  border-radius: 8px;
}

h1 {
  text-align: center;
}

.product-list {
  margin-top: 20px;
}

.product {
  background-color: #f9f9f9;
  padding: 15px;
  margin: 10px 0;
  border-radius: 8px;
  box-shadow: 0 0 5px rgba(0, 0, 0, 0.05);
}

.product h2 {
  font-size: 1.5em;
  margin-bottom: 10px;
}

.product p {
  font-size: 1em;
  margin-bottom: 10px;
}

.buy-link {
  display: inline-block;
  background-color: #28a745;
  color: #fff;
  padding: 10px 20px;
  text-decoration: none;
  border-radius: 5px;
  font-weight: bold;
  transition: background-color 0.3s;
}

.buy-link:hover {
  background-color: #218838;
}
<!DOCTYPE html>
<html lang="ru">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Обзоры товаров</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <div class="container">
    <h1>Обзоры популярных товаров</h1>
    <div class="product-list">
      <div class="product">
        <h2>Смартфон XYZ</h2>
        <p>Этот смартфон оснащен отличной камерой и мощным процессором. Идеален для любителей технологий!</p>
        <a href="https://example.com/smartphone" class="buy-link" target="_blank">Купить через партнерскую ссылку</a>
      </div>
      <div class="product">
        <h2>Ноутбук ABC</h2>
        <p>Мощный ноутбук для работы и развлечений. Легкий и с хорошей батареей.</p>
        <a href="https://example.com/laptop" class="buy-link" target="_blank">Купить через партнерскую ссылку</a>
      </div>
      <div class="product">
        <h2>Наушники DEF</h2>
        <p>Отличные наушники с шумоподавлением. Идеальны для прослушивания музыки или работы в шумных местах.</p>
        <a href="https://example.com/headphones" class="buy-link" target="_blank">Купить через партнерскую ссылку</a>
      </div>
    </div>
  </div>
  <script src="script.js"></script>
</body>
</html>
