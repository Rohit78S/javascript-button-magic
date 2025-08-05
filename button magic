<!DOCTYPE html>
<html>
<head>
<style>
  body {
    margin: 0;
    font-family: Arial, sans-serif;
    background: #f2f2f2;
    background-repeat: no-repeat;
    background-attachment: fixed;
  }

  .container {
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    text-align: center;
    padding: 20px;
  }

  .button-group {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    margin-top: 20px;
    gap: 10px;
  }

  button {
    width: 120px;
    height: 70px;
    background-color: black;
    color: white;
    font-size: 20px;
    text-align: center;
    box-shadow: 4px 4px 10px rgba(0, 0, 0, 0.4);
    transition: all 0.3s ease;
    border: none;
    border-radius: 10px;
    cursor: pointer;
  }

  button:hover {
    box-shadow: 2px 2px 8px rgba(0, 0, 0, 0.6);
    transform: translateY(-2px);
  }

  h1 {
    font-size: 36px;
    margin-bottom: 20px;
  }

  h1:hover {
    box-shadow: 2px 2px 8px rgba(0, 0, 0, 0.6);
    transform: translateY(-2px);
  }

  img {
    max-width: 90%;
    height: auto;
    border-radius: 10px;
    box-shadow: 0 4px 15px rgba(0, 0, 0, 0.2);
  }
</style>
</head>
<body>

<div class="container">
  <h1><i>Hey try it out</i></h1>
  <p>Click a button to change the image of Doraemon:)</p>

  <img id="myImage" src="https://hobbyindia.store/cdn/shop/products/MV5BZGM5MWM1MmUtZDM0ZC00Y2EwLWEwMzQtM2QwZDU4Yjc5ODJmXkEyXkFqcGdeQXVyMjgzNDQyMjE_._V1_1826d473-9611-49ff-8196-62ff1f6dca64_1200x1200.jpg?v=1721728847" width="400" height="500">

  <div class="button-group">
    <button onclick="doremon('stand')">Hello</button>
    <button onclick="doremon('walk')">Greeting</button> 
    <button onclick="doremon('happy')">Happy</button>   
    <button onclick="doremon('fly')">Bye</button> 
  </div>
</div>

<script>
function doremon(sw) {
  let pic;

  if (sw === "stand") {
    pic = "https://hobbyindia.store/cdn/shop/products/MV5BZGM5MWM1MmUtZDM0ZC00Y2EwLWEwMzQtM2QwZDU4Yjc5ODJmXkEyXkFqcGdeQXVyMjgzNDQyMjE_._V1_1826d473-9611-49ff-8196-62ff1f6dca64_1200x1200.jpg?v=1721728847";
  } else if (sw === "walk") {
    pic = "https://i.pinimg.com/originals/f9/35/e5/f935e5bba08c301cfac42235a419c54a.gif";
  } else if (sw === "happy") {
    pic = "https://i.pinimg.com/originals/eb/95/e2/eb95e2837964704d73cf82583915a4ea.gif";
  } else if (sw === "fly") {
    pic = "https://i.pinimg.com/originals/7a/2d/f3/7a2df393005784ae82886a596a93b07c.gif";
  } else {
    pic = "https://hobbyindia.store/cdn/shop/products/MV5BZGM5MWM1MmUtZDM0ZC00Y2EwLWEwMzQtM2QwZDU4Yjc5ODJmXkEyXkFqcGdeQXVyMjgzNDQyMjE_._V1_1826d473-9611-49ff-8196-62ff1f6dca64_1200x1200.jpg?v=1721728847";
  }

  document.getElementById('myImage').src = pic;
}
</script>

<footer style="background-color: #ffffff; color: #000000; padding: 20px; text-align: center;
               font-family: 'Brush Script MT', cursive; font-size: 40px;
               box-shadow: 0 -4px 10px rgba(0, 0, 0, 0.6);">
  <p style="text-shadow: 2px 2px 4px rgba(40, 38, 38, 0.244);">
    Designed and coded by 
    <span style="color: red; font-weight: bold;">Rohit</span>
  </p>
</footer>

</body>
</html>
