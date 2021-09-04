<template>
<img class="logo" src="../assets/resto.png" />
 <h1>Sign Up</h1>
 <div class="register">
    <input type="text" placeholder="Enter your name" />
    <input type="text" placeholder="Enter your email" />
    <input type="password" placeholder="Enter your password" />
    <button>Sign Up</button>

  </div>
</template>

<script>
export default{
    name: 'SignUp'
}
</script>

<style>
.logo{
    width:150px;
}
.register input{
    width: 300px;
    height: 20px;
    padding: 10px;
    display: block;
    margin-bottom: 30px;
    margin-left: auto;
    margin-right: auto;
    border: 1px solid skyblue;
}
.register button{
    width: 300px;
    height: 30px;
    border: 1px solid skyblue;
    background-color: skyblue;
}
</style>
    
