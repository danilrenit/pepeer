<!DOCTYPE html>
<html lang="uk">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Інтернет-магазин насіння супер-гострих перців</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #ff4500;
            color: white;
            padding: 10px 0;
            text-align: center;
        }
        .container {
            width: 80%;
            margin: auto;
            overflow: hidden;
            display: flex;
            flex-wrap: wrap;
            justify-content: space-between;
        }
        .product {
            background: white;
            padding: 20px;
            margin: 20px 10px;
            border-radius: 5px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            flex: 1 1 calc(33.33% - 40px);
            box-sizing: border-box;
            max-width: calc(33.33% - 40px);
            text-align: center;
        }
        .contact-form {
            background: white;
            padding: 20px;
            margin: 20px 0;
            border-radius: 5px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        .contact-form input, .contact-form textarea {
            width: 100%;
            padding: 10px;
            margin: 10px 0;
            border: 1px solid #ccc;
            border-radius: 5px;
        }
        .contact-form button {
            background-color: #ff4500;
            color: white;
            padding: 10px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }
        .cart-button {
            background-color: #ff4500;
            color: white;
            padding: 10px 20px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            margin-top: 10px;
            display: block;
            width: 100%;
        }
    </style>
</head>
<body>
    <header>
        <h1>Інтернет-магазин насіння супер-гострих перців</h1>
    </header>
    <div class="container">
        <div class="product">
            <h2>Назва продукту 1</h2>
            <p>Опис продукту 1...</p>
            <button class="cart-button">Додати в кошик</button>
        </div>
        <div class="product">
            <h2>Назва продукту 2</h2>
            <p>Опис продукту 2...</p>
            <button class="cart-button">Додати в кошик</button>
        </div>
        <div class="product">
            <h2>Назва продукту 3</h2>
            <p>Опис продукту 3...</p>
            <button class="cart-button">Додати в кошик</button>
        </div>
        <div class="product">
            <h2>Назва продукту 4</h2>
            <p>Опис продукту 4...</p>
            <button class="cart-button">Додати в кошик</button>
        </div>
        <div class="product">
            <h2>Назва продукту 5</h2>
            <p>Опис продукту 5...</p>
            <button class="cart-button">Додати в кошик</button>
        </div>
        <div class="product">
            <h2>Назва продукту 6</h2>
            <p>Опис продукту 6...</p>
            <button class="cart-button">Додати в кошик</button>
        </div>
    </div>
    <div class="container">
        <div class="contact-form">
            <h2>Форма зворотного зв'язку</h2>
            <form action="submit_form.php" method="post">
                <label for="name">Ім'я:</label>
                <input type="text" id="name" name="name" required>
                <label for="phone">Номер телефону:</label>
                <input type="tel" id="phone" name="phone" required>
                <button type="submit">Відправити</button>
            </form>
        </div>
    </div>
</body>
</html>
