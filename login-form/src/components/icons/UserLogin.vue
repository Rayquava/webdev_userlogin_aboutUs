<script>
  export default {
    name: 'UserLogin',
    data() {
      return {
        username: '',
        password: '',
        rememberMe: false,
      };
    },
    methods: {
      handleSubmit() {
        // Handle form submission logic here
        console.log('Username:', this.username);
        console.log('Password:', this.password);
        console.log('Remember Me:', this.rememberMe);
      },
    },
  };
  </script>

<template>
    <div class="login-container">
      <h1>LOGIN</h1>
      <form @submit.prevent="handleSubmit">
        <div class="input-group">
          <input 
            v-model="username" 
            type="text" 
            placeholder="USERNAME" 
            required
          >
          <span class="icon">&#128100;</span>
        </div>
        <div class="input-group">
          <input 
            v-model="password" 
            type="password" 
            placeholder="PASSWORD" 
            required
          >
          <span class="icon">&#128274;</span>
        </div>
        <div class="options">
          <label>
            <input type="checkbox" v-model="rememberMe"> REMEMBER ME
          </label>
          <a href="#">FORGOT PASSWORD?</a>
        </div>
        <button type="submit">LOGIN</button>
        <p class="register-text">
          DOESN'T HAVE ANY ACCOUNT? <a href="#">REGISTER</a>
        </p>
      </form>
    </div>
  </template>
  
  <style scoped>
  body {
    font-family: 'Arial', sans-serif;
    background-color: #f9f9f9;
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
    margin: 0;
  }
  
  .login-container {
    background: #ffffff;
    width: 400px;
    padding: 50px;
    border-radius: 34px;
    box-shadow: 0 4px 10px rgba(0, 0, 0, 0.2);
    text-align: center;
  }
  
  h1 {
    font-size: 24px;
    margin-bottom: 20px;
    font-family: 'Comic Sans MS', cursive, sans-serif;
  }
  
  .input-group {
    position: relative;
    margin-bottom: 20px;
  }
  
  .input-group input {
    width: 100%;
    padding: 12px 0px 12px 12px;
    border: 1px solid #000000;
    border-radius: 8px;
    font-size: 16px;
  }
  
  .input-group .icon {
    position: absolute;
    right: 10px;
    top: 50%;
    transform: translateY(-50%);
    font-size: 18px;
    color: #000000;
  }
  
  .options {
    display: flex;
    justify-content: space-between;
    margin-bottom: 20px;
    font-size: 14px;
  }
  
  .options label {
    cursor: pointer;
  }
  
  .options a {
    font-weight: bold;
    text-decoration: none;
    color: #4CAF50;
  }
  
  .options a:hover {
    text-decoration: underline;
  }
  
  button {
    background-color: #4CAF50;
    color: white;
    font-size: 16px;
    padding: 12px;
    width: 100%;
    border: none;
    border-radius: 8px;
    cursor: pointer;
    transition: background-color 0.3s ease;
  }
  
  button:hover {
    background-color: #634d4d;
  }
  
  .register-text {
    margin-top: 15px;
    font-size: 14px;
  }
  
  .register-text a {
    color: #4CAF50;
    text-decoration: none;
    font-weight: bold;
  }
  
  .register-text a:hover {
    text-decoration: underline;
  }
  </style>
  