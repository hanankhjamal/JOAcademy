<template>
  <v-footer class="footer">
    <v-container grid-list-md fluid>
      <v-layout row wrap text-sm-left mb-5 text-xs-center>
        <v-flex lg3 md3 sm6 xs12 style="text-align: right;">
          <div>
            <h3 class="footerTitle" target="_blank">{{'روابط سريعة'}}</h3>
          </div>
          <div>
            <a class="linkStyle" target="_blank">{{' دبلومات ودورات '}}</a>
          </div>
          <div>
            <a class="linkStyle" target="_blank">{{'المدارس والجامعات'}}</a>
          </div>
          <div>
            <a class="linkStyle" target="_blank">{{'بنك الأسئلة'}}</a>
          </div>
          <div>
            <a class="linkStyle" target="_blank">{{'احسب معدلك'}}</a>
          </div>
          <div>
            <a class="linkStyle" target="_blank">{{'الجدول الدراسي'}}</a>
          </div>
          <div>
            <a class="linkStyle" target="_blank">{{'معلمون'}}</a>
          </div>
          <div>
            <a class="linkStyle" target="_blank">{{'كتب الوزارة وأجوبتها'}}</a>
          </div>
        </v-flex>
        <v-flex lg3 md3 sm6 xs12 style="text-align: right;">
          <div>
            <h3 class="footerTitle" target="_blank">{{'الدعم'}}</h3>
          </div>
          <div>
            <a class="linkStyle" target="_blank">{{'اتصل بنا'}}</a>
          </div>
          <div>
            <a class="linkStyle" target="_blank">{{'الأسئلة الأكثر شيوعاً'}}</a>
          </div>
          <div>
            <a class="linkStyle" target="_blank">{{'منظار'}}</a>
          </div>
          <div>
            <a class="linkStyle" target="_blank">{{'نقاط البيع'}}</a>
          </div>
          <div>
            <a class="linkStyle" target="_blank">{{'استاذي'}}</a>
          </div>
          <div>
            <a class="linkStyle" target="_blank">{{'شبابيك'}}</a>
          </div>
          <div>
            <a class="linkStyle" target="_blank">{{'ألعاب'}}</a>
          </div>
          <div>
            <a class="linkStyle" target="_blank">{{'المدونة'}}</a>
          </div>
        </v-flex>
        <v-flex lg3 md3 sm6 xs12 style="text-align: right;">
          <div>
            <h3 class="footerTitle" target="_blank">{{'من نحن'}}</h3>
          </div>
          <div>
            <a class="linkStyle" target="_blank">{{'جو أكاديمي'}}</a>
          </div>
          <div>
            <a class="linkStyle" target="_blank">{{'الشروط والاحكام'}}</a>
          </div>
          <div>
            <a class="linkStyle" target="_blank">{{'سياسة الخصوصية'}}</a>
          </div>
          <div>
            <a class="linkStyle" target="_blank">{{'نقاط البيع'}}</a>
          </div>
          <div>
            <a class="linkStyle" target="_blank">{{'حمل تطبيق جو اكاديمي على موبايلك'}}</a>
          </div>

          <div class="row">
            <div class="column">
              <v-img contain src="../static/images/appstore.png" max-height="45" width="100%" />
            </div>
            <div class="column">
              <v-img contain src="../static/images/playstore.png" max-height="45" width="100%" />
            </div>
          </div>
        </v-flex>
        <v-flex lg3 md3 sm6 xs12 style="text-align: right;">
          <div>
            <h3 class="footerTitle" target="_blank">{{'من نحن'}}</h3>
          </div>
          <div>
            <a class="linkStyle" target="_blank">{{'جو أكاديمي'}}</a>
          </div>
          <div>
            <a class="linkStyle" target="_blank">{{'الشروط والاحكام'}}</a>
          </div>
          <div>
            <a class="linkStyle" target="_blank">{{'سياسة الخصوصية'}}</a>
          </div>
          <div>
            <a class="linkStyle" target="_blank">{{'نقاط البيع'}}</a>
          </div>
        </v-flex>
      </v-layout>
    </v-container>
  </v-footer>
</template>

<style scoped>
.footer {
  background-color: #001527 !important;
}

.footerTitle {
  line-height: 2.375rem;
  font-weight: 700;
  color: #9d9d9d;
  font-size: 20px;
}
.linkStyle {
  line-height: 1rem;
  line-height: 28px;
  color: #9d9d9d;
  text-decoration: none;
}

.column {
  float: left;
  width: 33.33%;
  padding: 5px;
}

/* Clearfix (clear floats) */
.row::after {
  content: "";
  clear: both;
  display: table;
}
</style>