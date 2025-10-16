  <!DOCTYPE html> 
  <html>
  <head>
    <title>Product Landing Page</title>
    <link href="style.css"/>
  </head>
  <body>
   <h1 id="title">David's Cupcakes</h1> 
   <header id="header">
     <img id="header-img" src=https://raw.githubusercontent.com/CMULS/Product-Landing-Page/refs/heads/main/Copilot_20251016_131229.png"" alt="Logo">
    <nav id="nav-bar">
      <a class="nav-link" href="#header">Section 1</a>
      <a class="nav-link" href="#header-img">Section 2</a>
      <a class="nav-link" href="#video">Section 3</a>
      </nav>
    </header>
    
    <video id="video" src="product-video.mp4" controls></video>
    <form id="form" action="https://www.freecodecamp.com/email-submit">
      <input id="email" type="email" name="email" placeholder="Enter your email" required>
      <input id="submit" type="submit" value="Submit">
      </form>
      <section id="section 1">
        <h2>Red velvet Cupcakes</h2>
        <p>Our red velvet Cupcakes are going for dicounted fee of K8 each!</p>
     </section>
     <section id="section2">
        <h2>Vanila Cupcakes</h2>
        <p>Our vanila cupcakes are going for a discounted fee of K5 each!</p>
      </section>
      <section id"section3">
        <h2>Choc-chip Cupcakes</h2>
        <p>Our chocolate chip Cupcakes are going for a discounted fee of K10 each!</p>
        </section>
    </body>
    
    </html>
        <style>
     @media (max-width: 600px) {
        body {
        background-color: #00ff00;
      }
    }
    #header {
      padding: 30px;
      position: fixed;
      top: 0;
      width: 100%;
      align-items: center;
      justify-content: space-between;
    } 
    #header-img {
      height: 50px;
    } 
    #nav-bar {
      position: fixed;
      top: 0;
      width: 100%;
      background-color: #808080;
      display: flex;
    } 
    .nav-link {
      margin-right: 20px;
    } 
    #video {
      width: 100%;
      height: auto;
    } 
    #form {
      margin-top: 30px;
    } 
    #email {
      width: 400px;
      padding: 20px;
      margin-right: 20px;
    } 
    #submit {
      padding: 20px 30px;
      background-color: #808080;
      color: black;
      border: none;
      cursor: pointer;
    } 
    section { 
      padding: 50px;
    } 
    #header-img {
      margin-bottom: 10px;
    } 
    #email {
      width: 100%;
      margin-right: 0;
      margin-bottom: 20px;
    } 
    #submit { 
      width: 100%;
    }
    </style> 
