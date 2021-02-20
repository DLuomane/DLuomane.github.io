<!DOCTYPE html>
<html lang="en">
<head>
  <title>Urheilu</title>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css">
  <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.5.1/jquery.min.js"></script>
  <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.16.0/umd/popper.min.js"></script>
  <script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
  <style>
      body {
          background-color: gainsboro;
      }
      h1 {
          color: black;
          text-align: center;
          text-transform: uppercase;
      }
      h2 {
          text-align: center;
      }
      p {
          text-align: center;
      }
      .kuva {
          display: block;
          margin-left: auto;
          margin-right: auto;
          width: 50%;
          }
  </style>
</head>
<body>

<nav class="navbar navbar-expand-sm bg-dark navbar-dark">
  <a class="navbar-brand" href="http://cs.uef.fi/~henrhyva/etusivu.html#">UUTISET</a>
  <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#collapsibleNavbar">
    <span class="navbar-toggler-icon"></span>
  </button>
  <div class="collapse navbar-collapse" id="collapsibleNavbar">
    <ul class="navbar-nav">
      <li class="nav-item">
        <a class="nav-link" href="http://cs.uef.fi/~henrhyva/etusivu.html#">Etusivu</a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="http://cs.uef.fi/~henrhyva/kotimaa.html#">Kotimaa</a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="http://cs.uef.fi/~henrhyva/urheilu.html#">Urheilu</a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="http://cs.uef.fi/~henrhyva/yhteystiedot.html#">Yhteystiedot</a>
      </li>
      <li>
      <a href="https://fi.wikipedia.org/wiki/Ruotsi"><img src="https://upload.wikimedia.org/wikipedia/en/4/4c/Flag_of_Sweden.svg" width="60" height="40" alt=""></a>
      </li>
    </ul>
  </div>  
</nav>

<h1>Ota yhteyttä!</h1>

<div class="container-fluid" style="height: 70vh">
    <div class="row">
        <div class="col-sm-8" style="background-color: lavender">
            <h2>UUTISET</h2><br>
            <p>Keskuskatu 2</p>
            <p>00100 Helsinki</p><br>
            <p>Puh. 012345678</p>
            <p>uutiset@uutiset.fi</p><br>
            <img src="https://cdn.pixabay.com/photo/2012/11/08/07/20/protection-65340_1280.jpg" alt="" style="width: 80%; height: 40%;" class="kuva">
        </div>
        <div class="col-sm-4" style="background-color: thistle">
            <form>
                <div class="form-group">
                    <label for="nimi">Nimi:</label>
                    <input type="text" id="nimi" name="nimi" class="form-control">
                </div>
                <div class="form-group">
                    <label for="sposti">Sähköposti:</label>
                    <input type="email" id="sposti" name="sposti" class="form-control">
                </div>
                <div class="form-group">
                    <label for="viesti">Viesti:</label>
                    <input type="text" id="viesti" name="viesti" class="form-control">
                </div>
                <input type="submit" value="Lähetä" class="btn btn-primary"><br><br>
              </form>
        </div>
    </div>
</div>

</body>
</html>
