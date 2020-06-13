<template>
  <div class="wrapper">
    <section class="left__sec">
      <h1>MY SKILLS</h1>
      <p>I mainly excell in front-end development, however that does not mean I lack back-end development skills.</p>
      <p>I the future I aim to take my skill set to being a fullstack developer</p>
    </section>
    <!--  -->
    <section class="right__sec">
      <ul class="skills__list">
        <li>
          <span class="m">M</span>ongo
        </li>
        <!--  -->
        <li>
          <span class="e">E</span>xpress
        </li>
        <!--  -->
        <li>
          <img src="../assets/logo.png" alt="vue.logo" />ue
        </li>
        <!--  -->
        <li>
          <span class="n">N</span>ode
        </li>
      </ul>
    </section>
  </div>
</template>


<style lang="scss" scoped>
.left__sec {
  width: 30%;
  h1 {
    font-size: 4.5em;
    font-weight: bold;
  }

  p {
    font-size: 1.3em;
    margin: 35px 0px;
    line-height: 1.2;
  }
}

.right__sec {
  padding: 0px 70px;
  margin-top: -45px;
  .m {
    color: #00b894;
  }

  .n {
    color: #55efc4;
  }

  .skills__list {
    font-size: 16vh;
    margin-left: 25%;
    font-weight: bold;
    opacity: 0.3;

    li {
      margin: 10px 0px;
    }
  }
}
</style>