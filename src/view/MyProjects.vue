
<template >
  <div class="slider-wrapper" style="">
      <h1>Projects</h1>
    <section id="slider">
      <input type="radio" name="slider" id="s1" />
      <input type="radio" name="slider" id="s2" />
      <input type="radio" name="slider" id="s3" checked />
      <input type="radio" name="slider" id="s4" />
      <input type="radio" name="slider" id="s5" />
      <label for="s1" id="slide1"></label>
      <label for="s2" id="slide2"></label>
      <label for="s3" id="slide3"></label>
      <label for="s4" id="slide4"></label>
      <label for="s5" id="slide5"></label>
    </section>
  </div>
</template>

<style >
.slider-wrapper h1{
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
.slider-wrapper {
  padding-top: 100px;
    overflow: hidden;
}

body {
  padding: 20px;

  
  user-select: none;
}

[type="radio"] {
  display: none;
}

#slider {
  padding-top: 50px;
  height: 35vw;
  position: relative;
  perspective: 1000px;
  transform-style: preserve-3d;
}

#slider label {
  margin: auto;
  width: 60%;
  height: 100%;
  border-radius: 4px;
  position: absolute;
  left: 0;
  right: 0;
  cursor: pointer;
  transition: transform 0.4s ease;
}

#s1:checked ~ #slide4,
#s2:checked ~ #slide5,
#s3:checked ~ #slide1,
#s4:checked ~ #slide2,
#s5:checked ~ #slide3 {
  box-shadow: 0 1px 4px 0 rgba(0, 0, 0, 0.37);
  transform: translate3d(-30%, 0, -200px);
}

#s1:checked ~ #slide5,
#s2:checked ~ #slide1,
#s3:checked ~ #slide2,
#s4:checked ~ #slide3,
#s5:checked ~ #slide4 {
  box-shadow: 0 6px 10px 0 rgba(0, 0, 0, 0.3), 0 2px 2px 0 rgba(0, 0, 0, 0.2);
  transform: translate3d(-15%, 0, -100px);
}

#s1:checked ~ #slide1,
#s2:checked ~ #slide2,
#s3:checked ~ #slide3,
#s4:checked ~ #slide4,
#s5:checked ~ #slide5 {
  box-shadow: 0 13px 25px 0 rgba(0, 0, 0, 0.3), 0 11px 7px 0 rgba(0, 0, 0, 0.19);
  transform: translate3d(0, 0, 0);
}

#s1:checked ~ #slide2,
#s2:checked ~ #slide3,
#s3:checked ~ #slide4,
#s4:checked ~ #slide5,
#s5:checked ~ #slide1 {
  box-shadow: 0 6px 10px 0 rgba(0, 0, 0, 0.3), 0 2px 2px 0 rgba(0, 0, 0, 0.2);
  transform: translate3d(15%, 0, -100px);
}

#s1:checked ~ #slide3,
#s2:checked ~ #slide4,
#s3:checked ~ #slide5,
#s4:checked ~ #slide1,
#s5:checked ~ #slide2 {
  box-shadow: 0 1px 4px 0 rgba(0, 0, 0, 0.37);
  transform: translate3d(30%, 0, -200px);
}

#slide1 {
  background-image: url(../assets/main-frilance.jpg);
  background-size: 1270px;
  background-repeat: no-repeat;
  background-position: center;
}
#slide2 {
  background-image: url(../assets/task-picture.jpg);
  background-size: 1270px;
  background-repeat: no-repeat;
  background-position: center;
}
#slide3 {
  background-image: url(../assets/crypt.jpg);
  background-size: 1270px;
  background-repeat: no-repeat;
  background-position: center;
}
#slide4 {
  background-image: url(../assets/auth.jpg);
  background-size: 1270px;
  background-repeat: no-repeat;
  background-position: center;
}
#slide5 {
  background-image: url(../assets/acarta-main.jpg);
  background-size: 1270px;
  background-repeat: no-repeat;
  background-position: center;
}
</style>