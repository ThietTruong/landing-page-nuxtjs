<template>
  <section>
    <div id="about-us">
      <div class="container">
        <div class="about-us--content">
          <div class="row g-xl-40">
            <div class="col-md-6">
              <div class="about-us--header">
                <h2 class="about-us--title">About Us</h2>
                <div class="about-us--excerpt">
                  Browse our selection of free online games and have a great
                  time without leaving the site! Our Kids Games option also
                  includes game reviews, extensive game cheats and walkthroughs,
                  and much more. We have exclusive free downloads, videos, and
                  articles as well. Etech reviews the most popular kids games
                  from all the most popular video gaming platforms, so you don’t
                  need to search around for fun anywhere else on the Internet.
                  Explore a whole new world of gaming on Etech.
                </div>
              </div>
              <ul class="about-us--list">
                <li class="col-6 col-md-12">
                  <p class="-number">600<span>M</span>+</p>
                  <p class="-text">Users</p>
                </li>
                <li class="col-6 col-md-12">
                  <p class="-number">135+</p>
                  <p class="-text">Games</p>
                </li>
              </ul>
            </div>
            <div class="col-md-6">
              <div class="about-us--box">
                <ul class="about-us--box__list">
                  <li>
                    <div class="about-us--box__thumb">
                      <img src="../static/icon-hour.svg" alt="" />
                    </div>
                    <div class="about-us--box__meta">
                      <h3 class="about-us--box__title">24 - Hour</h3>
                      <p>
                        24/7 access ensures operators' businesses runs smoothly
                        all year long.
                      </p>
                    </div>
                  </li>
                  <li>
                    <div class="about-us--box__thumb">
                      <img src="../static/icon-design.svg" alt="" />
                    </div>
                    <div class="about-us--box__meta">
                      <h3 class="about-us--box__title">Design</h3>
                      <p>
                        Combining imaginative universes, play dynamics, and
                        unprecedented gameplay, our games transcend the
                        boundaries of the virtual world by weaving innovative
                        gameplay.
                      </p>
                    </div>
                  </li>
                  <li>
                    <div class="about-us--box__thumb">
                      <img src="../static/icon-team.svg" alt="" />
                    </div>
                    <div class="about-us--box__meta">
                      <h3 class="about-us--box__title">Team</h3>
                      <p>
                        Etech is an award-winning, international studio of
                        designers, artists, animators and producers that create
                        content for the biggest names in film and video games.
                      </p>
                    </div>
                  </li>
                </ul>
              </div>
            </div>
          </div>
        </div>
        <div class="about-us--pattern">
          <div class="about-us--pattern__witch"></div>
          <div class="about-us--pattern__map"></div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {};
</script>

<style>
#about-us {
  position: relative;
  padding: 120px 0 0;
}
/* about us header */
.about-us--header {
  visibility: visible;
  animation-name: fadeInLeft;
}
.about-us--title {
  font-family: Playfair Display;
  font-weight: 900;
  font-size: 60px;
  line-height: 60px;
  letter-spacing: 3.6px;
  color: #000;
  margin-bottom: 0;
}
.about-us--excerpt {
  max-width: 860px;
  margin: 24px auto 0;
  color: #757575;
  font-size: 14px;
  font-family: "Montserrat", sans-serif;
  font-weight: 300;
}

.about-us--list {
  visibility: visible;
  animation-name: fadeInUp;
  padding-top: 20px;
  font-weight: 700;
  font-size: 24px;
  line-height: 30px;
  color: #000;
  list-style: none;
}
.about-us--list li:not(:last-child) {
  margin-bottom: 40px;
}
.about-us--list .-number {
  font-size: 80px;
  line-height: 98px;
  color: #079bee;
  margin-bottom: 4px;
}
.about-us--box__list {
  list-style: none;
  padding-left: 0px;
}
.about-us--box__list li {
  display: flex;
}
.about-us--box__list li:not(:last-child) {
  margin-bottom: 40px;
}

.about-us--box {
  padding: 110px 75px;
  background: #eee;
  margin-bottom: 70px;
}
.about-us--box__thumb {
  flex: 0 0 auto;
  width: 50px;
  margin-right: 24px;
}
.about-us--box__thumb img {
  border-style: none;
  max-width: 100%;
  height: auto;
  max-height: 100%;
}
.about-us--box__title {
  font-weight: 700;
  font-size: 24px;
  line-height: 30px;
  color: #000;
  margin-bottom: 8px;
}
.about-us--box__meta {
  max-width: 860px;
  margin: 24px auto 0;
  color: #757575;
  font-size: 14px;
  font-family: "Montserrat", sans-serif;
  font-weight: 300;
}

@media screen and (max-width: 1199px) {
  .about-us--box {
    padding: 60px 40px;
  }
}
@media screen and (max-width: 911px) {
  .about-us--box {
    margin-top: 40px 16px;
  }
}
/* pattern*/
.about-us--pattern {
  position: relative;
  margin-top: 200px;
}
/*  */
.about-us--pattern__witch {
  position: absolute;
  bottom: 76%;
  left: 0;
  right: 0;
  width: 41%;
  height: 88%;
  min-width: 300px;
  min-height: 240px;
  margin: 0 auto;
  background-image: url(../static/about-partern-witch.png);
  background-repeat: no-repeat;
  background-size: contain;
  z-index: 1;
  transition: all 0.5s;
  animation: lightAnimation 2s ease-in-out infinite,
    Mousex 3s ease-in-out infinite;
}
.about-us--pattern__map {
  position: relative;
  display: block;
  margin-top: 26%;
  padding-top: 37%;
  background-image: url(../static/about-partern-pin-map.png);
  background-repeat: no-repeat;
  background-size: contain;
  transition: all 0.8s;
  animation: Mousex 4s ease-in-out infinite;
}
@keyframes lightAnimation {
  0% {
    filter: brightness(1);
  }
  50% {
    filter: brightness(1.3);
  }
  100% {
    filter: brightness(1);
  }
}
@keyframes Mousex {
  0% {
    -webkit-transform: translate(0);
  }
  65% {
    -webkit-transform: translateY(10px);
  }
  100% {
    -webkit-transform: translate(0);
  }
}
</style>
