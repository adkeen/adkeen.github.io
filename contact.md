---
layout: page
title: Contact
subtitle: 
---

<!--https://forum.obsidian.md/t/adding-rounded-corners-to-markdown-tables-with-snippets-a-clean-solution/60551-->

<!--https://dev.to/tevko/create-a-virtual-business-card-with-devpage-4o21-->

<!--https://codepen.io/willalanjohnson/pen/epRbvb-->


<link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Poppins:wght@200;300;400;500&display=swap">
<style>
*{
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: 'Poppins', sans-serif;
}
.main{
  width: 100%;
  height: 100vh;
  display: flex;
  align-items: center;
  justify-content: center;
  background-image: url(assets/img/bgimage.png);
  background-position: center;
  background-size: cover;
}
.profile-card{
  display: flex;
  flex-direction: column;
  align-items: center;
  max-width: 600px;
  width: 100%;
  border-radius: 25px;
  padding: 30px;
  border: 1px solid #ffffff40;
  box-shadow: 0 5px 20px rgba(0,0,0,0.4);
}
.image{
  position: relative;
  height: 150px;
  width: 150px;
  border-radius: 50%;
  background-color: grey;
  padding: 3px;
}
.image .profile-pic{
  width: 100%;
  height: 100%;
  object-fit: cover;
  border-radius: 50%;
  box-shadow: 0 5px 20px rgba(0,0,0,0.4);
}
.data{
  display: flex;
  flex-direction: column;
  align-items: center;
  margin-top: 15px;
}
.data h2{
  font-size: 33px;
  font-weight: 600;
}
span{
  font-size: 18px;
}
.row{
  display: flex;
  align-items: center;
  margin-top: 30px;
}
.row .info{
  text-align: center;
  padding: 0 20px;
}
.buttons{
  display: flex;
  align-items: center;
  margin-top: 30px;
}
.buttons .btn{
  color: #fff;
  text-decoration: none;
  margin: 0 20px;
  padding: 8px 25px;
  border-radius: 25px;
  font-size: 18px;
  white-space: nowrap;
  background: linear-gradient(to left, #33ccff 0%, #ff99cc 100%);
}
.buttons .btn:hover{
  box-shadow: inset 0 5px 20px rgba(0,0,0,0.4);
}
</style>
<section class="main">
  <div class="profile-card">
    <div class="image">
      <img src="assets/img/keen_prof.jpg" alt="Austin Keen" class="profile-pic">
    </div>
    <div class="data">
      <h2>Austin D. Keen</h2>
      <span>Linguistics PhD Student</span>
      <span>Northwestern University</span>
      <br>
      <span>Name Pronunciation:<br>
      <a href="">[ˈɔstɪn · kiːn]</a></span>
      <span>Pronouns: he/él</span>
      <span>Email: <a href="mailto:aukeen@u.northwestern.edu">aukeen[at]u.northwestern.edu</a></span>
      <span>Mail: 2016 Sheridan Road, Evanston, IL 60208</span>
    </div>
    
    <div class="buttons">
      <a href="#" class="btn">Message</a>
      <a href="#" class="btn">Follow Me</a>
    </div>
  </div>
</section>
