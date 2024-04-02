<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Check this out!</title>
<style>
  /* Style for the 3D text */
  .text-3d {
    font-family: Arial, sans-serif;
    font-size: 50px;
    text-align: center;
    color: #ffffff;
    text-shadow: 0 0 5px #ffffff, 0 0 10px #ffffff, 0 0 15px #ffffff, 0 0 20px #ff0000, 0 0 30px #ff0000, 0 0 40px #ff0000, 0 0 55px #ff0000, 0 0 75px #ff0000;
    animation: glow 1.5s infinite alternate;
  }
  
  @keyframes glow {
    from {
      text-shadow: 0 0 5px #ffffff, 0 0 10px #ffffff, 0 0 15px #ffffff, 0 0 20px #ff0000, 0 0 30px #ff0000, 0 0 40px #ff0000, 0 0 55px #ff0000, 0 0 75px #ff0000;
    }
    to {
      text-shadow: 0 0 10px #ffffff, 0 0 20px #ffffff, 0 0 30px #ffffff, 0 0 40px #ff0000, 0 0 50px #ff0000, 0 0 60px #ff0000, 0 0 70px #ff0000, 0 0 80px #ff0000;
    }
  }
</style>
<script>
function show3DText() {
  // Create a new element for the 3D text
  var text3D = document.createElement("div");
  text3D.className = "text-3d";
  text3D.textContent = "Eid Mubarak";
  // Append the 3D text element to the body
  document.body.appendChild(text3D);
}
</script>
</head>
<body>
<h1>Click <a href="#" onclick="show3DText()">here</a> to see something interesting!</h1>
</body>
</html>
