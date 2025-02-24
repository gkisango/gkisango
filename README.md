<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tenfi - Wholesale Query</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            text-align: center;
            padding: 20px;
        }
        .container {
            background: white;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0px 0px 10px rgba(0, 0, 0, 0.1);
            max-width: 400px;
            margin: auto;
        }
        input, select {
            width: 100%;
            padding: 10px;
            margin: 10px 0;
            border: 1px solid #ccc;
            border-radius: 5px;
        }
        button {
            background: #28a745;
            color: white;
            padding: 10px;
            border: none;
            width: 100%;
            cursor: pointer;
        }
        button:hover {
            background: #218838;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Welcome to Tenfi</h1>
        <h2>Submit Your Wholesale Query</h2>
        <form action="https://formsubmit.co/info@tenfi.co.ke" method="POST">
            <input type="text" name="name" placeholder="Your Name" required>
            <input type="tel" name="phone" placeholder="Your Phone Number" required>
            <input type="text" name="location" placeholder="Your Location" required>

            <label for="product">What product are you interested in?</label>
            <select name="product" id="product" required>
                <option value="" disabled selected>Select a product</option>
                <option value="New Clothes">New Clothes</option>
                <option value="Mitumba Clothes">Mitumba Clothes</option>
                <option value="New Shoes">New Shoes</option>
                <option value="Mitumba Shoes">Mitumba Shoes</option>
                <option value="Kitchenware">Kitchenware</option>
            </select>

            <input type="hidden" name="_captcha" value="false"> 
            <input type="hidden" name="_next" value="https://tenfi.co.ke/thank-you.html">
            <button type="submit">Submit</button>
        </form>
    </div>
</body>
</html>
