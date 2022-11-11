# create-profile
<!DOCTYPE html>
<html>
<head>
	<title>Swazi Ink| Home</title>
	<link rel="stylesheet" type="text/css" href="../bootstrap/bootstrap.css">
	<link rel="stylesheet" type="text/css" href="../css/stylesheet.css">
</head>
<body>

	<nav class="navbar navbar-expand-md navbar-light fixed bg-warning" >
  <div class="container-fluid">
    <a class="navbar-brand active" href="#">Messages</a>
    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarCollapse" aria-controls="navbarCollapse" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarCollapse">
      <ul class="navbar-nav me-auto mb-2 mb-md-0">
        <li class="nav-item">
          <a class="nav-link" aria-current="page" href="#">Story Feed</a>
        </li>
        <li class="nav-item">
          <a class="nav-link active" href="#">Messages <span class="badge">5</span></a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#" tabindex="-1" aria-disabled="true">Notifications<span class="badge">55</span> </a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="">Profile</a>
        </li>
        <li class="dropdown">
              <a class="dropdown-toggle sm-hidden" data-toggle="dropdown" href=""> Options<span class="caret"></span></a>
             <ul class="dropdown-menu">
             <li><a href="#">follow</a></li>
             <li><a href="#">friends</a></li>
             <li><a href="#">update intrestes</a></li>
             <li class="divider"></li>
             <li><a href="#">learn More</a></li>
             </ul>
        </li>
        
      </ul>
     
      <form class="d-flex">
        <input class="form-control form-control-sm me-2" type="search" placeholder="Search" aria-label="Search">
        <button class="btn btn-sm btn-outline-success" type="submit">Search</button> 
      </form><a href="../index.html" class="btn btn-sm btn-outline-danger">Signout</a>
    </div>
  </div>
</nav>


<main class="flex-shrink-0">
  <div class="asticky-container">


<div class="">
  <div class="bg-gray"><img width="66" height="66" class="float-start" src="../img/user.ico">
    <div style="padding-left: 76 rem; padding-bottom: 6 rem;" class="">
  <h5>username</h5>
  <p>status + rating</p></div></div>
<!-- messages from database -->
  <div class=" message-tile">
    <p class=" message-received">hi how are you???</p>
    <p class="message-reply text-end">im okay hpow RE YOU?</p>
    <p class="message-received">all is well my man</p>
    <p class="message-reply text-end">hehehe</p>


    
  </div>
  
</div>



  </div>
</main>




<br><br><br>





<footer class="footer text-center mt-auto py-3 bg-light">
  <div class="container">
    <span class="text-dark"> a Swazi Ink Company | 2022 | ALL RIGHTS RESERVED | </span>
  </div>
</footer>

<script src="../bootstrap/bootstrap.bundle.min.js"></script>
</body>
</html>
