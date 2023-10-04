<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css">
  <link rel="stylesheet" href="css/ss.css">

    <title>Responsive Navigation</title>
</head>
<body>
  
    <nav class="navbar navbar-expand-lg navbar-dark bg-danger ">
  <a class="navbar-brand" href="index.php">MS</a>
  <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNavAltMarkup" aria-controls="navbarNavAltMarkup" aria-expanded="false" aria-label="Toggle navigation">
    <span class="navbar-toggler-icon"></span>
  </button>
  <div class="collapse navbar-collapse" id="navbarNavAltMarkup">
    <div class="navbar-nav">
      <a class="nav-item nav-link active" href="index.php">Home <span class="sr-only">(current)</span></a>
      <a class="nav-item nav-link" href="th.html">total money</a>
    </div>
  </div>
</nav>

  <div class="container mt-5">
  <form action="" method="POST">
    <div class="form-group">
    <label for="exampleInputEmail1"></label>
    <input type="text" name="date" class="form-control" id="exampleInputEmail1" value="<?php echo 'djdu'; ?>">
   </div>
    <div class="form-group">
    <label for="exampleInputEmail1"></label>
    <input type="text" name="price" class="form-control text-success" id="exampleInputEmail1" value="100">
   </div>
    <div class="form-group">
    <label for="exampleInputEmail1"></label>
    <input type="text" name="kata" class="form-control text-success" id="exampleInputEmail1" aria-describedby="emailHelp" placeholder="Enter number of kata">
   </div>
    <br>
      
        
       <select class="form-control form-control" name="select">
      <option>please select</option>
      <option>મોળી કળી</option>
      <option>તીખી કળી</option>
      <option>મોળી ફાફડી</option>
      <option>તીખી ફાફડી</option>
      <option>જીણા ગાઠિયા</option>
      <option>જાડા ગાઠિયા</option>
      <option>સેવ</option>
    </select>
    
    <br>
    
    <button type="submit" name="btn" class="btn btn-primary">Submit</button>
</form>
  </div>
  
  
  
  
  
    <!-- Bootstrap JS and jQuery -->
    <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.11.6/dist/umd/popper.min.js"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
</body>
</html>
