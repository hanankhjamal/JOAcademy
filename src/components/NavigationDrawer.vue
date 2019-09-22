<template>
  <v-navigation-drawer class="navDrawer" absolute permanent right v-model="drawer" >
    <div style="display: flex;flex-direction: row;margin-top: 10px;">
      <div class="iconDiv">
        <v-btn class="ma-1" primary medium fab color="primary">
          <v-icon>mdi-pencil</v-icon>
        </v-btn>

        <p style="font-size: 14px;color: #267CF3">مفضلتي</p>
      </div>

      <div class="iconDiv">
        <v-btn class="ma-1" primary medium fab color="primary">
          <v-icon>mdi-pencil</v-icon>
        </v-btn>

        <p style="font-size: 14px;color: #267CF3">دوراتي</p>
      </div>

      <div class="iconDiv">
        <v-btn class="ma-1" primary medium fab color="primary">
          <v-icon>mdi-pencil</v-icon>
        </v-btn>

        <p style="font-size: 14px;color: #267CF3">جروباتي</p>
      </div>

      <div class="iconDiv">
        <v-btn class="ma-1" primary medium fab color="primary">
          <v-icon>mdi-pencil</v-icon>
        </v-btn>

        <p style="font-size: 14px;color: #267CF3">ملفاتي</p>
      </div>
    </div>

    <v-list dense nav>
      <v-list-item link>
        <v-list-item-icon>
          <v-icon>mdi-pencil</v-icon>
        </v-list-item-icon>

        <v-list-item-content>
          <v-list-item-title>{{ 'item.title' }}</v-list-item-title>
        </v-list-item-content>
      </v-list-item>
    </v-list>
  </v-navigation-drawer>
</template>

<style scoped>
.navDrawer {
  box-shadow: 0 5px 11px 0 rgba(0, 0, 0, 0.18), 0 4px 15px 0 rgba(0, 0, 0, 0.15) !important;
}
.iconDiv {
  height: 102.28px;
  text-align: center;
}
</style>