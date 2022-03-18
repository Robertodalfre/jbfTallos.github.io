<html>
  <head>
    <title>Controle Tallos</title>
	
	<link rel="preconnect" href="https://fonts.googleapis.com">
	<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
	<link href="https://fonts.googleapis.com/css2?family=IBM+Plex+Mono:wght@300;400;500;700&display=swap" rel="stylesheet">
	<link href="http://fonts.cdnfonts.com/css/samsungone" rel="stylesheet">
	
    <style>
	  
	  html { height: 100%; }
	
      body { margin: 0; width: 98.8%; font-family: "SamsungOne", -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif !important; height: 100%; }

		#megasac-chat{
			position: relative !important;
		}

      #megasac-chat #chat-wrapper, #megasac-chat-iframe{
		width: 100% !important;
	  }
	  
    </style>
	<script src="https://cdnjs.cloudflare.com/ajax/libs/jquery/3.6.0/jquery.min.js" integrity="sha512-894YE6QWD5I59HgZOGReFYm4dnWc1Qt5NtvYSaNcOP+u1T9qYdvdihz0PPSiiqn/+/3e7Jo4EaG7TubfWGUrMQ==" crossorigin="anonymous" referrerpolicy="no-referrer"></script>
	<script src="https://cdnjs.cloudflare.com/ajax/libs/socket.io/4.2.0/socket.io.js" integrity="sha512-WL6WGKMPBiM9PnHRYIn5YEtq0Z8XP4fkVb4qy7PP4vhmYQErJ/dySyXuFIMDf1eEYCXCrQrMJfkNwKc9gsjTjA==" crossorigin="anonymous" referrerpolicy="no-referrer"></script>
	
	<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css" integrity="sha384-BVYiiSIFeK1dGmJRAkycuHAHRg32OmUcww7on3RYdg4Va+PmSTsz/K68vbdEjh4u" crossorigin="anonymous">
	
	<script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/js/bootstrap.min.js" integrity="sha384-Tc5IQib027qvyjSMfHjOMaLkfuWVxZxUPnCJA7l2mCWNIpG9mGCD8wGNIcPD7Txa" crossorigin="anonymous"></script>
	
	<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta2/css/all.min.css" integrity="sha512-YWzhKL2whUzgiheMoBFwW8CKV4qpHQAEuvilg9FAn5VJUDwKZZxkJNuGM4XkWuk94WCrrwslk8yWNGmY1EduTA==" crossorigin="anonymous" referrerpolicy="no-referrer" />
	
  </head>
  <body>

	<div class="container">
		<header>
			<div class="row">
				<div class="col-md-5 titulo">
					<!-- CENTRO TESTE -->
				</div>
				<div class="col-md-7" style="text-align: right; padding-top: 6px;">
					<span id="status"></span>
				</div>
			</div>
		</header>
		<div class="row" id="conteudo">
			
		</div>
		
	</div>

	
  </body>
  
  <script>
  
  $(document).ready(function(){
  
	(function() {
    window.megasac_c = '60958f8802d7b46cb01feb65';
    window.megasac_widget = 'integration-1';
    var s = document.createElement('script');
    s.setAttribute('src', 'https://kong.tallos.com.br:18000/megasac-api/widget/v2/load-scripts?load=1647611568433');
    s.onload = function() {
			document.getElementById('megasac-button').style.background = 'url(https://cdn.tallos.com.br/tallos-chat/public/images/logos/60958f883dcbb81a25a04e6b.png?load=1647611568433), url(https://cdn.tallos.com.br/tallos-chat/public/images/logos/avatar.png?load=1647611568433) center no-repeat #000';
			document.getElementById('megasac-button').style.backgroundPosition = 'center center';
			document.getElementById('megasac-button').style.backgroundSize = '105% 105%';
			document.getElementById('megasac-button').click()
		};
		document.getElementById('conteudo').appendChild(s);
	})();
		
	});  
	</script>
  
</html>
