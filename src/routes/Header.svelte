
<script>
  import logo from '/images/onc-logo.jpg';
  import logo1 from '/images/logo.jpg';
</script>

<!-- Hero -->
<header class="container">
    <div class="hero" data-theme="dark" style="width:100%;">
      <nav class="container-fluid" style="display: flex; width:100%; padding-left:5.3em; margin-right:4.7em;">
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
        </ul>
         <div>
          <h1>Office of The National Chairman</h1>
          <h2>Making sure your voice is heard everywhere</h2>

          <img src={logo1} alt="nrm" style="height:6em; width:6em; border-radius:20%;"/>
          <a href="/allMediaPage" role="button" style="background-color: #F4C430;">ONC Media</a>

        </div> <br>
      </nav>
      
        
        <!-- Button to trigger the modal -->
          <!-- <button class="modal-button" data-target="modal-example" onClick="{toggleModal()}">
             ONC Media
          </button> -->
          
  </div>
  </header>          

<!-- ./ Hero -->

    <style>
      /* Header */
      .hero {
        background-color: #F4C430;
        background: linear-gradient(to top, #041dfdb4, #fa073c25), url("/images/omalako.jpeg") no-repeat center center;
        background-position: center;
        -webkit-background-size: contain;
        -moz-background-size: contain;
        -o-background-size: contain;
        background-size: contain;
        width:100%;
      }

      .container{
        padding-bottom: 1.3em;
      }

      header {
        padding: 0.63em;
        padding-left: 0cm;
        margin-bottom: 0cm;
        margin-left: 4.7em;
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