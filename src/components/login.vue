<template>
    <div class="login_screen">
        <div class="row">
            <nav class="col-sm-12 logo">
                <img src="../assets/images/text-logo.png" loading="lazy" alt="logo">
            </nav>  

            <form action="" class="col-sm-9 form">
                <div class="title">
                    <h1>Welcome at You!</h1>
                    <p>Welcome back! please enter your details</p>
                </div>

                    <!-- Email input -->
                <div class="mb-2">
                    <label class="form-label" for="form1Example1">Email address</label>
                    <input type="email" id="form1Example1" class="form-control" />
                </div>

                    <!-- Password input -->
                <div class="mb-3">
                    <label class="form-label" for="form1Example2">Password</label>
                    <input type="password" id="form1Example2" class="form-control" />
                </div>

                    <!-- 2 column grid layout for inline styling -->
                <div class="row mb-4">
                    <div class="col-sm-6">
                        <!-- Checkbox -->
                        <div class="form-check">
                            <input class="form-check-input" type="checkbox" value="" id="form1Example3" />
                            <label class="form-check-label" for="form1Example3"> Remember for 30 days </label>
                        </div>
                    </div>

                    <div class="col-sm-6" id="forget">
                        <!-- Simple link -->
                        <a href="#!" style="float: right">Forgot password</a>
                    </div>
                </div>

                <!-- Submit button -->
                <div class="btns m-4">
                    <button type="submit" class="btn btn-primary w-100 mb-2" id="sign">Sign in</button>
                    <button type="submit" class="btn btn-outline-secondary w-100" id="google"><i class='bx bxl-google'></i> Sign in with Google</button>
                </div>

                <div class="sign text-center m-4">
                    <span>Don't have an account? <a href="">Sign Up</a></span>
                </div>
            </form>

            <footer class="col-sm-12 footer">
                <i class='bx bxs-copyright' ></i> You Company UI 2077 
            </footer>
        </div>
    </div>
</template>

<script>
    export default{
        name: 'loginView'
    }
</script>