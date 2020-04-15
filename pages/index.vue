<template>
<div>
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <meta http-equiv="X-UA-Compatible" content="ie=edge" />
    <title>Enrique Taietta | Web developer a Trento</title>
    <!-- <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/font-awesome/4.7.0/css/font-awesome.min.css"> -->
    <link
      rel="stylesheet"
      href="https://use.fontawesome.com/releases/v5.4.1/css/all.css"
      integrity="sha384-5sAR7xN1Nv6T6+dT2mhtzEpVJvfS3NScPQTrOxhwjIuvcA67KV2R5Jz6kr4abQsz"
      crossorigin="anonymous"
    />
    <link
      href="https://fonts.googleapis.com/css2?family=Comic+Neue:ital,wght@0,300;1,300&family=Girassol&family=Noto+Sans+SC:wght@500;900&family=Roboto+Slab:wght@900&display=swap"
      rel="stylesheet"
    />

    <!-- Bulma Version 0.8.x-->
    <link rel="stylesheet" href="https://unpkg.com/bulma@0.8.0/css/bulma.min.css" />
    <link rel="stylesheet" type="text/css" href="../css/personal.css" />
    <script async type="text/javascript" src="../js/bulma.js"></script>
  </head>

  <body>
    <!-- Navigation bar -->
    <nav class="navbar is-link is-fixed-top">
      <div class="navbar-brand">
        <div class="navbar-burger burger" data-target="navbarExampleTransparentExample">
          <span></span>
          <span></span>
          <span></span>
        </div>
      </div>

      <div id="navbarExampleTransparentExample" class="navbar-menu">
        <div class="navbar-end">
          <a class="navbar-item" href="#about">
            <span class="icon">
              <i class="fas fa-info"></i>
            </span>
            <span>About</span>
          </a>
          <a class="navbar-item" href="#skills">
            <span class="icon">
              <i class="fas fa-book"></i>
            </span>
            <span>Skills</span>
          </a>
          <a class="navbar-item" href="#services">
            <span class="icon">
              <i class="fas fa-bars"></i>
            </span>
            <span>Services</span>
          </a>
          <a class="navbar-item" href="#portfolio">
            <span class="icon">
              <i class="fas fa-th-list"></i>
            </span>
            <span>Portfolio</span>
          </a>
          <a class="navbar-item" href="#resume">
            <span class="icon">
              <i class="fas fa-file-alt"></i>
            </span>
            <span>Resume</span>
          </a>
        </div>
      </div>
    </nav>

    <!-- Header -->
    <section class="hero is-link is-fullheight is-fullheight-with-navbar">
      <div class="hero-body">
        <div class="container">
          Hello! I am
          <h1 class="title is-1">Taietta Enrique</h1>
          <h2 class="subtitle is-3">Software Developer</h2>
        </div>
      </div>
    </section>

    <!-- About -->
    <section class="section" id="about">
      <div class="section">
        <div class="columns">
          <div class="column is-2">
            <h3 class="title is-3">About Me</h3>
          </div>
          <div>
            <div class="columns">
              <div class="column">
                <!-- Title -->

                <p>
                  Web developer with more than
                  <strong>4 years</strong> of well-rounded experience with a degree in the
                  field of
                  <strong>Computer Science</strong>, extensive knowledge of modern Web techniques and love for
                  <strong>Coffee</strong>.
                  Looking for an opportunity to work and upgrade, as well as being involved in an organization that
                  believes
                  in gaining a competitive edge and giving back to the community.
                </p>

                <!-- Profile -->
                <div class="card">
                  <div class="card-content">
                    <h3 class="title is-4 has-text-centered">Profile</h3>

                    <div class="content">
                      <table class="table">
                        <tr>
                          <th colspan="1"></th>
                          <th colspan="2"></th>
                        </tr>
                        <tr>
                          <th>Phone:</th>
                          <td>
                            <a href="tel:+393393649790"></a>+39 339 3649790
                          </td>
                        </tr>
                        <tr>
                          <th>Email:</th>
                          <td>enrique.taietta@posteo.com</td>
                        </tr>
                        <tr>
                          <th>Based:</th>
                          <td>Verona - Trento</td>
                        </tr>
                      </table>
                    </div>
                    <br />
                    <div class="buttons has-addons is-centered">
                      <a href="#" class="button is-link">Github</a>
                      <a href="#" class="button is-link">LinkedIn</a>
                      <a href="#" class="button is-link">Twitter</a>
                    </div>
                  </div>
                </div>
              </div>
              <div class="column">
                <!-- Profile picture -->
                <div class="card">
                  <div class="card-image">
                    <figure class="image is-4by3">
                      <img
                        src="https://source.unsplash.com/random/1280x960"
                        alt="Placeholder image"
                      />
                    </figure>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>

    <!-- Skills tags -->
    <!-- <br>
        <div class="tags custom-tags">
          <span class="tag is-light">Node.js</span><span class="tag is-light">Express.js</span><span class="tag is-light">VueJS</span><span
            class="tag is-light">JavaScript</span><span class="tag is-light">HTML5</span><span class="tag is-light">Canvas</span><span
            class="tag is-light">CSS3</span><span class="tag is-light">Bulma</span><span class="tag is-light">Bootstrap</span><span
            class="tag is-light">jQuery</span><span class="tag is-light">Pug</span><span class="tag is-light">Stylus</span><span
            class="tag is-light">SASS/SCSS</span><span class="tag is-light">Webpack</span><span class="tag is-light">Git</span><span
            class="tag is-light">ASP.NET Web Forms</span><span class="tag is-light">MSSQL</span><span class="tag is-light">MongoDB</span><span
            class="tag is-light">Apache Cordova</span><span class="tag is-light">Chrome Extensions</span>
    </div>-->

    <section class="section" id="skills">
      <div class="section">
        <div class="columns">
          <!-- Skills -->
          <div class="column is-2">
            <h3 class="title is-3">Skills</h3>
          </div>
          <div class="column is-10">
            <p class="title is-4">Languages & Frameworks</p>
            <div class="columns is-variable is-1">
              <div class="column has-text-centered is-narrow">
                <div class="box">JavaScript</div>
              </div>

              <div class="column has-text-centered is-narrow">
                <div class="box">Typescript</div>
              </div>

              <div class="column has-text-centered is-narrow">
                <p class="box">Python</p>
              </div>

              <div class="column has-text-centered is-narrow">
                <p class="box">COBOL</p>
              </div>

              <div class="column has-text-centered is-narrow">
                <p class="box">Vue.js</p>
              </div>

              <div class="column has-text-centered is-narrow">
                <p class="box">Nuxt.js</p>
              </div>
            </div>

            <p class="title is-4">Databases</p>
            <div class="columns is-variable is-1">
              <div class="column is-narrow">
                <p class="box">MongoDB</p>
              </div>
              <div class="column is-narrow">
                <p class="box">DB2</p>
              </div>
              <div class="column is-narrow">
                <p class="box">Oracle</p>
              </div>
            </div>

            <p class="title is-4">Other</p>
            <div class="columns is-variable is-1">
              <div class="column is-narrow">
                <p class="box">ZEIT Now</p>
              </div>

              <div class="column is-narrow">
                <p class="box">Bulma</p>
              </div>

              <div class="column is-narrow">
                <p class="box">Rest API</p>
              </div>
              <div class="column is-narrow">
                <p class="box">Serverless</p>
              </div>
              <div class="column is-narrow">
                <p class="box">Git</p>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>

    <!-- Services -->
    <section class="section" id="services">
      <div class="section">
        <div class="columns">
          <div class="column is-2">
            <h3 class="title is-3">Services</h3>
          </div>
          <div class="column is-10">
            <div class="columns">
              <div class="column">
                <div class="box">
                  <div class="content">
                    <h4 class="title is-5">Front End Web Development</h4>Develop Front End using latest standards with HTML5/CSS3 with added funtionality using JavaScript and
                    Vue.js.
                  </div>
                </div>
              </div>
              <div class="column">
                <div class="box">
                  <div class="content">
                    <h4 class="title is-5">Back End Web Development</h4>Develop Back End application/service using Node.js or ASP .NET and SQL server or Mongo DB databases.
                  </div>
                </div>
              </div>
              <div class="column">
                <div class="box">
                  <div class="content">
                    <h4 class="title is-5">Software for Banks and Finance applications</h4>Support development of finance and Bank applications using COBOL and DB2 or Oracle databases.
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>

    <!-- Portfolio -->
    <section class="section" id="portfolio">
      <div class="section">
        <div class="columns">
          <div class="column is-2">
            <h3 class="title is-3">Portfolio</h3>
            <h4 class="subtitle is-5">My latest works</h4>
          </div>

          <div class="column is-10">
            <div class="columns">
              <div class="column">
                <div class="card">
                  <header class="card-header">
                    <p class="card-header-title">
                      <span>Cards</span>
                      <span class="is-pulled-right">
                        <a href="https://github.com/jgthms/bulma/releases/tag/0.7.2">
                          <span class="tag is-default">v0.7.2</span>
                        </a>
                        <span class="tag is-default">Desktop</span>
                        <span class="tag is-default">?</span>
                      </span>
                    </p>
                  </header>
                  <div class="card-image">
                    <figure class="image">
                      <img src="../images/cards.png" alt="Cards template screenshot" />
                    </figure>
                  </div>
                  <div class="card-content">
                    <div class="content">
                      Lorem ipsum dolor sit amet, consectetur adipiscing elit.
                      Phasellus nec iaculis mauris.
                      <a>@bulmaio</a>.
                      <a href="#">#css</a>
                      <a href="#">#responsive</a>
                      <br />
                    </div>
                  </div>
                  <footer class="card-footer">
                    <a href="templates/cards.html" class="card-footer-item">Preview</a>
                    <a
                      href="https://github.com/BulmaTemplates/bulma-templates/blob/master/templates/cards.html"
                      class="card-footer-item"
                    >
                      Source
                      Code
                    </a>
                  </footer>
                </div>
              </div>
              <div class="column">
                <div class="card">
                  <header class="card-header">
                    <p class="card-header-title">
                      <span>Cards</span>
                      <span class="is-pulled-right">
                        <a href="https://github.com/jgthms/bulma/releases/tag/0.7.2">
                          <span class="tag is-default">v0.7.2</span>
                        </a>
                        <span class="tag is-default">Desktop</span>
                        <span class="tag is-default">?</span>
                      </span>
                    </p>
                  </header>
                  <div class="card-image">
                    <figure class="image">
                      <img src="../images/cards.png" alt="Cards template screenshot" />
                    </figure>
                  </div>
                  <div class="card-content">
                    <div class="content">
                      Lorem ipsum dolor sit amet, consectetur adipiscing elit.
                      Phasellus nec iaculis mauris.
                      <a>@bulmaio</a>.
                      <a href="#">#css</a>
                      <a href="#">#responsive</a>
                      <br />
                    </div>
                  </div>
                  <footer class="card-footer">
                    <a href="templates/cards.html" class="card-footer-item">Preview</a>
                    <a
                      href="https://github.com/BulmaTemplates/bulma-templates/blob/master/templates/cards.html"
                      class="card-footer-item"
                    >
                      Source
                      Code
                    </a>
                  </footer>
                </div>
              </div>
              <div class="column"></div>
            </div>
          </div>
        </div>
      </div>
    </section>

    <!-- Resume -->
    <section class="section" id="resume">
      <div class="section-heading">
        <h3 class="title is-2 has-text-centered">Resume</h3>
        <div class="columns is-mobile is-centered">
          <div class=".is-centered">
            <a href="#" class="button is-link is-medium">
              <span class="icon">
                <i class="fas fa-file-alt"></i>
              </span>

              <span>Download My Resume</span>
            </a>
          </div>
        </div>
      </div>
    </section>
    <!-- Achievement Level -->
    <!-- <section class="section">
    <nav class="level">
      <div class="level-item has-text-centered">
        <div>
          <p class="heading">Tweets</p>
          <p class="title">3,456</p>
        </div>
      </div>
      <div class="level-item has-text-centered">
        <div>
          <p class="heading">Following</p>
          <p class="title">123</p>
        </div>
      </div>
      <div class="level-item has-text-centered">
        <div>
          <p class="heading">Followers</p>
          <p class="title">456K</p>
        </div>
      </div>
      <div class="level-item has-text-centered">
        <div>
          <p class="heading">Likes</p>
          <p class="title">789</p>
        </div>
      </div>
    </nav>
    </section>-->

    <!-- Footer -->
    <footer class="footer"></footer>
  </body>
</div>
</template>

<script lang="ts">
import Vue from "vue";

export default Vue.extend({
  components: {}
});
</script>

<style>
html {
  scroll-behavior: smooth;
}

body {
  font-family: "Noto Sans SC", sans-serif;
  font-family: "Comic Neue", cursive;
  font-family: "Girassol", cursive;
  font-family: "Roboto Slab", serif;
}
</style>
