# Valentine-website-
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Valentine's Day Proposal</title>
  <style>
    body {
      background-image: url('YOUR_IMAGE_LINK_HERE'); /* Replace with your background image link */
      background-size: cover;
      text-align: center;
      padding: 100px;
    }

    h1 {
      color: #fff;
      font-size: 36px;
    }

    button {
      font-size: 18px;
      margin-top: 20px;
      padding: 10px 20px;
      cursor: pointer;
    }

    #noButton {
      color: red;
    }

    #celebrateText {
      display: none;
      color: #fff;
      font-size: 24px;
      margin-top: 20px;
    }
  </style>
</head>
<body>
  <h1>Would you be my Val?</h1>
  <button id="yesButton" onclick="celebrate()">Yes</button>
  <button id="noButton" onclick="moveNo()">No</button>
  <div id="celebrateText">Yay! 🎉 Let's celebrate together!</div>

  <script>
    function celebrate() {
      document.getElementById('celebrateText').style.display = 'block';
    }

    function moveNo() {
      alert("Sorry, you can't say no to this!");
      // Feel free to add more interactive elements or animations here
    }
  </script>
</body>
</html>