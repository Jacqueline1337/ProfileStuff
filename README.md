<!DOCTYPE html>
<html>
<head>
<style>
html {
  box-sizing: border-box;
}

*, *:before, *:after {
  box-sizing: inherit;
}

.column {
  float: left;
  width: 33.3%;
  margin-bottom: 16px;
  padding: 0 8px;
}

@media (max-width: 650px) {
  .column {
    width: 100%;
    display: block;
  }
}

.card {
  box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2);
}

.container {
  padding: 0 16px;
}

.container::after, .row::after {
  content: "";
  clear: both;
  display: table;
}

.title {
  color: grey;
}

.button {
  border: none;
  outline: 0;
  display: inline-block;
  padding: 8px;
  color: white;
  background-color: #000;
  text-align: center;
  cursor: pointer;
  width: 100%;
}

.button:hover {
  background-color: #555;
}
</style>
</head>
<body>

<br>

<div class="row">
  <div class="column" <div style="background-color: #FFFF00; style="width:100%">
    <div class="card">
      <img src= alt="Vanesa" style="width:100%">
      <div class="container">
        <h2><font color="#153631">Vanesa Marar</h2>
        <p class="title">Co-Founder</p>
        <p><font color="#153631">As a </p>
        <p>mararvan000@auburnsd.org</p>  
        <p><button class="button">Contact</button></p>
      </div>
    </div>
  </div>

  <div class="column" <div style="background-color: #B9D9BD; style="width:100%">
    <div class="card" >
	   <img src= alt="Jacqueline" style="width:100%">
      <div class="container">
        <h2>Jacqueline Marchan</h2>
        <p class="title">Co-Founder</p>
        <p><font color="white">I am a motivated future leader that is ready to take on even the more grueling challenges!</p>
        <p>marchjac000@auburnsd.org</p>  
        <p><button class="button">Contact</button></p>
      </div>
    </div>
  </div>
  <div class="column" <div style="background-color: #383a87; style="width:100%">
    <div class="card">
      <img src= alt="Julia" style="width:100%">
      <div class="container">
        <h2 style="font-family:Cookie;"><font color="white
       ">Julia Devine</h2>
        <p class="title">Co-Founder</p>
        <p><font color="white">A STEM fanatic and competitive dancer, Julia is always on the lookout for innovation.</p>
        <p>example@example.com</p> 
        <p><button class="button">Contact</button></p>
      </div>
    </div>
  </div>
</div>

</body>
</html>
