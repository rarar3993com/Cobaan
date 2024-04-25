# Cobaan
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Perpustakaan</title>
  <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css">
  <link rel="stylesheet" href="Untitled-1.css">
</head>
<body>
  <nav class="navbar navbar-inverse">
    <div class="container-fluid">
      <div class="navbar-header">
        <button type="button" class="navbar-toggle" data-toggle="collapse" data-target="#myNavbar">
          <span class="icon-bar"></span>
          <span class="icon-bar"></span>
          <span class="icon-bar"></span>
        </button>
        <a class="navbar-brand" href="#">Perpustakaan Suka Baca</a>
      </div>
      <div class="collapse navbar-collapse" id="myNavbar">
        <ul class="nav navbar-nav">
          <li class="active"><a href="#">Beranda</a></li>
          <li class="dropdown">
            <a class="dropdown-toggle" data-toggle="dropdown" href="#">Menu <span class="caret"></span></a>
            <ul class="dropdown-menu">
              <li><a href="Modul 1 (fix).html">Modul 1</a></li>
            <li><a href="MODUL 2.html">Modul 2</a></li>
            <li><a href="modul 3.html">Modul 3</a></li>
            </ul>

          </li>
          <li><a href="#">Form Keanggotaan</a></li>
        </ul>
      </div>
    </div>
  </nav>
  
  <div class="container-fluid">
    <div class="row">
      <div class="col-md-4">
        <h2>SELAMAT DATANG DI PERPUSTAKAAN SUKA BACA</h2>
      </div>
      <div class="col-md-4">
        <h2>Data Anggota</h2>
        <table class="table table-bordered">
          <thead>
            <tr>
              <th>No</th>
              <th>Judul Buku</th>
              <th>Pengarang </th>
            </tr>
          </thead>
          <tbody>
            <tr>
              <td>1</td>
              <td>Hidup ini terlalu banyak kamu</td>
              <td>Pidi Baiq</td>
            </tr>
            <tr>
              <td>2</td>
              <td>Helen </td>
              <td>Pidi Baiq</td>
            </tr>
          </tbody>
        </table>
      </div>
      <div class="col-md-4">
        <h2>Form Keanggotaan</h2>
        <form>
          <div class="form-group">
            <label for="nama">Nama:</label>
            <input type="text" class="form-control" id="nama">
          </div>
          <div class="form-group">
            <label for="alamat">Alamat:</label>
            <input type="text" class="form-control" id="alamat">
          </div>
          <button type="submit" class="btn btn-default">Submit</button>
        </form>
      </div>
    </div>
  </div>

  <script src="https://ajax.googleapis.com/ajax/libs/jquery/1.12.4/jquery.min.js"></script>
  <script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/js/bootstrap.min.js"></script>
</body>
</html>
