<template>
  <section id="skills">
    <div class="row">
      <h1 class="col-md-3 text-left">SKILLS</h1>
      <div class="col-md-9">
        <br /><progress-bar name="Java" value="95" /> <br /><progress-bar
          name="Javascript"
          value="90"
        />
        <br /><progress-bar name="Spring" value="80" /> <br /><progress-bar
          name="HTML, CSS"
          value="80"
        />
        <br /><progress-bar name="Kotlin" value="80" /> <br /><progress-bar
          name="Vue JS"
          value="75"
        />
        <br /><progress-bar name="Unity" value="75" /> <br /><progress-bar
          name="C, C++"
          value="70"
        />
        <br /><progress-bar name="Native Android" value="70" />
        <br /><progress-bar name="Python" value="70" /> <br /><progress-bar
          name="Electron"
          value="70"
        />
        <br /><progress-bar name="Angular" value="65" /> <br /><progress-bar
          name="C#"
          value="60"
        />
        <br /><progress-bar name="PHP / Symfony" value="60" />
        <br /><progress-bar name="SQL" value="60" /> <br /><progress-bar
          name="Node JS"
          value="60"
        />
        <br /><progress-bar name="React" value="50" /> <br /><progress-bar
          name="Rust"
          value="50"
        />
        <br /><progress-bar name="Loopback" value="40" /> <br /><progress-bar
          name="Godot"
          value="40"
        />
        <br /><progress-bar name="Django" value="30" /> <br /><progress-bar
          name="JavaFX"
          value="30"
        />
        <!-- <progress-bar /> -->
      </div>
    </div>
    <!-- <br>
        <br>
        <div class="row">
            <h1 class="col-md-3 text-left"> COMPUTER SCIENCE </h1>
            <div class="col-md-9">
                <br><progress-bar name="Object Oriented Modeling & Design" value="85" />
                <br><progress-bar name="Software Quality & Testing" value="80"  />
                <br><progress-bar name="Software Engineering" value="80"  />
                <br><progress-bar name="Database Management Systems" value="70"  />
                <br><progress-bar name="Machine Learning" value="70"  />
                <br><progress-bar name="AR, ARCore, Vuforia, Wikitude" value="50"  />
                <br><progress-bar name="Computer Vision" value="40"  />
                <br><progress-bar name="System Prog." value="30"  />
            </div>
        </div> -->
    -->
  </section>
</template>

<script>
import progressBar from "../sm-components/progressBar";

export default {
  data: function () {
    return {};
  },
  components: {
    progressBar,
  },
};
</script>

<style lang="scss">
</style>



