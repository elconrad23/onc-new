<script>
  import logo from '/images/onc-logo.jpg';
  import logo1 from '/images/logo.jpg';
 </script>

 
  <!-- Footer -->
  <footer class="container">
    <section class="aria-label">
      <article>
        <hgroup>
          <h2>Subscribe</h2>
          <h3>To our live updates</h3>
        </hgroup>
        <form class="grid">
          <input
            type="text"
            id="firstname"
            name="firstname"
            placeholder="First name"
            aria-label="First name"
            required
          />
          <input
            type="email"
            id="email"
            name="email"
            placeholder="Email address"
            aria-label="Email address"
            required
          />
          
          <button type="submit" onclick="event.preventDefault()" style="border-radius:9%; border-color:transparent; background-color:#F4C430;">Subscribe</button>
        </form>
      </article>
    </section>
  <!-- ./ Subscribe -->

    <small>Copyright © 2023 of <a href="/">Office of the National Chairman</a> •</small>
    <img src={logo} alt="logo" style="width:2em; border-radius:16%" />
    <img src={logo1} alt="logo" style="width:2em; border-radius:16%" />
    <br/>
  </footer>
  <!-- ./ Footer -->

  <style>
    footer{
      margin-bottom: 3em;
    }
  </style>