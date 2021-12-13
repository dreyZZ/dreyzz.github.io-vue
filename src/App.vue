<template>
  <div id="app">
    <app-navbar></app-navbar>
    <app-header></app-header>
    <app-about></app-about>
    <app-experience></app-experience>
    <app-education></app-education>
    <app-skills></app-skills>
    <!-- work -->
  </div>
</template>

<script>
import navbar from "./md-components/navbar";
import header from "./md-components/header";
import about from "./md-components/about";
import education from "./md-components/education";
import skills from "./md-components/skills";
import experience from "./md-components/experience";

import progressBar from "./sm-components/progressBar";

export default {
  name: "app",
  data: function () {
    return {};
  },
  components: {
    "app-navbar": navbar,
    "app-header": header,
    "app-about": about,
    "app-education": education,
    "app-experience": experience,
    "app-skills": skills,
    progressBar,
  },
};
</script>

<style lang="scss">
* {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
}

body {
  font-family: "IBM Plex Sans Condensed", sans-serif;
  font-weight: 400;
  font-size: 16px;
  line-height: 1.7;
  color: #777;
  background-image: -webkit-gradient(
    linear,
    left top,
    left bottom,
    from(#181616),
    to(#616060)
  );
  background-image: linear-gradient(to bottom, #181616, #616060);
}

.row {
  margin-left: 8%;
}

.col-md-9 {
  padding-left: 4%;
}

//1

#app {
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}

//2
.navBar {
  background-color: #2b2a2a;
  position: fixed;
  top: 0;
  width: 100%;
  z-index: 100;
  list-style: none;
  // display: inline-block;
  text-align: center;
  li {
    display: inline-block;
    a {
      display: inline-block;
      color: #f2f2f2;
      text-align: center;
      padding: 14px 16px;
      text-decoration: none;
      &:hover {
        background: #ddd;
        color: black;
      }
    }
  }
}

#about {
  padding: 70px 10px 0 0%;
  font-size: 18px;
  line-height: 30px;
  // padding-left: 10%;

  img {
    // float: left;
    // margin-right: 50px;
    // left: 10%;
    width: 170px;
    height: 260px;
    opacity: 0.9;
  }

  .center {
    float: center;
    color: white;

    h2 {
      opacity: 0.95;
      font-weight: bold;
      padding-bottom: 10px;
    }

    p {
      color: #8f8f8f;
      font-size: 17px;
    }
  }
}

#education {
  padding: 70px 0% 0 0;

  font-size: 18px;
  line-height: 30px;

  .text {
    color: white;

    h1 {
      opacity: 0.95;
    }

    h2 {
      color: rgb(240, 240, 240);
    }

    ul {
      color: rgb(143, 143, 143);
      li {
        display: inline;
        // overflow: ;
        list-style-type: disc;
        // display: list-item;
      }
    }

    li {
      color: rgb(143, 143, 143);
      list-style-type: none;
    }
  }
}

#skills {
  padding: 70px 0% 5% 0;

  .col-md-9 {
    padding-right: 20%;
  }

  h1 {
    color: white;
  }
}

//3

.text-left {
  text-align: center !important;
}

//ANIMATIONS

@keyframes moveInLeft {
  0% {
    opacity: 0;
    transform: translateY(-100px);
  }
  100% {
    opacity: 1;
    transform: translate(0);
  }
}

.bar {
  background-color: black !important;
  color: rgba(255, 255, 255, 0.664);
}
.space {
  background-color: grey;
}
</style>
