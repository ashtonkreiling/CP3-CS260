<template>
  <div>
    <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
      <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav">
          <li class="nav-item">
            <router-link to="/">
              <p class="nav-link">Back</p>
            </router-link>
          </li>
        </ul>
      </div>
    </nav>

    <div class='input-box'>
      <div class='input-field-container'>
        <input type="text" name="firstname" placeholder="First Name" id="firstName"/>
        <input type="text" name="lastname" placeholder="Last Name" id="lastName"/>
        <input type="text" name="age" placeholder="Age" id="age"/>
        <input type="text" name="gender" placeholder="Gender" id="gender"/>
        <input type="text" name="username" placeholder="Username" id="username"/>
        <input type="text" name="password" placeholder="Password" id="password"/>
      </div>
      <router-link to="/feed"><a href="">Sign Up</a></router-link>
    </div>

    <div class='footer-container'>
      <div class='footer'><a href="https://github.com/BYU-CS-260-Winter-2021/lab-1-photography-website-ashtonkreiling">
          Find Me On Github</a></div>
    </div>
  </div>
</template>

<style>

router-link {
  display: inline;
}

</style>

<!--script src="../components/signup.js"></script-->
