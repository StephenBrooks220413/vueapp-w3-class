<template>
  <div class="w3-container">
    <div class="w3-animate-zoom">
      <h1 class="w3-container w3-center">{{ msg }}</h1>
      <p class="w3-sans-serif w3-text-blue">
        This App also uses
        <a href="https://www.w3schools.com/w3css/default.asp" target="_blank"
          >w3schools</a
        >
        and
        <a href="https://mdbootstrap.com/docs/standard/" target="_blank"
          >MDB5</a
        >
        styles for layouts instead of the traditional Material-UI or TailWind
        Css
      </p>
    </div>
    <br /><br />
    <div class="w3-container">
      <div class="row">
        <div class="col-md hover-shadow">
          <br />
          <i class="fas icon fa-headset"></i>
          <p class="lead">Ongoing Support For Our Members</p>
        </div>
        <div class="col-md hover-shadow">
          <br />
          <i class="far icon fa-file-code"></i>
          <p class="lead">Best Code Practices In Our Apps</p>
        </div>
        <div class="col-md hover-shadow">
          <br />
          <i class="fab icon fa-internet-explorer"></i>
          <p class="lead">Generated Site Maps for Best SEO</p>
        </div>
        <div class="col-md hover-shadow">
          <br />
          <i class="fab icon fa-vuejs"></i>
          <p class="lead">Light & Fast JavaScript Framework</p>
        </div>
      </div>
    </div>
    <br /><br />
    <div class="row mt-5 mb-5">
      <div
        data-mdb-toggle="animation"
        data-mdb-animation-start="onScroll"
        data-mdb-animation-on-scroll="repeat"
        data-mdb-animation="slide-in-left"
        class="col-md m t-5">
        <img
          src="https://images.unsplash.com/photo-1502945015378-0e284ca1a5be?ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&ixlib=rb-1.2.1&auto=format&fit=crop&w=1350&q=80"
          class="img-fluid"
          alt=""
        />
      </div>
      <div
        data-mdb-toggle="animation"
        data-mdb-animation-start="onScroll"
        data-mdb-animation-on-scroll="repeat"
        data-mdb-animation="slide-in-right"
        class="col-md mt-5">
        <h1 class="display-4">Title</h1>
        Lorem ipsum dolor sit, amet consectetur adipisicing elit. Vitae iste
        repellendus cum adipisci reiciendis animi ea alias saepe dolor, dolore
        dolorem aliquid recusandae doloremque vel quia consectetur sit a dicta?
        <br />
        <button class="btn btn-outline-dark btn-lg">MORE INFO</button>
      </div>
    </div>
    <br /><br />
    <div class="max-content">
      <form name="subsrcibe" netlify class="w3-container text-center">
        <h1 class="display-4">Subscribe</h1>
        <label class="w3-text-blackblue"><b>First & Last Name</b></label>
        <input name="name" class="w3-input w3-border" type="text" />

        <label class="w3-text-black"><b>Your E-Mail</b></label>
        <input name="email" class="w3-input w3-border" type="text" />
        <br />
        <button type="submit" class="w3-btn w3-black">Register</button>
      </form>
    </div>
    <br />
    <div class="row mt-5 mb-5">
      <div
        data-mdb-toggle="animation"
        data-mdb-animation-start="onScroll"
        data-mdb-animation-on-scroll="repeat"
        data-mdb-animation="slide-in-left"
        class="col-md mt-5">
        <h1 class="display-4">Title</h1>
        Lorem ipsum dolor sit, amet consectetur adipisicing elit. Vitae iste
        repellendus cum adipisci reiciendis animi ea alias saepe dolor, dolore
        dolorem aliquid recusandae doloremque vel quia consectetur sit a dicta?
        <br />
        <button class="btn btn-outline-dark btn-lg">MORE INFO</button>
      </div>
      <div
        data-mdb-toggle="animation"
        data-mdb-animation-start="onScroll"
        data-mdb-animation-on-scroll="repeat"
        data-mdb-animation="slide-in-left"
        class="col-md m t-5">
        <br />
        <img
          src="https://images.unsplash.com/photo-1502945015378-0e284ca1a5be?ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&ixlib=rb-1.2.1&auto=format&fit=crop&w=1350&q=80"
          class="img-fluid w3-animate-right"
          alt=""
        />
      </div>
    </div>
  </div>
</template>

<script lang="ts">
import { Options, Vue } from "vue-class-component";

@Options({
  props: {
    msg: String,
  },
})
export default class HelloWorld extends Vue {
  msg!: string;
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
.icon {
  font-size: 2.7em;
}
</style>
