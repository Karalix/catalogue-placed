<template>
  <div>
    <div class="header">
      <h1>PLACED - The catalogue</h1>
      <img class="placed-logo" src="/Logo_Placed.svg"/>
    </div>
    <div class="main">
      <p class="intro">How can new and dynamic digital services help libraries transform into vibrant urban innovation hubs by supporting knowledge creation activities among citizens and turning this knowledge into an ever-growing part of the urban community's shared resources?</p>
      <p>The PLACED project introduces a new type of place- and activity-centric digital library services. Whereas library services typically focus on providing access to a collection of media, PLACED services support activities in the library.</p>
      <p>The groundbreaking aspect is that these services capture knowledge generated through these activities, make them a part of the library's collection, and allow future library users to explore and access them. In this way, PLACED services help break down the institutional walls of the library and make it an integrated part of urban life by creating an ever-evolving collection built on urban activities and knowledge generation.</p>
      <p>Find below the links to the 2 catalogues summarizing our results, in english and in french :</p>
      <div class="links">
        <a href="/fr-catalogue-s.pdf">Version Française</a>
        <a href="/eng-catalogue-v3-s.pdf">English Version</a>
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

.main {
  display: flex;
  flex-direction: column;
  justify-content: center;
  justify-items: center;
  align-items: center;
  padding: 0.5em;
}

.main p {
  max-width: 600px;
}

.intro {
  font-weight: bold;
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