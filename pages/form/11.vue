<template>
  <section>
    <div class="wrapper">
      <!-- Sidebar Holder -->
      <nav id="sidebar">
        <div class="sidebar-header text-center">
          <img 
            src="~assets/images/zurich-logo.png" 
            alt="logo">
        </div>
        <ul class="list-unstyled components">
          <li>
            <a href="1">Unternehmensdaten</a>
          </li>
          <li>
            <a href="2">Haftungsrisiken</a>
          </li>
          <li>
            <a href="3">Gebäude-Werte</a>
          </li>
          <li>
            <a href="4">Inhalt-Werte</a>
          </li>
          <li>
            <a href="5">Elektronik/Maschinen-Werte</a>
          </li>
          <li>
            <a href="6">Unterbrechung Ihres Betriebes</a>
          </li>
          <li>
            <a href="7">Kosten bei Rechtsangelegenheiten</a>
          </li>
          <li>
            <a href="8">Transporte</a>
          </li>
          <li>
            <a href="9">Kfz-Risiken</a>
          </li>
          <li>
            <a href="10">Spezial-Risiken</a>
          </li>
          <li class="active">
            <a href="11">Mitarbeiter</a>
          </li>
          <li class="active">
            <a href="12">Belegschaft / Inhabers / GGf / etc.</a>
          </li>
          <li>
            <a href="13">Offene Punkte und weiteres Vorgehen</a>
          </li>
        </ul>
        <ul class="list-unstyled CTAs">
          <li>
            <a 
              href="../analyse"
              class="resume mt-3"><i class="fas fa-sliders-h"/> Analyse</a>
          </li>
        </ul>
      </nav>
      <!-- Page Content Holder -->
      <div id="content">
        <nav class="navbar sticky-top navbar-expand-lg navbar-light bg-light">
          <div class="container-fluid">
            <button 
              id="sidebarCollapse" 
              type="button" 
              class="navbar-btn">
              <span/>
              <span/>
              <span/>
            </button>
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
            <ul class="nav navbar-nav navbar-expand ml-auto">
              <li class="nav-item">
                <a 
                  class="nav-link" 
                  href="selectuser"><i class="fas fa-users"/> Kunden</a>
              </li>
              <li class="nav-item">
                <a 
                  class="nav-link" 
                  href="login"><i class="fas fa-sign-out-alt"/> Abmelden</a>
              </li>
            </ul>
          </div>
        </nav>
        <div class="container-fluid">
          <div class="row">
            <div class="col-10">
              <h3>Absicherung Ihrer Mitarbeiter</h3>
            </div>
            <div class="col-2 float-sm-right text-right">
              <a 
                href="12"
                class="btn btn-success">Speichern</a>
            </div>
          </div>
          <div class="line"/>
          <form>
            <div class="form-row">
              <div class="form-group col-xl-6">
                <div class="card">
                  <div class="card-body">
                    <label for="company">Ist Ihr Internehmen Tarifgebunden oder an einen Tarifvertrag angelehnt, wenn ja, um welchen Tarifvertrag handelt es sich?</label>
                    <textarea 
                      id="place" 
                      type="text-area" 
                      class="form-control" 
                      rows="2" 
                      placeholder=""/>
                  </div>
                </div>
              </div>
              <div class="form-group col-xl-6">
                <div class="card">
                  <div class="card-body aligner">
                    <div class="row aligner-item">
                      <label 
                        class="col-sm-9 col-form-label" 
                        for="user">Ist ein Betriebsrat vorhanden?</label>
                      <div class="col-sm-3">
                        <div class="text-right">
                          <div class="text-right">
                            <div class="custom-control custom-radio custom-control-inline">
                              <input 
                                id="customRadioInline1" 
                                type="radio" 
                                name="customRadioInline1" 
                                class="custom-control-input">
                              <label 
                                class="custom-control-label" 
                                for="customRadioInline1">ja</label>
                            </div>
                            <div class="custom-control custom-radio custom-control-inline">
                              <input 
                                id="customRadioInline2" 
                                type="radio" 
                                name="customRadioInline1" 
                                class="custom-control-input">
                              <label 
                                class="custom-control-label" 
                                for="customRadioInline2">nein</label>
                            </div>
                          </div>
                        </div>
                      </div>
                    </div>
                  </div>
                </div>
              </div>
            </div>
            <div class="form-row">
              <div class="form-group col-xl-6">
                <div class="card">
                  <div class="card-body">
                    <label for="company">Wie ist die betriebliche Alterversorgungen für Ihre Matarbeiter geregelt?</label>
                    <textarea 
                      id="place" 
                      type="text-area" 
                      class="form-control" 
                      rows="2" 
                      placeholder=""/>
                  </div>
                </div>
              </div>
              <div class="form-group col-xl-6">
                <div class="card">
                  <div class="card-body">
                    <label for="company">Wie werden neue Mitarbeiter über die Möglickeiten der betrieblichen Alterversorgung informiert?</label>
                    <textarea 
                      id="place" 
                      type="text-area" 
                      class="form-control" 
                      rows="2" 
                      placeholder=""/>
                  </div>
                </div>
              </div>
            </div>
            <div class="form-group">
              <div class="card">
                <div class="card-body">
                  <label for="company">Wie wurden Sie über das Betriebsrentenstärkungsgesetz 2018 und den damit verbundenen Möglichkeiten und Pflichten für Arbeitnehmer und Arbeitgeber informiert?</label>
                  <textarea 
                    id="place" 
                    type="text-area" 
                    class="form-control" 
                    rows="2" 
                    placeholder=""/>
                </div>
              </div>
            </div>
            <div class="form-group">
              <div class="card">
                <div class="card-body">
                  <label for="place">Notizen</label>
                  <textarea 
                    id="place" 
                    type="text-area" 
                    class="form-control" 
                    rows="3" 
                    placeholder=""/>
                </div>
              </div>
            </div>
          </form>
        </div>
      </div>
    </div>
  </section>
</template>
