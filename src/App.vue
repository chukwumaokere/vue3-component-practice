<template>
  <div class="container">
    <img src="./assets/logo.png" />
    <br /><br />
    <br /><br />
    <div>
      <Button
        text="Home"
        className="btn btn-red text-color-white"
        type="button"
      />
      <Button
        text="Profile"
        className="btn btn-green text-color-white"
        type="button"
      />
      <Button
        text="Subscriptions"
        className="btn btn-blue text-color-white"
        type="button"
      />
      <Button
        text="Log In"
        className="btn btn-gold text-color-black"
        type="button"
        disabled="true"
      />
    </div>
    <br /><br />
    <Input placeholder="Search..." />
  </div>
  <Footer text="Created by Chuck!" />
</template>

<script>
import Button from "./components/Button";
import Input from "./components/Input";
import Footer from "./components/Footer";

export default {
  components: {
    Button,
    Input,
    Footer,
  },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
.container {
  width: 80%;
  margin: 0 auto;
}
body {
  background-color: #ececec;
}
</style>
