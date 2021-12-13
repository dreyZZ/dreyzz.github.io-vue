<template>
  <section id="experience">
    <div class="text row">
      <h1 class="col-md-3 text-left">WORK</h1>
      <div class="col-md-9 center">
        <h2>Enuygun.com</h2>
        <ul class="details">
          <li>July 2018 - October 2018</li>
        </ul>
        <ul class="work_list">
          <li>
            Took part in a PHP-Python Computer Vision project and experienced
            OOP programming, Version Control Systems, Jira, in a professional
            environment
          </li>
          <li>Got a course about various web technologies for 2 weeks</li>
          <li>Implemented a Web Crawler project with Node.js</li>
        </ul>
        <br />
        <h2>Hitit Computer Services</h2>
        <ul class="details">
          <li>August 2019 -</li>
        </ul>
        <ul class="work_list">
          <li>
            Created three demo projects with Angular, React and Vue frameworks
            to compare them
          </li>
          <li>Worked in a team that created a Spring REST API</li>
          <li>
            Maintaining and adding new features to a JSF / Spring Web App which
            is a Passenger Ticketing System for Airline companies
          </li>
          <li>
            Maintaining a Spring Rest API which acts as Gateway to a Soap API
            System
          </li>
          <li>Worked with Oracle DB's and SQL</li>
        </ul>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  data: () => {
    return {};
  },
};
</script>

<style lang="scss">
#experience {
  padding: 70px 0% 3% 0;

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

    ul.details {
      color: rgb(143, 143, 143);
      li {
        display: inline;
        // overflow: ;
        list-style-type: disc;
        // display: list-item;
      }
    }

    li {
      color: rgb(180, 176, 176);
      // list-style-type: none;
    }
  }
}

.work_list {
  list-style-type: square !important;
  padding-right: 20%;
  padding-left: 2%;
}
</style>


