  <template>
  <section  ref="aboutMeSection" class="first">
    <div class="main">
      <div class="mainh1">
        <h1>HEY, I'M FRONTEND DEVELOPER</h1>
      </div>
      <div class="mainp">
        <p>
          A Frontend focused Web Developer building the Frontend of Websites and
          Web Application that leads to the success of the overall product
        </p>
      </div>
    </div>
    <div class="main-information">

<h1>Skills</h1>
      <div class="inf2">
        
        <div class="card">
              
            <img src="../assets/javascript.jpg" alt="Mountains" />
           
          
          <p>
             Portfolio Website: Created a responsive portfolio using HTML,
            CSS, and JavaScript.
          </p>
          <div class="cr"></div>
        </div>
        <div class="card">
  
            <img src="../assets/logo.png" alt="Mountains" />
          <p>
           Vue.js SPA: Developed a single-page application using Vue.js to
            manage data.
          </p>
        </div>
      </div>
    </div>



  </section>
</template>

  <style scoped>
:root {
  font-size: 20px;
}

*,
*:before,
*:after {
  box-sizing: border-box;
}

p {
  margin: 0;
}

p:not(:last-child) {
  margin-bottom: 1.5em;
}

body {
  font: 1em/1.618 Inter, sans-serif;

  display: flex;
  align-items: center;
  justify-content: center;

  min-height: 100vh;
  padding: 30px;
  margin: 0;

  color: #224;
  background: url(https://source.unsplash.com/E8Ufcyxz514/2400x1823) center /
    cover no-repeat fixed;
}

.card {
  max-width: 300px;
  min-height: 430px;
  display: flex;
  flex-direction: column;
  justify-content: space-between;

  max-width: 500px;
  height: 300px;
  padding: 35px;

  border: 1px solid rgba(255, 255, 255, 0.25);
  border-radius: 20px;
  background-color: rgba(255, 255, 255, 0.45);
  box-shadow: 0 0 10px 1px rgba(0, 0, 0, 0.25);

  backdrop-filter: blur(15px);
}

.card-footer {
  font-size: 0.65em;
  color: #446;
}
.inf2 h1{
text-align: center;
}
.inf2 {
  color: rgb(255, 255, 255);
  font-family: "Dosis", sans-serif;
  font-optical-sizing: auto;
  font-weight: 700;
  font-style: normal;
  font-size: 30px;
  
  /* padding-top: -40px; */
  display: flex;
}

.cr {
  display: flex;
}
.card {
  justify-content: center; /* Distribute space evenly between elements */
  /* margin-top: 100px; Optional: Add margin for spacing */
  width: 1000px;
}
 img {
  margin-bottom: 30px;
  width: 200px; /* Set the desired width */
  height: auto; /* Maintain aspect ratio */
  border-radius: 8px; /* Optional: Add border-radius for rounded corners */
}
figure {
  display: grid;
  border-radius: 1rem;
  overflow: hidden;
  cursor: pointer;
}
figure > * {
  grid-area: 1/1;
  transition: 0.4s;
}
figure figcaption {
  display: grid;
  align-items: end;
  font-family: sans-serif;
  font-size: 2.3rem;
  font-weight: bold;
  color: #0000;
  padding: 0.75rem;
  background: var(--c, rgba(0, 0, 0, 0.432));
  clip-path: inset(0 var(--_i, 100%) 0 0);
  -webkit-mask: linear-gradient(#000 0 0), linear-gradient(#000 0 0);
  -webkit-mask-composite: xor;
  -webkit-mask-clip: text, padding-box;
  margin: -1px;
}
figure:hover figcaption {
  --_i: 0%;
}
figure:hover img {
  transform: scale(1.2);
}
@supports not (-webkit-mask-clip: text) {
  figure figcaption {
    -webkit-mask: none;
    color: #fff;
  }
}

body {
  margin: 0;
  padding: 0;
  /* min-height: 400vh; */
  /* max-height: 1000vh;  */
  display: flex;
  flex-direction: column;
}
.main-information h1{

  color: rgb(255, 255, 255);
  font-family: "Dosis", sans-serif;
  font-optical-sizing: auto;
  font-weight: 700;
  font-style: normal;
  font-size: 50px;
  padding-top: 150px;
  display: flex;
 justify-content: center;
}
.main-information {
  padding-top: 250px;
  
}
.first .main-information ul li {
  font-family: "Dosis", sans-serif;
  font-weight: 700;
  font-size: 30px;
  font-style: normal;
  color: white;
  list-style: none;
  display: flex;
  /* align-items: center;   */
  padding-left: 50px;
  text-align: start;
}

.img-place img {
  /* margin-top: 100px;
        margin-left: 100px; */
  width: 240px;
  height: 240px;
}
.skills {
  width: 1400px;
  margin-right: 500px;
  /* margin-top: 100px; */
}
.skills h1 {
  margin-left: 400px;
  color: rgb(255, 255, 255);
  font-family: "Dosis", sans-serif;
  font-optical-sizing: auto;
  font-weight: <weight>;
  font-style: normal;
  font-size: 50px;
}
.first {
  /* display: flex; */
  justify-content: center;
  align-items: center;
  height: 100%;
  background-size: 1870px 1170px;
}
.mainp {
  color: white;
  /* margin-right: 200px; */
  padding-top: 20px;
  text-align: center;
  font-family: "Dosis", sans-serif;
  font-optical-sizing: auto;
  font-weight: <weight>;
  font-style: normal;
  font-size: 30px;

  width: 900px;
}
.main {
  padding-top: 200px;
  justify-content: center;
  align-items: center;
}
.mainh1 {
  margin-left: 340px;
  color: white;
  font-family: "Roboto Condensed", sans-serif;
  font-optical-sizing: auto;
  font-weight: <weight>;
  font-style: normal;
  font-size: 60px;
  
}
</style>
