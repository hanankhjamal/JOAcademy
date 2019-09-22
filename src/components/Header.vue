<template>
  <div>
    <v-app-bar app absolute class="vAppBar">
      <!-- <v-app-bar-nav-icon class="d-flex d-sm-none"></v-app-bar-nav-icon> -->
      <v-flex xs>
        <v-toolbar-title class="d-flex align-center ml-0 mr-2">
          <div class="logo pa-0 ma-0">
            <div class="logoS">
              <v-img contain src="../static/images/menthar-logo.png" max-height="45" width="100%" />
            </div>
          </div>
        </v-toolbar-title>
      </v-flex>
      <v-flex xs6 class="d-none d-sm-flex">
        <div
          class="searchDiv"
          style="flex-direction: row;display: flex; justify-content: center;align-items: center;"
        >
          <input placeholder="ابحث  عن  دورات , معملين , أوراق عمل" class="searchInput" />
          <span icon>
            <v-icon style="color:#FFFFFF; font-size:1rem">mdi-heart</v-icon>
          </span>
        </div>
      </v-flex>

      <v-flex
        xs4
        class="d-none d-sm-flex"
        style="flex-direction: row;display: flex; justify-content: center;align-items: center;"
      >
        <div style="flex-direction: row;display: flex;">
          <div
            style="flex-direction: row;display: flex;margin-left:20px; justify-content: center;align-items: center;"
          >
            <span icon>
              <v-icon style="color:#FFFFFF; font-size:1rem,">mdi-heart</v-icon>
            </span>
            <h3 class="username">{{' لين قطاونة '}}</h3>
          </div>

          <v-avatar color="grey lighten-5" title="ggg" size="25">
            <img
              src="https://www.pngarts.com/files/3/Avatar-Transparent-Image.png"
              width="auto"
              alt="avatar"
            />
          </v-avatar>

          <v-btn icon style="margin-right: 16px;width: 30px;height: 30px;">
            <v-icon style="font-size:1.5rem">mdi-magnify</v-icon>
          </v-btn>
          <v-btn icon style="margin-right: 16px;width: 30px;height: 30px;">
            <v-icon style="font-size:1.5rem">mdi-magnify</v-icon>
          </v-btn>
        </div>
      </v-flex>

      <v-flex
        xs1
        style="flex-direction: row;display: flex; justify-content: center;align-items: center;"
      >
        <v-btn icon style="background-color:#FFFFFF;width: 30px;height: 30px;">
          <v-icon style="font-size:1.3rem">mdi-magnify</v-icon>
        </v-btn>
      </v-flex>
    </v-app-bar>
  </div>
</template>

<style scoped>
.vAppBar {
  background-color: #327bf9 !important;
  border-color: #707070;
  color: #ffffff;
  height: 70px;
}

.searchDiv {
  border: #707070;
  box-shadow: 0 5px 11px 0 rgba(245, 245, 245, 0.15),
    0 4px 15px 0 rgba(0, 0, 0, 0.15) !important;
  height: 2.5rem;
  background-color: #002f57;
  opacity: 0.4;
  padding-right: 1.125rem;
  border-radius: 5px;
  width: 100%;
}

.searchInput {
  color: #ffffff;
  font-size: 0.9375rem;
  width: 90%;
  height: 100%;
}

.searchInput::placeholder {
  color: #ffffff;
  font-size: 0.9375rem;
}

.flex {
  display: flex;
  padding-right: 0.5rem;
}

.username {
  font-size: 1.125rem;
  color: #ffffff;
  margin-right: 0.3125rem;
}

.maR-16 {
  margin-right: 1rem;
}

.circle {
  width: 3.5625rem;
  height: 3.5625rem;
  border-radius: 50%;
}

@media only screen and (max-width: 600px) {
  body {
    background-color: red;
  }
}
</style>