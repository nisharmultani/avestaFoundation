<template>
  <div class="container">
    <div class="heading">
      <h1>
        YOU CAN SAVE <span>ELDERLY</span> AND <span>ABANDONED</span> LIFE.
      </h1>
      <p>
        To give an underprivileged person a pair of clothes is as good as
        dressing him with self-respect with this objective.
      </p>
    </div>
    <div class="cardcontainer">
      <div class="cardtitle">
        <h3>Glimpses of our extraordinary social work</h3>
      </div>
      <div class="row">
        <div class="col-sm-3">
          <div class="card">
            <img src="@/assets/img/img.jpeg" alt="" />
            <div class="cardDetails">
              <span>Food Distribution</span>
              <p>We have distributed food materials to needy during lockdown</p>
            </div>
          </div>
        </div>
        <div class="col-sm-3">
          <div class="card">
            <img src="@/assets/img/img.jpeg" alt="" />
            <div class="cardDetails">
              <span>Food Distribution</span>
              <p>We have distributed food materials to needy during lockdown</p>
            </div>
          </div>
        </div>
        <div class="col-sm-3">
          <div class="card">
            <img src="@/assets/img/img.jpeg" alt="" />
            <div class="cardDetails">
              <span>Food Distribution</span>
              <p>We have distributed food materials to needy during lockdown</p>
            </div>
          </div>
        </div>
        <div class="col-sm-3">
          <div class="card">
            <img src="@/assets/img/img.jpeg" alt="" />
            <div class="cardDetails">
              <span>Food Distribution</span>
              <p>We have distributed food materials to needy during lockdown</p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped>
.cardcontainer {
  margin: 0px 0 50px 0px;
}
.heading {
  padding: 20px;
  margin: 50px 0 50px 0;
}
.heading h1 {
  font-size: 40px;
  text-align: center;
  font-weight: bold;
}
.heading p {
  font-size: 18px;
  text-align: center;
  color: rgb(124, 121, 121);
}
.cardtitle h3 {
  font-size: 20px;
  font-family: Arial, Helvetica, sans-serif;
  font-weight: bold;
  margin: 0 0 20px 0;
}

.card {
  position: relative;
  height: 300px;
  box-shadow: 10px 10px 10px rgba(0, 0, 0, 0.25);
  border-radius: 15px;
  cursor: pointer;
}
img {
  border-radius: 15px 15px 0px 0px;
  background-size: cover;
  background-repeat: no-repeat;
  background-position: 50%;
  height: 100%;
  width: 100%;
  transition: all 0.5s ease-out;
}
/* img:hover {
  transform: scale(1.1);
} */
.cardDetails {
  padding: 20px;
}
.cardDetails span {
  font-size: 20px;
  font-weight: bold;
}
</style>