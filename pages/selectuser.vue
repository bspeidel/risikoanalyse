<template>
  <section>
    <nav class="navbar sticky-top navbar-expand-lg navbar-light bg-light">
      <div class="container-fluid">
        <div class="sidebar-header text-center">
          <img
            class="fixed"
            src="~assets/images/zurich-logo.png"
            alt="">
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
                href="index"><i class="fas fa-sign-out-alt"/> Abmelden</a>
            </li>
          </ul>
        </div>
      </div>
    </nav>
    <div class="container-fluid">
      <div class="row">
        <div class="col">
          <h2>Kunden</h2>
        </div>
        <div class="col d-flex justify-content-end">
          <form class="form-inline my-2 my-lg-0">
            <input
              type="search"
              placeholder="kunden suchen..."
              name="search"
              class="form-control searchbox-input mr-sm-2"
              required="">
            <b-btn 
              v-b-modal.modal1 
              class="btn-success"><i class="fas fa-user-plus"/> Kunde hinzufügen</b-btn>
          </form>
        </div>
      </div>
      <div class="line"/>
      <div class="card-columns user">
        <div class="card mt-2">
          <div class="card-header">
            <h5 class="card-title">Heidelberger Druckmaschinen AG
              <span class="float-sm-right">
                <a href="#"><i class="fas fa-edit"/></a>
              </span>
            </h5>
          </div>
          <div class="card-body">
            <h6 class="card-subtitle mb-2 text-muted">Ute Wechsler</h6>
            <p class="card-text"/>
            <address>
              Kurfürsten-Anlage 52-60<br>
              69115 Heidelberg<br>
              Tel: 6221 92 00<br>
              E-Mail: <a href="mailto:#">ute.wechsler@heidelberg.de</a>
            </address>
          </div>
          <div class="card-footer">
            <div
              class="btn-group d-flex"
              role="group">
              <a
                href="#14"
                class="btn btn-primary w-100"
                data-toggle="collapse"
                role="button"
                aria-expanded="false"
                aria-controls="14"><i class="far fa-calendar-check"/> Jahreshespräch</a>
              <a
                href="analyse"
                class="btn btn-secondary w-100"><i class="fas fa-sliders-h"/> Analyse</a>
            </div>
            <div
              id="14"
              class="collapse">
              <div class="list-group mt-4">
                <a
                  href="form/1"
                  type="button"
                  class="list-group-item"><i class="far fa-calendar-check"/> Jahreshespräch<span class="float-sm-right">01.03.2018</span></a>
                <a
                  href="form/1"
                  type="button"
                  class="list-group-item"><i class="far fa-calendar-check"/> Jahreshespräch<span class="float-sm-right">12.04.2017</span></a>
                <a
                  href="form/1"
                  type="button"
                  class="list-group-item"><i class="far fa-calendar-check"/> Jahreshespräch<span class="float-sm-right">24.02.2016</span></a>
              </div>
            </div>
          </div>
        </div>
        <div class="card mt-2">
          <div class="card-header">
            <h5 class="card-title">Linde Material Handling GmbH
              <span class="float-sm-right">
                <a href="#"><i class="fas fa-edit"/></a>
              </span>
            </h5>
          </div>
          <div class="card-body">
            <h6 class="card-subtitle mb-1 text-muted">Phillipp Koehler</h6>
            <p class="card-text"/>
            <address>
              Heinrich Heine Platz 84<br>
              99722 Nordhausen<br>
              Tel: 03631 76 20 73<br>
              E-Mail: <a href="mailto:#">p.koehler@gmx.de</a>
            </address>
          </div>
          <div class="card-footer">
            <div
              class="btn-group d-flex"
              role="group">
              <a
                href="/form/1"
                class="btn btn-primary w-100"><i class="far fa-calendar-check"/> Jahreshespräch</a>
              <a
                href="#16"
                class="btn btn-secondary w-100"
                data-toggle="collapse"
                role="button"
                aria-expanded="false"
                aria-controls="14"><i class="fas fa-sliders-h"/> Analyse</a>
            </div>
            <div
              id="16"
              class="collapse">
              <div class="list-group mt-4">
                <a
                  href="analyse"
                  type="button"
                  class="list-group-item"><i class="fas fa-sliders-h"/> Analyse<span class="float-sm-right">01.03.2018</span></a>
                <a
                  href="analyse"
                  type="button"
                  class="list-group-item"><i class="fas fa-sliders-h"/> Analyse<span class="float-sm-right">12.04.2017</span></a>
                <a
                  href="analyse"
                  type="button"
                  class="list-group-item"><i class="fas fa-sliders-h"/> Analyse<span class="float-sm-right">24.02.2016</span></a>
              </div>
            </div>
          </div>
        </div>
        <div class="card mt-2">
          <div class="card-header">
            <h5 class="card-title">Umicore AG & Co. KG
              <span class="float-sm-right">
                <a href="#"><i class="fas fa-edit"/></a>
              </span>
            </h5>
          </div>
          <div class="card-body">
            <h6 class="card-subtitle mb-2 text-muted">Martin Konig</h6>
            <p class="card-text"/>
            <address>
              Budapester Strasse 4<br>
              24516 Neumünster<br>
              Tel: 04321 63 97 12<br>
              E-Mail: <a href="mailto:#">martinkonig@teleworm.de</a>
            </address>
          </div>
          <div class="card-footer">
            <div
              class="btn-group d-flex"
              role="group">
              <a
                href="/form/1"
                class="btn btn-primary w-100"><i class="far fa-calendar-check"/> Jahreshespräch</a>
              <a
                href="analyse"
                class="btn btn-secondary w-100"><i class="fas fa-sliders-h"/> Analyse</a>
            </div>
          </div>
        </div>
        <div class="card mt-2">
          <div class="card-header">
            <h5 class="card-title">TLG Immobilien
              <span class="float-sm-right">
                <a href="#"><i class="fas fa-edit"/></a>
              </span>
            </h5>
          </div>
          <div class="card-body">
            <h6 class="card-subtitle mb-2 text-muted">Maik Bachmeier</h6>
            <p class="card-text"/>
            <address>
              Flughafenstrasse 8<br>
              95671 Bärnau<br>
              Tel: 09635 78 10 80<br>
              E-Mail: <a href="mailto:#">maik-bachmeier@telekom.de</a>
            </address>
          </div>
          <div class="card-footer">
            <div
              class="btn-group d-flex"
              role="group">
              <a
                href="/form/1"
                class="btn btn-primary w-100"><i class="far fa-calendar-check"/> Jahreshespräch</a>
              <a
                href="analyse"
                class="btn btn-secondary w-100"><i class="fas fa-sliders-h"/> Analyse</a>
            </div>
          </div>
        </div>
        <div class="card mt-2">
          <div class="card-header">
            <h5 class="card-title">Carl Zeiss AG
              <span class="float-sm-right">
                <a href="#"><i class="fas fa-edit"/></a>
              </span>
            </h5>
          </div>
          <div class="card-body">
            <h6 class="card-subtitle mb-2 text-muted">Katrin Wurfel</h6>
            <p class="card-text"/>
            <address>
              Leopoldstraße 68<br>
              12489 Berlin Adlershof<br>
              Tel: 030 14 64 62<br>
              E-Mail: <a href="mailto:#">k.wurfel@zeiss.de</a>
            </address>
          </div>
          <div class="card-footer">
            <div
              class="btn-group d-flex"
              role="group">
              <a
                href="/form/1"
                class="btn btn-primary w-100"><i class="far fa-calendar-check"/> Jahreshespräch</a>
              <a
                href="analyse"
                class="btn btn-secondary w-100"><i class="fas fa-sliders-h"/> Analyse</a>
            </div>
          </div>
        </div>
        <div class="card mt-2">
          <div class="card-header">
            <h5 class="card-title">ThyssenKrupp Rasselstein GmbH
              <span class="float-sm-right">
                <a href="#"><i class="fas fa-edit"/></a>
              </span>
            </h5>
          </div>
          <div class="card-body">
            <h6 class="card-subtitle mb-2 text-muted">Lucas Maier</h6>
            <p class="card-text"/>
            <address>
              Rhinstrasse 86<br>
              80935 München<br>
              Tel: 089 64 73 92<br>
              E-Mail: <a href="mailto:#">l.amsel@thyssenkrupp.de</a>
            </address>
          </div>
          <div class="card-footer">
            <div
              class="btn-group d-flex"
              role="group">
              <a
                href="/form/1"
                class="btn btn-primary w-100"><i class="far fa-calendar-check"/> Jahreshespräch</a>
              <a
                href="analyse"
                class="btn btn-secondary w-100"><i class="fas fa-sliders-h"/> Analyse</a>
            </div>
          </div>
        </div>
        <div class="card mt-2">
          <div class="card-header">
            <h5 class="card-title">Alfred Kärcher GmbH & Co. KG
              <span class="float-sm-right">
                <a href="#"><i class="fas fa-edit"/></a>
              </span>
            </h5>
          </div>
          <div class="card-body">
            <h6 class="card-subtitle mb-2 text-muted">Julia Strauss</h6>
            <p class="card-text"/>
            <address>
              Brandenburgische Straße 91<br>
              10179 Berlin Mitte<br>
              Tel: 030 71 14 54<br>
              E-Mail: <a href="mailto:#">juliastrauss@rhyta.com</a>
            </address>
          </div>
          <div class="card-footer">
            <div
              class="btn-group d-flex"
              role="group">
              <a
                href="/form/1"
                class="btn btn-primary w-100"><i class="far fa-calendar-check"/> Jahreshespräch</a>
              <a
                href="analyse"
                class="btn btn-secondary w-100"><i class="fas fa-sliders-h"/> Analyse</a>
            </div>
          </div>
        </div>
        <div class="card mt-2">
          <div class="card-header">
            <h5 class="card-title">Zeppelin GmbH
              <span class="float-sm-right">
                <a href="#"><i class="fas fa-edit"/></a>
              </span>
            </h5>
          </div>
          <div class="card-body">
            <h6 class="card-subtitle mb-2 text-muted">Christian Reinhard</h6>
            <p class="card-text"/>
            <address>
              Prenzlauer Allee 25<br>
              04307 Leipzig<br>
              Tel: 0341 64 56 91<br>
              E-Mail: <a href="mailto:#">c.reinhard@zeppelin.com</a>
            </address>
          </div>
          <div class="card-footer">
            <div
              class="btn-group d-flex"
              role="group">
              <a
                href="/form/1"
                class="btn btn-primary w-100"><i class="far fa-calendar-check"/> Jahreshespräch</a>
              <a
                href="analyse"
                class="btn btn-secondary w-100"><i class="fas fa-sliders-h"/> Analyse</a>
            </div>
          </div>
        </div>
        <div class="card mt-2">
          <div class="card-header">
            <h5 class="card-title">Bosch Thermotechnik GmbH
              <span class="float-sm-right">
                <a href="#"><i class="fas fa-edit"/></a>
              </span>
            </h5>
          </div>
          <div class="card-body">
            <h6 class="card-subtitle mb-2 text-muted">Katrin Maier</h6>
            <p class="card-text"/>
            <address>
              Landsberger Allee 18<br>
              80045 München<br>
              Tel: 089 19 49 94<br>
              E-Mail: <a href="mailto:#">k.maier@armyspy.com</a>
            </address>
          </div>
          <div class="card-footer">
            <div
              class="btn-group d-flex"
              role="group">
              <a
                href="/form/1"
                class="btn btn-primary w-100"><i class="far fa-calendar-check"/> Jahreshespräch</a>
              <a
                href="analyse"
                class="btn btn-secondary w-100"><i class="fas fa-sliders-h"/> Analyse</a>
            </div>
          </div>
        </div>
        <div class="card mt-2">
          <div class="card-header">
            <h5 class="card-title">Wieland-Werke AG
              <span class="float-sm-right">
                <a href="#"><i class="fas fa-edit"/></a>
              </span>
            </h5>
          </div>
          <div class="card-body">
            <h6 class="card-subtitle mb-2 text-muted">Anne Friedman</h6>
            <p class="card-text"/>
            <address>
              Brandenburgische Straße 26<br>
              12307 Berlin Marienfelde<br>
              Tel: 030 89 52 44<br>
              E-Mail: <a href="mailto:#">anne.friedman@wieland.de</a>
            </address>
          </div>
          <div class="card-footer">
            <div
              class="btn-group d-flex"
              role="group">
              <a
                href="/form/1"
                class="btn btn-primary w-100"><i class="far fa-calendar-check"/> Jahreshespräch</a>
              <a
                href="analyse"
                class="btn btn-secondary w-100"><i class="fas fa-sliders-h"/> Analyse</a>
            </div>
          </div>
        </div>
        <div class="card mt-2">
          <div class="card-header">
            <h5 class="card-title">Bosch Thermotechnik GmbH
              <span class="float-sm-right">
                <a href="#"><i class="fas fa-edit"/></a>
              </span>
            </h5>
          </div>
          <div class="card-body">
            <h6 class="card-subtitle mb-2 text-muted">Ute Maier</h6>
            <p class="card-text"/>
            <address>
              Landsberger Allee 18<br>
              80045 München<br>
              Tel: 089 19 49 94<br>
              E-Mail: <a href="mailto:#">ute.maier@bosch.de</a>
            </address>
          </div>
          <div class="card-footer">
            <div
              class="btn-group d-flex"
              role="group">
              <a
                href="form/1"
                class="btn btn-primary w-100"><i class="far fa-calendar-check"/> Jahreshespräch</a>
              <a
                href="analyse"
                class="btn btn-secondary w-100"><i class="fas fa-sliders-h"/> Analyse</a>
            </div>
          </div>
        </div>
        <div class="card mt-2">
          <div class="card-header">
            <h5 class="card-title">Bosch Thermotechnik GmbH
              <span class="float-sm-right">
                <a href="#"><i class="fas fa-edit"/></a>
              </span>
            </h5>
          </div>
          <div class="card-body">
            <h6 class="card-subtitle mb-2 text-muted">Leonie Farber</h6>
            <p class="card-text"/>
            <address>
              Unter den Linden 7<br>
              39008 Magdeburg<br>
              Tel: 0391 79 53 02<br>
              E-Mail: <a href="mailto:#">leonie.farber@bosch.de</a>
            </address>
          </div>
          <div class="card-footer">
            <div
              class="btn-group d-flex"
              role="group">
              <a
                href="/form/1"
                class="btn btn-primary w-100"><i class="far fa-calendar-check"/> Jahreshespräch</a>
              <a
                href="/analyse"
                class="btn btn-secondary w-100"><i class="fas fa-sliders-h"/> Analyse</a>
            </div>
          </div>
        </div>
      </div>
    </div>
    <b-modal 
      id="modal1" 
      title="Kunde hinzufügen">
      <div class="modal-content">
        <div class="modal-header">
          <h5 class="modal-title">Kunde hinzufügen</h5>
          <button
            type="button"
            class="close"
            data-dismiss="modal"
            aria-label="Close">
            <span aria-hidden="true">&times;</span>
          </button>
        </div>
        <div class="modal-body">
          <form>
            <div class="form-group">
              <label for="exampleFormControlInput1">Vorname</label>
              <input
                type="text"
                class="form-control"
                placeholder="">
            </div>
            <div class="form-group">
              <label for="exampleFormControlInput1">Nachname</label>
              <input
                type="text"
                class="form-control"
                placeholder="">
            </div>
            <div class="form-group">
              <label for="exampleFormControlInput1">Firma</label>
              <input
                type="text"
                class="form-control"
                placeholder="">
            </div>
            <div class="form-group">
              <label for="exampleFormControlInput1">Ort</label>
              <input
                type="text"
                class="form-control"
                placeholder="">
            </div>
            <div class="form-group">
              <label for="exampleFormControlInput1">Telefon</label>
              <input
                type="text"
                class="form-control"
                placeholder="">
            </div>
            <div class="form-group">
              <label for="exampleFormControlInput1">E-Mail</label>
              <input
                type="email"
                class="form-control"
                placeholder="">
            </div>
          </form>
        </div>
        <div class="modal-footer">
          <button
            type="button"
            class="btn btn-danger"
            data-dismiss="modal">abbrechen</button>
          <button
            type="button"
            class="btn btn-success">speichern</button>
        </div>
      </div>
    </b-modal>
  </section>
</template>
