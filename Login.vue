<template>
    <div class="vue-tempalte">
    
    
    
             <h3>Sign In</h3>

            <div class="form-group">
                <label>Email address</label>
                <input type="email">
            </div>

            <div class="form-group">
                <label>ID</label>
                <input type="ID">
            </div>

            <div class="form-group">
                <label>Password</label>
                <input type="password">
            </div>

            <button type="submit">Sign In</button>

            <router-link to="/forgot-password">Forgot password ?</router-link>
            

            

        
    </div>
</template>

<script>
    export default {
        data() {
            return {}
        }
    }
</script>