<template>
<div>
  <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
    <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarNav">
      <ul class="navbar-nav">
        <li class="nav-item">
          <input type="text" name="Search" placeholder="Search"/>
        </li>
        <li class="nav-item active">
          <router-link class="nav-link" to="/feed"><img src="../assets/FeedIcon.svg" width="30px"></router-link>
        </li>
        <li class="nav-item">
          <router-link class="nav-link" to="/groups"><img src="../assets/GroupIcon.svg" width="30px"></router-link>
        </li>
        <li class="nav-item">
          <router-link class="nav-link" to="/profile"><img src="../assets/PersonIcon.svg" width="30px"></router-link>
        </li>
        <li class="nav-item">
          <router-link class="nav-link" to="/"><img src="../assets/LogOutIcon.svg" width="30px"></router-link>
        </li>
        <li class="nav-item">
          <router-link class="nav-link" to="/projects"><img src="../assets/HammerIcon.svg" width="30px"></router-link>
        </li>
      </ul>
    </div>
  </nav>
  <div class='main-wrap'>

    <div class='side-bar projects-bar'>
      <h4>Projects Near You</h4>
      <p class='post'><img src="../assets/Park_Trash.jpg" width="50px">Park Cleanup</p>
      <p class="post"><img src="../assets/English_Teaching.jpg" width="50px">Teach Refugees English</p>
      <p class='post'><span class='img-box'><img src="../assets/Nursing_Home.jpg" width="50px"></span>Nursing Home Voluntering: Positions Available </p>
      <p class="post"><img src="../assets/Utah_Lake.jpg" width="50px">Help Clean Up Utah Lake</p>
      <p class="post"><img src="../assets/Hopscotch.jpg" width="50px">Help Build ADA playground for disabled children</p>
      <p class="post"><img src="../assets/Sad_Dog.jpg" width="50px">Help make dog beds for animal shelter</p>
      <p class="post"><img src="../assets/Gazebo.jpg" width="50px">Build a gazebo at this local park</p>
      <p class="post"><img src="../assets/Sports.jpg" width="50px">Build a community equipment shed for local sports teams</p>
      <p class="post"><img src="../assets/Small_House.jpg" width="50px">Help build housing for veterans</p>
      <p class="post"><img src="../assets/Hopscotch.jpg" width="50px">Paint hopscotch areas at local elementary school</p>
      <p class="post"><img src="../assets/PersonIcon.png" width="50px">Help sew dolls for local children's hospital</p>
      <p class="post"><a href = ''>See More</a></p>

    </div>

  <div class="feed-main">
    <h4>Your Feed</h4>
    <ul>
    <li class ='post'><div class="post-header"><img src="../assets/PersonIcon.svg"><h5>J.B. Fordham</h5>
    </div><p>Happy Birthday!! <a href="profile.html">@John Doe</a></p></li>
    <li class ='post'><div class="post-header"><img src="../assets/PersonIcon.svg"><h5>E.K. Ryan</h5>
    </div><p>Happy Birthday!! <a href="profile.html">@John Doe</a></p></li>
    <li class ='post'><div class="post-header"><img src="../assets/PersonIcon.svg"><h5>G.J. Volk</h5>
    </div><p>Happy Birthday!! <a href="profile.html">@John Doe</a></p></li>
    <li class ='post'><div class="post-header"><img src="../assets/PersonIcon.svg"><h5>Jane Doe</h5>
    </div><p>Happy Birthday!! <a href="profile.html">@John Doe</a></p></li>
    <li class ='post'><div class="post-header"><img src="../assets/PersonIcon.svg"><h5>Cravat Caveat</h5>
    </div><p>Come see us play at <a href="">The Jam Cave</a> on Wednesday! 50% off at the door if you mention
    this post!</p><img src="../assets/Band_Image.jpg" width="100%"></li>
    <li class ='post'><div class="post-header"><img src="../assets/PersonIcon.svg"><h5>CommUnitY News</h5>
    </div><p>We are excited to announce that CommUnitY now has a grand total of 7 users!
      Thank you to all our loyal CommUnitY members!</p></li>
    <li class="post"><a href=''>See More</a></li>
  </ul>
    </div>

  <div class='side-bar petitions-bar'>
    <h4>Petitions</h4>
    <p class="post"><img src="../assets/Hydroponic_Garden.jpg" width="50px">Add sustainable growing methods to curriculum for local
    elementary school's biology  class</p>
    <p class="post"><img src="../assets/Fish.jpg" width="50px">Raise funds to protect local fish</p>
    <p class="post"><img src="../assets/PersonIcon.png" width="50px">Prevent Lorem Ipsum industries from dumping hazardous waste
    into local river</p>
    <p class="post"><img src="../assets/PersonIcon.png" width="50px">Clemency for James Smith</p>
    <p class="post"><img src="../assets/PersonIcon.png" width="50px">New green energy legislation</p>
    <p class="post"><img src="../assets/PersonIcon.png" width="50px">Repeal act 11219-14</p>
    <p class="post"><img src="../assets/PersonIcon.png" width="50px">Invest more in our local parks</p>
    <p class="post"><img src="../assets/PersonIcon.png" width="50px">Start a fund to counter our city's debt</p>
    <p class="post"><a href = ''>See More</a></p>

    </div>
  </div>

  <div class='footer-container'>
    <div class='footer'><a href="https://github.com/BYU-CS-260-Winter-2021/lab-1-photography-website-ashtonkreiling">
        Find Me On Github</a></div>
  </div>
</div>
</template>
