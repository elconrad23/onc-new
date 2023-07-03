
<script>
  import logo from '/images/onc-logo.jpg';
  import logo1 from '/images/logo.jpg';
</script>

<!-- Hero -->
<header class="container">
    <div class="hero" data-theme="dark" style="width:100%;">
      <nav class="container-fluid" style="display: flex; width:100%; padding-left:0.3em; margin-right:1.7em;">
        <ul>
          <li>
            <a href="./" class="contrast" onclick="event.preventDefault()">
            </a>
          </li>
        </ul>
        <ul>
          <li>
            <details role="list" dir="rtl">
              <summary aria-haspopup="listbox" role="link" class="contrast">Menu</summary>
              <ul role="listbox">
                <li><a href="/"><strong>Home</strong></a></li>
                <li><a href="/allMediaPage"><strong>Media</strong></a>  </li>
                <li><a href="/about" ><strong>About</strong></a></li>
                <li><a href="/"><strong>Create Subscriber Account</strong></a></li>
              </ul>
            </details>
          </li>
          <li>
            <img src={logo} alt="onc" style="height:6em; width:6em; border-radius:20%;"/>
          </li>
          <li><h1 style="padding-bottom: 0em;">Office of The National Chairman</h1>
          <h2>Making sure your voice is heard everywhere</h2><br>
          </li>
          <li><img src={logo1} alt="nrm" style="height:6em; width:6em; border-radius:20%;"/></li><br>
          <li><a href="/allMediaPage" role="button" style="background-color: #F4C430;">ONC Media</a></li>

        </ul>
      </nav>
  </div>
  </header>          

<!-- ./ Hero -->

    <style>
      /* Header */
      .hero {
        background-color: #F4C430;
        background: linear-gradient(to top, #041dfdb4, #fa073c25), url("/images/omalako.jpeg") no-repeat center center;
        background-position: center;
        -webkit-background-size: cover;
        -moz-background-size: cover;
        -o-background-size: cover;
        background-size: contain;
        width:100%;
      }

      h2{
        color: #F4C430;
      }
      header {
        margin-bottom: 3.06em;
        padding-bottom: 3.06em;
        width:100%;
      }

      header div> :last-child {
        color: yellow;
      }

      header div {
        display: flex;
        flex-direction: column;
        position: absolute;
        width:100%;
        margin-bottom: var(--spacing-company);
      }

    </style>