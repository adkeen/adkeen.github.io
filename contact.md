---
layout: page
title: Contact
subtitle: 
---

<!--https://forum.obsidian.md/t/adding-rounded-corners-to-markdown-tables-with-snippets-a-clean-solution/60551-->

<!--https://dev.to/tevko/create-a-virtual-business-card-with-devpage-4o21-->

<!--https://codepen.io/willalanjohnson/pen/epRbvb-->


<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
<style>
.card {
  border-radius: 15px;
  box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2);
  max-width: 600px;
  margin: auto;
  text-align: center;
  font-family: arial;
}

.title {
  color: grey;
  font-size: 18px;
}

button {
  border: none;
  outline: 0;
  display: inline-block;
  padding: 8px;
  color: white;
  background-color: #000;
  text-align: center;
  cursor: pointer;
  width: 100%;
  font-size: 18px;
}

a {
  text-decoration: none;
  font-size: 22px;
  color: black;
}

button:hover, a:hover {
  opacity: 0.7;
}
</style>

<div class="card">
  <!--<img src="/assets/img/keen_prof.jpg" alt="Austin Keen" style="width:100%">-->
  <h1>Austin D. Keen</h1>
  <p class="title">Linguistics PhD Student</p>
  <p>Northwestern University</p>
  <p>Name Pronunciation (IPA):<br>
  <a href="">[ˈɔstɪn · kiːn]</a></p>
  <p>Pronouns: he/él</p>
  <p>Email: <a href="mailto:aukeen@u.northwestern.edu"></a>aukeen[at]u.northwestern.edu</p>
  <p>Mail: 2016 Sheridan Road, Evanston, IL 60208</p>
  <div style="margin: 24px 0;">
    <a href="#"><i class="fa fa-dribbble"></i></a> 
    <a href="#"><i class="fa fa-twitter"></i></a>  
    <a href="#"><i class="fa fa-linkedin"></i></a>  
    <a href="#"><i class="fa fa-facebook"></i></a> 
  </div>
  <p><button>Contact</button></p>
</div>

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
  background-image: url(images/back.jpg);
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
    </div>
    <div class="row">
      <div class="info">
        <h3>Following</h3>
        <span>120</span>
      </div>
      <div class="info">
        <h3>Followers</h3>
        <span>5000</span>
      </div>
      <div class="info">
        <h3>Posts</h3>
        <span>209</span>
      </div>
    </div>
    <div class="buttons">
      <a href="#" class="btn">Message</a>
      <a href="#" class="btn">Follow Me</a>
    </div>
  </div>
</section>
