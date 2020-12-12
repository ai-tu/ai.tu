<title>AI.TU</title>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="https://www.w3schools.com/w3css/4/w3.css">
<link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Poppins">
<link rel="stylesheet" type="text/css" href="css/main.css">
<style>
body,h1,h2,h3,h4,h5 {font-family: "Poppins", sans-serif}
body {font-size:30px;}
.w3-half img{margin-bottom:-6px;margin-top:20px;opacity:0.8;cursor:pointer}
.w3-half img:hover{opacity:0.9}
</style>
<head>
		<title>AI.TU</title>
</head>
<!-- Sidebar/menu -->
<nav class="w3-sidebar w3-dark-gray w3-collapse w3-top w3-large w3-padding" style="z-index:3;width:300px;font-weight:bold;position: fixed;left: 0;" id="mySidebar"><br>
  <a href="javascript:void(0)" onclick="w3_close()" class="w3-button w3-hide-large w3-display-topleft" style="width:100%;font-size:27px;left: 0;">Close Menu</a>
  <div class="w3-container">
    <h3 class="w3-padding-64"><b>AI.TU</b></h3>
  </div>
  <div class="w3-bar-block">
    <a href="#" onclick="w3_close()" class="w3-bar-item w3-button w3-hover-white">Home</a> 
    <a href="#Über uns" onclick="w3_close()" class="w3-bar-item w3-button w3-hover-white">Über uns</a> 
    <a href="#Mitglieder" onclick="w3_close()" class="w3-bar-item w3-button w3-hover-white">Mitglieder</a> 
   <!--  <a href="#Projekte" onclick="w3_close()" class="w3-bar-item w3-button w3-hover-white">Projekte</a> -->
    <a href="#Kontakt" onclick="w3_close()" class="w3-bar-item w3-button w3-hover-white">Kontakt</a>
  </div>
</nav>

<!-- Top menu on small screens -->
<header class="w3-container w3-top w3-hide-large w3-dark-gray w3-xlarge w3-padding">
  <a href="javascript:void(0)" class="w3-button w3-dark-gray w3-margin-right" onclick="w3_open()">☰</a>
  <span>AI.TU</span>
</header>

<!-- Overlay effect when opening sidebar on small screens -->
<div class="w3-overlay w3-hide-large" onclick="w3_close()" style="cursor:pointer;left: 0;width:100%;" title="close side menu" id="myOverlay"></div>

<!-- !PAGE CONTENT! -->
<div class="w3-main" style="margin-left:200px;margin-right:10px">

  <!-- Header -->
  <div class="w3-container" style="margin-top:40px" id="showcase">

  </div>
  
  <!-- Photo grid (modal) -->
  <div class="w3-row-padding">
    <div>
      <img src="box_logo.png" style="width:100%;display: block;margin-left: auto; margin-right: auto; width: 100%;" alt="AI.TU - Studentische Hochschulgruppe der TU Berlin">

  </div>

  <!-- Modal for full size images on click-->
  <div id="modal01" class="w3-modal w3-dark-gray" style="padding-top:0" onclick="this.style.display='none'">
    <span class="w3-button w3-dark-gray w3-xxlarge w3-display-topright">×</span>
    <div class="w3-modal-content w3-animate-zoom w3-center w3-transparent w3-padding-64">
      <img id="img01" class="w3-image">
      <p id="caption"></p>
    </div>
  </div>

  <!-- Über uns -->
  <div class="w3-container" id="Über uns" style="margin-top:50px">
    <h1 class="w3-xxxlarge w3-text-dark-gray"><b>Über uns</b></h1>
    <hr style="width:50px;border:4px solid #616161" class="w3-round">
    <p>AI.TU ist eine studentische Organisation der Technischen Universität Berlin zu den Themen Künstliche Intelligenz und Machine Learning.</p>
    <p>
      Es ist uns ein Anliegen, künstliche Intelligenz ganzheitlich zu behandeln und weder die technisch, noch die gesellschaftlich Fragestellungen zu vernachlässigen.
    </p>
    <p>
    Inhaltliche Schwerpunkte hierbei sind der regelmäßige Austausch über klassische und aktuelle Forschungsbeiträge, die Diskussion über ethische Aspekte der AI-Forschung, die gemeinsame Konzeption und Umsetzung selbstgewählter Forschungsprojekte. In diesen versuchen wir, praxisorientierte und theoriegetriebene Herangehensweisen zu verbinden und unser Verständnis des Themengebietes zu vertiefen. 
    </p>
  </div>
  
  <!-- Mitglieder -->
  <div class="w3-container" id="Mitglieder" style="margin-top:50px">
    <h1 class="w3-xxxlarge w3-text-dark-gray"><b>Mitglieder</b></h1>
    <hr style="width:50px;border:4px solid #616161" class="w3-round">
    <p> Wir sind eine interdisziplinäre Gruppe von Menschen mit verschiedenen Interessenschwerpunkten, die sich aus verschiedenen Motivationen mit der Materie befassen. 
    </p>
    <p><b>Wer sind wir?</b></p>
  </div>

  <!-- Über uns (Mitgliederliste) -->
  <div class="w3-row-padding w3-grayscale">
    <div class="w3-col m4 w3-margin-bottom">
      <div class="w3-light-grey">
        <img src="member_pictures_formatted/NicolasFrey.jpg" alt="Jane" style="width:100%">
        <div class="w3-container">
          <h3>Nicolas Frey  <br> </h3>
          <p class="w3-opacity">Gründungsmitglied & Vorstand <br> <br> </p>
          <p>Nicolas interessiert sich vorwiegend für explainable Artificial Intelligence und Deep Learning.</p>
        </div>
      </div>
    </div>
    <div class="w3-col m4 w3-margin-bottom">
      <div class="w3-light-grey">
        <img src="member_pictures_formatted/LeonardPleiss.jpg" alt="Jane" style="width:100%">
        <div class="w3-container">
          <h3>Leonard Santiago Pleiss</h3>
          <p class="w3-opacity">Gründer & Vorstandsvorsitzender</p>
          <p>Leonards besonderes Interesse gilt der Erforschung und Reproduktion menschlichen Bewusstseins.</p>
        </div>
      </div>
    </div>
      <div class="w3-col m4 w3-margin-bottom">
      <div class="w3-light-grey">
        <img src="member_pictures_formatted/SvenSchulz-Niethammer.jpg" alt="Jane" style="width:100%">
        <div class="w3-container">
          <h3>Sven Schulz-Niethammer</h3>
          <p class="w3-opacity">Gründungsmitglied & Vorstand  <br> <br> </p>
          <p>Sven interessiert sich besonders für komplexe statistische Modelle und Data Science.</p>
        </div>
      </div>
    </div>

  <div class="w3-row-padding w3-grayscale">
    <div class="w3-col m4 w3-margin-bottom">
      <div class="w3-light-grey">
        <img src="member_pictures_formatted/placeholder.png" alt="Jane" style="width:100%">
        <div class="w3-container">
          <h3>Ulrike Schäfer</h3>
          <p class="w3-opacity">Mitglied</p>
          <p>Ulrike interessiert sich besonders für Machine Learning, inbesondere für Unsupervised Learning.</p>
        </div>
      </div>
    </div>
    <div class="w3-col m4 w3-margin-bottom">
      <div class="w3-light-grey">
        <img src="member_pictures_formatted/LukasSeiling.jpg" alt="Jane" style="width:100%">
        <div class="w3-container">
          <h3>Lukas Kurt Seiling</h3>
          <p class="w3-opacity">Gründungsmitglied & Vorstand</p>
          <p>Lukas beschäftigt sich mit den gesellschaftlichen Auswirkungen und Regulierungsmöglichkeiten von AI.</p>
        </div>
      </div>
    </div>
      <div class="w3-col m4 w3-margin-bottom">
      <div class="w3-light-grey">
        <img src="member_pictures_formatted/RajmundStankiewicz.jpg" alt="Jane" style="width:100%">
        <div class="w3-container">
          <h3>Rajmund Stankiewicz</h3>
          <p class="w3-opacity"> <br> Gründungsmitglied</p>
          <p>Rajmund beschäftigt sich momentan vornehmlich mit Data Science und Data Engineering.  <br>   <br> </p>
        </div>
      </div>
    </div>

  <!-- Projekte 
  <div class="w3-container" id="Projekte" style="margin-top:10px">
    <h1 class="w3-xxxlarge w3-text-dark-gray"><b>Projekte</b></h1>
    <hr style="width:50px;border:4px solid #616161" class="w3-round">
    <p> Wir freuen uns immer über neue Projektideen und Challenges. Einige unsere aktuellen, vergangenen und geplanten Projekte sind:</p>
	<div class="team" id="team">
	<div class="container">
		<div class="row">
			<div class="col-lg-3 col-md-3 col-sm-12 item">
				<img src="member_pictures_formatted/SvenSchulz-Niethammer.jpg" class="img-fluid" alt="team">
				<div class="des">
				 	Sara
				 </div>
				<span class="text-muted">Manager</span>
			</div>
			<div class="col-lg-3 col-md-3 col-sm-12 item">
				<img src="member_pictures_formatted/SvenSchulz-Niethammer.jpg" class="img-fluid" alt="team">
				<div class="des">
				 	 Chris
				 </div>
				<span class="text-muted">S.enginner</span>
			</div>
			<div class="col-lg-3 col-md-3 col-sm-12 item">
				<img src="member_pictures_formatted/SvenSchulz-Niethammer.jpg" class="img-fluid" alt="team">
				<div class="des">
				 	Layla 
				 </div>
				<span class="text-muted">Front End Developer</span>
			</div>
			<div class="col-lg-3 col-md-3 col-sm-12 item">
				<img src="member_pictures_formatted/SvenSchulz-Niethammer.jpg" class="img-fluid" alt="team">
				 <div class="des">
				 	J.Jirard
				 </div>
				<span class="text-muted">Team Manger</span>
			</div>
		</div>
		</div>
	</div>
  </div> -->

  <!-- Kontakt -->
  <div class="w3-container" id="Kontakt" style="margin-top:500px; padding-bottom: 50px">
    <h1 class="w3-xxxlarge w3-text-dark-gray"><b>Kontakt</b></h1>
    <hr style="width:50px;border:4px solid #616161" class="w3-round">
    <p>Du möchtest in unserer Gruppe mitarbeiten oder mehr über uns erfahren? Wir freuen uns, von dir zu hören!</p>
    <p>Schreibe uns gern eine E-Mail: <a href="mailto:TUB_AI_Group@web.de">TUB_AI_Group@web.de</a> oder nutze unsere Kontaktform:</p>
    <div class="contact-form" id="contact">
		<div class="container">
			<form action="mailto:pandemicnomad@contact.com?subject=Contact Pandemic Nomad" method="post" enctype="text/plain">
				<div class="row">
					<div class="col-lg-4 col-md-4 col-sm-12">
					</div>
					<div class="col-lg-8 col-md-8 col-sm-12 right">
					<div class="form-group">
						<input type="text" class="input" placeholder="Dein Name" name="name">
					</div>
					<div class="form-group">
						<input type="email" class="input" placeholder="DeineEmail@email.com" name="mail">
					</div>
					<div class="form-group">
						<textarea class="inputbox" name="message">
							
						</textarea>
					</div>
					<input type="submit" class="button" value="Absenden" name="">
					</div>
				</div>
			</form>
		</div>
	</div>
    
  </div>

<!-- End page content -->
</div>

<script>
// Script to open and close sidebar
function w3_open() {
  document.getElementById("mySidebar").style.display = "block";
  document.getElementById("myOverlay").style.display = "block";
}
 
function w3_close() {
  document.getElementById("mySidebar").style.display = "none";
  document.getElementById("myOverlay").style.display = "none";
}

// Modal Image Gallery
function onClick(element) {
  document.getElementById("img01").src = element.src;
  document.getElementById("modal01").style.display = "block";
  var captionText = document.getElementById("caption");
  captionText.innerHTML = element.alt;
}
</script>
