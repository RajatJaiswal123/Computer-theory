<!DOCTYPE html>
<td="en">

    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>Indian Flag</title>
        <link rel="stylesheet" href="styles.css">
    </head>
    <style>
        body {
            display: flex;
            height: 100vh;
            background-color: #f0f0f0;
            margin: 0;
            font-family: Arial, sans-serif;
        }
        
        .stripe {
            height: 100px;
            width: 100%;
        }
        
        .saffron {
            margin-top: 300px;
            background-color: #FF9933;
            width: 1150px;
        }
        
        .white {
            background-color: white;
            position: relative;
            width: 1150px;
        }
        
        .green {
            background-color: #138808;
            width: 1150px;
        }
        /* Ashoka Chakra */
        
        .spokes-container {
            position: relative;
            height: 100%;
            width: 100%;
            display: flex;
            justify-content: center;
            align-items: center;
        }
        
        .spoke {
            position: absolute;
            height: 35px;
            width: 2px;
            background-color: #000080;
            transform-origin: 50% 100%;
        }
        
        .spoke:nth-child(1) {
            transform: rotate(0deg);
        }
        
        .spoke:nth-child(2) {
            transform: rotate(15deg);
        }
        
        .spoke:nth-child(3) {
            transform: rotate(30deg);
        }
        
        .spoke:nth-child(4) {
            transform: rotate(45deg);
        }
        
        .spoke:nth-child(5) {
            transform: rotate(60deg);
        }
        
        .spoke:nth-child(6) {
            transform: rotate(75deg);
        }
        
        .spoke:nth-child(7) {
            transform: rotate(90deg);
        }
        
        .spoke:nth-child(8) {
            transform: rotate(105deg);
        }
        
        .spoke:nth-child(9) {
            transform: rotate(120deg);
        }
        
        .spoke:nth-child(10) {
            transform: rotate(135deg);
        }
        
        .spoke:nth-child(11) {
            transform: rotate(150deg);
        }
        
        .spoke:nth-child(12) {
            transform: rotate(165deg);
        }
        
        .spoke:nth-child(13) {
            transform: rotate(180deg);
        }
        
        .spoke:nth-child(14) {
            transform: rotate(195deg);
        }
        
        .spoke:nth-child(15) {
            transform: rotate(210deg);
        }
        
        .spoke:nth-child(16) {
            transform: rotate(225deg);
        }
        
        .spoke:nth-child(17) {
            transform: rotate(240deg);
        }
        
        .spoke:nth-child(18) {
            transform: rotate(255deg);
        }
        
        .spoke:nth-child(19) {
            transform: rotate(270deg);
        }
        
        .spoke:nth-child(20) {
            transform: rotate(285deg);
        }
        
        .spoke:nth-child(21) {
            transform: rotate(300deg);
        }
        
        .spoke:nth-child(22) {
            transform: rotate(315deg);
        }
        
        .spoke:nth-child(23) {
            transform: rotate(330deg);
        }
        
        .spoke:nth-child(24) {
            transform: rotate(345deg);
        }
        /* CSS */
        /* Add this to existing CSS */
        
        @keyframes rotateChakra {
            from {
                transform: rotate(0deg);
            }
            to {
                transform: rotate(360deg);
            }
        }
        
        .ashoka-chakra {
            position: absolute;
            top: 20%;
            left: 50%;
            transform: translate(-50%, -50%);
            height: 70px;
            width: 70px;
            border: 3px solid #0101f7;
            border-radius: 50%;
            animation: rotateChakra 5s linear infinite;
            /* Chakra rotation */
        }
        /* Global Styling */
        
        body,
        html {
            margin: 0;
            padding: 0;
            height: 100%;
            display: flex;
            justify-content: center;
            align-items: center;
            background-color: #f4f4f4;
            font-family: 'Poppins', sans-serif;
        }
        
        .container {
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            background: linear-gradient(45deg, #FF9933, white, #138808);
        }
        /* Stylish India Text */
        
        .stylish-text {
            font-size: 100px;
            font-weight: bold;
            letter-spacing: 5px;
            color: #000080;
            background: linear-gradient(to right, #FF9933, #FFFFFF, #138808);
            -webkit-background-clip: text;
            color: transparent;
            animation: textAnimation 3s ease-in-out infinite;
            transition: all 0.5s ease-in-out;
            position: relative;
        }
        /* Shadow Effects */
        
        .stylish-text::before {
            content: 'India';
            position: absolute;
            top: 0;
            left: 0;
            right: 0;
            bottom: 0;
            background: inherit;
            -webkit-background-clip: text;
            color: rgba(0, 0, 0, 0.1);
            z-index: -1;
            filter: blur(10px);
        }
        /* Text Glow Effect on Hover */
        
        .stylish-text:hover {
            text-shadow: 0 0 50px rgba(255, 255, 255, 0.8);
            transform: scale(2.1);
        }
        /* Keyframes Animation for the Text Gradient */
        
        @keyframes textAnimation {
            0% {
                background-position: 0%;
            }
            100% {
                background-position: 400%;
            }
        }
        /* Making the Text Glow */
        
        .stylish-text:hover {}
    </style>


    <script src="script.js">
        document.querySelector('.stylish-text').addEventListener('click', () => {
            alert('You clicked on India!');
        });
    </script>


    <body>


        <table>
            <tr>
                <>
                    <div>



                        <div class="flag-container">
                            <!-- Saffron Band -->
                            <div class="stripe saffron"></div>

                            <!-- White Band with Ashoka Chakra -->
                            <div class="stripe white">
                                <div class="ashoka-chakra">
                                    <div class="2D spin">
                                        <div class="outer-circle"></div>
                                        <div class="spokes-container">
                                            <div class="wheel-container">
                                                <div class="wheel">

                                                    <div class="spoke"></div>
                                                    <div class="spoke"></div>
                                                    <div class="spoke"></div>
                                                    <div class="spoke"></div>
                                                    <div class="spoke"></div>
                                                    <div class="spoke"></div>
                                                    <div class="spoke"></div>
                                                    <div class="spoke"></div>
                                                    <div class="spoke"></div>
                                                    <div class="spoke"></div>
                                                    <div class="spoke"></div>
                                                    <div class="spoke"></div>
                                                    <div class="spoke"></div>
                                                    <div class="spoke"></div>
                                                    <div class="spoke"></div>
                                                    <div class="spoke"></div>
                                                    <div class="spoke"></div>
                                                    <div class="spoke"></div>
                                                    <div class="spoke"></div>
                                                    <div class="spoke"></div>
                                                    <div class="spoke"></div>
                                                    <div class="spoke"></div>
                                                    <div class="spoke"></div>
                                                    <div class="spoke"></div>

                                                </div>
                                            </div>
                                        </div>
                                    </div>
                                </div>
                            </div>

                            <!-- Green Band -->
                            <div class="stripe green"></div>
                        </div>

                    </div>
                    </td>
            </tr>

            <tr>

                <div class="container">
                    <h1 class="stylish-text">India</h1>
                </div>

            </tr>
        </table>






    </body>

    </html>
