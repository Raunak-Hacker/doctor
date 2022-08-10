<template>
  <section>
    <div class="container">
      <div class="namerow row1">
        <div class="name">
          <h1>MEET THE DOCTER</h1>
          <p>Home > About Us</p>
        </div>
        <div class="image">
          <img src="doc.png" alt="docimg" />
        </div>
      </div>

      <div class="row2">
        <div class="docname">
          <h1>Dr. Hema Datar</h1>
        </div>
        <div class="adoc">ABOUT DOCTOR</div>
      </div>
      <div class="row3">
        <div class="info">
          <h1>Summary</h1>
          <p>
            <br />
            Dr. Hema completed her Medical Graduation (MBBS) from D Y Patil Medical
            College, Kolhapur, Maharashtra. After this, she obtained a Diploma In
            Orthopaedic Surgery from CPS Mumbai, Hardikar Hospital Pune. She did
            Fellowship Developmental Orthopaedics And Closed Chain Biomechanics in the
            USA, Clinical And Surgical Fellowship In Hand And Orthoplastic Surgery With
            Dr. Pankaj Jindal in Pune, and Fellow Interventional Pain Management from
            Aescolap Academy, Austria.
            <br />
          </p>
          <br />

          <h1>Education</h1>
          <p>
            <br />
            Apart from her vast educational background, she has worked as a Clinical
            Assistant in Pediatric Orthopedics since 2004. She has also gained her
            experience in Closed chain biomechanics and cerebral palsy rehabilitation.
            Since 2010. Dr. Hema has been practicing Interventional Pain Management.<br />
          </p>
            <br />

          <div class="underlinediv">
            <ul>
              <li>2004: &nbsp; Medical Graduation (MBBS)</li>
            </ul>
          </div>
          <div class="underlinediv">
            <ul>
              <li>2010: &nbsp; Stated practationing interventional pain management</li>
            </ul>
          </div>
          <div class="underlinediv">
            <ul>
              <li>2015: &nbsp; MWIA Kolkata</li>
            </ul>
          </div>
          <div class="underlinediv">
            <ul>
              <li>2016: &nbsp; ICRA Kolkata</li>
            </ul>
          </div>
          <div class="underlinediv">
            <ul>
              <li>2017: &nbsp; ICGO Prague</li>
            </ul>
          </div>
          <div class="underlinediv" style="border:none">
            <ul>
              <li>2022: &nbsp; ISSPCON</li>
            </ul>
          </div>
          <br />

          <h1>Experience</h1>
          <p>
            <br />
            Over the years she has presented at various medical conventions and
            conferences like MWIA Kolkata 2015, ICRA Kolkata 2016, ICGO Prague 2017, and
            ISSPCON 2020 & 2022. Dr. Hema has been a faculty with the Symposium on Low
            Back Pain & Sciatica and International Operative, Cadaveric Workshop, &
            Training Course on Transforaminal Endoscopic Spine Surgery, Minimally Invasive
            Intradiscal Procedures & Interventional Spinal Pain Management.
          </p>

          <br />
          <div class="underlinediv">
            <ul>
              <li>Impressive educational background and vast experience</li>
            </ul>
          </div>
          <div class="underlinediv">
            <ul>
              <li>Specialised experience in interventional pain management procedures</li>
            </ul>
          </div>
          <div class="underlinediv">
            <ul>
              <li>Expertise in oercutaneous minimaly </li>
            </ul>
          </div>
          <div class="underlinediv" style="border:none">
            <ul>
              <li>2022: &nbsp; ISSPCON</li>
            </ul>
          </div>
          <br />
        </div>
        <div class="mapside">
          <h1>Location</h1>
          <br />

          <iframe src="https://www.google.com/maps/embed?pb=!1m14!1m8!1m3!1d15275.748604751416!2d74.6442643!3d16.8294737!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x0%3A0xea37789c80dde4ca!2sDr%20Hema%20Datar!5e0!3m2!1sen!2sin!4v1660046230782!5m2!1sen!2sin" width="100%" height="100%" style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  data() {
    return {
      images: ["edited"],
    };
  },
};
</script>

<style>
@import url("https://fonts.googleapis.com/css2?family=Cookie&family=Montserrat&family=Work+Sans:wght@300;400;500;600;700&display=swap");
:root {
  --orange: #d54655;
  --grey: rgba(204, 204, 204, 0.366);
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
<style>
.name {
  display: flex;
  flex-direction: column;
  justify-content: center;

  align-items: flex-start;
}
.image {
  width: 20vw;
  height: 20vw;
}

.image img {
  width: 100%;
  height: 100%;
}

.namerow {
  display: flex;
  justify-content: space-between;
  align-items: center;

  width: 100%;
  max-width: 100%;
  padding-right: 5rem;
  padding-left: 5rem;
}
.row1 {
  background-color: #292b2b;
  color: white;
}
.row2 {
  display: flex;
  justify-content: space-between;
  height: 8rem;
  width: 100%;
  max-width: 100%;
  padding-right: 5rem;
  padding-left: 5rem;
}

.docname {
  border-left: 2px solid #696f6f;
  padding-left: 2rem;
  padding-top: 3rem;
}
.adoc {
  background-color: #d44755;
  width: 20vw;
  height: 8rem;
  padding-top: 3rem;
  text-align: center;
}
.row3 {
  display: flex;
  justify-content: space-between;
  align-items: center;
  height: 220vh;
  width: 100%;
  max-width: 100%;
  padding-right: 5rem;
  padding-left: 5rem;
}
.info {
  height: 100%;
  padding-top: 2rem;
  width: 60vw;
  text-align: justify;
}
.mapside {
  height: 100%;
  width: 20vw;
  padding-top: 2rem;
  padding-left: 1rem;
  padding-right: 1rem;
  background-color: #e7e7e7;
}
.mapside iframe {
  width: 100%;
  height: 17rem;
}
.underlinediv{
    border-bottom: 1px solid #696f6f;
    padding-bottom: .5rem;
    padding-top: .5rem;
}
.underlinediv li {
  list-style: disc;
  list-style-position: inside;
}
</style>
