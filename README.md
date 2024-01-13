<!DOCTYPE html>
<html lang="en">
<head>
    
    <link rel="stylesheet" href="Buynow.css">
    
  
    <link rel="icon" type="image/png" href="logob.png">
    <title>Etherealla - Place Order</title>
</head>
<body>

    <header>
        
        <h1 class="logo" style="font-family: 'Malibu Sunset', cursive;">Etherealla ®</h1>
        <nav>
            <ul>
                <li><a href="homepage.html">Home</a></li>
                <li><a href="categories.html">Categories</a></li>
                <li><a href="cartpage.html">Cart</a></li>
            </ul>
        </nav>
    </header>

    <div class="main-content">
        <h2>Place Your Order</h2>

        <form action="process_order.php" method="post">
            <label for="firstName">First Name:</label>
            <input type="text" id="firstName" name="firstName" required>

            <label for="lastName">Last Name:</label>
            <input type="text" id="lastName" name="lastName" required>

            <label for="phoneNumber">Phone Number:</label>
            <input type="tel" id="phoneNumber" name="phoneNumber" required>

            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required>

            <label for="province">Province:</label>
            <input type="text" id="province" name="province" required>

            <label for="city">City:</label>
            <input type="text" id="city" name="city" required>

            <label for="address">Current Address:</label>
            <textarea id="address" name="address" rows="4" required></textarea>

            <label for="landmarks">Landmarks:</label>
            <input type="text" id="landmarks" name="landmarks">

            <button type="submit" class="place-order-btn">Place Order</button>
        </form>
    </div>

    <footer>
        <p>Contact Information:</p>
        <p>Number: 03270636029</p>
        <p>Email: srk@gmail.com</p>
        
        <p>Social Media Pages:</p>
        <p>Instagram: <a href="https://www.instagram.com/srkofficial_" target="_blank">@srkofficial_</a></p>
        <p>Facebook: <a href="https://www.facebook.com/shopatSRK" target="_blank">shopatSRK</a></p>
        <p>Twitter: <a href="https://twitter.com/SRKofficial" target="_blank">@SRKofficial</a></p>

       
        <button class="cart-btn"><a href="cartpage.html">Cart</a></button>
    </footer>

</body>
</html>
