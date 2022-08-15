# Front-end-website
Website created using HTML, CSS
<!DOCTYPE html>
<html lang="en" dir="ltr">
  <head>
    <meta charset="utf-8">
    <title>FRIENDLY NEIGHBOURHOOD COLLEGE GUIDE</title>
    <link rel="stylesheet" href="style.css">
      <link rel="stylesheet" media="screen and (max-width:1170px)" href="phone.css">
  </head>
  <body>
    <nav id="navbar">
      <div id="logo">
        <img src="https://cdn.pixabay.com/photo/2016/09/16/19/16/hat-1674894__340.png">


      </div>
      <ul>
      <li class="item"><a href="#">Home</a></li>
      <li class="item"><a href="#">Services</a></li>
      <li class="item"><a href="#">About us</a></li>
      <li class="item"><a href="#">Contact us</a></li>



        </ul>
    </nav>
    <section id="home">
      <h1 class="h-primary">Welcome to your college guide</h1>
      <p>Confused? Overwhelmed? Need a guiding light? The transition from a naive school going student to a young, ambitious adult is enriching in its own ways. If you are new to this, don't worry! YOU GOT THIS! It surely gets a bit overwhelming at times but don't you worry, we are here to make your college life easy.</p>
      <p>Got a query? Don't bottle it up.</p>
    <button class="btn" >Shoot your queries</button>
    </section>

    <section class="services-container">
      <h1 class="h-primary center">Our services</h1>
      <div id="services">
        <div class="box">
          <img src="https://cdn.pixabay.com/photo/2022/03/28/05/34/teacher-7096632__340.png">
          <h2 class="h-secondary center">CONTACT YOUR PROFESSORS</h2>
          <p class="center">Faculties for you, just one click away.</p>
        </div>
        <div class="box">
          <img src="https://cdn.pixabay.com/photo/2016/01/27/04/32/books-1163695__340.jpg">
          <h2 class="h-secondary center">BUY/SELL OLD BOOKS</h2>
          <p class="center">We believe in the 3R's-Reduce,Reuse and Recycle!</p>
        </div>
        <div class="box">
          <img src="https://cdn.pixabay.com/photo/2018/09/21/13/11/checklist-3693113__340.jpg">
          <h2 class="h-secondary center">PLACEMENT GUIDANCE</h2>
          <p class="center">One step close to unlatching the door to success</p>
        </div>
      </div>
    </section>

    <section id="contact">
      <h1 class="h-primary center">Contact Us</h1>
      <div id="contact-box">
        <form action="">
          <div class="form-group">
            <label for="name">Name:</label>
            <input type="text" name="name" id="name" placeholder="Enter your name">
          </div>
        </form>
      </div>
    </section>
    <footer>
      <div class="center">
        Copyright &copy www.friendlyneighbourhoodcollegeguide.com. All rights reserved!

      </div>
    </footer>

  </body>
</html>
