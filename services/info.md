<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <meta name="author" content="Sidharth Sreekumar" />
    <meta http-equiv="X-UA-Compatible" content="ie=edge" />
    <title>Acme Web Design | Services</title>
    <link rel="stylesheet" href="./css/style.css" />
  </head>
  <body>
    <header>
      <div class="container">
        <div id="branding">
          <h1 id="title"><span class="highlight">Acme</span> Web Design</h1>
        </div>
        <nav>
          <ul>
            <li><a href="index.html">Home</a></li>
            <li><a href="about.html">About</a></li>
            <li class="current"><a href="services.html">Services</a></li>
          </ul>
        </nav>
      </div>
    </header>
    <section id="main">
      <div class="container">
        <article id="main-col">
          <h1 class="page-title">Services</h1>
          <ul id="services">
            <li>
              <h3 id="webdesign">Web Design</h3>
              <p>
                Lorem ipsum dolor sit, amet consectetur adipisicing elit.
                Inventore magnam eos dolorem officia, non aliquid quos dicta
                quod voluptatum laudantium voluptate repellat fugit modi atque
                animi possimus laborum autem obcaecati.
              </p>
              <p>Pricing $250 - $300</p>
            </li>
            <li>
              <h3 id="webmain">Website Maintenance</h3>
              <p>
                Lorem ipsum dolor sit, amet consectetur adipisicing elit.
                Inventore magnam eos dolorem officia, non aliquid quos dicta
                quod voluptatum laudantium voluptate repellat fugit modi atque
                animi possimus laborum autem obcaecati.
              </p>
              <p>Pricing $500 - $100</p>
            </li>
            <li>
              <h3 id="webhosting">Website Hosting</h3>
              <p>
                Lorem ipsum dolor sit, amet consectetur adipisicing elit.
                Inventore magnam eos dolorem officia, non aliquid quos dicta
                quod voluptatum laudantium voluptate repellat fugit modi atque
                animi possimus laborum autem obcaecati.
              </p>
              <p>Pricing $25 per month</p>
            </li>
          </ul>
        </article>
        <aside id="sidebar">
          <div class="dark">
            <h3>Get a Quote</h3>
            <form action="" class="quote">
              <div>
                <label>Name</label><br />
                <input class="form_fix" type="text" placeholder="Name" />
              </div>
              <div>
                <label>Email</label><br />
                <input class="form_fix" type="email" placeholder="Email Address" />
              </div>
              <div>
                <label>Message</label><br />
                <textarea class="form_fix" placeholder="Message"></textarea>
              </div>
              <button type="submit" class="button1">Send</button>
            </form>
          </div>
        </aside>
      </div>
    </section>
    <footer>
        <a id="link" href="#title">Title</a>
      <a id="link" href="#webdesign">Web Design</a>
      <a id="link" href="#webmain">Web Maintenance</a>
      <a id="link" href="#webhosting">Web Hosting</a>
      <p>Acme Web Design, Copyright &copy; 2019</p>
    </footer>
  </body>
</html>
