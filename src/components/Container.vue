<template>
  <div class="main-content">
    <h2 class="title-screen">تاريخ الأردن - توجيهي علمي</h2>
    <v-container class="grey lighten-5">
      <v-row class="mb-6" justify="center" no-gutters>
        <v-col md="8" xs="12" style="padding: 6px;">
          <div>
            <h4 style="font-size: 27px; color: #535962; text-align: right;">فهرس الكتاب</h4>
          </div>
          <v-card
            style="height: 913px;box-shadow:0 2px 5px 0 rgba(0,0,0,.16),0 2px 10px 0 rgba(0,0,0,.12)!important; border-radius: 8px"
          >
            <v-row style="margin-right : 16px;margin-left : 16px">
              <v-col md="6" xs="12">
                <p>hhhhhh</p>
              </v-col>
              <v-col lg="6">
                <div class="col-6-p">
                  <p class="pBook">
                    تتكون السلطة التنفيذية في الأردن من مكونين رئيسين هما
                    مؤسسة العرش
                    نظام الحكم في الأردن نيابي ملكي وراثي ، ويمثل الملك مؤسسة العرش في المملكة الأردنية الهاشمية ، حيث جاء في المادة (28) من الدستور الأردني أن عرش المملكة الأردنية الهاشمية وراثي في أسرة الملك عبدالله الأول ابن الحسين مؤسس المملكة الأردنية ، وكون وراثة العرش في الذكور من أبنائه وفقا للأسس التالية:
                    - تنتقل ولاية الملك من صاحب العرش إلى أكبر أبنائه سنا ، ثم إلى أكبر أبناء ذلك الابن الأكبر ، وهكذا طبقة بعد طبقة.
                    - إذا لم يكن لمن له ولاية الملك عقب إلى أكبر إخوته ، وإذا لم يكن له إخوة ، فإلى أكبر أبناء إخوته ، وهكذا حسب الترتيب.
                    مجلس الوزارء (الحكومة)
                    يتألف مجلس الوزراء من رئيس الوزراء وعدد من الوزراء حسب الحاجة ومقتضيات المصلحة العامة ، وتعد الحكومة صاحبة الولاية العامة على شؤون الدولة كافة ، ويُشكل مجلس الوزارء وفق الأسس الآتية :
                    - يختار الملك رئيس الوزراء ، ويكلفه رسميا بتشكيل الوزارة.
                    - يختار رئيس الوزارء الوزراء ، ويعرض أسماءهم على الملك لإصدار الإرادة الملكية السامية بتشكيل الحكومة.
                    - يؤدي أعضاء مجلس الوزراء اليمين الدستورية أمام جلالة الملك.
                    - يتقدم مجلس الوزراء ببيانه الوزاري إلى مجلس النواب خلال شهر من تشكيله للحصول على الثقة.
                  </p>
                </div>
              </v-col>
            </v-row>
          </v-card>
        </v-col>
        <v-col lg="4" style="padding: 6px;">
          <div>
            <h4 style="font-size: 27px; color: #535962; text-align: right;">ملفات المادة</h4>
          </div>
          <v-card
            style="height: 913px;box-shadow:0 2px 5px 0 rgba(0,0,0,.16),0 2px 10px 0 rgba(0,0,0,.12)!important; border-radius: 8px"
          >
            <v-card-title
              style="font-size:20px; color: #535962;text-align: center;padding: 24px;"
            >اختر الملفات التي تريد عرضها او تحميلها من ملفات المادة</v-card-title>
            <div class="my-2" style="display: flex;justify-content: center;border-radius: 10px;">
              <v-btn small color="primary" style="font-size: 15px">الملفات</v-btn>
            </div>

            <div style="display: flex;justify-content: center;margin-bottom: 30px;">
              <v-btn
                small
                outlined
                color="indigo"
                class="ma-1"
                style="border-radius: 10px;font-size:0.625rem"
              >حلول الكتاب</v-btn>
              <v-btn
                small
                outlined
                color="indigo"
                class="ma-1"
                style="border-radius: 10px;font-size:0.625rem"
              >امتحانات وملخصات</v-btn>
              <v-btn
                small
                outlined
                color="indigo"
                class="ma-1"
                style="border-radius: 10px;font-size:0.625rem"
              >دليل المعلم</v-btn>
            </div>
            <v-card
              v-for="n in 5"
              :key="n"
              style="height: 89.88px;margin: 16px;box-shadow:0 5px 11px 0 rgba(0,0,0,.18),0 4px 15px 0 rgba(0,0,0,.15)!important;border-radius: 10px;margin-bottom: 35px;"
            >
              <v-card-title>I'm a title</v-card-title>
              <v-card-text>I'm card text</v-card-text>
            </v-card>
          </v-card>
        </v-col>
      </v-row>
    </v-container>
  </div>
</template>
<script>
export default {
  
}
</script>
<style scoped>
.title-screen {
  font-size: 2.1875rem;
  color: #535962;
  text-align: center;
  margin-top: 40px;
  margin-bottom: 40px;
}

.main-content {
  margin-right: 256px;
}
.pBook {
  font-size: 0.8125rem;
  color: #7b7b7b;
  line-height: 2;
  margin: 8px;
}

.col-6-p {
  background-color: #e9e9e9;
  height: 791px;
  border-radius: 10px;
  margin-top: 16px;
  padding: 16px;
  overflow: auto;
}

@media screen and (min-width: 601px) {
  .main-content {
    margin-right: 256px;
  }
  .pBook {
    font-size: 0.8125rem;
  }
}

@media screen and (max-width: 600px) {
  .title-screen {
    font-size: 1.1875rem;
  }
  .main-content {
    margin-right: 0;
  }
  .pBook {
    font-size: 9px;
  }
}
</style>