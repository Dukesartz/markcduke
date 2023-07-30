<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <link rel="stylesheet" href="style.css" />
    <script
      src="https://kit.fontawesome.com/91f4d89934.js"
      crossorigin="anonymous"
    ></script>

    <title>MARK C DUKE</title>
  </head>
  <header>
    <nav class="navbar">
      <a href="#" class="nav-branding">MARK C DUKE</a>
      <ul class="sidebar">
        <li class="just" onclick="hidesidebar()">
          <a href="#"
            ><svg
              xmlns="http://www.w3.org/2000/svg"
              height="26"
              viewBox="0 -960 960 960"
              width="26"
              style="border: 1px solid black"
            >
              <path
                d="m249-207-42-42 231-231-231-231 42-42 231 231 231-231 42 42-231 231 231 231-42 42-231-231-231 231Z"
              />
            </svg>
          </a>
        </li>
        <li class="nav-item">
          <a href="index.html" class="nav-link">HOME</a>
        </li>
        <li class="nav-item">
          <a href="bio.html" class="nav-link">BIOGRAPHY</a>
        </li>
        <li class="nav-item"><a href="#" class="nav-link">GALLERY</a></li>
        <li class="nav-item">
          <a href="exh.html" class="nav-link">EXHIBITIONS</a>
        </li>
        <li class="nav-item">
          <a href="contact.html" class="nav-link">CONTACT</a>
        </li>
      </ul>
      <ul class="nav-menu">
        <li class="hideOnMobile">
          <a href="index.html">HOME</a>
        </li>
        <li class="hideOnMobile">
          <a href="bio.html">BIOGRAPHY</a>
        </li>
        <li class="hideOnMobile"><a href="#">GALLERY</a></li>
        <li class="hideOnMobile">
          <a href="exh.html">EXHIBITIONS</a>
        </li>
        <li class="hideOnMobile">
          <a href="contact.html">CONTACT</a>
        </li>

        <li class="menu-button" onclick="showsidebar()">
          <a href="#"
            ><svg
              xmlns="http://www.w3.org/2000/svg"
              height="26"
              viewBox="0 -960 960 960"
              width="26"
            >
              <path
                d="M120-240v-60h720v60H120Zm0-210v-60h720v60H120Zm0-210v-60h720v60H120Z"
              />
            </svg>
          </a>
        </li>
      </ul>
    </nav>
  </header>
  <body id="top">
    <div class="bio">
      <section class="hidden">
        <img src="bioimg.JPG" alt="" />
      </section>

      <div class="container">
        <h3>Biography</h3>
        <div class="text">
          Mark C Duke is a self-taught artist who is gaining recognition for his
          photorealistic art created using ballpoint pens. He was born on August
          10th in umuguma umunweanyi Owerri west imo state and is currently a
          student of imo state university computer science department. Duke has
          managed to carve out a niche for himself in the art world with his
          unique approach to ballpoint pen art and has experimented with various
          mediums including pencils and paints, but he prefers the ballpoint pen
          because of it's precision and ability to create fine lines.He has
          honed his skill over the years and has become a master of the
          craft.His art is highly detailed and often leaves viewers in awe of
          his talent.
        </div>
      </div>
    </div>
    <section class="hidden">
      <div class="bioy">
        <div class="test">
          <q
            >I aim to weave the narratives of resilence, optimism, and the
            triumph of the human spirit.</q
          >
        </div>
        <img src="ISMUE9636.JPG" loading="lazy" alt="" />
      </div>
    </section>
    <section class="hidden">
      <h2>Most frequently asked Question:</h2>
      <details class="big">
        <summary class="bold">
          How long does it take you to finish an art piece?
        </summary>
        <p class="power">A month, depending on how large my concept is...</p>
      </details>
    </section>

    <div class="ment">
      <span><h3>Artist Statement</h3></span>
      <div class="text">
        "Within the delicate interplay of pen and coffee, I embark on a creative
        journey centered on home Lorem ipsum dolor sit amet, consectetur
        adipisicing elit. Molestiae unde ex recusandae at. Sunt voluptatum
        praesentium culpa, doloribus corrupti, neque, unde non modi debitis eos
        exercitationem molestiae soluta ipsam amet?
      </div>
    </div>

    <div class="bioy">
      <img src="bioimg.JPG" alt="" />
    </div>

    <a class="gotopbtn" href="#"> <i class="fas fa-arrow-up"></i></a>
    <script src="open.js"></script>
    <footer>
      <p>
        Copyright &copy;
        <script>
          document.write(new Date().getFullYear());
        </script>
        Developed by MARK C DUKE
      </p>
    </footer>
  </body>
</html>
