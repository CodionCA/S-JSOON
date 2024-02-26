---
layout: soon
permalink: /
---
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>HP Speed</title>
    <style>
        body {
            font-family: Genos, sans-serif;
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        h1 {
            text-align: center;
            margin-top: 0;
        }
		h2 {
            text-align: center;
            margin-top: 0;
			font-size: 50px;
        }
        button {
            color: #ffffff;
            background-color: #2d63c8;
            font-size: 19px;
            border: 4px solid #89a9e4;
            border-radius: 32px;
            padding: 15px 50px;
            cursor: pointer;
            margin-top: 55px;
        }
        button:hover {
            color: #2d63c8;
            background-color: #ffffff;
        }
        p {
            text-align: center;
            margin-top: 20px;
        }
    </style>
</head>
<body>
    <h1>HP Speed</h1>
	<h2>Coming soon</h2>
    <button type="button" name="Email" onclick="openContact('mailto:info@hpspeed.ca')">Email Us</button>
    <button type="button" name="Call us" onclick="openContact('tel:6136407223')">Call Us</button>
    <p>info@hpspeed.ca / 613-640-7223</p>
    <script>
        function openContact(contactType) {
            window.location.href = contactType;
        }
    </script>
</body>
</html>



