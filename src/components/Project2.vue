<template>
  <div id="a">
    <div id="b"></div>
    <div id="c" v-for="row in project2" :key="row.id">{{ row.resume }}</div>
    <div id="d">
      <div id="e" v-for="row in project2" :key="row.id">
        <img
          id="f"
          src="https://i.pinimg.com/736x/3b/a2/c4/3ba2c46051c4fc2e7eb353f2eb1f08e4.jpg"
        />
        <h1 style="margin-left: 20px">
          {{ row.nama }}<br />
          {{ row.nama1 }}
        </h1>
      </div>
    </div>
    <div class="ab" v-for="row in project2" :key="row.id">
      <div class="bb">
        <h2>
          {{ row.profile }}
          <hr style="border: 1px dashed black" />
        </h2>
        <div class="cb">
          <p>
            <b>{{ row.profile1 }}</b
            ><br />
            {{ row.profile2 }}
          </p>
          <p>
            <b>{{ row.profile3 }}</b
            ><br />
            {{ row.profile4 }}
          </p>
          <p>
            <b>{{ row.profile5 }}</b
            ><br />
            {{ row.profile6 }} <br />
            {{ row.profile7 }} <br />
            {{ row.profile8 }} <br />
            {{ row.profile9 }}
          </p>
          <h2 style="font-family: courier new">
            {{ row.profile10 }}
            <hr style="border: 1px dashed black" />
          </h2>
          <p>
            <b>{{ row.profile11 }}</b
            ><br />
            {{ row.profile12 }}
          </p>
          <p>
            <b>{{ row.profile13 }}</b
            ><br />
            {{ row.profile14 }}
          </p>
          <h2 style="font-family: courier new">
            {{ row.profile15 }}
            <hr style="border: 1px dashed black" />
          </h2>
          <p>
            <b>{{ row.profile16 }}</b
            ><i class="fas fa-phone-square"></i><br />
            {{ row.profile17 }}
          </p>
          <p>
            <b>{{ row.profile18 }}</b
            ><i class="fas fa-phone-square-alt"></i><br />
            {{ row.profile19 }}
          </p>
          <p>
            <b>{{ row.profile20 }}</b
            ><i class="fas fa-envelope-square"></i><br />
            {{ row.profile21 }}
          </p>
          <h2 style="font-family: courier new">
            {{ row.profile22 }}
            <hr style="border: 1px dashed black" />
          </h2>
          <p>
            <b>{{ row.profile23 }}</b
            ><i class="fab fa-twitter-square"></i><br />
            {{ row.profile17 }}
          </p>
          <p>
            <b>{{ row.profile24 }}</b
            ><i class="fab fa-facebook-square"></i><br />
            {{ row.profile25 }}
          </p>
        </div>
      </div>
      <div class="db">
        <h2 style="font-family: courier new">
          {{ row.isi }}
          <hr color="black" />
        </h2>
        <div class="eb">
          <h2 style="margin-left: 20px; font-family: courier new">
            <i class="fas fa-briefcase"></i> {{ row.isi1 }}
          </h2>
          <hr
            style="
              border: 1px dashed black;
              margin-left: 20px;
              margin-right: 20px;
            "
          />
          <div style="display: flex; margin-left: 20px; margin-right: 20px">
            <p>
              <b>{{ row.isi2 }}</b
              ><br />{{ row.isi3 }}
            </p>
            <div style="margin-left: 60px">
              <p>
                <b>{{ row.isi4 }}</b
                ><br />{{ row.isi5 }}
              </p>
            </div>
          </div>
          <div style="display: flex; margin-left: 20px; margin-right: 20px">
            <p>
              <b>{{ row.isi2 }}</b
              ><br />{{ row.isi3 }}
            </p>
            <div style="margin-left: 60px">
              <p>
                <b>{{ row.isi4 }}</b
                ><br />{{ row.isi5 }}
              </p>
            </div>
          </div>
          <div style="display: flex; margin-left: 20px; margin-right: 20px">
            <p>
              <b>{{ row.isi2 }}</b
              ><br />{{ row.isi3 }}
            </p>
            <div style="margin-left: 60px">
              <p>
                <b>{{ row.isi4 }}</b
                ><br />{{ row.isi5 }}
              </p>
            </div>
          </div>
        </div>
        <div class="fb">
          <h2 style="margin-left: 20px; font-family: courier new">
            <i class="fas fa-book"></i> {{ row.isi6 }}
          </h2>
          <hr
            style="
              border: 1px dashed black;
              margin-left: 20px;
              margin-right: 20px;
            "
          />
          <div style="display: flex; margin-left: 20px; margin-right: 20px">
            <p>
              <b>{{ row.isi7 }}</b
              ><br />{{ row.isi8 }}
            </p>
            <div style="margin-left: 60px">
              <p>
                <b>{{ row.isi9 }}</b
                ><br />{{ row.isi10 }}
              </p>
            </div>
          </div>
          <div style="display: flex; margin-left: 20px; margin-right: 20px">
            <p>
              <b>{{ row.isi7 }}</b
              ><br />{{ row.isi8 }}
            </p>
            <div style="margin-left: 60px">
              <p>
                <b>{{ row.isi9 }}</b
                ><br />{{ row.isi10 }}
              </p>
            </div>
          </div>
          <div style="display: flex; margin-left: 20px; margin-right: 20px">
            <p>
              <b>{{ row.isi7 }}</b
              ><br />{{ row.isi8 }}
            </p>
            <div style="margin-left: 60px">
              <p>
                <b>{{ row.isi9 }}</b
                ><br />{{ row.isi10 }}
              </p>
            </div>
          </div>
        </div>
        <div class="fb">
          <h2 style="margin-left: 20px; font-family: courier new">
            <i class="fas fa-lightbulb"></i> SKILLS
          </h2>
          <hr
            style="
              border: 1px dashed black;
              margin-left: 20px;
              margin-right: 20px;
            "
          />
          <div style="display: flex; margin-left: 20px; margin-right: 20px">
            <p>
              <b>PROFESSIONAL SKILL</b><br />
              Microsoft Windows
              <font style="margin-left: 11px">
                <i class="fas fa-circle"></i><i class="fas fa-circle"></i
                ><i class="fas fa-circle"></i><i class="fas fa-circle"></i
                ><i class="fas fa-circle"></i><i class="far fa-circle"></i
                ><i class="far fa-circle"></i></font
              ><br />
              Windows
              <font style="margin-left: 82px">
                <i class="fas fa-circle"></i><i class="fas fa-circle"></i
                ><i class="fas fa-circle"></i><i class="fas fa-circle"></i
                ><i class="fas fa-circle"></i><i class="far fa-circle"></i
                ><i class="far fa-circle"></i></font
              ><br />
              Mac OSX
              <font style="margin-left: 83px">
                <i class="fas fa-circle"></i><i class="fas fa-circle"></i
                ><i class="fas fa-circle"></i><i class="fas fa-circle"></i
                ><i class="fas fa-circle"></i><i class="far fa-circle"></i
                ><i class="far fa-circle"></i></font
              ><br />
              Data Handling
              <font style="margin-left: 46px">
                <i class="fas fa-circle"></i><i class="fas fa-circle"></i
                ><i class="fas fa-circle"></i><i class="fas fa-circle"></i
                ><i class="fas fa-circle"></i><i class="far fa-circle"></i
                ><i class="far fa-circle"></i></font
              ><br />
              Record Keeping
              <font style="margin-left: 36px">
                <i class="fas fa-circle"></i><i class="fas fa-circle"></i
                ><i class="fas fa-circle"></i><i class="fas fa-circle"></i
                ><i class="fas fa-circle"></i><i class="far fa-circle"></i
                ><i class="far fa-circle"></i></font
              ><br />
              Web Skills
              <font style="margin-left: 76px">
                <i class="fas fa-circle"></i><i class="fas fa-circle"></i
                ><i class="fas fa-circle"></i
                ><i class="fas fa-circle"><i class="fas fa-circle"></i></i
                ><i class="far fa-circle"></i><i class="far fa-circle"></i
              ></font>
            </p>
            <div style="margin-left: 50px">
              <p>
                <b>PERSONAL SKILLS</b><br />
                Organisation
                <font style="margin-left: 35px">
                  <i class="fas fa-circle"></i><i class="fas fa-circle"></i
                  ><i class="fas fa-circle"></i><i class="fas fa-circle"></i
                  ><i class="fas fa-circle"></i><i class="far fa-circle"></i
                  ><i class="far fa-circle"></i></font
                ><br />
                Communication
                <font style="margin-left: 14px">
                  <i class="fas fa-circle"></i><i class="fas fa-circle"></i
                  ><i class="fas fa-circle"></i><i class="fas fa-circle"></i
                  ><i class="fas fa-circle"
                    ><i class="far fa-circle"></i
                    ><i class="far fa-circle"></i></i
                ></font>
                <br />
                Time Keeping
                <font style="margin-left: 30px">
                  <i class="fas fa-circle"></i><i class="fas fa-circle"></i
                  ><i class="fas fa-circle"></i><i class="fas fa-circle"></i
                  ><i class="fas fa-circle"></i><i class="far fa-circle"></i
                  ><i class="far fa-circle"></i></font
                ><br />
                Team Player
                <font style="margin-left: 42px">
                  <i class="fas fa-circle"></i><i class="fas fa-circle"></i
                  ><i class="fas fa-circle"></i><i class="fas fa-circle"></i
                  ><i class="fas fa-circle"></i><i class="far fa-circle"></i
                  ><i class="far fa-circle"></i></font
                ><br />
                Commitment
                <font style="margin-left: 33px">
                  <i class="fas fa-circle"></i><i class="fas fa-circle"></i
                  ><i class="fas fa-circle"></i><i class="fas fa-circle"></i
                  ><i class="fas fa-circle"></i><i class="far fa-circle"></i
                  ><i class="far fa-circle"></i></font
                ><br />
                Multitasking
                <font style="margin-left: 39px">
                  <i class="fas fa-circle"></i><i class="fas fa-circle"></i
                  ><i class="fas fa-circle"></i><i class="fas fa-circle"></i
                  ><i class="fas fa-circle"></i><i class="far fa-circle"></i
                  ><i class="far fa-circle"></i
                ></font>
              </p>
            </div>
          </div>
        </div>
      </div>
    </div>
    <br /><br />
    <div class="ah"></div>
  </div>
</template>
<script>
/* eslint-disable */
import axios from "axios";
export default {
  data() {
    return {
      project2: [],
    };
  },
  mounted() {
    this.load();
  },
  methods: {
    load() {
      axios
        .get("http://localhost:3000/prject2")
        .then((res) => {
          this.project2 = res.data;
        })
        .catch((err) => {
          console.log(err);
        });
    },
  },
  name: "Project2",
  computed: {
    Project2() {
      return this.$store.state.project2;
    },
  },
};
</script>
<style>
#a {
  width: 950px;
  font-family: "Courier New", Courier, monospace;
  background-color: white;
  margin-left: 220px;
}
#b {
  background-color: darkslateblue;
  height: 40px;
}
#c {
  background-color: darkslateblue;
  height: 2px;
  margin-left: 50px;
  width: 130px;
  font-family: "Courier New", Courier, monospace;
  color: white;
  font-size: 20px;
  text-align: center;
  padding-bottom: 20px;
}
#d {
  background-color: darkslateblue;
  height: 150px;
  font-family: "Courier New", Courier, monospace;
  color: white;
}
#e {
  padding-top: 30px;
  display: flex;
}
#f {
  width: 200px;
  height: 200px;
  display: flex;
  border-radius: 100%;
  margin-left: 20px;
}
.ab {
  display: flex;
}
.bb {
  text-align: right;
  width: 250px;
  padding-left: 15px;
  padding-right: 15px;
  padding-top: 65px;
}
.cb {
  text-align: right;
  font-family: "Segoe UI", Tahoma, Geneva, Verdana, sans-serif;
}
.db {
  width: auto;
  padding-left: 10px;
  padding-right: 10px;
  font-family: "Segoe UI", Tahoma, Geneva, Verdana, sans-serif;
}
.eb {
  background-color: rgb(212, 209, 209);
  padding-top: 1px;
  padding-bottom: 2px;
}
.fb {
  background-color: rgb(212, 209, 209);
  margin-top: 20px;
  padding-top: 1px;
  padding-bottom: 2px;
}
.ah {
  background-color: darkslateblue;
  height: 40px;
}
</style>