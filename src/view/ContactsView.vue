    <template >
  <div class="footer">
    <h1>If you want to see my projects or write to me</h1>
    <ul class="information">
      <li>
        <a href="https://github.com/monkkeydrag228"
          ><img
            style="width: 260px; height: 149px"
            src="../assets/Remove-bg.ai_1712493821933.png"
            alt=""
        /></a>
      </li>
      <li>
        <a href="https://t.me/eb_whispererbot"
          ><img
            style="width: 120px; height: 120px"
            src="../assets\Remove-bg.ai_1712494331777.png"
            alt=""
        /></a>
      </li>
    </ul>

    <!-- <input type="text" class="input-search" id="input-search" />
        <label class="search" for="input-search"></label> -->
  </div>
</template>
    
    <style scoped>
.footer h1 {
  margin-left: 33%;
  font-family: "Nanum Gothic Coding", monospace;
  font-weight: 400;
  font-style: normal;
  color: rgb(226, 221, 221);
}

.information li,
ul {
    display: flex;
    align-items: center;
  width: 300px;
}

.information {
  display: flex;
  align-items: center;
  justify-content: center;
  list-style: none;
}
.footer {
  margin-top: 180px;
  padding-top: 100px;
  background-color: #0000008d;
  
  width: 100vw;
  height: 200px;
}
body {
  margin: 0px;
  padding: 100px;
  text-align: center;
}

.search {
  position: relative;
}

.input-search {
  background-color: transparent;
  border: none;
  height: 30px;
  width: 30px;
  padding: 0 0px;
  font-size: 1.1em;
  font-weight: lighter;
  color: transparent;
  border-radius: 24px;
  -webkit-transition: all 0.4s;
  transition: all 0.4s;
  -webkit-transition-timing-function: ease-out;
  transition-timing-function: ease-out;
}

.input-search:focus {
  color: #37afe2;
  width: 400px;
  padding: 0 12px;
  outline: none;
  border: 2px solid white !important;
}

.input-search + .search:after {
  content: url("../assets/pngwing.com (1).png"); /* Путь к изображению иконки Telegram */
  max-width: 20px; /* Максимальная ширина изображения */
  display: block;
  position: absolute;
  right: 20px;
  bottom: -8px;
  -ms-transform: rotate(45deg);
  -webkit-transform: rotate(45deg);
  transform: rotate(45deg);
  -webkit-transition: all 0.2s;
  transition: all 0.2s;
  -webkit-transition-timing-function: ease-out;
  transition-timing-function: ease-out;
}

.input-search + .search:before {
  content: "";
  width: 0px;
  display: block;
  position: absolute;
  right: -2px;
  bottom: 19px;
  -ms-transform: rotate(-45deg);
  -webkit-transform: rotate(-45deg);
  transform: rotate(-45deg);
  -webkit-transition: all 0.2s;
  transition: all 0.2s;
  -webkit-transition-timing-function: ease-out;
  transition-timing-function: ease-out;
  -webkit-transition-delay: 0s; /* Safari */
  transition-delay: 0s;
  border: solid 2px linear-gradient(to right, #15e8fb, #0000ff) !important;
}
</style>
    