<template>
    <div class="wrapper-register">
        <div class="form-box login">
            <h2>Register</h2>
            <form action="#">
                <div class="input-box">
                    <span class="icon"><ion-icon name="person"></ion-icon></span>
                    <input type="text" required>
                    <label>Name</label>
                </div>
                <div class="input-box">
                    <span class="icon"><ion-icon name="mail"></ion-icon></span>
                    <input type="email" required>
                    <label>Email</label>
                </div>
                <div class="input-box">
                    <span class="icon"><ion-icon name="lock-closed"></ion-icon></span>
                    <input type="password" required>
                    <label>Password</label>
                </div>
                <div class="input-box">
                    <span class="icon"><ion-icon name="repeat-outline"></ion-icon></span>
                    <input type="password" required>
                    <label>Repeat Password</label>
                </div>
                <button type="submit" class="btn">Register</button>
                <div class="login-register">
                    <p>You already have account? <a href="/login" class="register-link">Login</a></p>
                </div>
            </form>
        </div>
    </div>
</template>