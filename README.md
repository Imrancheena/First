
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>❤️Imran Ghani❤️</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background-color: #f4f4f4;
    }

   
    header {
      background-color: #222;
      color: #fff;
      text-align: center;
      padding: 30px 20px;
      font-size: 22px;
    }

   
    .main-content {
      padding: 60px 20px;
      text-align: center;
      color: #444;
      font-size: 18px;
    }

    footer {
      background-color: #333;
      color: #fff;
      padding: 40px 20px 20px 20px;
    }

    .footer-container {
      max-width: 1200px;
      margin: auto;
      display: flex;
      flex-wrap: wrap;
      justify-content: space-between;
    }

    .footer-box {
      flex: 1 1 250px;
      margin: 20px;
    }

    .footer-box ul {
      list-style: none;
      padding: 0;
    }

    .footer-box ul li {
      margin-bottom: 10px;
      font-size: 14px;
    }

    .footer-box ul li a {
      color: #ccc;
      text-decoration: none;
      transition: 0.3s;
    }

    .footer-box ul li a:hover {
      color: #fff;
    }

    .subscribe-box input[type="email"] {
      width: 80%;
      padding: 10px;
      margin-bottom: 10px;
      border: none;
      border-radius: 5px;
      
    }

    .subscribe-box button {
      padding: 10px 20px;
      color: white;
      background-color: #745959;
      border: none;
      border-radius: 5px;
      cursor: pointer;
      font-weight: bold;
    }

    .subscribe-box button:hover {
      background-color: #0c0c0c;
    }

    .bottom-nav {
      text-align: center;
      border-top: 1px solid #444;
      padding-top: 20px;
      margin-top: 20px;
      color: #aaa;
      font-size: 14px;
    }

    .bottom-nav a {
      color: #aaa;
      margin: 0 10px;
      text-decoration: none;
    }

    .bottom-nav a:hover {
      color: #fff;
    }

    /* Logo styles */
    .footer-logo {
      display: flex;
      align-items: center;
      margin-bottom: 20px;
    }

    .footer-logo img {
      width: 60px;
      height: 60px;
      margin-right: 10px;
      border-radius: 50%;
    }

    .footer-logo span {
      font-size: 22px;
      font-weight: bold;
      color: #ffcc00;
    }

   
    @media screen and (max-width: 768px) {
      .footer-container {
        flex-direction: column;
        align-items: center;
      }
      .footer-box {
        text-align: center;
      }
      .footer-logo {
        justify-content: center;
      }
    }
  </style>
</head>
<body>

<header>
  Welcome 
</header>


<div class="main-content">

</div>

<!-- Footer -->
<footer style="padding-top: 100px;margin-top: 100px;">
  <div class="footer-container">
   
    <div class="footer-box">
      <div class="footer-logo">
        <img src="DDH4.jpg" alt="LETBOLY Logo">
        <span>LETBOLY</span>
      </div>
    </div>

    
    <div class="footer-box subscribe-box">
      <p style="color: #745959;font-size: medium;">SUBSCRIPTION</P>
      <input type="email" id="email" placeholder="Your email address">
      <br>
      <button onclick="subscribe()">Subscribe</button>
    </div>

    <!-- Recent Posts -->
    <div class="footer-box">
      <p style="color: #745959;font-size: medium;">Recent Posts</p>
      <ul>
        <li ><a href="#"><b>BEAUTY OF NATURE</b> </a></li><p style="color: #745959; font-size: medium;"><i>July 22, 2015</i></p>
        <li><a href="#"><b>FASHION MODEL SHOOTS</b></a></li><p style="color: #745959; font-size: medium;"><i>July 22, 2015</i></p>
        <li><a href="#"><b>GOLDEN SNOW LAND </b></a></li><p style="color: #745959; font-size: medium;"><i>July 22, 2015</i></p>
      </ul>
    </div>

    <div class="footer-box">
      <p style="color: #745959;font-size: medium;">POPULAR POSTS</p>
      <ul>
        <li><a href="#"><b>TOP 10 INGREDIENTS</b> </a></li><p style="color: #745959; font-size: medium;"><i>July 22, 2015</i></p>
        <li><a href="#"><b>FAIMLY COMES FIRST</b> </a></li><p style="color: #745959; font-size: medium;"><i>July 22, 2015</i></p>
        <li><a href="#"><b>GOLDEN SNOW LAND</b> </a></li><p style="color: #745959; font-size: medium;"><i>July 22, 2015</i></p>
      </ul>
    </div>
  </div>

  <!-- Navigation -->
  <div class="bottom-nav">
    <a href="#">Home</a> |
    <a href="#">Lifestyle</a> |
    <a href="#">About</a> |
    <a href="#">Contact Me</a>
  </div>
</footer>

<!-- JavaScript -->
<script>
  function subscribe() {
    const email = document.getElementById('email').value;
    if (email.trim() === '') {
      alert('Please enter a valid email address.');
    } else {
      alert(`Subscribed successfully with: ${email}`);
      document.getElementById('email').value = '';
    }
  }
</script>

</body>
</html># First
