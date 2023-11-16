PORTFOLIO 
----------
assets
  -fonts
  -images
  -scss
    -component
    -global.scss
    -style.scss
index.html
main.js
========================
  <body>
    <!-- header section code starts here   -->
    <header class="header" id="header">
      <nav>
        <div class="navbar">
          <div class="navbar__logo">
            <h4>
              <a href="Homepage">Manish</a>
            </h4>
          </div>

          <ul class="navbar__link">
            <li><a href="#home">HOME</a></li>
            <li><a href="#about">ABOUT</a></li>
            <li><a href="#skills">SKILLS</a></li>
            <li><a href="#work">WORK</a></li>
          </ul>

          <div class="navbar__menu">
            <a href="contact">let's work together</a>
            <!-- <span class="navbar__menu-point"></span> -->
          </div>
        </div>
      </nav>
    </header>

    <main class="grid">
      <!-- hero section code starts here   -->
      <section class="hero-wrapper" id="hero">
        <div class="wrapper">
          <div class="hero">
            <h1>Manish Kumar</h1>
            <h1>Frontend Developer</h1>
          </div>
        </div>
      </section>

      <!-- about section code starts here   -->
      <section class="about-wrapper" id="about">
        <div class="wrapper">
          <div class="about">
            <div class="about__left">
              <h2>
                I enjoy creating things that live on the internet.
                <br />
                I'm happiest when I'm learning, creating, exploring and thinking
                about how to make things better in my domain.
              </h2>
            </div>
            <div class="about__right">
              <p>
                I have a bachelor degree in computer science from Lovely
                Professional University, Punjab (India).
                <br />
                I have also done Meta Front-End Developer Professional
                Certificate from Coursera.
              </p>
              <a class="about__btn btn" href="#about">About me</a>
            </div>
          </div>
          <hr />
        </div>
      </section>

      <!-- skills section code starts here   -->
      <section class="skills-wrapper" id="skills">
        <div class="wrapper">
          <div class="skill">
            <div class="skill__top">
              <h1 class="skill__title">Skills</h1>
              <div class="skill__top-abb">
                <p>
                  The skills, tools and <br />
                  technologies I play with
                </p>
                <p>( Techstack )</p>
              </div>
            </div>

            <div class="skill__bottom">
              <ul>
                <li>
                  <img
                    src="https://skillicons.dev/icons?i=html&theme=light"
                    alt=""
                  />
                </li>
                <li>
                  <img
                    src="https://skillicons.dev/icons?i=css&theme=light"
                    alt=""
                  />
                </li>
                <li>
                  <img
                    src="https://skillicons.dev/icons?i=javascript&theme=light"
                    alt=""
                  />
                </li>
                <li>
                  <img
                    src="https://skillicons.dev/icons?i=typescript&theme=light"
                    alt=""
                  />
                </li>
                <li>
                  <img
                    src="https://skillicons.dev/icons?i=react&theme=light"
                    alt=""
                  />
                </li>
                <li>
                  <img
                    src="https://skillicons.dev/icons?i=next&theme=light"
                    alt=""
                  />
                </li>
                <li>
                  <img
                    src="https://skillicons.dev/icons?i=tailwind&theme=light"
                    alt=""
                  />
                </li>
                <li>
                  <img
                    src="https://skillicons.dev/icons?i=sass&theme=light"
                    alt=""
                  />
                </li>
                <li>
                  <img
                    src="https://skillicons.dev/icons?i=nodejs&theme=light"
                    alt=""
                  />
                </li>
                <li>
                  <img
                    src="https://skillicons.dev/icons?i=expressjs&theme=light"
                    alt=""
                  />
                </li>
                <li>
                  <img
                    src="https://skillicons.dev/icons?i=mongodb&theme=light"
                    alt=""
                  />
                </li>
                <li>
                  <img
                    src="https://skillicons.dev/icons?i=github&theme=light"
                    alt=""
                  />
                </li>
              </ul>
            </div>
          </div>
        </div>
      </section>

      <!-- project section code starts here   -->
      <section class="project-wrapper" id="work">
        <div class="wrapper">
          <h1>Project</h1>
          <div class="project"></div>
        </div>
      </section>

      <!-- contact section code starts here   -->
      <section class="contact-wrapper" id="contact">
        <div class="wrapper">
          <div class="contact">
            <div class="contact__info">
              <h1>contact</h1>
              <p>
                I am always open to discuss or collaborate for any intersting
                projects &nbsp;
              </p>
            </div>
            <hr class="line" />
            <div class="contact__input">
              <form class="contact__input-form">
                <div class="contact__input-form-field">
                  <input
                    id="fname"
                    type="text"
                    placeholder="Enter the name ..."
                    name="fname"
                    required
                  />
                </div>

                <div class="contact__input-form-field">
                  <input
                    type="email"
                    id="email"
                    placeholder="Your email address..."
                    name="email"
                    required
                  />
                </div>

                <div class="contact__input-form-field">
                  <textarea
                    name="message"
                    id="message"
                    cols="7"
                    rows="4"
                    placeholder="message"
                  ></textarea>
                </div>
                <button class="contact__input-form-btn btn" type="submit">
                  Send
                </button>
              </form>
            </div>
          </div>
        </div>
      </section>

      <!-- footer section code starts here   -->

      <section class="footer-wrapper" id="footer">
        <div class="wrapper">
          <div class="footer">
            <div class="footer__content">
              <div class="footer__logo">
                <img
                  src="./assets/images/logo.png"
                  width="100px"
                  alt="foot-logo"
                />
              </div>

              <div class="footer__social">
                <div class="footer__social-link">
                  <i class="fa-brands fa-github icons"></i>
                </div>
                <div class="footer__social-link">
                  <i class="fa-brands fa-linkedin-in icons"></i>
                </div>

                <div class="footer__social-link">
                  <i class="fa-brands fa-twitter icons"></i>
                </div>
              </div>
            </div>

            <hr />

            <div class="footer__copy">
              <p>All rights reserved | Copyright © 2023 Manish Kumar</p>
            </div>
          </div>
        </div>
      </section>
    </main>
  </body>
------------------
@font-face {
  font-family: "Dennis Sans";
  src: url(../assets/fonts/NeueMontreal-Regular.otf) format("opentype");
  font-weight: 450;
  font-style: normal;
  font-display: auto;
}

:root {
  --color-black: #1c1d20;
  --color-black-dark: #141517;
  --color-gray: #999d9e;
  --color-lightgray: #e9eaeb;
  --color-blue: #455ce9;
  --color-white: #fff;

  --color-text: #1c1d20;
  --color-text-light: #fff;
  --color-border: #545557;
}

* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

html,
body {
  width: 100%;
  position: relative;
  -webkit-font-smoothing: antialiased;
}

body {
  width: 100%;
  font-family: "Dennis Sans", sans-serif;
  color: var(--color-text);
  line-height: 1.6;
  font-weight: 450;
  font-style: normal;
  font-size: 16px;
  font-size: clamp(16px, 1.2vw, 19px);
  -webkit-font-smoothing: antialiased;
}

.wrapper {
  max-width: min(1110px, calc(100% - 32px));
  margin-inline: auto;
}
.grid {
  display: grid;
  grid-template-columns: auto;
  row-gap: 7rem;
}
a {
  text-decoration: none;
  color: inherit;
  font-style: inherit;
}
li {
  list-style: none;
}

.btn {
  display: flex;
  align-items: center;
  justify-content: center;

  width: clamp(9em, 12vw, 11em);
  height: clamp(9em, 12vw, 11em);
  border-radius: 50%;
  border: 0;

  color: #fff;
  background-color: black;
}

h2 {
  font-family: "Dennis Sans", sans-serif;
  font-weight: 450;
  font-style: normal;
  font-size: clamp(1.55em, 2.3vw, 2.5em);
  line-height: 1.45;
}
.line {
  width: 100%;
  // color: var(--color-border);
  height: 2px;
  background-color: var(--color-border);
}

input,
button,
textarea {
  display: inline-block;
}

header {
  display: inline-block;
  margin-inline: auto;
}

//media queries for responsive
@media (max-width: 912px) {
}
@media (max-width: 768px) {
}
@media (max-width: 480px) {
}

//mobile
@media (max-width: 567px) {
  body {
    background-color: green;
  }
}
//tablets
@media (min-width: 568px) and (max-width: 767px) {
  body {
    background-color: #807500;
  }
}
// ipad
@media (min-width: 768px) and (max-width: 912px) {
  body {
    // background-color: #000480;
  }
}
.auto-grid {
  display: grid;
  gap: 1rem;
  // grid-template-columns: repeat(auto-fit, minmax(25rem, 1fr));
  grid-template-columns: repeat(auto-fit, minmax(min(22rem, 100%), 1fr));
}
for style.scss-----
@use "components";
@use "global";

------
.about-wrapper {
  width: 100%;
  // background-color: #bbedbb;
}

.about {
  display: flex;
  padding-inline-start: 8vw;
  column-gap: 8rem;

  &__left {
    flex: 2;
  }
  &__right {
    flex: 1;
    display: flex;
    flex-direction: column;
    align-items: center;
    padding-inline-start: 1rem;
    p {
      font-family: "Dennis Sans", sans-serif;
      // font-weight: 450;
      // font-style: normal;
      color: var(--text);
      font-size: 1em;
      line-height: 1.66;
      margin-bottom: 5rem;

      // padding-inline: 2rem;
    }
  }
  &__btn {
    margin-bottom: 2rem;
  }
}

@media (max-width: 820px) {
  .about {
    column-gap: 3rem;
    padding-inline-start: 0;

    &__right {
      padding-inline-start: 0;
    }
  }
}

@media (max-width: 768px) {
  .about {
    flex-direction: column;

    &__left {
      flex: 1;
    }
    &__right {
      flex: 1;

      margin-top: 3rem;

      p {
        text-align: center;
      }
    }

    &__btn {
      display: flex;
      align-items: center;
      justify-content: center;
    }
  }
}
---------
.contact-wrapper {
  width: 100%;
  padding-bottom: 10rem;
  background-color: #e0e1df;
}

.contact {
  display: flex;
  flex-direction: column;
  row-gap: 1.5rem;

  &__info {
    line-height: 1.2;

    h1 {
      font-size: 10vw;
      text-align: center;
      letter-spacing: 0.6rem;
    }

    p {
      text-align: center;
      font-size: 1.5rem;
    }
  }

  &__input {
    width: 60%;
    margin-top: 3rem;
    margin-inline: auto;

    &-form {
      display: flex;
      position: relative;
      flex-direction: column;
      row-gap: 1rem;

      &-field {
        display: flex;
        position: relative;
        flex-direction: column;
        border-bottom: 1px solid var(--color-black);

        input {
          background: transparent;
          // display: inline-block;
          outline: none;
          border: none;
          padding: 1rem;
          font-size: 1.2rem;
        }
        textarea {
          // display: inline-block;
          background: transparent;
          outline: none;
          border: none;
          padding: 1rem;
          font-size: 1.6rem;
          resize: none;
        }
      }

      &-btn {
        position: absolute;
        bottom: -5rem;
        right: 2rem;
      }
    }
  }
}

* {
  // outline: 1px solid red;
}
------------
.footer-wrapper {
  width: 100%;
  background-color: #e0e1df;
}
.footer {
  width: 100%;
  display: flex;
  flex-direction: column;

  gap: 3rem;

  &__content {
    display: flex;
    flex-wrap: wrap;
    justify-content: space-between;
  }

  &__social {
    display: flex;
    column-gap: 1rem;
    align-items: center;

    &-link {
      font-size: 1.5rem;
      color: #7f7e7e;
    }
    :hover {
      color: #3a3939;
    }
  }

  &__copy {
    text-align: center;
    margin-block-end: 3rem;
    letter-spacing: 0.5px;
  }
}
-----------------
.hero-wrapper {
  width: 100%;
  background-color: #a3c3f4;
}

.hero {
  height: calc(100vh - 50px);
}
-----------------------
@forward "navbar";
@forward "hero";
@forward "about";
@forward "skills";
@forward "work";
@forward "contact";
@forward "footer";
-------------------------
.header {
  width: 100%;
  background-color: #d1b6eb;
}

nav {
  width: 100%;

  max-width: 1232px;
  margin-inline: auto;
  padding-inline: 2rem;
}

.navbar {
  height: 50px;

  display: flex;
  flex-wrap: wrap;
  align-items: center;
  justify-content: space-between;

  &__logo {
  }
  &__link {
    display: flex;
    gap: 1rem;
  }
  &__menu {
    display: flex;
    align-items: center;
  }

  @media (max-width: 768px) {
    &__link {
      // display: none;
      flex-wrap: wrap;
    }
    &__menu {
      display: none;
    }
  }
}
----------------------------
.skills-wrapper {
  width: 100%;
  // background-color: #a4eddc;
}

.skill {
  // height: 100vh;

  display: flex;
  flex-direction: column;
  gap: 5rem;

  &__top {
    display: flex;
    gap: 5rem;
    line-height: 1;

    h1 {
      flex: 1;
      font-size: 15vw;
    }

    &-abb {
      flex: 1;
      display: flex;
      justify-content: space-around;
      margin-bottom: 1rem;

      p {
        align-self: flex-end;
        font-size: 1em;
        line-height: 1.1;
        // letter-spacing: 0.01em;
      }
    }
  }

  &__bottom {
    width: 60%;
    margin-inline: auto;
    ul {
      display: flex;
      flex-wrap: wrap;
      margin-inline: auto;

      li {
        padding: 1rem;
      }
    }
  }
}

@media (max-width: 820px) {
  .skill {
    &__top {
      flex-direction: column;
      row-gap: 2rem;
    }

    &__bottom {
      width: 80%;
    }
  }
}
@media (max-width: 540px) {
  .skill {
    &__bottom {
      width: 100%;
      margin-inline: 0;
    }
  }
}
-----------------------
.project-wrapper {
  width: 100%;
  background-color: #cdf1cd;
}

.project {
  height: 50vh;
}








**********************************************************
