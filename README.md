<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Checkout - Maaz Masood</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }
        .container {
            width: 80%;
            margin: auto;
            overflow: hidden;
        }
        header {
            background: #35424a;
            color: #ffffff;
            padding-top: 30px;
            min-height: 70px;
            border-bottom: #e8491d 3px solid;
        }
        header a {
            color: #ffffff;
            text-decoration: none;
            text-transform: uppercase;
            font-size: 16px;
        }
        header ul {
            padding: 0;
            list-style: none;
        }
        header li {
            display: inline;
            padding: 0 20px 0 20px;
        }
        .showcase {
            min-height: 400px;
            background: url('https://via.placeholder.com/1200x400') no-repeat 0 -400px;
            text-align: center;
            color: #ffffff;
        }
        .showcase h1 {
            margin-top: 100px;
            font-size: 55px;
            margin-bottom: 10px;
        }
        .main-content {
            padding: 30px;
            background: #ffffff;
            text-align: center;
        }
        .main-content h2 {
            margin-top: 0;
        }
        .payment-methods {
            display: flex;
            justify-content: space-around;
            flex-wrap: wrap;
        }
        .payment-method {
            background: #e2e2e2;
            padding: 20px;
            margin: 10px;
            border-radius: 8px;
            width: 45%;
            box-sizing: border-box;
        }
        .note {
            margin-top: 20px;
        }
    </style>
</head>
<body>
    <header>
        <div class="container">
            <h1>Checkout - Maaz Masood</h1>
        </div>
    </header>

    <section class="showcase">
        <div class="container">
            <h1>Complete Your Purchase</h1>
        </div>
    </section>

    <div class="container main-content">
        <h2>Select Your Payment Method</h2>
        <div class="payment-methods">
            <div class="payment-method">
                <h3>Payoneer (For International Users)</h3>
                <p>Account Holder Name: Maaz Masood</p>
                <p>Account Number: [Your Payoneer Account Number]</p>
                <p>Note: Please send a screenshot as payment proof.</p>
            </div>
            <div class="payment-method">
                <h3>JazzCash (For Pakistanis)</h3>
                <p>Account Holder Name: Maaz Masood</p>
                <p>Account Number: [Your JazzCash Account Number]</p>
                <p>Note: Please send a screenshot as payment proof.</p>
            </div>
        </div>
        <div class="note">
            <p><strong>Note:</strong> Send me a screenshot as a payment proof.</p>
        </div>
    </div>
</body>
</html>
