<!DOCTYPE HTML>
<html>
  <head>
    <title>Title of the document</title>
    <meta http-equiv="Content-Type" content="text/html; charset=UTF-8" />
    <style>
      html, body {
      height: 100%;
      }
      body {
      display: flex;
      flex-wrap: wrap;
      margin: 0;
      }
      .header-menu, footer {
      display: flex;
      align-items: center;
      width: 100%;
      }
      .header-menu {
      justify-content: flex-end;
      height: 60px;
      background: #1c87c9;
      color: #fff;
      }
      h2 {
      margin: 0 0 8px;
      }
      ul li {
      display: inline-block;
      padding: 0 10px;
      list-style: none;
      }
      aside {
      flex: 0.4;
      height: 165px;
      padding-left: 15px;
      border-left: 1px solid #666;
      }
      section {
      flex: 1;
      padding-right: 15px;
      }
      footer {
      padding: 0 10px;
      background: #ccc;
      }
    </style>
  </head>
  <body>
  <script>
	  window.fbAsyncInit = function() {
		FB.init({
		  appId      : '2617163505184405',
		  xfbml      : true,
		  version    : 'v6.0'
		});
		FB.AppEvents.logPageView();
	  };

	  (function(d, s, id){
		 var js, fjs = d.getElementsByTagName(s)[0];
		 if (d.getElementById(id)) {return;}
		 js = d.createElement(s); js.id = id;
		 js.src = "https://connect.facebook.net/en_US/sdk.js";
		 fjs.parentNode.insertBefore(js, fjs);
	   }(document, 'script', 'facebook-jssdk'));
	   

	</script>
    <header class="header-menu">
      <nav>
        <ul>
          <li>Menu item</li>
          <li>Menu item</li>
          <li>Menu item</li>
        </ul>
      </nav>
    </header>
    <section>
      <article>
        <header>
          <h2>Learn HTML</h2>
		  <div
				  class="fb-like"
				  data-share="true"
				  data-width="450"
				  data-show-faces="true">
				</div>
          <small>Hyper Text Markup Language</small>
        </header>
        <p>Our free HTML tutorial for beginners will teach you HTML and how to create your website from the scratch. HTML isn't difficult, so hoping you will enjoy learning.</p>
      </article>
      <article>
        <header>
          <h2>Start Quiz "HTML Basic"</h2>
          <small>You can test your HTML skills with W3docs' Quiz.</small>
        </header>
        <p>You will get 5% for each correct answer for single choice questions. In multiple choice question it might be up to 5%. At the end of the Quiz, your total score will be displayed. Maximum score is 100%.</p>
      </article>
    </section>
    <aside>
      <h2>Our Books</h2>
      <p>HTML</p>
      <p>CSS</p>
      <p>JavaScript</p>
      <p>PHP</p>
    </aside>
    <footer>
      <small>Company © W3docs. All rights reserved.</small>
    </footer>
  </body>
</html>