<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <p>
      I have spent more than 2 decades in various senior positions in the IT
      industry in South Africa, Australia and the USA. I have had broad
      management, consulting, sales, and technical experience in this time with
      global companies such as Nampak, Microsoft and VMware in a leadership
      position. From the data center to the cloud, containers, automation and
      infrastructure as code, I have tried to keep my experience varied and
      customer centric, to the constant changes in our world. I have had
      extensive and incredibly varied experience in my career, and thrive as a
      “motivated, passionate and results driven individual”, who loves his
      customer and always does the right thing.
    </p>
    <h3>Career Summary</h3>
    <ul>
      <li>USA</li>
      <li>
        - 2021-Present: Manager, Tanzu Customer Success West US @ VMware
        <p></p>
        - 2020-Present: Tanzu Customer Success Manager – West @ VMware
        <p></p>
        - 2014-2020: Staff TAM, Team Lead, CTO Ambassador @ VMware
      </li>
    </ul>
    <h3>Professional Media</h3>
    <ul>
      <li>
        <a
          href="https://vmw.mynewsletter.club/vmwnews"
          target="_blank"
          rel="noopener"
          >Newsletter</a
        >
      </li>
      <li>
        <a href="https://github.com/neiliss" target="_blank" rel="noopener"
          >Github</a
        >
      </li>
      <li>
        <a href="https://twitter.com/neiliss" target="_blank" rel="noopener"
          >Twitter</a
        >
      </li>
    </ul>
  </div>
</template>

<script>
export default {
  name: "HelloWorld",
  props: {
    msg: String,
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
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
</style>
