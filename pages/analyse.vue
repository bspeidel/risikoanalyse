<template>
  <section>
    <nav class="navbar sticky-top navbar-expand-lg navbar-light bg-light">
      <div class="container-fluid">
        <div class="sidebar-header text-center">
          <img 
            src="~assets/images/zurich-logo.png" 
            alt="logo">
        </div>
        <button 
          class="btn btn-dark d-inline-block d-lg-none ml-auto" 
          type="button" 
          data-toggle="collapse" 
          data-target="#navbarSupportedContent" 
          aria-controls="navbarSupportedContent" 
          aria-expanded="false" 
          aria-label="Toggle navigation">
          <i class="fas fa-align-justify"/>
        </button>
        <div 
          id="navbarSupportedContent" 
          class="collapse navbar-collapse">
          <ul class="nav navbar-nav ml-auto">
            <li class="nav-item">
              <a 
                class="nav-link" 
                href="#"><i class="fas fa-user-edit"/> Max Mustermann</a>
            </li>
            <li class="nav-item">
              <a 
                class="nav-link" 
                href="/"><i class="fas fa-sign-out-alt"/> Abmelden</a>
            </li>
          </ul>
        </div>
      </div>
    </nav>
    <div class="container-fluid">
      <div class="row">
        <div class="col">
          <h2>Analyse</h2>
        </div>
        <div class="col text-right">
          <a 
            href="#" 
            class="btn btn-primary"><i class="fas fa-envelope"/> E-Mail senden</a>
          <a 
            href="#" 
            class="btn btn-primary"><i class="fas fa-file-pdf"/> PDF erzeugen</a>
          <button 
            class="btn btn-default" 
            onclick="history.go(-1)"><i class="fas fa-chevron-left"/> Zurück</button>
        </div>
      </div>
      <strong>Linde Material Handling GmbH</strong>
      <address>
        Heinrich Heine Platz 84<br>
        99722 Nordhausen<br>
      </address>
      <div class="line"/>
      <h3 class="text-center">Absicherung und Risiko</h3>
      <div class="gauge mx-auto mb-5"/>
      <div class="legend-container text-center">
        <div class="dot-green"/><h5 style="display: inline-block">&nbsp;Absicherung</h5>
        <div class="dot-red"/><h5 style="display: inline-block">&nbsp;Risiko</h5>
      </div>
      <div class="card-columns analyse">
        <div class="card mt-3">
          <div class="card-header">
            <h5>Unternehmensdaten
              <span class="float-sm-right">
                <a href="#"><i class="fas fa-eye-slash"/></a>
              </span>
            </h5>
          </div>
          <ul class="list-group list-group-flush">
            <li class="list-group-item">
              <p class="card-text"><strong>Was ist die aktuelle Situation in Ihrem Unternehmen?</strong></p>
              Eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non
              proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
            </li>
            <li class="list-group-item">
              <p class="card-text"><strong>Was sind Ihre Wünsche, Ziele und Erwartungen an das heutige Gespräch?</strong></p>
              Dolore magna aliqua. Ut enim ad minim veniam,
              quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo
            </li>
          </ul>
          <div class="card-footer">
            <label for="note">Notizen</label>
            <textarea 
              id="note" 
              class="form-control mb-2" 
              name="note" 
              rows="2"/>
          </div>
        </div>
        <div class="card mt-3">
          <div class="card-header">
            <h5>Absicherung Ihrer Haftungsrisiken
              <span class="float-sm-right">
                <a href="#"><i class="fas fa-eye-slash"/></a>
              </span>
            </h5>
          </div>
          <ul class="list-group list-group-flush">
            <li class="list-group-item">
              <p class="card-text"><strong>Versicherungssumme Betriebshaftpflicht</strong></p>
              500.000€
            </li>
            <li class="list-group-item">
              <p class="card-text"><strong>Reparieren bzw. warten Sie Kundeneigentum auf Ihrem Grundstück?</strong></p>
              <i class="fas fa-check"/> JA
            </li>
            <li class="list-group-item">
              <p class="card-text"><strong>Haben Sie Arbeisgeräte / Werkzeuge gemietet, für die Sie die Gefahr tragen? (Mietsachschäden beweglich)</strong></p>
              <i class="fas fa-check"/> JA
            </li>
            <li class="list-group-item">
              <p class="card-text"><strong>Werden Ihrer Arbeitsmaschinen / Stapler auch außerhalb Ihres Betriebsgrundstückes eingesetzt? (Sondergenehmigung / AKB_Deckung)</strong></p>
              <i class="fas fa-times"/> NEIN
            </li>
            <li class="list-group-item">
              <p class="card-text"><strong>Reparieren bzw. warten Sie Kundeneigentum auf Ihrem Grundstück?</strong></p>
              <i class="fas fa-check"/> JA
            </li>
            <li class="list-group-item">
              <p class="card-text"><strong>Reparieren bzw. warten Sie Kundeneigentum auf Ihrem Grundstück?</strong></p>
              <i class="fas fa-check"/> JA
            </li>
            <li class="list-group-item">
              <p class="card-text"><strong>Reparieren bzw. warten Sie Kundeneigentum auf Ihrem Grundstück?</strong></p>
              <i class="fas fa-check"/> JA
            </li>
          </ul>
          <div class="card-footer">
            <label for="note">Notizen</label>
            <textarea 
              id="note" 
              class="form-control mb-2" 
              name="note" 
              rows="2"/>
            Absicherung
            <div 
              id="slider_2" 
              class="noUi-target noUi-ltr noUi-horizontal mt-2"/>
          </div>
        </div>
        <div class="card mt-3">
          <div class="card-header">
            <h5>Absicherung Ihrer Gebäude-Werte
              <span class="float-sm-right">
                <a href="#"><i class="fas fa-eye-slash"/></a>
              </span>
            </h5>
          </div>
          <ul class="list-group list-group-flush">
            <li class="list-group-item">
              <p class="card-text"><strong>Was ist die aktuelle Situation in Ihrem Unternehmen?</strong></p>
              Eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non
              proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
            </li>
            <li class="list-group-item">
              <p class="card-text"><strong>Was sind Ihre Wünsche, Ziele und Erwartungen an das heutige Gespräch?</strong></p>
              Dolore magna aliqua. Ut enim ad minim veniam,
              quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo
            </li>
          </ul>
          <div class="card-footer">
            <label for="note">Notizen</label>
            <textarea 
              id="note" 
              class="form-control mb-2" 
              name="note" 
              rows="2"/>
          </div>
        </div>
        <div class="card mt-3">
          <div class="card-header">
            <h5>Absicherung Ihrer Inhalt-Werte
              <span class="float-sm-right">
                <a href="#"><i class="fas fa-eye-slash"/></a>
              </span>
            </h5>
          </div>
          <ul class="list-group list-group-flush">
            <li class="list-group-item">
              <p class="card-text"><strong>Was ist die aktuelle Situation in Ihrem Unternehmen?</strong></p>
              Eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non
              proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
            </li>
            <li class="list-group-item">
              <p class="card-text"><strong>Was sind Ihre Wünsche, Ziele und Erwartungen an das heutige Gespräch?</strong></p>
              Dolore magna aliqua. Ut enim ad minim veniam,
              quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo
            </li>
          </ul>
          <div class="card-footer">
            <label for="note">Notizen</label>
            <textarea 
              id="note" 
              class="form-control mb-2" 
              name="note" 
              rows="2"/>
            Absicherung
          </div>
        </div>
        <div class="card mt-3">
          <div class="card-header">
            <h5>Absicherung Ihrer Elektronik/Maschinen-Werte
              <span class="float-sm-right">
                <a href="#"><i class="fas fa-eye-slash"/></a>
              </span>
            </h5>
          </div>
          <ul class="list-group list-group-flush">
            <li class="list-group-item">
              <p class="card-text"><strong>Was ist die aktuelle Situation in Ihrem Unternehmen?</strong></p>
              Eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non
              proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
            </li>
            <li class="list-group-item">
              <p class="card-text"><strong>Was sind Ihre Wünsche, Ziele und Erwartungen an das heutige Gespräch?</strong></p>
              Dolore magna aliqua. Ut enim ad minim veniam,
              quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo
            </li>
          </ul>
          <div class="card-footer">
            <label for="note">Notizen</label>
            <textarea 
              id="note" 
              class="form-control mb-2" 
              name="note" 
              rows="2"/>
            Absicherung
          </div>
        </div>
        <div class="card mt-3">
          <div class="card-header">
            <h5>Absicherung bei einer Unterbrechung Ihres Betriebes
              <span class="float-sm-right">
                <a href="#"><i class="fas fa-eye-slash"/></a>
              </span>
            </h5>
          </div>
          <ul class="list-group list-group-flush">
            <li class="list-group-item">
              <p class="card-text"><strong>Was ist die aktuelle Situation in Ihrem Unternehmen?</strong></p>
              Eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non
              proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
            </li>
            <li class="list-group-item">
              <p class="card-text"><strong>Was sind Ihre Wünsche, Ziele und Erwartungen an das heutige Gespräch?</strong></p>
              Dolore magna aliqua. Ut enim ad minim veniam,
              quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo
            </li>
          </ul>
          <div class="card-footer">
            <label for="note">Notizen</label>
            <textarea 
              id="note" 
              class="form-control mb-2" 
              name="note" 
              rows="2"/>
            Absicherung
          </div>
        </div>
        <div class="card mt-3">
          <div class="card-header">
            <h5>Absicherung Ihrer Kosten bei Rechtsangelegenheiten
              <span class="float-sm-right">
                <a href="#"><i class="fas fa-eye-slash"/></a>
              </span>
            </h5>
          </div>
          <ul class="list-group list-group-flush">
            <li class="list-group-item">
              <p class="card-text"><strong>Sie sind aktuell in folgenden Rechtsbereichen abgesichert</strong></p>
              Privat
            </li>
            <li class="list-group-item">
              Haus- und Grundbesitz vermietet
            </li>
            <li class="list-group-item">
              <p class="card-text"><strong>Anstellungsvertrag-RS für die Geschäftsführung</strong></p>
              <i class="fas fa-check"/> JA
            </li>
            <li class="list-group-item">
              <p class="card-text"><strong>Versicherungssumme</strong></p>
              500.000€
            </li>
          </ul>
          <div class="card-footer">
            <label for="note">Notizen</label>
            <textarea 
              id="note" 
              class="form-control mb-2" 
              name="note" 
              rows="2"/>

          </div>
        </div>
        <div class="card mt-3">
          <div class="card-header">
            <h5>Absicherung Ihrer Transporte
              <span class="float-sm-right">
                <a href="#"><i class="fas fa-eye"/></a>
              </span>
            </h5>
          </div>
        </div>
        <div class="card mt-3">
          <div class="card-header">
            <h5>Absicherung Ihrer Kfz-Risiken
              <span class="float-sm-right">
                <a href="#"><i class="fas fa-eye"/></a>
              </span>
            </h5>
          </div>
        </div>
        <div class="card mt-3">
          <div class="card-header">
            <h5>Absicherung Ihrer Spezial-Risiken
              <span class="float-sm-right">
                <a href="#"><i class="fas fa-eye-slash"/></a>
              </span>
            </h5>
          </div>
          <ul class="list-group list-group-flush">
            <li class="list-group-item">
              <p class="card-text"><strong>Wie hoch schätzen Sie das Risiko von Zahlungsausfällen durch Ihre geverblicken Kunden ein?</strong></p>
              sehr hoch
            </li>
            <li class="list-group-item">
              <p class="card-text"><strong>Werden von Ihren Kunden Bürgschäften eingefordert?</strong></p>
              <i class="fas fa-check"/> JA
            </li>
            <li class="list-group-item">
              <p class="card-text"><strong>Welche Folgen können Datenklau und Datenmissbrauch bei Ihnen haben (Cyber-Attacken)?</strong></p>
              Es wäre dramatisch
            </li>
          </ul>
          <div class="card-footer">
            <label for="note">Notizen</label>
            <textarea 
              id="note" 
              class="form-control mb-2" 
              name="note" 
              rows="2"/>
            <div>
              <label for="">Risiko</label>
              <div 
                id="slider1" 
                class="noUi-av noUi-ltr noUi-horizontal mt-2"/>
            </div>
            <div class="mt-4">
              <label for="">Absicherung</label>
              <div 
                id="slider11" 
                class="slider noUi-ltr noUi-horizontal mt-2"/>
            </div>
          </div>
        </div>
        <div class="card mt-3">
          <div class="card-header">
            <h5>Absicherung Ihrer Mitarbeiter
              <span class="float-sm-right">
                <a href="#"><i class="fas fa-eye-slash"/></a>
              </span>
            </h5>
          </div>
          <ul class="list-group list-group-flush">
            <li class="list-group-item">
              <p class="card-text"><strong>Was ist die aktuelle Situation in Ihrem Unternehmen?</strong></p>
              Eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non
              proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
            </li>
            <li class="list-group-item">
              <p class="card-text"><strong>Was sind Ihre Wünsche, Ziele und Erwartungen an das heutige Gespräch?</strong></p>
              Dolore magna aliqua. Ut enim ad minim veniam,
              quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo
            </li>
          </ul>
          <div class="card-footer">
            <label for="note">Notizen</label>
            <textarea 
              id="note" 
              class="form-control mb-2" 
              name="note" 
              rows="2"/>
            <div>
              <label for="">Risiko</label>
            </div>
            <div class="mt-4">
              <label for="">Absicherung</label>
            </div>
          </div>
        </div>
        <div class="card mt-3">
          <div class="card-header">
            <h5>Vorsorge und Absicherung Belegschaft / Inhabers / GGf / etc.
              <span class="float-sm-right">
                <a href="#"><i class="fas fa-eye-slash"/></a>
              </span>
            </h5>
          </div>
          <ul class="list-group list-group-flush">
            <li class="list-group-item">
              <p class="card-text"><strong>Was ist die aktuelle Situation in Ihrem Unternehmen?</strong></p>
              Eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non
              proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
            </li>
            <li class="list-group-item">
              <p class="card-text"><strong>Was sind Ihre Wünsche, Ziele und Erwartungen an das heutige Gespräch?</strong></p>
              Dolore magna aliqua. Ut enim ad minim veniam,
              quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo
            </li>
          </ul>
          <div class="card-footer">
            <label for="note">Notizen</label>
            <textarea 
              id="note" 
              class="form-control mb-2" 
              name="note" 
              rows="2"/>
            Absicherung
          </div>
        </div>
        <div class="card mt-3">
          <div class="card-header">
            <h5>Offene Punkte und weiteres Vorgehen
              <span class="float-sm-right">
                <a href="#"><i class="fas fa-eye-slash"/></a>
              </span>
            </h5>
          </div>
          <div class="card-body">
            <textarea 
              id="note" 
              class="form-control mb-2" 
              name="note" 
              rows="3"/>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<style lang="scss">
.gauge {
	max-width: 300px;
}

.dot-red {
	height: 25px;
	width: 25px;
	background-color: #ff0000;
	border-radius: 50%;
	display: inline-block;
	margin-bottom: -6px;
	margin-left: 20px;
}

.dot-green {
	height: 25px;
	width: 25px;
	background-color: #1ec481;
	border-radius: 50%;
	display: inline-block;
	margin-bottom: -6px;
}

.noUi-horizontal {
	height: 1rem;
	//padding-right: 17px;
}

.noUi-connects {
	overflow: unset;
	z-index: 0;
}

html:not([dir='rtl']) .noUi-horizontal .noUi-handle {
	right: -20px;
	left: auto;
}

.noUi-target {
	background-image: -webkit-gradient(
		linear,
		left top,
		right top,
		from(#ff394f),
		to(#ff8090)
	);
	background-image: -webkit-linear-gradient(left, #ff394f 0, #ff8090 100%);
	background-image: -moz-linear-gradient(left, #ff394f 0, #ff8090 100%);
	background-image: -o-linear-gradient(left, #ff394f 0, #ff8090 100%);
	background-image: linear-gradient(to right, #ff394f 0, #ff8090 100%);
	background-repeat: repeat-x;
	border: 0;
	-webkit-box-shadow: none;
	box-shadow: none;
	border-radius: 0.25rem;
}

.noUi-av.noUi-target {
	background-image: -webkit-gradient(
		linear,
		left top,
		right top,
		from(#fff),
		to(#eae8e6)
	);
	background-image: -webkit-linear-gradient(left, #fff 0, #eae8e6 100%);
	background-image: -moz-linear-gradient(left, #fff 0, #eae8e6 100%);
	background-image: -o-linear-gradient(left, #fff 0, #eae8e6 100%);
	background-image: linear-gradient(to right, #fff 0, #eae8e6 100%);
}

.noUi-av .noUi-connect {
	background-image: -webkit-gradient(
		linear,
		right top,
		left top,
		from(#ff394f),
		to(#ff8090)
	);
	background-image: -webkit-linear-gradient(right, #ff394f 0, #ff8090 100%);
	background-image: -moz-linear-gradient(right, #ff394f 0, #ff8090 100%);
	background-image: -o-linear-gradient(right, #ff394f 0, #ff8090 100%);
	background-image: linear-gradient(to left, #ff394f 0, #ff8090 100%);
	background-repeat: repeat-x;
}

.slider.noUi-target {
	background-image: -webkit-gradient(
		linear,
		left top,
		right top,
		from(#fff),
		to(#eae8e6)
	);
	background-image: -webkit-linear-gradient(left, #fff 0, #eae8e6 100%);
	background-image: -moz-linear-gradient(left, #fff 0, #eae8e6 100%);
	background-image: -o-linear-gradient(left, #fff 0, #eae8e6 100%);
	background-image: linear-gradient(to right, #fff 0, #eae8e6 100%);
}

//.noUi-connect {
//  background-image: -webkit-gradient(linear,right top,left top,from(#1EC481),to(#69DEB4));
//  background-image: -webkit-linear-gradient(right,#1EC481 0,#69DEB4 100%);
//  background-image: -moz-linear-gradient(right,#1EC481 0,#69DEB4 100%);
//  background-image: -o-linear-gradient(right,#1EC481 0,#69DEB4 100%);
//  background-image: linear-gradient(to left,#1EC481 0,#69DEB4 100%);
//  background-repeat: repeat-x;
//}

.slider {
	.noUi-origin:nth-child(3) {
		.noUi-handle {
			display: none;
		}
	}
}

.c-1-color {
	background: #1ec481;
}
.c-2-color {
	background: #ff394f;
}

.noUi-handle {
	-webkit-box-shadow: none;
	box-shadow: none;
	border-radius: 50%;
	background: #fff;
	border: 5px solid #343a40;
}

.noUi-horizontal .noUi-handle {
	height: 25px;
	top: -4px;
	width: 25px;
}

.noUi-pips-horizontal {
	left: 8px;
	width: 98.6%;
}

.noUi-pips-horizontal,
.noUi-value-sub {
	font-size: 12px;
	color: #aaa;
}

.noUi-value-horizontal {
	margin-top: 5px;
}

.noUi-connects {
	border-radius: 3px;
}

.noUi-handle:before,
.noUi-handle:after {
	display: none;
}

@media (max-width: 767px) {
	.noUi-value-large,
	.noUi-value-sub {
		display: none;
	}
}
</style>
<script>
// new RadialProgressChart('.gauge', {
// 	series: [
// 		{
// 			value: 60,
// 			color: '#ff0000'
// 		},
// 		{
// 			value: 48,
// 			color: '#1EC481'
// 		}
// 	]
// })

// var slider1 = document.getElementById('slider1')
//
// noUiSlider.create(slider1, {
// 	start: 0,
// 	connect: [true, false],
// 	// Disable animation on value-setting,
// 	// so the sliders respond immediately.
// 	animate: false,
// 	range: {
// 		min: 0,
// 		max: 100
// 	}
// })
//
// var slider11 = document.getElementById('slider11')
//
// noUiSlider.create(slider11, {
// 	start: [0, 0],
// 	connect: [true, true, false],
// 	range: {
// 		min: [0],
// 		max: [100]
// 	}
// })
//
// var connect = slider11.querySelectorAll('.noUi-connect')
// var classes = ['c-1-color', 'c-2-color', 'c-3-color']
//
// for (var i = 0; i < connect.length; i++) {
// 	connect[i].classList.add(classes[i])
// }
//
// slider1.noUiSlider.on('slide', setLockedValues)
//
// function setLockedValues() {
// 	slider11.noUiSlider.set(['null', slider1.noUiSlider.get()])
// }
</script>
