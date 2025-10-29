<!DOCTYPE html>   
<html>
<head>
  <title>Product Landing Page</title>
  <link rel="stylesheet" href="style.css" />
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
    }

    /* Header/Nav Bar Styling */
    #header {
      position: fixed;
      top: 0;
      width: 100%;
      background-color: #808080;
      display: flex;
      align-items: center;
      justify-content: space-between;
      padding: 10px 30px;
      box-sizing: border-box;
      z-index: 1000;
    }

    #header-img {
      height: 60px;
    }

    #nav-bar {
      display: flex;
      gap: 20px;
    }

    .nav-link {
      text-decoration: none;
      color: white;
      font-weight: bold;
      transition: color 0.3s;
    }

    .nav-link:hover {
      color: #ffcccb;
    }

    /* Title styling (moved below nav bar) */
    #title {
      margin-top: 120px;
      text-align: center;
    }

    /* Video styling */
    #video {
      width: 100%;
      height: auto;
    }

    /* Form styling */
    #form {
      margin-top: 30px;
      text-align: center;
    }

    #email {
      width: 300px;
      padding: 10px;
      margin-right: 10px;
    }

    #submit {
      padding: 10px 20px;
      background-color: #808080;
      color: white;
      border: none;
      cursor: pointer;
    }

    #submit:hover {
      background-color: #666666;
    }

    section { 
      padding: 50px;
      text-align: center;
    }

    /* Responsive for small screens */
    @media (max-width: 600px) {
      #header {
        flex-direction: column;
        align-items: flex-start;
      }

      #nav-bar {
        flex-direction: column;
        align-items: flex-start;
      }

      #email, #submit {
        width: 100%;
        margin: 5px 0;
      }
    }
          #img {
            width: 200px;
            height: 200px;
            object-fit: cover;
            border-radius: 50%;
            display: block;
            margin: 20px auto;
        } 
      
  </style>
</head>

<body>
  <header id="header">
    <img id="header-img" src="https://raw.githubusercontent.com/CMULS/Product-Landing-Page/refs/heads/main/Copilot_20251016_131229.png" alt="Logo">
    <nav id="nav-bar">
      <a class="nav-link" href="#section1">Section 1</a>
      <a class="nav-link" href="#section2">Section 2</a>
      <a class="nav-link" href="#section3">Section 3</a>
    </nav>
  </header>

  <h1 id="title">Dave's Cupcakes</h1> 

  <video id="video" src="product-video.mp4" controls></video>

  <form id="form" action="https://www.freecodecamp.com/email-submit">
    <input id="email" type="email" name="email" placeholder="Enter your email" required>
    <input id="submit" type="submit" value="Submit">
  </form>

  <section id="section1">
    <h2>Red Velvet Cupcakes</h2>
    <img id="img" src="https://raw.githubusercontent.com/CMULS/Product-Landing-Page/refs/heads/main/Copilot_20251016_145131.png" alt= "red velvet">
    <p>Our red velvet cupcakes are going for a discounted fee of $8 each!</p>
  </section>

  <section id="section2">
    <h2>Vanilla Cupcakes</h2>
    <img id="img" src="https://raw.githubusercontent.com/CMULS/Product-Landing-Page/refs/heads/main/Copilot_20251016_154915.png" alt= "vanilla">
    <p>Our vanilla cupcakes are going for a discounted fee of $5 each!</p>
  </section>

  <section id="section3">
    <h2>Choc-chip Cupcakes</h2>
    <img id="img" src="https://raw.githubusercontent.com/CMULS/Product-Landing-Page/refs/heads/main/Copilot_20251016_154900.png" alt= "chocolate chip">
    <p>Our chocolate chip cupcakes are going for a discounted fee of $10 each!</p>
  </section>
</body>
</html>

