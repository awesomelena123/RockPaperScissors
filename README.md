# RockPaperScissors
Rock, Paper, Scissors-- Web edition
<!DOCTYPE html>
<html>
<head>
   <!-- Required meta tags -->
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">
  <link href="https://fonts.googleapis.com/css?family=Kumar+One+Outline" rel="stylesheet"> 
  <link href="https://fonts.googleapis.com/css?family=Amatic+SC|Cinzel" rel="stylesheet">
  <link href="https://stackpath.bootstrapcdn.com/bootstrap/4.1.3/css/bootstrap.min.css" integrity="sha384-MCw98/SFnGE8fJT3GXwEOngsV7Zt27NXFoaoApmYm81iuXoPkFOJwJ8ERdknLPMO" crossorigin="anonymous">
  <link href="https://fonts.googleapis.com/css?family=Dancing+Script" rel="stylesheet">
  <style>
    /* YOUR CSS GOES HERE */
    body{
      background:#bddef9;
    }
    #title_header {
      font-family:'Kumar One Outline', cursive;
      color: #FFD700;
    }
     #secondtitle_header {
      font-family: 'Cinzel', serif;
      color:#3a5872;
    }
    button {
      font-family: 'Gochi Hand', cursive;

      background-color: #800080;
      color: white;
    }
  </style>
</head>
<body>
  <!-- Elena, make me Rock Paper -->
  <!-- OUR HTML GOES HERE -->
  <h1 id="title_header">Rock, Paper, Scissors</h1>

  <p id= "secondtitle_header">What is your choice?</p>
  <button onclick="myFunction('rock');"><strong>Rock</strong></button>
  <button onclick="myFunction('paper')"><strong>Paper</strong></button>
  <button onclick="myFunction('scissors')"><strong>Scissors</strong></button>
  <p>
    <a href=""></a>
  </p>
<script src="https://code.jquery.com/jquery-3.3.1.slim.min.js" integrity="sha384-q8i/X+965DzO0rT7abK41JStQIAqVgRVzpbzo5smXKp4YfRvH+8abtTE1Pi6jizo" crossorigin="anonymous"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.14.3/umd/popper.min.js" integrity="sha384-ZMP7rVo3mIykV+2+9J3UJ46jBk0WLaUAdn689aCwoqbBJiSnjAK/l8WvCWPIPm49" crossorigin="anonymous"></script>
<script src="https://stackpath.bootstrapcdn.com/bootstrap/4.1.3/js/bootstrap.min.js" integrity="sha384-ChfqqxuZUCnJSK3+MXmPNIyE6ZbWh2IMqE241rYiqJxyMiZ6OW/JmZQ5stwEULTy" crossorigin="anonymous"></script>
<script>
  // Our JavaScript GOES HERE
  function myFunction() {
    alert("hello, world");
  }
  

</script>
</body>
</html>
