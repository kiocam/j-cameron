<template>
  <div class="wrapper">
    <section class="left__sec">
      <h1>WHO AM I</h1>
      <p>
        I enjoy working on exciting and challenging projects, with fun and
        energetic individuals.
      </p>
      <p>Have a vision ? Lets make it real!</p>
    </section>
    <!--  -->
    <section class="right__sec">
      <p>
        Front-end
        <br />developer
      </p>
      <img class="time-line" src="../assets/Timeline.png" alt="time-line" />
    </section>
    <!--  -->
  </div>
</template>

<style lang="scss" scoped>
.left__sec {
  width: 26%;
  h1 {
    font-size: 4.5em;
    font-weight: bold;
  }

  p {
    font-size: 1.3em;
    margin-top: 20px;
    line-height: 1.2;
  }
}

.right__sec {
  padding-left: 30px;
  p {
    font-size: 20vh;
    opacity: 0.1;
    font-weight: bold;
    font-style: italic;
    margin: 0 auto;
  }
}

.time-line {
  margin: 75px auto;
}
</style>
