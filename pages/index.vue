<script>
import { mdiServer } from '@mdi/js';
import { mdiApi, mdiDatabase, mdiGraphql, mdiJquery, mdiLanguageCsharp, mdiLanguageHtml5, mdiNuxt, mdiVuejs, mdiVuetify } from '@mdi/js';

import svgBootstrap from '~/assets/icons/bootstrap.svg';
import svgCSharp from '~/assets/icons/c-sharp.svg';
import svgCss from '~/assets/icons/css-3.svg';
import svgEsLint from '~/assets/icons/eslint.svg';
import svgGraphQl from '~/assets/icons/graphql.svg';
import svgHtml from '~/assets/icons/html-5.svg';
import svgJava from '~/assets/icons/java.svg';
import svgJavaScript from '~/assets/icons/javascript.svg';
import svgJquery from '~/assets/icons/jquery.svg';
import svgNuxt from '~/assets/icons/nuxt.svg';
import svgOracle from '~/assets/icons/oracle.svg';
import svgPostgreSql from '~/assets/icons/postgresql.svg';
import svgSqlServer from '~/assets/icons/sqlserver.svg';
import svgStyleLint from '~/assets/icons/stylelint.svg';
import svgVue from '~/assets/icons/vue.svg';
import svgVuetify from '~/assets/icons/vuetify.svg';
import svgWebpack from '~/assets/icons/webpack.svg';
import svgXamarin from '~/assets/icons/xamarin.svg';
export default {
  components: {
    svgBootstrap,
    svgCSharp,
    svgCss,
    svgEsLint,
    svgGraphQl,
    svgHtml,
    svgJava,
    svgJavaScript,
    svgJquery,
    svgNuxt,
    svgOracle,
    svgPostgreSql,
    svgSqlServer,
    svgStyleLint,
    svgVue,
    svgVuetify,
    svgWebpack,
    svgXamarin,
  },
  data() {
    return {
      skills: [
        { title: 'C#', description: '', icon: mdiLanguageCsharp, color: '' },
        { title: 'REST', description: '', icon: mdiApi, color: '' },
        { title: 'GraphQL', description: '', icon: mdiGraphql, color: '' },
        { title: 'HTML5', description: '', icon: mdiLanguageHtml5, color: '' },
        { title: 'jQuery', description: '', icon: mdiJquery, color: '' },
        { title: 'Vue.js', description: '', icon: mdiVuejs, color: '' },
        { title: 'Vuetify', description: '', icon: mdiVuetify, color: '' },
        { title: 'Nuxt.js', description: '', icon: mdiNuxt, color: '' },
        { title: 'SQL Server', description: '', icon: mdiDatabase, color: '' },
        { title: 'Oracle', description: '', icon: mdiDatabase, color: '' },
        { title: 'Postgre SQL', description: '', icon: mdiDatabase, color: '' },
      ],
      technologies: [
        {
          icon: mdiServer,
          name: '言語',
          skills: [
            { name: 'HTML, CSS, JavaScript', rating: 5 },
            { name: 'C#, VB.NET', rating: 5 },
            { name: 'VB, VBA', rating: 5 },
          ],
        },
        {
          icon: mdiServer,
          name: 'Web',
          skills: [
            { name: 'GraphQL', rating: 4 },
            { name: 'jQuery', rating: 5 },
            { name: 'REST', rating: 4 },
            { name: 'Vue.js, Nuxt.js, Vuetify', rating: 4 },
          ],
        },
        {
          icon: mdiServer,
          name: 'Desktop',
          skills: [
            { name: 'WinForms', rating: 4 },
            { name: 'WPF', rating: 5 },
          ],
        },
        {
          icon: mdiServer,
          name: 'Mobile',
          skills: [{ name: 'Xamarin', rating: 4 }],
        },
        {
          icon: mdiServer,
          name: '資格',
          skills: [
            { name: '応用情報技術者', rating: 5 },
            { name: '情報セキュリティスペシャリスト', rating: 5 },
            { name: 'ネットワークスペシャリスト', rating: 5 },
          ],
        },

        {
          icon: mdiServer,
          name: 'フロントエンド',
          skills: [
            { name: 'HTML/CSS/SCSS', rating: 5 },
            { name: 'JavaScript/jQuery', rating: 5 },
            { name: 'Vue.js/Nuxt.js', rating: 4 },
          ],
        },
        {
          icon: mdiServer,
          name: 'バックエンド',
          skills: [
            { name: 'Classic ASP', rating: 5 },
            { name: 'ASP.NET WebForms', rating: 5 },
            { name: 'ASP.NET MVC5', rating: 5 },
            { name: 'ASP.NET Core', rating: 4 },
          ],
        },
        {
          icon: mdiServer,
          name: 'データベース',
          skills: [
            { name: 'SQL Server', rating: 5 },
            { name: 'Oracle', rating: 5 },
            { name: 'Postgre SQL', rating: 3 },
          ],
        },
      ],
    };
  },
};
</script>

<template>
  <v-app>
    <header>
      <div class="area">
        <ul class="circles">
          <li />
          <li />
          <li />
          <li />
          <li />
          <li />
          <li />
          <li />
          <li />
          <li />
        </ul>
      </div>
      <section>
        <v-container>
          <v-row justify="center">
            <v-col cols="auto">
              <v-avatar size="96">
                <v-img src="avatar.jpg" />
              </v-avatar>
            </v-col>
          </v-row>
          <v-row justify="center">
            <v-col cols="auto">
              <h1>
                Yuichiro Tada's Portfolio
              </h1>
            </v-col>
          </v-row>
        </v-container>
      </section>
    </header>
    <v-main>
      <section>
        <v-container>
          <v-row justify="center">
            <v-col cols="auto">
              <h2>
                About
              </h2>
            </v-col>
          </v-row>
          <v-row justify="center">
            <v-col cols="auto">
              <v-skeleton-loader type="paragraph" width="480" />
              <v-skeleton-loader type="paragraph" width="480" />
              <v-skeleton-loader type="paragraph" width="480" />
            </v-col>
          </v-row>
        </v-container>
      </section>
      <section style="background-color: rgba(0, 0, 0, 0.04);">
        <v-container>
          <v-row justify="center">
            <v-col cols="auto">
              <h2>
                Works
              </h2>
            </v-col>
          </v-row>
          <v-row justify="center">
            <v-col cols="auto">
              <v-skeleton-loader type="card" width="320" />
            </v-col>
          </v-row>
        </v-container>
      </section>
      <section>
        <v-container>
          <v-row justify="center">
            <v-col cols="auto">
              <h2>
                Skills
              </h2>
            </v-col>
          </v-row>
          <v-row justify="center">
            <v-col cols="auto">
              <h4>
                Front-end
              </h4>
            </v-col>
          </v-row>
          <v-row dense justify="center">
            <app-skill-card name="HTML" :rating="5" remarks="xxxx">
              <svg-html />
            </app-skill-card>
            <app-skill-card name="CSS" :rating="5" remarks="xxxx">
              <svg-css />
            </app-skill-card>
            <app-skill-card name="JavaScript" :rating="5" remarks="xxxx">
              <svg-java-script />
            </app-skill-card>
            <app-skill-card name="jQuery" :rating="5" remarks="xxxx">
              <svg-jquery />
            </app-skill-card>
            <app-skill-card name="Vue.js" :rating="4" remarks="xxxx">
              <svg-vue />
            </app-skill-card>
            <app-skill-card name="Nuxt.js" :rating="4" remarks="xxxx">
              <svg-nuxt />
            </app-skill-card>
            <app-skill-card name="Bootstrap" :rating="5" remarks="xxxx">
              <svg-bootstrap />
            </app-skill-card>
            <app-skill-card name="Vuetify.js" :rating="4" remarks="xxxx">
              <svg-vuetify />
            </app-skill-card>
            <app-skill-card name="ESLint" :rating="4" remarks="xxxx">
              <svg-es-lint />
            </app-skill-card>
            <app-skill-card name="stylelint" :rating="4" remarks="xxxx">
              <svg-style-lint />
            </app-skill-card>
            <app-skill-card name="webpack" :rating="4" remarks="xxxx">
              <svg-webpack />
            </app-skill-card>
          </v-row>
          <v-row justify="center">
            <v-col cols="auto">
              <h4>
                Back-end
              </h4>
            </v-col>
          </v-row>
          <v-row justify="center">
            <v-col cols="auto">
              <h4>
                Desktop
              </h4>
            </v-col>
          </v-row>
          <v-row justify="center">
            <v-col cols="auto">
              <h4>
                Mobile
              </h4>
            </v-col>
          </v-row>
          <v-row justify="center">
            <v-col cols="auto">
              <h4>
                Database
              </h4>
            </v-col>
          </v-row>
        </v-container>
      </section>

      <v-container>
        <h3>
          Back-end
        </h3>
        <v-row dense>
          <v-col cols="12" md="4" sm="6">
            <app-skill-card>
              <template v-slot:name>
                WebForms
              </template>
              <template v-slot:tips>
                WebForms, ASP.NET 5, ASP.NET Core による Web アプリ、API サービスを開発します。
              </template>
              <template v-slot:icon>
                <svg-c-sharp />
                <v-rating dense readonly :value="5" x-small />
              </template>
            </app-skill-card>
          </v-col>
          <v-col cols="12" md="4" sm="6">
            <app-skill-card>
              <template v-slot:name>
                ASP.NET 5
              </template>
              <template v-slot:tips>
                WebForms, ASP.NET 5, ASP.NET Core による Web アプリ、API サービスを開発します。
              </template>
              <template v-slot:icon>
                <svg-c-sharp />
                <v-rating dense readonly :value="5" x-small />
              </template>
            </app-skill-card>
          </v-col>
          <v-col cols="12" md="4" sm="6">
            <app-skill-card>
              <template v-slot:name>
                ASP.NET Core
              </template>
              <template v-slot:tips>
                WebForms, ASP.NET 5, ASP.NET Core による Web アプリ、API サービスを開発します。
              </template>
              <template v-slot:icon>
                <svg-c-sharp />
                <v-rating dense readonly :value="5" x-small />
              </template>
            </app-skill-card>
          </v-col>
          <v-col cols="12" md="4" sm="6">
            <app-skill-card>
              <template v-slot:name>
                GraphQL
              </template>
              <template v-slot:tips>
                GraphQL による API サービスを開発します。
              </template>
              <template v-slot:icon>
                <svg-graph-ql />
                <v-rating dense readonly :value="3" x-small />
              </template>
            </app-skill-card>
          </v-col>
        </v-row>

        <h3>
          Desktop
        </h3>
        <v-row dense>
          <v-col cols="12" md="4" sm="6">
            <app-skill-card>
              <template v-slot:name>
                WinForms
              </template>
              <template v-slot:tips>
                WinForms, WPF による Windows プラットフォーム向けのアプリを開発します。
              </template>
              <template v-slot:icon>
                <svg-c-sharp />
                <v-rating dense readonly :value="5" x-small />
              </template>
            </app-skill-card>
          </v-col>
          <v-col cols="12" md="4" sm="6">
            <app-skill-card>
              <template v-slot:name>
                WPF
              </template>
              <template v-slot:tips>
                WinForms, WPF による Windows プラットフォーム向けのアプリを開発します。
              </template>
              <template v-slot:icon>
                <svg-c-sharp />
                <v-rating dense readonly :value="5" x-small />
              </template>
            </app-skill-card>
          </v-col>
        </v-row>

        <h3>
          Mobile
        </h3>
        <v-row dense>
          <v-col cols="12" md="4" sm="6">
            <app-skill-card>
              <template v-slot:name>
                Xamarin
              </template>
              <template v-slot:tips>
                Xamarin.Forms による Android, iOS プラットフォーム向けのアプリを開発します。
              </template>
              <template v-slot:icon>
                <svg-xamarin />
                <v-rating dense readonly :value="4" x-small />
              </template>
            </app-skill-card>
          </v-col>
        </v-row>

        <h3>
          Database
        </h3>
        <v-row dense>
          <v-col cols="12" md="4" sm="6">
            <app-skill-card>
              <template v-slot:name>
                SQL Server
              </template>
              <template v-slot:tips>
                Supports Console, WinForms, WPF, WebForm, ASP.NET 5, ASP.NET Core, Xamarin
              </template>
              <template v-slot:icon>
                <svg-sql-server />
                <v-rating dense readonly :value="5" x-small />
              </template>
            </app-skill-card>
          </v-col>
          <v-col cols="12" md="4" sm="6">
            <app-skill-card>
              <template v-slot:name>
                Oracle
              </template>
              <template v-slot:tips>
                Supports Console, WinForms, WPF, WebForm, ASP.NET 5, ASP.NET Core, Xamarin
              </template>
              <template v-slot:icon>
                <svg-oracle />
                <v-rating dense readonly :value="4" x-small />
              </template>
            </app-skill-card>
          </v-col>
          <v-col cols="12" md="4" sm="6">
            <app-skill-card>
              <template v-slot:name>
                PostgreSQL
              </template>
              <template v-slot:tips>
                Supports Console, WinForms, WPF, WebForm, ASP.NET 5, ASP.NET Core, Xamarin
              </template>
              <template v-slot:icon>
                <svg-postgre-sql />
                <v-rating dense readonly :value="3" x-small />
              </template>
            </app-skill-card>
          </v-col>
        </v-row>
      </v-container>
    </v-main>
    <v-footer color="#424242" dark>
      xxx
    </v-footer>
  </v-app>
</template>

<style lang="scss" scoped>
h1,
h2,
h3 {
  font-family: 'Exo 2', sans-serif;
}

header ::v-deep {
  background: #4e54c8;
  position: relative;

  h1 {
    color: #fff;
  }

  .circles li {
    animation: animate 25s linear infinite;
    background: rgba(255, 255, 255, 0.2);
    bottom: -150px;
    display: block;
    height: 20px;
    list-style: none;
    position: absolute;
    width: 20px;
  }

  .circles li:nth-child(1) {
    animation-delay: 0s;
    height: 80px;
    left: 25%;
    width: 80px;
  }

  .circles li:nth-child(2) {
    animation-delay: 2s;
    animation-duration: 12s;
    height: 20px;
    left: 10%;
    width: 20px;
  }

  .circles li:nth-child(3) {
    animation-delay: 4s;
    height: 20px;
    left: 70%;
    width: 20px;
  }

  .circles li:nth-child(4) {
    animation-delay: 0s;
    animation-duration: 18s;
    height: 60px;
    left: 40%;
    width: 60px;
  }

  .circles li:nth-child(5) {
    animation-delay: 0s;
    height: 20px;
    left: 65%;
    width: 20px;
  }

  .circles li:nth-child(6) {
    animation-delay: 3s;
    height: 110px;
    left: 75%;
    width: 110px;
  }

  .circles li:nth-child(7) {
    animation-delay: 7s;
    height: 150px;
    left: 35%;
    width: 150px;
  }

  .circles li:nth-child(8) {
    animation-delay: 15s;
    animation-duration: 45s;
    height: 25px;
    left: 50%;
    width: 25px;
  }

  .circles li:nth-child(9) {
    animation-delay: 2s;
    animation-duration: 35s;
    height: 15px;
    left: 20%;
    width: 15px;
  }

  .circles li:nth-child(10) {
    animation-delay: 0s;
    animation-duration: 11s;
    height: 150px;
    left: 85%;
    width: 150px;
  }

  @keyframes animate {
    0% {
      border-radius: 0;
      opacity: 1;
      transform: translateY(0) rotate(0deg);
    }

    100% {
      border-radius: 50%;
      opacity: 0;
      transform: translateY(-1000px) rotate(720deg);
    }
  }
}

section ::v-deep {
  padding: 24px 0;
}
</style>
