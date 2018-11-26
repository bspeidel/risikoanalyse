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
          <li class="active">
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
                  href="index"><i class="fas fa-sign-out-alt"/> Abmelden</a>
              </li>
            </ul>
          </div>
        </nav>
        <div class="container-fluid">
          <div class="row">
            <div class="col-10"/>
            <div class="col-2 float-sm-right text-right"/>
          </div>
          <h3>Absicherung Ihrer Transporte
            <span class="float-sm-right">
              <a 
                href="9" 
                class="btn btn-success">Speichern</a>
            </span>
          </h3>
          <div class="line"/>
          <form>
            <div class="form-row">
              <div class="form-group col-xl-6">
                <div class="card">
                  <div class="card-body">
                    <label for="company">Was ist die aktuelle Situation in Ihrem Unternehmen?</label>
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
                    <label for="user">Was sind Ihre Wünsche, Ziele und Erwartungen an das heutige Gespräch?</label>
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
            <div class="form-row">
              <div class="form-group col-xl-6">
                <div class="card">
                  <div class="card-body">
                    <label for="place">Hat sich Ihre Tätigkeit seit unserem letzen Gespräch verändert? Wenn ja, was ist neu?</label>
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
                    <label for="place">Planen Sie eine Anpassung Ihrer Taätigkeit? Wenn ja, welche und wann?</label>
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
            <div class="form-row">
              <div class="form-group col-xl-6">
                <div class="card">
                  <div class="card-body">
                    <label for="place">Wie ist Ihre aktuelle Inhaber-/Geschäftsführerstruktur? Sind ggf. Änderungen geplant?</label>
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
                    <label for="place">Welchen Umsatz (ohne MWSt.) haben Sie im abgelaufenen Geschäftjahr erzielt?</label>
                    <div class="input-group mb-3">
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

            <div class="form-group">
              <div class="card">
                <div class="card-body">
                  <div class="card-title"> Wie ist Ihre aktuelle Mitarbeiterstruktur?</div>
                  <div class="form-row">
                    <div class="form-group col-md-3">
                      <label for="inputEmail4">Anzahl Gesamt</label>
                      <input 
                        id="inputEmail4" 
                        type="text" 
                        class="form-control" 
                        placeholder="">
                    </div>
                    <div class="form-group col-md-3">
                      <label for="inputPassword4">davon Teilzeit</label>
                      <input 
                        id="inputPassword4" 
                        type="text" 
                        class="form-control" 
                        placeholder="">
                    </div>
                    <div class="form-group col-md-6">
                      <label for="inputPassword4">Lohn und Gehaltssumme im abgelaufenen Geschäftsjahr</label>
                      <div class="input-group mb-3">
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
                  <div class="form-row">
                    <div class="form-group col-md-3">
                      <label for="inputEmail4">kaufmännisch Anzahl</label>
                      <input 
                        id="inputEmail4" 
                        type="text" 
                        class="form-control" 
                        placeholder="">
                    </div>
                    <div class="form-group col-md-3">
                      <label for="inputPassword4">davon Teilzeit</label>
                      <input 
                        id="inputPassword4" 
                        type="text" 
                        class="form-control" 
                        placeholder="">
                    </div>
                    <div class="form-group col-md-6">
                      <label for="inputPassword4">Lohn und Gehaltssumme im abgelaufenen Geschäftsjahr</label>
                      <div class="input-group mb-3">
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
                  <div class="form-row">
                    <div class="form-group col-md-3">
                      <label for="inputEmail4">Gewerblich Anzahl</label>
                      <input 
                        id="inputEmail4" 
                        type="text" 
                        class="form-control" 
                        placeholder="">
                    </div>
                    <div class="form-group col-md-3">
                      <label for="inputPassword4">davon Teilzeit</label>
                      <input 
                        id="inputPassword4" 
                        type="text" 
                        class="form-control" 
                        placeholder="">
                    </div>
                    <div class="form-group col-md-6">
                      <label for="inputPassword4">Lohn und Gehaltssumme im abgelaufenen Geschäftsjahr</label>
                      <div class="input-group mb-3">
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
            <div class="form-group">
              <div class="card">
                <div class="card-body">
                  <label for="place">Sinf ggf. Veränderungen der Mitarbeiterstruktur geplant?</label>
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
