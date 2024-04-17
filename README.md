<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Self-Raising Moms Money Making Help</title>
    <style>
        /* Add your CSS styles here */
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #ffcccc; /* Light red background */
        }

        header {
            background-color: #ff3333; /* Red header */
            color: #fff;
            padding: 20px;
            text-align: center;
        }

        nav {
            background-color: #ff6666; /* Slightly darker red navigation bar */
            padding: 10px;
            text-align: center;
        }

        nav a {
            color: #fff;
            text-decoration: none;
            margin: 0 10px;
            font-weight: bold; /* Make navigation links bold */
        }

        nav a:hover {
            text-decoration: underline;
        }

        main {
            padding: 20px;
            text-align: center;
        }

        footer {
            background-color: #ff3333; /* Red footer */
            color: #fff;
            padding: 10px;
            text-align: center;
            position: fixed;
            bottom: 0;
            width: 100%;
        }

        .signup-form {
            margin-top: 20px;
        }

        .signup-form button {
            background-color: #ff6666; /* Red button */
            color: #fff;
            padding: 10px 20px;
            border: none;
            border-radius: 5px;
            font-size: 16px;
            cursor: pointer;
        }

        .signup-form button:hover {
            background-color: #ff5050; /* Darker red on hover */
        }

        .paypal-container {
            margin-top: 20px;
        }
    </style>
    <!-- PayPal button script -->
    <script src="https://www.paypal.com/sdk/js?client-id=BAA-QBwNkzsqj9eemGI50fTue_8uTJXi6iwMePiUoVuDZ4gJqzpvhBKe2yl9rpS13h07F3MMBRVmJHmSE8&components=hosted-buttons&disable-funding=venmo&currency=USD"></script>
</head>

<body>
    <header>
        <h1>Self-Raising Moms Money Making Help</h1>
    </header>

    <nav>
        <a href="#">Home</a>
        <a href="#">About</a>
        <a href="#">Services</a>
        <a href="#">Contact</a>
    </nav>

    <main>
        <h2>Welcome to Self-Raising Moms Money Making Help!</h2>
        <p>We provide personalized assistance and guidance to help self-raising moms make money from home.</p>
        <p>Our expert advisors will work with you to develop a customized plan tailored to your skills and interests.</p>
        <p>To get started, sign up for our services for only $9.99!</p>
        <!-- PayPal button container -->
        <div class="paypal-container" id="paypal-container-3TRXN9WJUBDAG"></div>
        <!-- PayPal button rendering script -->
        <script>
            paypal.HostedButtons({
                hostedButtonId: "3TRXN9WJUBDAG",
            }).render("#paypal-container-3TRXN9WJUBDAG")
        </script>
        <form class="signup-form" action="https://www.paypal.com/ncp/payment/3TRXN9WJUBDAG">
            <button type="submit">Sign Up Now</button>
        </form>
    </main>

    <footer>
        &copy; 2024 Self-Raising Moms Money Making Help
    </footer>
</body>

</html>

