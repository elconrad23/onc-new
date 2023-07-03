
<script>
  import logo from '/images/onc-logo.jpg';
  import logo1 from '/images/logo.jpg';
</script>

<!-- Hero -->
<header class="container" style="100%">
  <div class="hero" data-theme="dark" >
    <nav class="container-fluid" style="display: flex; width: fit-content; padding-left:0.3em; margin-right:1.7em;">
      <hgroup style="padding-top: 6.3em; width:fit-content;">
        <h1 style="margin-bottom: 0em;">Office of The National Chairman</h1>
        <h2>Making sure your voice is heard everywhere</h2><br>
        <a href="/allMediaPage" role="button" style="background-color: #F4C430; border-radius:15%;">ONC Media</a>
      </hgroup>
      <section style="margin-top: 3em;">
        <ul><li>
        <details role="list" dir="rtl">
          <summary aria-haspopup="listbox" role="link" class="contrast">Menu</summary>
          <ul role="listbox">
            <li><a href="/"><strong>Home</strong></a></li>
            <li><a href="/allMediaPage"><strong>Media</strong></a>  </li>
            <li><a href="/about" ><strong>About</strong></a></li>
            <li><a href="/"><strong>Create Subscriber Account</strong></a>
        </details></li></ul>
        <p>
          <img src={logo} alt="onc" style="height:5.3em; margin-bottom:3.3em; width:5.3em; border-radius:20%;"/><br/>
          <img src={logo1} alt="nrm" style="height:3.6em; text-align:center; width:3.6em; margin-bottom:0.3em; border-radius:20%;"/><br>
        </p> 
      </section> <br/>
    </nav>
  </div>
</header>          

<!-- ./ Hero -->

    <style>
      /* Header */
      .container{
        background-color: #F4C430;
        background-position: center;
        -webkit-background-size: cover;
        -moz-background-size: cover;
        -o-background-size: cover;
        background-size: contain;
        width:100%;
        height:20em;
      }
      .hero {
        background-color: #F4C430;
        background: linear-gradient(to top, #041dfdb4, #fa073c25), url("/images/omalako.jpeg") no-repeat center center;
        background-position: center;
        -webkit-background-size: cover;
        -moz-background-size: cover;
        -o-background-size: cover;
        background-size: contain;
        width:fit-content;
        height:20em;

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