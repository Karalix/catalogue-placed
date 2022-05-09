<template>
  <div>
    <div class="header">
      <img class="placed-logo" src="~/assets/Logo_Placed.svg"/>
    </div>
    <div class="ubermain">
      <div class="main">
        <h1>PLACED</h1>
        <p class="intro">How can new and dynamic digital services help libraries transform into vibrant urban innovation hubs by supporting knowledge creation activities among citizens and turning this knowledge into an ever-growing part of the urban community's shared resources?</p>
        <p>The PLACED project introduces a new type of place- and activity-centric digital library services. Whereas library services typically focus on providing access to a collection of media, PLACED services support activities in the library.</p>
        <p>The groundbreaking aspect is that these services capture knowledge generated through these activities, make them a part of the library's collection, and allow future library users to explore and access them. In this way, PLACED services help break down the institutional walls of the library and make it an integrated part of urban life by creating an ever-evolving collection built on urban activities and knowledge generation.</p>
        <br/>
        <h2>Learn more about PLACED</h2>
        <ul>
          <li>The website of the project <a href="https://placedproject.eu/">placedproject.eu</a></li>
          <li>Our current work bringing our prototypes to the field <a href="https://www.kronikle.eu">kronikle.eu</a></li>
        </ul>
        <h2>The PLACED catalogue</h2>
        <p>Find below the links to the 2 catalogues summarizing our results, in english and in french :</p>
        <div class="links">
          <a href="/fr-catalogue-s.pdf">
            <div class="thumb-wrapper">
              <img class="thumb" src="~/assets/catalogue-fr.png">
              <span>Version française</span>
            </div>
          </a>
          <a href="/eng-catalogue-v3-s.pdf">
            <div class="thumb-wrapper">
            <img class="thumb" src="~/assets/catalogue-en.png">
            <span>English version</span>
            </div>
          </a>
        </div>
      </div>
    </div>
  </div>
</template>

<style>
@import url('https://fonts.googleapis.com/css2?family=Fira+Sans&display=swap');

html {
  font-family: 'Fira Sans', sans-serif;
}

.header {
  display: flex;
  flex-direction: row;
  justify-content: space-between;
  align-items: center;
  padding: 0.5em;
}

.placed-logo {
  width: 120px
}

.ubermain {
  display: flex;
  justify-content: center;
  align-items: center;
}

.main {
  display: flex;
  flex-direction: column;
  justify-content: center;
  justify-items: center;
  padding: 0.5em;
}

.main p {
  max-width: 600px;
}

.intro {
  font-weight: bold;
}

.thumb-wrapper {
  display: flex;
  flex-direction: column;
}

.thumb {
  width: 120px;
  margin-bottom: 15px;
}

.links {
  display: flex;
  flex-direction: row;
  justify-content: space-between;
  align-items: center;
  padding: 0.5em;
}

.links a {
  margin: 0.5em;
}
</style>
