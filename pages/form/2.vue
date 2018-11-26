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
          <li class="active">
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
          <li>
            <a href="11">Mitarbeiter</a>
          </li>
          <li>
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
              class="resume mt-3"><i class="fas fa-chart-pie"/> Bedarfsanalyse</a>
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
              <h3>Absicherung Ihrer Haftungsrisiken</h3>
            </div>
            <div class="col-2 float-sm-right text-right">
              <a 
                href="3"
                class="btn btn-success">Speichern</a>
            </div>
          </div>
          <div class="line"/>
          <form>
            <div class="form-row">
              <div class="form-group col-xl-6">
                <div class="card">
                  <div class="card-body aligner">
                    <div class="row aligner-item">
                      <label 
                        class="col-sm-9 col-form-label" 
                        for="place">Verischerungssumme Betriebshaftpflicht</label>
                      <div class="col-sm-3">
                        <div class="input-group">
                          <input 
                            type="text" 
                            class="form-control" 
                            placeholder="" 
                            aria-label="" 
                            aria-describedby="basic-addon2">
                          <div class="input-group-append">
                            <span 
                              id="basic-addon2" 
                              class="input-group-text">€</span>
                          </div>
                        </div>
                      </div>
                    </div>
                  </div>
                </div>
              </div>
              <div class="form-group col-xl-6">
                <div class="card">
                  <div class="card-body aligner">
                    <div class="row aligner-item">
                      <label 
                        class="col-sm-9 col-form-label" 
                        for="user">Reparieren bzw. warten Sie Kundeneigentum auf Ihrem Grundstück?</label>
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
                  <div class="card-body aligner">
                    <div class="row aligner-item">
                      <label 
                        class="col-sm-9 col-form-label" 
                        for="user">Haben Sie Arbeisgeräte / Werkzeuge gemietet, für die Sie die Gefahr tragen? (Mietsachschäden beweglich)</label>
                      <div class="col-sm-3">
                        <div class="text-right">
                          <div class="text-right">
                            <div class="custom-control custom-radio custom-control-inline">
                              <input 
                                id="customRadioInline11" 
                                type="radio" 
                                name="customRadioInline11" 
                                class="custom-control-input">
                              <label 
                                class="custom-control-label" 
                                for="customRadioInline11">ja</label>
                            </div>
                            <div class="custom-control custom-radio custom-control-inline">
                              <input 
                                id="customRadioInline21" 
                                type="radio" 
                                name="customRadioInline11" 
                                class="custom-control-input">
                              <label 
                                class="custom-control-label" 
                                for="customRadioInline21">nein</label>
                            </div>
                          </div>
                        </div>
                      </div>
                    </div>
                  </div>
                </div>
              </div>
              <div class="form-group col-xl-6">
                <div class="card">
                  <div class="card-body aligner">
                    <div class="row aligner-item">
                      <label 
                        class="col-sm-9 col-form-label" 
                        for="user">Werden Ihrer Arbeitsmaschinen / Stapler auch außerhalb Ihres Betriebsgrundstückes eingesetzt? (Sondergenehmigung / AKB_Deckung)</label>
                      <div class="col-sm-3">
                        <div class="text-right">
                          <div class="text-right">
                            <div class="custom-control custom-radio custom-control-inline">
                              <input 
                                id="customRadioInline13" 
                                type="radio" 
                                name="customRadioInline13" 
                                class="custom-control-input">
                              <label 
                                class="custom-control-label" 
                                for="customRadioInline13">ja</label>
                            </div>
                            <div class="custom-control custom-radio custom-control-inline">
                              <input 
                                id="customRadioInline23" 
                                type="radio" 
                                name="customRadioInline13" 
                                class="custom-control-input">
                              <label 
                                class="custom-control-label" 
                                for="customRadioInline23">nein</label>
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
                  <div class="card-body aligner">
                    <div class="row aligner-item">
                      <label 
                        class="col-sm-9 col-form-label" 
                        for="user">Können Schäden an anderen Gewerken durch Nachbesserungsarbeiten entsehen? (Nachbesserungsbegleitschäden)</label>
                      <div class="col-sm-3">
                        <div class="text-right">
                          <div class="text-right">
                            <div class="custom-control custom-radio custom-control-inline">
                              <input 
                                id="customRadioInline14" 
                                type="radio" 
                                name="customRadioInline14" 
                                class="custom-control-input">
                              <label 
                                class="custom-control-label" 
                                for="customRadioInline14">ja</label>
                            </div>
                            <div class="custom-control custom-radio custom-control-inline">
                              <input 
                                id="customRadioInline24" 
                                type="radio" 
                                name="customRadioInline14" 
                                class="custom-control-input">
                              <label 
                                class="custom-control-label" 
                                for="customRadioInline24">nein</label>
                            </div>
                          </div>
                        </div>
                      </div>
                    </div>
                  </div>
                </div>
              </div>
              <div class="form-group col-xl-6">
                <div class="card">
                  <div class="card-body aligner">
                    <div class="row aligner-item">
                      <label 
                        class="col-sm-9 col-form-label" 
                        for="user">Werden Ihre Produkte mit anderen Produkten vermischt, verbunden, weiterverarbeitet oder eingebaut?</label>
                      <div class="col-sm-3">
                        <div class="text-right">
                          <div class="text-right">
                            <div class="custom-control custom-radio custom-control-inline">
                              <input 
                                id="customRadioInline15" 
                                type="radio" 
                                name="customRadioInline15" 
                                class="custom-control-input">
                              <label 
                                class="custom-control-label" 
                                for="customRadioInline25">ja</label>
                            </div>
                            <div class="custom-control custom-radio custom-control-inline">
                              <input 
                                id="customRadioInline25" 
                                type="radio" 
                                name="customRadioInline15" 
                                class="custom-control-input">
                              <label 
                                class="custom-control-label" 
                                for="customRadioInline25">nein</label>
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
                  <div class="card-body aligner">
                    <div class="row aligner-item">
                      <label 
                        class="col-sm-9 col-form-label" 
                        for="user">Arbeiten Sie auch im außereuropäischen Ausland? Werden Ihre Produkte auch in die USA/CAN exportiert?</label>
                      <div class="col-sm-3">
                        <div class="text-right">
                          <div class="text-right">
                            <div class="custom-control custom-radio custom-control-inline">
                              <input 
                                id="customRadioInline155" 
                                type="radio" 
                                name="customRadioInline155" 
                                class="custom-control-input">
                              <label 
                                class="custom-control-label" 
                                for="customRadioInline155">ja</label>
                            </div>
                            <div class="custom-control custom-radio custom-control-inline">
                              <input 
                                id="customRadioInline255" 
                                type="radio" 
                                name="customRadioInline155" 
                                class="custom-control-input">
                              <label 
                                class="custom-control-label" 
                                for="customRadioInline255">nein</label>
                            </div>
                          </div>
                        </div>
                      </div>
                    </div>
                  </div>
                </div>
              </div>
              <div class="form-group col-xl-6">
                <div class="card">
                  <div class="card-body aligner">
                    <div class="row aligner-item">
                      <label 
                        class="col-sm-9 col-form-label" 
                        for="user">Sind umweltrelevante Anlagen bzw. Lagermengen > 15.000 Liter umweltgefährender Stoffe vorhanden?</label>
                      <div class="col-sm-3">
                        <div class="text-right">
                          <div class="text-right">
                            <div class="custom-control custom-radio custom-control-inline">
                              <input 
                                id="customRadioInline16" 
                                type="radio" 
                                name="customRadioInline16" 
                                class="custom-control-input">
                              <label 
                                class="custom-control-label" 
                                for="customRadioInline16">ja</label>
                            </div>
                            <div class="custom-control custom-radio custom-control-inline">
                              <input 
                                id="customRadioInline26" 
                                type="radio" 
                                name="customRadioInline16" 
                                class="custom-control-input">
                              <label 
                                class="custom-control-label" 
                                for="customRadioInline26">nein</label>
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
                  <div class="card-body aligner">
                    <div class="row aligner-item">
                      <label 
                        class="col-sm-9 col-form-label" 
                        for="user">Besteht eine Absicherung Ihres Privatvermögens bei schuldhaften Pflichtverletzungen? (D&O-Entcheiderhafplicht)?</label>
                      <div class="col-sm-3">
                        <div class="text-right">
                          <div class="custom-control custom-radio custom-control-inline">
                            <input 
                              id="customRadioInline17" 
                              type="radio" 
                              name="customRadioInline17" 
                              class="custom-control-input">
                            <label 
                              class="custom-control-label" 
                              for="customRadioInline17">ja</label>
                          </div>
                          <div class="custom-control custom-radio custom-control-inline">
                            <input 
                              id="customRadioInline27" 
                              type="radio" 
                              name="customRadioInline17" 
                              class="custom-control-input">
                            <label 
                              class="custom-control-label" 
                              for="customRadioInline27">nein</label>
                          </div>
                        </div>
                      </div>
                      <div class="col-sm-12">
                        <small 
                          id="passwordHelpBlock" 
                          class="form-text text-danger">
                          <strong>Wichtig:</strong> Geschäftsführer / Vorstände von Kapitalgesellschaften haften ggf. für Verletzungen der Sorgfalspflicht persönlich und unbegrenzt.
                        </small>
                      </div>
                    </div>
                  </div>
                </div>
              </div>
              <div class="form-group col-xl-6">
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
            </div>
          </form>
        </div>
      </div>
    </div>
  </section>
</template>
