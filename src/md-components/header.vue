<template>
  <header id="header">
    <div class="text-box">
      <h1 class="heading-primary">Idris Bulut</h1>
    </div>
    <ul class="social">
      <li>
        <a
          target="_blank"
          href="https://www.linkedin.com/in/idris-bulut-827b1a155/"
        >
          <img src="../assets/linkedin.png" alt="Linked In Profile"
        /></a>
      </li>
      <li>
        <a target="_blank" href="https://github.com/dreyZZ">
          <img src="../assets/github.png" alt="Github Profile"
        /></a>
      </li>
      <li>
        <a target="_blank" href="https://leetcode.com/dreyZZ/">
          <img src="../assets/leetcode.png" alt="Leetcode Profile"
        /></a>
      </li>
      <li>
        <a target="_blank" href="https://www.codewars.com/users/dreyZZ">
          <img src="../assets/codewars.png" alt="Codewars Profile"
        /></a>
      </li>
    </ul>
  </header>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
ul {
  img {
    width: 50px;
    // height: 50px;
    // opacity: 0.3;
    &:hover {
      background-color: rgb(35, 75, 75) !important;
      opacity: 0.8;
    }
  }
  position: absolute;
  list-style-type: none;
  overflow: hidden;
  li {
    line-height: 18px;
    display: inline;
  }
  left: 50%;
  top: 55%;
  transform: translate(-50%, -50%);
}

#header {
  height: 95vh;
  background-image: linear-gradient(
      to right bottom,
      rgba(56, 56, 56, 0.8),
      rgba(50.2, 50.2, 50.2, 0.8)
    ),
    url("../assets/background.jpg");
  background-size: cover;
  background-position: top;
  clip-path: polygon(0 0, 100% 0, 100% 90vh, 0 100%);
  background-color: grey;

  .text-box {
    position: absolute;
    left: 50%;
    top: 40%;
    transform: translate(-50%, -50%);

    .heading-primary {
      color: #fff;
      text-transform: uppercase;
      display: block;
      font-size: 60px;
      font-weight: 400;
      letter-spacing: 10px;
      animation-name: moveInLeft;
      animation-duration: 1s;
      animation-timing-function: ease-out;

      // &:hover{
      //   opacity: 0;
      //   width: 300px;
      // }
    }
  }
}
</style>
