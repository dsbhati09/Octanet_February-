Made a landing page for a gym website.

<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Fitness Freak - Best Gym in town</title>
    <!-- <link rel="stylesheet" href="style.css" /> -->
    <!-- <link rel="stylesheet" href="utils.css" /> -->
    <style>
      * {
        margin: 0;
        padding: 0;
        box-sizing: border-box;
      }
    
      nav {
        display: flex;
        justify-content: space-around;
        align-items: center;
        height: 70px;
        border: 1px solid black;
        background-color:rgb(28, 28, 28);
      }
      .logo {
        font: 50px;
        font-weight: bold;
        letter-spacing: 2px;
        background-image: url(Screenshot\ 2024-02-05\ 210434.png);
      }

      .menu * {
        text-decoration: none;
        font-size: 20px;
        color: black;
        background-color: rgb(231, 231, 224);
        margin: 5px;
        padding: 10px 20px;
        border-radius: 20px 0px 20px 0px;
        border: solid black 1px;
      }
      .container {
        display: flex;
        justify-content: center;
        align-items: center;
        background-image: url(sven-mieke-MsCgmHuirDo-unsplash.jpg);
        background-size: cover;
        background-position: center;
        background-repeat: no-repeat;
        height: auto;
      }
      .left,
      .right {
        flex-basis: 50%;
      }

      .left{
        padding: 100px 0px;
        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: start;
        gap: 3rem;
      }

      .left h1 {
        font-size: 50px;
        margin-bottom: 20px;
        color: white;
      }
      .left {
        max-width: 450px;
        padding-left: 70px;
      }

      .left p {
        font-size: 20px;
        margin-bottom: 20px;
        color: white;
      }
    </style>
  </head>
  <body>
    <header>
      <nav>
        <div class="logo">
          <img
            src="Screenshot 2024-02-05 210434.png"
            height="60px"
            width="60px"
          />
        </div>
        <div class="menu">
          <a href="#">Home</a>
          <a href="#">About</a>
          <a href="#">Contact us</a>
          <a href="#">login</a>
        </div>
      </nav>
      <div class="container">
        <div class="left">
          <h1>Unlock Your Potential with us, One Rep at a Time!</h1>
          <p>
            Welcome to our fitness community, where every rep counts towards
            your journey of self-discovery and empowerment.
          </p>
        </div>
        <div class="right"></div>
      </div>
    </header>
  </body>
</html>
