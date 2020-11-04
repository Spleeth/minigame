<!DOCTYPE html>
  <html>
    <head>
      <link rel="shortcut icon" href="favicon.ico" type="image/x-icon">
      <link rel="icon" href="favicon.png" type="image/png">
      <link rel="icon" sizes="32x32" href="favicon-32.png" type="image/png">
      <link rel="icon" sizes="64x64" href="favicon-64.png" type="image/png">
      <link rel="icon" sizes="96x96" href="favicon-96.png" type="image/png">
      <link rel="icon" sizes="196x196" href="favicon-196.png" type="image/png">
      <link rel="apple-touch-icon" sizes="152x152" href="apple-touch-icon.png">
      <link rel="apple-touch-icon" sizes="60x60" href="apple-touch-icon-60x60.png">
      <link rel="apple-touch-icon" sizes="76x76" href="apple-touch-icon-76x76.png">
      <link rel="apple-touch-icon" sizes="114x114" href="apple-touch-icon-114x114.png">
      <link rel="apple-touch-icon" sizes="120x120" href="apple-touch-icon-120x120.png">
      <link rel="apple-touch-icon" sizes="144x144" href="apple-touch-icon-144x144.png">
      <meta name="msapplication-TileImage" content="favicon-144.png">
      <meta name="msapplication-TileColor" content="#FFFFFF">
      <meta name="viewport" content="width=device-width, initial-scale=1">
    <style>
      .center {
      display: block;
      margin-left: auto;
      margin-right: auto;
      width: 50%;
    }
      body {font-family: Monaco, "Franklin Gothic Medium", monospace;}

      body {
        background-image: url('https://d2gg9evh47fn9z.cloudfront.net/800px_COLOURBOX14997032.jpg');
      }

      .button {
        background-color: #ddd;
        border: none;
        color: black;
        padding: 10px 20px;
        text-align: center;
        text-decoration: none;
        display: inline-block;
        margin: 500px 50%;
        cursor: pointer;
        border-radius: 16px;
      }

      .button:hover {
        background-color: #f1f1f1;
      }

      * {box-sizing: border-box;}

      body { 
        margin: 0;
        font-family: Arial, Helvetica, sans-serif;
      }

      .header {
        overflow: hidden;
        background-color: #f1f1f1;
        padding: 20px 10px;
      }

      .header a {
        float: left;
        color: black;
        text-align: center;
        padding: 12px;
        text-decoration: none;
        font-size: 18px; 
        line-height: 25px;
        border-radius: 4px;
      }

      .header a.logo {
        font-size: 25px;
        font-weight: bold;
      }

      .header a:hover {
        background-color: #ddd;
        color: black;
      }

      .header a.active {
        background-color: rgb(63, 63, 63);
        color: white;
      }

      .header-right {
        float: right;
      }

      @media screen and (max-width: 500px) {
        .header a {
          float: none;
          display: block;
          text-align: left;
        }
        
        .header-right {
          float: none;
        }
      }

      ::-moz-selection { /* Code for Firefox */
        color:white;
        background: gray;
    }

      ::selection {
        color: white;
        background: gray;
    }
    .container {
      position: relative;
      width: 50%;
    }

    /* Make the image responsive */
    .container img {
      width: 100%;
      height: auto;
    }

    /* Style the button and place it in the middle of the container/image */
    .container .btn {
      position: center;
      top: 50%;
      left: 50%;
      transform: translate(-50%, -50%);
      -ms-transform: translate(-50%, -50%);
      background-color: #555;
      color: white;
      font-size: 16px;
      padding: 12px 24px;
      border: none;
      cursor: pointer;
      border-radius: 5px;
    }

    .container .btn:hover {
      background-color: black;
    }
    </style>
    </head>
    <body>

      <div class="header">
        <a href="main.html" class="logo">Spleeth</a>
        <div class="header-right">
          <a class="active" href="main.html">Acceuil</a>
          <a href="projects.html">Mes Projets</a>
          <a href="#about">À propos</a>
        </div>
      </div>
    </body>
</html> 

