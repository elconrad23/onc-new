
<script>
  import logo from '/images/onc-logo.jpg';
  import logo1 from '/images/logo.jpg';

</script>

<!-- Hero -->
    <div class="hero" data-theme="dark" style="width:100%;">
      <nav class="container-fluid" style="display: flex; width:100%; padding-left:5.3em; margin-right:4.7em;">
        <ul>
          <li>
            <a href="./" class="contrast" onclick="event.preventDefault()">
              <img src={logo} alt="hh" style="height:6em; width:6em; border-radius:20%;"/>
            </a>
          </li>
        </ul>
        <ul>
          <li>
            <details role="list" dir="rtl">
              <summary aria-haspopup="listbox" role="link" class="contrast">Menu</summary>
              <ul role="listbox">
                <li><a href="/">Home</a></li>
                  <li><details role="list" dir="rtl">
                    <summary aria-haspopup="listbox" role="link" class="contrast">News</summary>
                    <ul role="listbox">
                      <li><a href="/media_WestNile" >West Nile</a></li>
                      <li><a href="/Buko_media">Bukomansimbi</a></li>
                      <li><a href="/Bika_media" >Bika bya Buganda</a></li>
                    </ul>
                  </details>
                  </li>
                <li><a href="/about" ><strong>About</strong></a></li>
                <li><a href="/recent_media" ><strong> Careers</strong></a></li>
                <li><a href="/">Create Subscriber Account</a></li>
              </ul>
            </details>
          </li>
          <li>
            <img src={logo1} alt="nrm" style="width: 6em; height:6em; border-radius: 9%;" >
          </li>
        </ul>
       
      </nav>
      <header class="container">
        <hgroup>
          <h1>Office of The National Chairman</h1>
          <h2>Making sure your voice is heard everywhere</h2>
        </hgroup> <br>
        
        <!-- Button to trigger the modal -->
          <button class="contrast" data-target="modal-example" onClick="toggleModal(event)">
             ONC Media
          </button>

           <!-- Modal -->
           <dialog id="modal-example">
            <article class="modal-content">
              <a href="#close"
                aria-label="Close"
                class="close" data-target="modal-example" onClick="toggleModal(event)">
              x</a>
            <h5 id="title">Pick your area of interest</h5>
            <div class="text-gray-700"><p>Media on today's updates.</p></div>
            <div>
              <a href="/media_WestNile" role="button">West Nile</a>
              <a href="/Bika_media" role="button">Bika bya Buganda</a>
              <a href="/Buko_media" role="button">Bukomansimbi</a>
            </div>
            <footer>
            <div id="actions">
              <a href="#cancel"
              role="button"
              class="secondary"
              data-target="modal-example"
              onClick="toggleModal(event)">Back</a> <br>
           </div> </footer>
           </article>
           </dialog> 
    </header>          
  </div>

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

      header hgroup> :last-child {
        color: yellow;
      }

      header hgroup {
        margin-bottom: var(--spacing-company);
      }

      /* The Modal (background) */
      #modal-example {
        display: none; /* Hidden by default */
        position: fixed; /* Stay in place */
        z-index: 1; /* Sit on top */
        left: 0;
        top: 0;
        width: 100%; /* Full width */
        height: 100%; /* Full height */
        overflow: auto; /* Enable scroll if needed */
        background-color: rgb(0,0,0); /* Fallback color */
        background-color: rgba(0,0,0,0.4); /* Black w/ opacity */
      }

      /* Modal Content/Box */
      .modal-content {
        background-color: #fefefe;
        margin: 15% auto; /* 15% from the top and centered */
        padding: 20px;
        border: 1px solid #888;
        width: 80%; /* Could be more or less, depending on screen size */
      }

      /* The Close Button */
      .close {
        color: #aaa;
        float: right;
        font-size: 28px;
        font-weight: bold;
      }

      .close:hover,
      .close:focus {
        color: black;
        text-decoration: none;
        cursor: pointer;
      }
    </style>