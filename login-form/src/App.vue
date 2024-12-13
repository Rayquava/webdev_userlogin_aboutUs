<script>
import AboutUs from "./components/icons/AboutUs.vue";
import UserLogin from "./components/icons/UserLogin.vue";

export default {
  name: "App",
  components: {
    AboutUs,
  },
};
</script>

<template>
  <div id="app">
    <AboutUs />
  </div>
</template>

<style>
/* Reset CSS (optional, for consistent styling across browsers) */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

/* Global font and colors */
body {
  font-family: Arial, sans-serif;
  background-color: #f4f4f4;
  color: #333;
  line-height: 1.6;
}

a {
  text-decoration: none;
  color: inherit;
  transition: color 0.3s ease-in-out;
}

a:hover {
  color: #007bff;
}

/* Reusable container style */
.container {
  width: 90%;
  max-width: 1200px;
  margin: 0 auto;
  padding: 20px;
  background-color: #fff;
  border-radius: 5px;
  box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
}

/* Navbar styles */
.navbar {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 20px 50px;
  background-color: #333;
  color: #fff;
}

.navbar .logo {
  font-size: 24px;
  font-weight: bold;
}

.navbar nav {
  display: flex;
  align-items: center;
  gap: 20px;
}

.navbar nav a {
  color: #fff;
  padding: 5px 10px;
  border-radius: 3px;
}

.navbar nav a:hover {
  background-color: rgba(255, 255, 255, 0.1);
}

/* Button styles */
button {
  padding: 10px 20px;
  border: none;
  border-radius: 5px;
  background-color: #007bff;
  color: #fff;
  font-size: 16px;
  cursor: pointer;
  transition: background-color 0.3s ease-in-out;
}

button:hover {
  background-color: #0056b3;
}

/* Utility classes */
.text-center {
  text-align: center;
}

.mt-20 {
  margin-top: 20px;
}

.mb-20 {
  margin-bottom: 20px;
}

/* Responsive design */
@media (max-width: 768px) {
  .navbar {
    flex-direction: column;
    text-align: center;
  }

  .container {
    width: 95%;
  }
}
</style>
