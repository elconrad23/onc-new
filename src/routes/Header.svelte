
<script>
  import logo from '/images/onc-logo.jpg';
</script>

<!-- Hero -->
<header class="container" >
      <div class="container-a" data-theme="dark" >
        <div class="header-left">
          <h1 >Office of The National Chairman</h1>
          <h2>Making sure your voice is heard everywhere</h2><br>
          <a href="/allMediaPage" role="button" id="btn">ONC Media</a>
        </div>
        <aside>
        <nav class="header-right">
          <ul style="width:5em; text-align:right; margin-bottom:3em;">
          <details role="list" dir="rtl" style=" text-align:center;">
            <summary aria-haspopup="listbox" role="link" class="contrast">Menu</summary>
            <ul role="listbox">
              <li><a href="/"><strong>Home</strong></a></li>
              <li><a href="/allMediaPage"><strong>Media</strong></a>  </li>
              <li><a href="/about" ><strong>About</strong></a></li>
              <li><a href="/"><strong>Subscribe</strong></a>
          </details></ul>
            <img src={logo} alt="onc" style="text-align:right; height:3.3em; margin-right:3.3em; width:3.3em; border-radius:20%;"/><br/>
        </nav> </aside><br/>
        </div>
</header>          

<!-- ./ Hero -->

    <style>
      /* Header */
      header {
        margin-bottom: 1.06em;
        padding-bottom: 3.06em;
        background-position: center;
        -webkit-background-size: cover;
        -moz-background-size: cover;
        -o-background-size: cover;
        background-size: contain;
        width:100%;
        height:20em;
      }

      .container-a {
        background-color: #F4C430;
        background: linear-gradient(to top, #04fdd3b4, #1707fa65), url("/images/omalako.jpeg") no-repeat center center;
        background-position: center;
        background-size: cover;
        -webkit-background-size: cover;
        -moz-background-size: cover;
        -o-background-size: cover;
        width: 100%;
        height:20em;
      }

      .header-left{
        float: left;  
        margin-top: 6.3em;
        padding-left:3.3em;
        width:fit-content;
      }

      #btn{
        background-color: #F4C430; 
        border-radius:15%;
        width: 9em;
      }
      
      .header-right{
        margin-top: 1.3em;
        text-align: right;
        align-self: right;
        float: right;
      }

      .contrast{
        text-align: center;
        font-weight: bold;
      }

      h1{
        font-size: medium;
        margin-bottom: 0em;
      }
      h2{
        font-size: small;
        color: #F4C430;
        margin-bottom: 0em;
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