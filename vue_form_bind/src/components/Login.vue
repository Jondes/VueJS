<template>
<div>
    <input type="text" v-model="loginForm.username" placeholder="enter username" /><br><br>
    <input type="text" v-model="loginForm.password" placeholder="enter password" /><br><br>
    <button v-on:click="getLogin">Login</button>
</div>
</template>

<script>
export default{
        name: 'Login',
        data(){
            return {
                loginForm: {
                username:null,
                password:null
            }
        }
     
    },
    methods:{
        getLogin(){
            console.log("getLogin called",this.loginForm.username,this.loginForm.password)
        }
    }
}
</script>