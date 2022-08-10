<template>
  <section class="home">
    <link href="https://unpkg.com/boxicons@2.1.1/css/boxicons.min.css" rel="stylesheet" />
    <the-header />
    <div class="hero">
      <img src="hero1.jpg" alt="" />
    </div>
    <section class="second">
      <div class="staff">
        <div class="top">
          <div class="top-box info">
            <p>Miraj Pain <br />Management</p>

            <div class="det" style="margin-top: 15%">
              <small>Excellent Support Staff</small>
            </div>
            <div class="det">
              <small>Experienced Doctors</small>
            </div>
            <div class="det" style="height: 20%">
              <small>Specialized Experienced for every treatment</small>
            </div>
            <div class="det" style="border: 0">
              <small>Best results</small>
            </div>
          </div>
          <div class="top-box">
            <img src="hemaFull.png" alt="" />
          </div>
          <div class="top-box">
            <div class="search">
              <small>Accessing</small>
              <h3>Our Service</h3>
              <div class="bar">
                <input
                  type="text"
                  v-model="filter"
                  @keyup="changeIcon"
                  @focusin="changeIcon"
                  @focusout="changeIcon"
                />
                <i class="bx bx-x" v-if="search" />
                <i class="bx bx-search" v-else />
              </div>
            </div>
            <div class="bar">
              <iframe
                src="https://www.youtube.com/embed/K4TOrB7at0Y?controls=0"
                title="YouTube video player"
                frameborder="0"
                allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
                allowfullscreen
                height="170"
              ></iframe>
            </div>
          </div>
          <div class="top-box stories">
            <small>Our</small>
            <h3>Success Stories</h3>
            <br />
            <div class="story">
              <img src="doc.png" alt="" />
              <div class="dets">
                <p>Spine Pain</p>
                <small style="font-weight: 400">Read More</small>
              </div>
            </div>
            <div class="story">
              <img src="doc.png" alt="" />
              <div class="dets">
                <p>Pain Management</p>
                <small style="font-weight: 400">Read More</small>
              </div>
            </div>
          </div>
        </div>
        <div class="bot">
          <div class="bot-box info">
            <div class="call">
              <!-- <img src="" alt="ph"> -->
              <i class="bx bx-phone" />
              <p>
                Want to get in <br />
                touch with us?
              </p>
            </div>
            <div class="head">
              <p>
                You can reach us <br />
                in following ways
              </p>
            </div>
            <div class="det">
              <small>Email us on: drhemadatar@gmail.com</small>
            </div>
            <div class="det">
              <small>Phone Number: +91 98900 98900</small>
            </div>
            <div class="det">
              <small>Find us on maps</small>
            </div>
            <div class="det" style="border: 0">
              <small>Look for Doctor's timetable</small>
            </div>
          </div>
          <div class="bot-box info">
            <div class="head" style="height: 20%">
              <p>
                Find our <br />
                Departments Here
              </p>
            </div>

            <div class="det">
              <small>Interventional Pain Management</small>
            </div>
            <div class="det">
              <small>Musculoskeletal Pain</small>
            </div>
            <div class="det">
              <small>Spinal Pain</small>
            </div>
            <div class="det">
              <small>Low Back Pain & Sciatica</small>
            </div>
            <div class="det">
              <small>Cancer Pain</small>
            </div>
            <div class="det">
              <small>Non - Cancer Pain</small>
            </div>
            <div class="det" style="border: 0">
              <small>BMD & Osetoporosis Treatment</small>
            </div>
          </div>
          <div class="bot-box consult info">
            <div class="head" style="height: 20%">
              <p>
                Consult our <br />
                Doctor's For
              </p>
            </div>
            <div class="det">
              <small>Musculoskeletal System</small>
            </div>
            <div class="det">
              <small>Spine</small>
            </div>
            <div class="det">
              <small>Post Surgical Pain Syndrome</small>
            </div>
            <div class="det">
              <small>Others</small>
            </div>
            <div class="call" style="">
              <!-- <img src="" alt="ph"> -->
              <i class="bx bx-phone" />
              <p>
                Book Your <br />
                Consultstion Now
              </p>
            </div>
          </div>
        </div>
      </div>
      <div class="poster">
        <img src="doctor.jpg" alt="" />
        <div class="post-info">
          <p>LEARN MORE ABOUT OUR WORLD-CLASS FACILITIES</p>
          <br />
          <br />
          <small>Discover More</small>
        </div>
        <div class="post-head">
          <p>TAKE A TOUR</p>
        </div>
      </div>
      <div class="service">
        <div class="links">
          <div class="link">
            <small>Interventional Pain Management</small>
          </div>
          <div class="link">
            <small>Musculoskeletal Pain</small>
          </div>
          <div class="link">
            <small>Spinal Pain</small>
          </div>
          <div class="link">
            <small>Low Back Pain & Sciatica</small>
          </div>
          <div class="link">
            <small>Cancer Pain</small>
          </div>
          <div class="link">
            <small>Non - Cancer Pain</small>
          </div>
          <div class="link">
            <small>BMD & Osetoporosis Treatment</small>
          </div>
        </div>
        <div class="service-info">
          <h3>Service Overview</h3>
          <p>
            Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor
            incididunt ut labore et dolore magna aliqua. Scelerisque purus semper eget
            duis at tellus at urna. Erat imperdiet sed euismod nisi. Turpis egestas
            maecenas pharetra convallis posuere morbi. Amet facilisis magna etiam tempor
            orci eu lobortis. Neque sodales ut etiam sit. Vitae purus faucibus ornare
            suspendisse sed nisi lacus sed viverra. Odio aenean sed adipiscing diam. Eu mi
            bibendum neque egestas congue quisque egestas diam in. Augue eget arcu dictum
            varius duis. Id aliquet risus feugiat in ante.
          </p>
          <div class="flex-box">
            <img src="pain.png" alt="" />
            <div class="time">sds</div>
          </div>
        </div>
      </div>
      <div style="height: 100vh"></div>
    </section>
  </section>
</template>

<script>
import TheHeader from "../components/layout/TheHeader.vue";
export default {
  components: { TheHeader },
  data() {
    return {
      filter: "",
      search: false,
    };
  },
  methods: {
    changeIcon() {
      if (this.filter.length > 0) {
        this.search = true;
      } else {
        this.search = false;
      }
    },
  },
};
</script>

<style>
@import url("https://fonts.googleapis.com/css2?family=Cookie&family=Montserrat&family=Work+Sans:wght@300;400;500;600;700&display=swap");
:root {
  --red: #d54655;
  --grey: rgba(204, 204, 204, 0.366);
  --dark-red: #cb4450;
}
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  list-style: none;
  text-decoration: none;
  font-family: "Work Sans", sans-serif;
}
</style>

<style scoped>
.home {
  width: 100%;
}
.hero {
  width: 100%;
  height: 94vh;
}
.hero img {
  width: 100%;
  height: 100%;
}
.second {
  width: 100%;
  padding: 0 12.5%;
}
.staff {
  border: 1px solid var(--grey);
  width: 100%;
  height: 100%;
}
.top {
  width: 100%;
  height: 45vh;
  border-bottom: 1px solid var(--grey);
  display: flex;
}

.top-box {
  width: calc(100% / 4);
  height: 100%;
  font-weight: 500;
}
.top-box img {
  width: 100%;
  height: 100%;
}
.top .info {
  padding: 2.5%;
  font-size: 1.12rem;
}
.info .det {
  height: 16.5%;
  display: flex;
  align-items: center;
  border-bottom: 1px solid black;
}
.info .det small {
  font-size: 0.9rem;
}
.top .search {
  height: 49.5%;
  width: 100%;
  padding: 12% 9.8%;
  background-color: var(--red);
  color: white;
}
.top-box h3 {
  font-weight: 500;
}
.top-box .stories,
.top-box .search small {
  font-size: 0.7rem;
  font-weight: 500;
}
.search .bar {
  height: 40%;
  width: 100%;
  border-bottom: 1px solid white;
  display: flex;
  align-items: center;
}
.search .bar input {
  width: 80%;
  height: 100%;
  border: 0;
  outline: 0;
  text-indent: 1rem;
  background-color: transparent;
  color: white;
}
.stories {
  color: white;
  background-color: transparent;
  padding: 3%;
  background-image: linear-gradient(251deg, var(--dark-red) 30%, var(--red) 15%);
}
.stories img {
  width: 30%;
  height: 100%;
  object-fit: cover;
  border-radius: 50%;
  margin-right: 4%;
}
.story {
  width: 100%;
  height: 22%;
  display: flex;
  align-items: center;
  margin-bottom: 8%;
}
.story .dets {
  line-height: 1.35rem;
}
.bot {
  width: 100%;
  height: 71vh;
  border-bottom: 1px solid var(--grey);
  display: flex;
}
.bot-box {
  width: calc(100% / 3);
  height: 100%;
  font-weight: 500;
  border-right: 1px solid var(--grey);
}
.bot .info {
  padding: 2.5%;
}

.bot .info {
  padding: 2.5%;
  font-size: 1.12rem;
}
.bot .info .det {
  height: 10.5%;
  display: flex;
  align-items: center;
  border-bottom: 1px solid var(--grey);
}
.bot .info .det small {
  font-size: 0.9rem;
}
.bot .call {
  height: 20%;
  width: 100%;
  background-image: linear-gradient(228deg, var(--dark-red) 22%, var(--red) 15%);
  display: flex;
  align-items: center;
  color: white;
  padding-left: 4%;
}
.call i {
  font-size: 3.5rem;
  font-weight: 1;
  margin-right: 8.5%;
}
.call p {
  width: 80%;
}
.bot .head {
  height: 30%;
  display: flex;
  align-items: center;
}

.bot .consult {
  background-color: #e7e6e6;
}
.consult .call {
  margin-top: 15%;
  background-image: linear-gradient(228deg, #414040 22%, #292b2b 15%);
}

.poster {
  margin: 7vh 0;
  width: 100%;
  height: 53.5vh;
  position: relative;
}
.poster img {
  width: 100%;
  height: 100%;
  object-fit: cover;
  object-position: center;
}
.post-info {
  position: absolute;
  top: 0;
  left: 0;
  width: 22%;
  height: 100%;
  background-color: rgba(0, 0, 0, 0.5);
  display: flex;
  flex-direction: column;
  justify-content: center;
  padding: 3.5%;
  color: white;
}
.poster p {
  font-size: 1.12rem;
  font-weight: 500;
  letter-spacing: 2px;
  color: white;
}
.post-head {
  position: absolute;
  background-color: rgba(0, 0, 0, 0.5);
  top: 0;
  right: 0;
  width: 26%;
  height: 20%;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
}
.service {
  width: 100%;
  height: 79vh;
  display: flex;
  border: 1px solid var(--grey);
  border: 1px solid black;
  padding: 1.5% 3%;
  padding-bottom: 4.3%;
}

.service .links {
  width: 26%;
  height: 100%;
  display: flex;
  flex-direction: column;
  padding-right: 4%;
}
.links .link {
  border-bottom: 1px solid black;
  height: calc(100% / 7);
  display: flex;
  flex-direction: column;
  justify-content: center;
}
.service-info {
  padding-top: 2.5%;
  width: 70%;
  height: 100%;
  display: flex;
  flex-direction: column;
}
.service-info h3 {
  font-size: 1rem;
  font-weight: 500;
  color: black;
}
.service-info p {
  margin: 5% 0;
  font-size: 0.9rem;
  color: gray;
}
.services .time {
  width: 100%;
  height: 100%;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  border: 1px solid black;
  background: black;
}
.flex-box {
  height: 61%;
  width: 100%;
  display: flex;
  justify-content: space-between;
}
.flex-box img {
  width: 48%;
  height: 100%;
  object-fit: cover;
}
.time{
  width: 48%;
  height: 100%;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  border: 1px solid black;
  background: black;
}
</style>
