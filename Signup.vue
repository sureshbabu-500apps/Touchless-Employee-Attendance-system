<template>
    <div>
        
            <h3>Sign Up</h3>

            <div>
                <label>Full Name</label>
                <input type="text"/>
            </div>

            <div>
                <label>Email address</label>
                <input type="email"  />
            </div>

            <div>
                <label>Password</label>
                <input type="password" />
            </div>

            <button type="submit">Sign Up</button>

            
                Already registered 
                <router-link :to="{name: 'login'}">sign in?</router-link>
           
       
    </div>
</template>

<script>
    export default {
        data() {
            return {}
        }
    }
</script>