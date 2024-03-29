<template>
    <div class="wrapper">
        <div class="main-container">
            <div class="container-one">
                <div class="profile">
                    <img src="../assets/profilepic.jpg" alt="">
                    <h3>Aeron Kent Degamo</h3>
                    <p>Student/Developer</p>
                </div>
                <div class="social-link">
                    <div class="link">
                        <a href="https://github.com/aers2505" target="blank">
                            <img src="../assets/github.jpg" alt="">
                            <h2>GITHUB</h2>
                        </a>
                    </div>
                    <div class="link">
                        <a href="https://www.facebook.com/aeronkent17" target="blank"> 
                            <img src="../assets/facebook.jpg" alt="">
                            <h2>FACEBOOK</h2>
                        </a>
                    </div>
                    <div class="link">
                        <a href="https://www.instagram.com/aers_kape/" target="blank">
                            <img src="../assets/instagram.jpg" alt="">
                            <h2>INSTAGRAM</h2>
                        </a>
                    </div>
                    <div class="link">
                        <a href="https://twitter.com/KaogL96483" target="blank">
                            <img src="../assets/twitter.jpg" alt="">
                            <h2>TWITTER</h2>
                        </a>
                    </div>
                </div>
            </div>
            <div class="container-two">
                <div class="about me ">
                    <h1>About Me</h1>
                    <p>Hey there! I'm Aeron, a BSIT student diving headfirst into the world of technology. I'm all about learning and exploring new stuff in IT, from coding to cybersecurity.

I don't just stick to books—I love getting my hands dirty with real projects. Whether it's joining hackathons or internships, I'm always up for a challenge and eager to learn by doing.

Collaboration is key for me. I enjoy teaming up with classmates and mentors to tackle tough problems and grow together. I believe we're stronger when we work as a team.

Besides tech, I've got interests outside the digital world, like reading manga. They help me stay balanced and bring fresh perspectives to my work.

Thanks for stopping by! I'm excited to share my projects and experiences with you. Let's connect and geek out over all things tech!






</p>
                    <div class="Language-Section">
                        <h1>Language Studied</h1>
                        <div class="logos">
                            <img src="../assets/japan.jpg" alt="">
                            <img src="../assets/english.jpg" alt="">
                            <img src="../assets/bisaya.jpg" alt="">
                            <div class="button-container">
                                <div class="project-button">
                                    <a href="">Contact Number : 09070774066</a>
                                </div>
                                <div class="project-button">
                                    <a href="">Email:kentaeron1@gmail.com</a>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
export default {

}
</script>


<style scoped>
.wrapper {
    display: flex;
    justify-content: center;
}

img {
    height: 40px;
}

.main-container {
    display: flex;
    flex-direction: center; /* Change flex-direction to column for smaller screens */
    background-color: rgb(245, 251, 249);
   
}

.container-one {
    background-color: rgb(252, 253, 252);
    width: 70%; /* Take full width */
    padding: 10px; /* Add padding */
    margin-bottom: 20px; /* Add margin-bottom for spacing */
    height: fit-content;
    box-shadow: 0px 3px 8px rgba(0, 0, 0, 0.5);
}

.profile img {
    height: 80px; /* Adjust height for profile image */
    border-radius: 50%; /* Make the profile image circular */
    box-shadow: 0px 3px 8px rgba(0, 0, 0, 0.5);
}

.link a {
    text-decoration: none;
    color: #080d11;
    font-size: 14px; /* Increase font size for links */
    margin-bottom: 10px; /* Add margin bottom for spacing */
    display: block; /* Display links as block elements */
}

.link img {
    height: 20x; /* Adjust height for social media icons */
}

.container-two {
    background-color: rgb(248, 249, 247);
    margin: 2%;
    width: 100%; 
    height: 95%;
    padding: 5px; 

    box-shadow: 0px 3px 8px rgba(0, 0, 0, 0.5);
}

.about-me {
    text-align: center; /* Center align the text */
    margin-bottom: 20px; /* Add margin bottom for spacing */
}

.logos img {
    height: 30px; /* Adjust height for language logos */
    margin-right: 10px; /* Add margin-right for spacing between logos */
    border-radius: 50%; /* Make the logos circular */
}

.button-container {
    display: flex;
    flex-wrap: wrap;
    justify-content: center; 
}

.project-button {
    background-color: #f7fbf9;
    border-radius: 25px;
    padding: 10px 20px; 
    margin: 50px; 
    box-shadow: 0px 3px 8px rgba(0, 0, 0, 0.5);
}

.project-button a {
    text-decoration: none;
    color: #000407;
    font-size: 22x;
}

@media only screen and (min-width: 680px) {
    .main-container {
        width: 80%; 
    }
}
</style>
