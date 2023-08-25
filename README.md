# Homepage-of-Netflix
<!DOCTYPE html>
<html>

<head>
    <title>Netflix Homepage</title>
    <link rel="stylesheet" type="text/css" href="styles.css">
</head>

<body>
    <header>
        <nav>
            <div class="logo">
                <img src="netflixlogo.jpeg" alt="Netflix Logo">
            </div>
            <ul class="nav-links">
                <li><a href="#">Home</a></li>
                <li><a href="#">TV Shows</a></li>
                <li><a href="#">Movies</a></li>
                <li><a href="#">New & Popular</a></li>
                <li><a href="#">My List</a></li>
            </ul>
        </nav>
    </header>



    #style.css
    
    body {
              margin: 0;
              padding: 0;
              font-family: Arial, sans-serif;
          }
          
          header {
              background-color: #000;
              padding: 20px;
          }
          
          .logo img {
              width: 120px;
          }
          
          .nav-links {
              display: flex;
              justify-content: flex-end;
              list-style: none;
              margin-top: 10px;
          }
          
          .nav-links li {
              margin-left: 15px;
          }
          
          .nav-links li a {
              color: #fff;
              text-decoration: none;
          }
          
          .hero-section {
              background-image: url("BG_netflix.jpg");
              background-size: cover;
              background-position: center;
              text-align: center;
              padding: 150px 0;
              color: #fff;
          }
          
          .hero-section h1 {
              font-size: 42px;
              margin-bottom: 20px;
          }
          
          .hero-section p {
              font-size: 18px;
              margin-bottom: 30px;
          }
          
          button {
              padding: 10px 20px;
              font-size: 16px;
              background-color: #e50914;
              color: #fff;
              border: none;
              border-radius: 5px;
              cursor: pointer;
          }
          
          footer {
              background-color: #333;
              color: #fff;
              text-align: center;
              padding: 20px;
          }
          
