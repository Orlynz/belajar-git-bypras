<template>
  <div class="a">
    <div style="background-color: silver" v-for="row in project1" :key="row.id">
      <div class="c" style="padding-top: 30px">
        <h1 style="text-align: left">
          {{ row.nama }}<br />
          <font style="color: tomato">{{ row.nama1 }}</font>
        </h1>
      </div>
      <div class="b">
        <img
          src="https://images3.alphacoders.com/704/704387.png"
          width="310px"
        />
      </div>
      <div class="c">
        <h2>
          {{ row.data }}
          <hr color="black" size="1" />
        </h2>
        <p>
          <b>{{ row.data1 }}</b
          ><br />{{ row.data2 }}<br />{{ row.data3 }}
        </p>
        <p>
          <b>{{ row.data4 }}</b
          ><br />{{ row.data5 }}
        </p>
        <p>
          <b>{{ row.data6 }}</b
          ><br /><u>{{ row.data7 }}</u>
        </p>
        <P
          ><b>{{ row.data8 }}</b
          ><br /><u>{{ row.data9 }}</u></P
        >
        <h2>
          {{ row.datae }}
          <hr color="black" size="1" />
        </h2>
        <p>{{ row.datae1 }}<br />{{ row.datae2 }}<br />{{ row.datae3 }}</p>
        <h2>
          {{ row.hobi }}
          <hr color="black" size="1" />
        </h2>
        <ul>
          <li>{{ row.hobi1 }}</li>
          <li>{{ row.hobi2 }}</li>
          <li>{{ row.hobi3 }}</li>
        </ul>
      </div>
    </div>
    <div class="d" v-for="row in project1" :key="row.id">
      <h2>
        {{ row.judul }}
        <hr />
      </h2>
      <p>
        {{ row.isi }}
      </p>
      <h2>
        {{ row.judul1 }}
        <hr />
      </h2>
      <ul>
        <div style="display: flex">
          <div>
            <li>{{ row.list }}</li>
            <li>{{ row.list1 }}</li>
            <li>{{ row.list2 }}</li>
          </div>
          <div style="margin-left: 60px">
            <li>{{ row.list3 }}</li>
            <li>{{ row.list4 }}</li>
            <li>{{ row.list5 }}</li>
          </div>
        </div>
      </ul>
      <h2>
        {{ row.judul2 }}
        <hr />
      </h2>
      <p>
        <b>{{ row.web }}</b
        >{{ row.web1 }}<br /><b>{{ row.web2 }}</b>
        {{ row.web3 }}
      </p>
      <ul>
        <li>
          {{ row.web4 }}
        </li>
        <li>{{ row.web5 }}</li>
        <li>
          {{ row.web6 }}
        </li>
        <li>{{ row.web7 }}.</li>
        <li>
          {{ row.web8 }}
        </li>
      </ul>
      <h2>
        {{ row.judul3 }}
        <hr />
      </h2>
      <p>
        {{ row.issi }}<b>{{ row.issi1 }}</b
        >{{ row.issi2 }} <b>{{ row.issi3 }}</b
        >{{ row.issi4 }}
      </p>
      <h2>
        {{ row.judul4 }}
        <hr />
      </h2>
      <p>
        {{ row.eve }}<b>{{ row.eve1 }}</b
        >.
        {{ row.eve2 }}
        <b>{{ row.eve3 }}</b
        >.
      </p>
    </div>
  </div>
</template>
<script>
/* eslint-disable */
import axios from "axios";
export default {
  data() {
    return {
      project1: [],
    };
  },
  mounted() {
    this.load();
  },
  methods: {
    load() {
      axios
        .get("http://localhost:3000/project1")
        .then((res) => {
          this.project1 = res.data;
        })
        .catch((err) => {
          console.log(err);
        });
    },
  },
  name: "Project1",
  computed: {
    Project1() {
      return this.$store.state.project1;
    },
  },
};
</script>
<style>
body {
  background-color: gray;
  padding-top: 30px;
  padding-bottom: 30px;
}
.a {
  font-family: "Segoe UI", Tahoma, Geneva, Verdana, sans-serif;
  display: flex;
  margin-left: 300px;
}
.b {
  text-align: center;
}
.c {
  text-align: left;
  background-color: silver;
  padding-left: 34px;
  padding-right: 34px;
}
.d {
  width: 450px;
  background-color: white;
  padding-left: 15px;
  padding-right: 15px;
  padding-top: 30px;
  padding-bottom: 100px;
}
</style>