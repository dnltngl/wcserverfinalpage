<template>
  <div>
    <!-- Nav bar -->
    <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
      <div class="container">
        <a class="navbar-brand float-left">Health Mockup tool Application</a>
        <ul class="nav navbar-nav flex-row float-right">
          <div class="container1">
            <li class="nav-item">
              <router-link class="nav-link pr-3" to="home">Home</router-link>
              <router-link class="nav-link pr-3" to="/"
                >Create Patient</router-link
              >

              <router-link class="nav-link" to="/view"
                >View Patients</router-link
              >

              <router-link class="nav-link" to="/about">About</router-link>
            </li>
          </div>
        </ul>
      </div>
    </nav>
    <!-- Router view -->
    <div class="container mt-5">
      <router-view></router-view>
    </div>
  </div>
</template>

<style scoped>
.container1 {
  grid-row: 30%;
}
</style>
