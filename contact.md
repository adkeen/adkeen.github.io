---
layout: page
title: Contact
subtitle: 
---

<!--https://forum.obsidian.md/t/adding-rounded-corners-to-markdown-tables-with-snippets-a-clean-solution/60551-->

<!--https://dev.to/tevko/create-a-virtual-business-card-with-devpage-4o21-->

<!--https://www.codingnepalweb.com/10-profile-card-template-designs-html-css/-->


<link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Poppins:wght@200;300;400;500&display=swap">
<style>
*{
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: 'Poppins', sans-serif;
}
.main {
    height: 50vh;
    display: flex;
    align-items: center;
    justify-content: center;
}
.profile-card {
    display: flex;
    flex-direction: column;
    align-items: center;
    max-width: 600px;
    width: 100%;
    background: #fff;
    border-radius: 24px;
    padding: 25px;
    box-shadow: 0 5px 10px rgba(0, 0, 0, 0.1);
    position: relative;
}
.profile-card::before{
    content: "";
    position: absolute;
    top: 0;
    left: 0;
    height: 36%;
    width: 100%;
    border-radius: 24px 24px 0 0;
    background-color: #4070f4;
}
.image {
    position: relative;
    height: 150px;
    width: 150px;
    border-radius: 50%;
    background-color: #4070f4;
    padding: 3px;
    margin-bottom: 10px;
}
.image .profile-img {
    height: 100%;
    width: 100%;
    object-fit: cover;
    border-radius: 50%;
    border: 3px solid #fff;
}
.profile-card .text-data {
    display: flex;
    flex-direction: column;
    align-items: center;
    color: #333;
}
.text-data .name {
    font-size: 22px;
    font-weight: 500;
}
.text-data .desc {
    font-size: 15px;
    font-weight: 400;
}
.text-data .school {
    font-size: 15px;
    font-weight: 400;
    color: #4E2A84;
}
.profile-card .media-buttons {
    display: flex;
    align-items: center;
    margin-top: 15px;
}
.media-buttons .link {
    display: flex;
    align-items: center;
    justify-contant: center;
    color: #fff;
    font-size: 18px;
    height: 34px;
    width: 34px;
    border-radius: 50%;
    margin: 0 8px;
    background-color: #4070f4;
    text-decoration: none;
}
.profile-card .buttonrow {
    display: flex;
    align-items: center;
    margin-top: 25px;
}
.buttonrow .buttonitem {
    color: #fff;
    font-size: 14px;
    font-weight: 400;
    border: none;
    border-radius: 24px;
    margin: 0 10px;
    padding: 8px 24px;
    background-color: #4070f4;
    cursor: pointer;
    transition: all 0.3s ease;
}
.buttonrow .buttonitem::hover {
    background-color: #0e4bf1;
}
</style>
<section class="main">
    <div class="profile-card">
        <div class="image">
            <img src="/assets/img/keen_prof.jpg" alt="Austin Keen" class="profile-img">
        </div>
        <div class="text-data">
            <span class="name">Austin D. Keen</span>
            <span class="desc">Linguistics PhD Student</span>
            <span class="school">Northwestern University</span>
            <span>Name Pronunciation (IPA):</span>
            <span><a href="https://www.name-coach.com/austin-d-keen">[ˈɔstɪn · kiːn]</a></span>
            <span>Pronouns: he/él</span>
            <br>
            <span>Email: <a href="mailto:aukeen@u.northwestern.edu">aukeen[at]u.northwestern.edu</a></span>
            <br>
            <span>Mail: 2016 Sheridan Road, Evanston, IL 60208</span>
        </div>
        <div class="media-buttons">
            <a href="#" class="link">
                <i class="bx bxl-facebook"></i>
            </a>
        </div>
        <div class="buttonrow">
            <button class="buttonitem">Email</button>
        </div>
    </div>
</section>