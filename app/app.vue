<template>
  <div>
    <div id="first-section">
      <h1>
        Hello world!
      </h1>
      <firstcomp />
    </div>
    <div id="second-section">
      <nav>
        <ul>
          <li><NuxtLink to="/firstpage">First Page</NuxtLink></li>
          <li><NuxtLink to="/secondpage">Second Page</NuxtLink></li>
        </ul>
      </nav>
    </div>
    <div>
      <NuxtPage />
    </div>
  </div>
</template>

<style>
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin-right: 10px;
  height: 50px;
  width: 120px;
  background-color: azure;
  line-height: 50px;
  border-radius: 20px;
  text-align: center;
}
a {
  text-decoration: none;
  color: black;
}
</style>
