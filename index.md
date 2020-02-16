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
  </body>
</html>