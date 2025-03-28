<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Add Cash</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: whitesmoke;
            margin: 0;
            padding: 0;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
        }

        .container {
            background: #fff;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
            width: 90%; /* Responsive width */
            max-width: 400px; /* Maximum width for larger screens */
            text-align: center;
        }

        h2 {
            margin-bottom: 20px;
        }

        #amountInput {
        width: 100%; /* Ensure it takes full width */
        padding: 10px;
        font-weight: bold;
        background-color: #F7F3F9;
        margin: 0 auto 20px; /* Add space below */
        font-size: 18px; /* Larger font size */
        border: 1px solid #ddd;
        border-radius: 50px;
        display: block;
        box-sizing: border-box; /* Ensures padding doesn't cause overflow */

        .balance-options {
            display: flex;
            justify-content: space-between;
            align-items: center;
        }

}


        .balance-options button {
            margin: 10px 5px;
            padding: 10px 20px;
            border: 1px solid #ddd;
            background: #f0f0f0;
            cursor: pointer;
            border-radius: 10px;
            font-weight: bold; /* Made text bold */
        }

        .balance-options button.selected {
            background: #007bff;
            color: white;
        }

        #bonusMessage {
            margin-top: 10px;
            font-size: 16px;
            color: #008000; /* Green color for bonus */
            font-weight: bold;
        }

        #totalAmountMessage {
            margin: 10px;
            font-size: 16px;
            color: #008000; /* Blue color for total amount */
            font-weight: bold;
        }

        #submitButton {
            padding: 15px;
            background: #008000; /* Green color for button */
            color: white;
            border: none;
            border-radius: 50px;
            cursor: pointer;
            width: 100%; /* Button spans full width */
            font-size: 16px; /* Larger font size */
            opacity: 0.5;
            pointer-events: none;
        }

        /* Image display styling */
        .hidden {
            display: none;
        }

        .message {
            margin-top: 15px;
            font-size: 14px;
            color: #ff0000; /* Red for error */
        }

        .message.success {
            color: #008000; /* Green for success */
        }
        .cashback {
            width: 100%; /* Ensure it takes full width */
            text-align:left;
            background-color: #E4D8F2
            ;
            font-size: 10px;
            margin: 0 auto 20px; /* Add space below */
            border: 1px solid #ddd;
            border-radius: 20px;
            display: block;
            box-sizing: border-box; 
        }
        .cash {
            margin-bottom: 0px;
            display: flex;
            align-items: center;
            justify-content: space-between;
            
        }
        .cou {
            color: green;
            font-size: 12px;
            font-weight: bold;
            margin-right: 10px;
        }
        #b {
            margin-left: 15px;
        }
        .up {
            font-weight: bold;
        }
        .pl {
            font-size: 12px;
            text-align: center;
            margin-left:10px ;

        }
        .ad {
            color: green;

        }
        #en {
            font-size: 12px;
            text-align: left ;
            margin-left: 15px;
            color: #555;
        }
        .py {
            margin-bottom: 20px;
            color: #007bff;
        }


        /* Responsive Design */
        @media (max-width: 768px) {
            .container {
                padding: 15px;
            }

            #amountInput {
                padding: 12px;
                font-size: 16px;
                font-weight: bold;
            }

            .balance-options button {
                padding: 8px 15px;
                font-size: 14px;
            }

            #submitButton {
                padding: 12px;
                font-size: 14px;
            }

            #bonusMessage, #totalAmountMessage {
                font-size: 14px;
            }
        }
    </style>
</head>
<body>

    <div class="container" id="mainContainer">
        <h2>Add Cash</h2>
        <h1 id="en">Enter Amount</h1>
        <input type="text" id="amountInput" placeholder="₹ Enter amount here" readonly />

        <div class="balance-options">
            <button type="button" onclick="selectAmount(500)">₹500</button>
            <button type="button" onclick="selectAmount(300)">₹300</button>
            <button type="button" onclick="selectAmount(100)">₹100</button>
        </div>

        <h1 class="pl">👥51253 Players <span class="ad">added cash today</span></h1>
            <div class="cashback">
                <h2 class="cash" id="b">% CASHMAGIC
                    <p class="cou">🎉Coupon Already Applied</p>
                </h2>
                <p class="up"id="b">Upto 70% Instant cashback</p>
                <p id="b">DEPOSIT MINIMUM ₹100</p>
                <P id="b">APPLICABLE ONCE IN 24 HOURS(S)</P>
            </div>
            <div id="bonusMessage"></div> <!-- Bonus message section -->
            <div id="totalAmountMessage"></div> <!-- Total amount message section -->

        <button type="button" id="submitButton" onclick="showImage()">Add Money</button>
    </div>

    <div class="image-container hidden" id="imageContainer">
        <h2 class="py">Payment Confirmation</h2>
        <p style="color: #008000; font-weight: bold; text-align: center; font-size: 12px;"> No Risk... 100% Secure </p>
        <img id="displayImage" src="" alt="Selected Amount Image">
    </div>

    <script>
        let selectedAmount = null;

        function selectAmount(amount) {
            selectedAmount = amount;
            document.getElementById('amountInput').value = `₹${amount}`;

            document.querySelectorAll('.balance-options button').forEach(button => {
                button.classList.remove('selected');
            });

            event.target.classList.add('selected');
            enableSubmitButton();
        
        // Calculate and display bonus
        const bonusMessage = document.getElementById('bonusMessage');
            const totalAmountMessage = document.getElementById('totalAmountMessage');
            const bonus = Math.floor(amount * 0.7); // Calculate 70% bonus
            const totalAmount = amount + bonus; // Add balance + bonus

            bonusMessage.textContent = `You get a bonus of ₹${bonus}!`;
            totalAmountMessage.textContent = `Your total amount is ₹${totalAmount}!`;
        }

        function enableSubmitButton() {
            const submitButton = document.getElementById('submitButton');
            submitButton.style.opacity = '1';
            submitButton.style.pointerEvents = 'auto';
        }

        function showImage() {
            if (!selectedAmount) return;

            let imagePath = "";
            if (selectedAmount === 500) {
                imagePath = "img5.png";
            } else if (selectedAmount === 300) {
                imagePath = "img3.png";
            } else if (selectedAmount === 100) {
                imagePath = "img1.png";
            }

            document.getElementById("displayImage").src = imagePath;

            // Hide everything else
            document.getElementById("mainContainer").classList.add("hidden");
            document.getElementById("imageContainer").classList.remove("hidden");
        }
    </script>

</body>
</html>
