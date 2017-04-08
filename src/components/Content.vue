<template lang="html">
  <div class="content">
    <ul>
      <md-icon><i class="material-icons">turned_in</i></md-icon>
      <b id="title-font">  Objectives</b>
      <ul id="content-font">
        <br>
        <li>Front-end Website Developer Internship</li>
        <li>Back-end Website Developer Internship</li>
      </ul>
      <br>
      <md-divider></md-divider><br>
      <md-icon><i class="material-icons">turned_in</i></md-icon>
      <b id="title-font">  Education</b>
      <ul id="content-font">
        <br>
        <li><b>Bachelor Degree in Computer Science,
          Mahidol University International College, Thailand</b>
          (2014 - present)</li>
        <br>
        <ul>
          <li>A member of MUIC Student Committee, 2016 - present</li>
          <li>Photo Club executive, 2016 - present</li>
        </ul>
        <br>
        <li><b>Ping Yi Secondary School, Singapore</b> (2011 - 2014)</li>
      </ul>
      <br>
      <md-divider></md-divider><br>
      <md-icon><i class="material-icons">turned_in</i></md-icon>
      <b id="title-font">  Experiences</b> (school projects)
      <ul id="content-font">
        <br>
        <li><b>Web Application Development:</b></li>
        <br>
        <ul>
          <li>Front-end website developer of team project:
             Developing a Card Game web application</li>
          <md-subheader>Ruby on Rails, NodeJs</md-subheader>
        </ul>
        <li><b>Object-Oriented Design and Methodology</b></li>
        <br>
        <ul>
          <li>Team project: Developing Stock Manager web application</li>
          <md-subheader>Java - Spring Boot</md-subheader>
        </ul>
      </ul>
      <br>
      <md-divider></md-divider><br>
      <md-icon><i class="material-icons">turned_in</i></md-icon>
      <b id="title-font">  Coding Skills</b>
      <ul id="content-font">
        <br>
        <li>HTML & CSS</li>
        <div id="myProgress">
          <div id="myBar" style="width: 75%;"></div>
        </div>
        <br>
        <li>Java</li>
        <div id="myProgress">
          <div id="myBar" style="width: 60%;"></div>
        </div>
        <br>
        <li>Javascript</li>
        <div id="myProgress">
          <div id="myBar" style="width: 40%;"></div>
        </div>
        <br>
        <li>Python</li>
        <div id="myProgress">
          <div id="myBar" style="width: 70%;"></div>
        </div>
        <br>
        <li>NodeJs</li>
        <div id="myProgress">
          <div id="myBar" style="width: 50%;"></div>
        </div>
        <br>
        <li>MySQL</li>
        <div id="myProgress">
          <div id="myBar" style="width: 50%;"></div>
        </div>
      </ul>
    </ul>
    <br>
  </div>
</template>

<script>
export default {
  name: 'content'
}
</script>

<style lang="css">
#myProgress {
    width: 80%;
    /*background-color: black;*/
}
#myBar {
    height: 15px;
    background-color: #22A2DE;
    -webkit-border-radius: 10px;
    -moz-border-radius: 10px;
    border-radius: 10px;
}
#content-font {
  font-size: 16px;
}
#title-font {
  font-size: 22px;
  color: #D46D21;
}
.icon-color {
  color: #F37532;
}
</style>
