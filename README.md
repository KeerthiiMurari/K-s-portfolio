<!---------------HTML,JavaScript--------------->
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portfolio</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
   <div id="header">
    <div class="container">
        <nav>
            <ul id="sidemenu">
                <li><a href="#header"><h4>HOME</h4></a></li>
                <li><a href="#about"><h4>ABOUT</h4></a></li>
                <li><a href="#Education"><h4>EDUCATION</h4></a></li>
                <li><a href="#contact"><h4>CONTACT</h4></a></li>
                <i class="fas fa-times" onclick="closemenu()"></i>
            </ul>
            <i class="fas fa-bars" onclick="openmenu()"></i>
        </nav>
        <div class="header-text">
           
            <h2>Hi,I'm Murari Sai <span>Keerthi</span></h2>
            <p class="para">Web Developer.<br>Engineering Student.</p><br>
            <p class="para1"><b>I am eagerly pursuing opportunities to apply my proficiency<br> in programming languages,software development an analytical <br>problem-solving to drive forward-thinking initiatives and froster <br>meaningful change.</b></p>
        </div>
    </div>
   </div>
   <!----------------about----------->
   <div id="about">
    <div class="container">
        <div class="row">
            <div class="about-col-1">
                <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcT_-MQxdkdbc2CIRfmqEWX5E6x6ZTO6P41piQ&s">
            </div>
            <div class="about-col-2">
                <h1 class="sub-title">About Me</h1>
                <p class="abt">I am a hard-working and driven individual who isn’t afraid to face a challenge.

                    I’m passionate about my work and I know how to get the job done.
                    
                    I would describe myself as an open and honest person who doesn’t believe in misleading other people and tries to be fair in everything I do.I like to study new things. Being knowledgeable about (your field) or any subject is an ongoing process, and I’m always proactive about seeking new opportunities to develop and grow in my role. Those opportunities could be in the form of training, a conference, listening to a speaker, or taking on a new project, but the motivation is to increase my knowledge of the field.</p>
                    <div class="tab-titles">
                        <p class="tab-links active-link" onclick="opentab('skills')">Skills</p>
                        <p class="tab-links" onclick="opentab('studies')">Studies</p>
                       <p class="tab-links" onclick="opentab('certificate')">Certificate</p>

                    </div>
                    <div class="tab-contents active-tab" id="skills">
                        <ul>
                            <li><span>C,C++,Python,HTML,CSS,JavaScript</span><br>Software(Web)development,operating systems.</li>
                            <li><span>Data Structures,OOPS</span><br>Fundamental Concepts</li>
                            <li><span>MySQL</span><br>Database managment syatem.</li>
                            <li><span>Word,Excel,Power point</span><br>MS Office.</li>
                            <li><span>React Js</span><br>Web app Development</li>
                        </ul>
                    </div>
                    <div class="tab-contents" id="studies">
                        <ul>
                            <li><span>2022-present</span><br>Undergraduate(SRMAP UNIVERSITY).</li>
                            <li><span>2020-2022</span><br>Intermediate(Sarada Junior College).</li>
                            <li><span>2019-2020</span><br>SSC(Sri Chaitanya School).</li>
                        </ul>
                    </div>
                    <div class="tab-contents" id="certificate">
                        <ul>
                            <li><span>SWAYAM-NPTEL</span><br>1.The Joy of Computing using Python<br>2.E-busines<br>3.Psychology and Well-Being.</li>
                        </ul>
                    </div>
            </div>
        </div>
    </div>
</div><br><br>
<!------------education------------------->

<div id="Education">
    <div class="container1">
        <div class="row1">
         <div class="edu-col-1">
            <img src="https://img.freepik.com/premium-vector/books-black-silhouette-isolated-vector_566661-19767.jpg">
         </div>
         <div class="edu-col-2">
            <h1 class="sub-title1">Education</h1><br>
           <!---<p>abcdefg.</p>---->
            <div class="tab-title1">
                <!----<p class="tab-links1 active-link1">edu</p><br>--->
                
            </div>
            <div class="tab-contents1">
                <ul>
                    <li><span>Bachelor of Technology(Computer Science)</span><br>SRM AP University <br>2022-present</li><br>
                    <li><span>Intermediate</span><br>Sarada Junior College. <br>2020-2022</li><br>
                    <li><span>SSC</span><br>Sri Chaintanya School. <br>2019-2020</li><br>
                </ul> <br>

<!----------------------------sample--------------->
   
                    
               
            </div>

         </div>
        </div>
    </div>
</div><br><br><br><br>

<!------------------contact------------------->
<div id="contact">
    <div class="container">
        <div class="row">
            <div class="contact-left">
                <h1 class="sub-title">Contact Me</h1><br>
                <p><b>Email:</b>saikeerthi_murari@srmap.edu.in</p>
                <p><i class="fa-solid fa-phone"></i><b>Phone:</b>9613613123</p>
                <div class="social-icons">
                    <a href="www.linkedin.com/in/saikeerthimurari1" target="blank"><img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQnkbhtVhmWuv-46hzDwF0olerfjqSYkjTgR1-w-De7fFetg_vE6JUex4XptvplHVGEUrQ&usqp=CAU" width="20" 
                        height="50"alt="linkedin-logo"></a>
                    <a href="mailto:saikeerthi_murari@srmap.edu.in" ><img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRI7-f_5T9TN3Ma6CVGGs4Ii3q4pKlUveOPWA&s"  width="20" 
                        height="50"
                        alt="email-logo"></a>
                    <a href="https://github.com/dashboard"><img src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAOEAAADhCAMAAAAJbSJIAAAAflBMVEX///8AAACPj4/V1dX8/Pzz8/Pn5+fu7u7e3t739/c1NTXr6+v29vbx8fGlpaWwsLCYmJhRUVEfHx+CgoIlJSV6enrNzc07Ozu8vLxERER0dHRJSUlhYWHGxsZYWFgaGhpqamouLi6dnZ0LCwuQkJB/f3+tra0UFBQjIyNlZWWz/V0sAAALM0lEQVR4nO1da3eqOhDVgqhYBcUH9vgA7ev8/z94L6VWwITsCQmTrnX250KzJZn3TAaDf/gHFKNxMJl43tbzJpNgPOJejjkEx2iRHHbn67CO63l3SBbRMeBeoD6egzTehEM1wk2cBs/cyyVi5r0ezgC5O86HV2/GvWwUx2Tf3JIYrvvkyL14JUbRQYvcHYfIYSEUXJYd6ZVYXpwUP9P0ZIReiVM65SbUgLfRO3pyXDceN6k7ptGHYXolPiI3PuQ4pukFCs7xmJveIEis0SuR8EqdWWaZX4GMzxIY2/5+NyQ8e3Ua98SvQMwgc95XPRIcDlfvPfPzEKfBLMI+9eNzXwewjqQ3FytdsxAcDtdpL/zmXb2HLjjM7RNMGfkVsP0Z/Q0zweFw49skOOlfhD4inNgjeOEm942LJX5TThFTx8HKTg123Lwq2FnwOLbcpBrYmia44Gb0gIVZgvxK4hFvJgn+5WYjxF9zBM2EQc1jaYjfaM/NRIq9kfj42CUt0cTOQHxj3q8vT8VnZ2dj5DbB/yl23Kgjl7doiV0nir6rUrSKZRcj9TcQ7KQ03FT0j9BW/TwRNR0kegQj7nUTEOkQ9LhXTYJGuHjMvWYiyMaN764xKsaeqjNeuFdMxguN4G+SMjeQpE2gfN3ZTnGCFNdPtYFMiU6pDmEUzMdBECX9WK1ZvJ2NR/NAlZLd4wSfFK/Kf0717JIboiFDdq8dmqv+9gkleFS9qWZCTBJ71SbhoiYhlXURYOHfs3LFDfX6HNlRLYdmTFSZ9zpjOVRl5DB/fGZrvuzk6VFwjJS//QYhqLbWhK+Zm7XTX4UKXF0ciFhv6gSaJElpsLzmTRJ9eVc+GaoJAhk0afAnMBMaz6QJwon6YWXmTa3rh6uWx8Up1PUpiRfpcetNZqPRaDbxtsd0EScnYcVDa1WJenVKvQ/ELdoNwOoeuOaHS9qesZ2kl0NerU1t/wZAla4ipqFUhUNl0icoYx9hFnloLHPuRVn58Q+KL4BUmrUrRSRPr1Sr6W4TBVRnxg+izU5ZaIFUgrQKG8il4CxqBURNq5MxhYqdrFZ7KPCMLHAtXyGW6OVk6EMrlEoK6Adq+4Xsw4fc0qvMPFU5TSV2vVJqIofW+Cp+GNsBiF1kDz5YFil+Giy3EHgW/cEHk33ik/iJPcx7DkFvey16GA6vuS9Lh2L/B/bTObvnRugi/zw+i1ikJTg7rvBkymNVGJ4r1MrzGAIeqc6ajyojdXdoJuuMgBBGaB4mQmWeUE71BEKXQFNhUBoM+LoCp4RVNvQ2KR3aT9eDCKRGgbpEJIWQTkz8oCDGHbXqTHWYuwauhsAZaZWrqoeBK8NfxLCmEmlxTj6VT6ueqMTm/ZzyIJ+gIeam70lALL5zg8S77AmYl/6Ne6iW0u8qMGl7BSWRF/88Relm4h5ZAaQdfvATjqCIqL7bcR9B6fy4CX2CpcAapPlGji/3JhQJusKFaRyE/qSbvsCt7oyR2B14Rv3bDSIcQ4u9jQQQlFt5EHGTjc/krgM3wMs8Ga5EjXfEaQI/iWUNEVyu7oIgLQEr8K+E8AgWNIY7/joA1onrIlqDGwn8835uwAuYCxMM3tTcFmkVf9BFF6ID/uK2esR1APfNFyfrDf1jN5RhCVglFsEaVLmcXZr2p67h+8YJz1c5o+5LwN/Fx4OscAFuL4DNlClulXKGZx4Be3wzXFm44DjdAUfdtviP4ZIoJQjTFChKLbFyY0rjDXCU/h3Wne6Y3SVycN0XWOG7xhB1L95gxcJbCvUItF3nBNuwLtndBfB1ozFkU1M2TAH12/fwfv6t3zAc5PBv4RbQvZcP0LkXv1XSrAZop+Rv1RYfA3QON2vRpQA5uO4r0oXyBc46IRHgCCG8Sz/cibQVGMPrhiXNb/UtVoMc/dNf6h/msNR1JmlRAnbcd3jmnz+/XQXq1v5vi8F5Gc6y0kfAkajTAB5KanCGnwHAJc1/8ZRx6FIYw4fFxwuhrtglhYgnnxLCbGCX1AVewrcg1MK5kyCllA1FhDqFjJtWBXjByZFSJ8ZNqwJ80QGl/N2dg0iopJ0OpvhFTe4kgfFjePXxcIBLgQy8yLRYM2E4Indt6Q2EOrXCEoPz+O5sU0KJaZHHJxSHu7JNCZXQRaMdpYzdDWlKWXERmYAjHkPDY9C1QajXL6NLcH3RkLdD9gZsMEKJMhdBGZEYK/57H6DcI1LO0iH1oTCzK0C5S7Ls6CXdXMHvYMARmgJl+AzuAP8C90kkWJn31ZLmO3IHpEiNTzcFTrsCiDf2TWpC+zHCaF19vKlSimqrWCikp1j3KWmPViQ/cWgwX3yfeGHRfbIccWrwlesoTojXKt/nW1Bnd695VMaYetdGJcJLO79M8W+8MeQb1QIZ8rWwYf8B8IB8c2bViKZpmQJ53xENjz5euyYuqNt0CE8lNgSNqzPrdWo6M9h7bFvXujqzPimIMhblB8u+dqqnNWu6IQ31Zjn34xATooEVZI23EGd/3PBp/zTqXl77YHnpDlZf2rXhjrqj+x+nHb9qvkkwOt0cUg0Z/41HOSiOlO/eJ2N/dly0V2yEdvppOl3fLpihIzrPn/cfYJG3vvDJtDXu6cmXG0QunsiuOVckrq8w7ZYXYyR977XrXQRCRSZKQtV+ipkqTRW+RN3j/t57lnekJyv+ERqn9ROGSO4/cTrWG4/pz9InQ7eeSLaTUJzUbR/UwM+zZHGETR5/crwkB7LvIIesdUIcI6jbLfMc/z94utH0DW9S/SXWPmHNbsH9UErEihhhUkDeGyILK9aSamiKmXbDlNFbzVvEnSzoVrvLHAt4rWmBDnKIogVtv630+9QauSFnjWrm6BrYArSOBJRap1UFgwzVpjeCGbsRVOGZS6MhVZEKuFp0+8bUfYsfiv8jD2dUj6/SX9bpsKFMjWuBcsyx1CAMK9JGOXVYJ5FKSn1KoU4cyTfLG/RXJXTukiYMa24BYBjLXYiqpdBelqRX9W5C1kCRI+l5qJVEtVohejM0DBg2WA+hPABe03Ft69GLT2lGw6oARbg0613/hVo2ql4glTLWUgzY1pfGf+qGipdL/uxTzz98lr0PBd6NLd2nDUvFF3/tV91Jyl1DFwQzQ7oBm7J4FDeMoFXSIUZMGtf9CJISlhkt2eOfbuPTnzDc/1meNu+4Wy9Et0uIBWtrgbSvSJzf9s3cW9LpcsEdcQ0yuWa1ELpTMIO8fWTKyWaRQheVr3H8JdYbdJepJjow1MrzSUInFnNN+gwPWv9vmovfZi/zq80w16x+kVTofOq4RhB0Ga60a18kAnVtq+pLl2GHXSVzdC3N39Nk2CkbJNMZmZWyLz2GHUsJpGHMC3bJNwlaDDvvJ6kR/mk87avF0EDzQIujG74J7zOe6FLXYGikO0JVEbZMLoso3XrbY3EXdZbrjzqlMzR0Bxw5paBb8UZmaEymU0NEfX1DgwYkMafQE0Oj3ZATUlFYLwxXhu3jOSVKpNuRQWG4N++oEkIMPTC00s2K54bsM7R0UyhcTG6b4Ye1jusxmB3S3UIgw6XNVghsDXYZWh4O7yG5aN1oFcIwtD4TwAeWYZHhUx93ZnvKK8qtMVz3NdRBVb5LK/i6Q8Wwx95Or12o2mG47HcqR5r3zDDv/fYJv8X3zzTf2cJw0YeEaWIqPY6Z5hulDN+4JhpOJCnNTPN9EoYvnCMAAuGidMdkCisjn7inUz0LsnC6VpvAe4mdmLj53rTkdMVeM1gSujP3dls7kGdtuVerHnhxa3LxKLobAfqa+V7Is4wsZA26Ioi/wlX7LpIv+CrHOsdct7crEXhe17XNPI9beP6Da/gPfNWsZr34KLUAAAAASUVORK5CYII=" width="20" 
                        height="50" alt="github-logo"></a>
                        
                </div>
                    <a href="download/MURARI SAI KEERTHI" download class="btn">Download CV</a>
            </div>
            <div class="contact-right">
                <form>
                    <b><label for="fullName">Your Name:</label></b>
                    <input type="text" name="Name" placeholder="Your Name" required>
                    <b><label for="email">Your Email:</label></b>
                    <input type="email" name="email" placeholder="Your Email" required>
                    <b><label for="subject">Subject:</label></b>
                    <input type="subject" name="text" placeholder="Job Enquiry" required>
                    <b><label for="message">Your Message:</label></b>
                    <textarea name="message" row="6" placeholder="Your Message"></textarea>
                    <button type="submit" class="btn btn2">Submit</button>
                </form>
                <span id="msg"></span>
            </div>
        </div>
    </div>
    <div class="copyright">
        <p>Copyright © abc.<i class="fas fa-heart"></i></p>
    </div>
</div>

<script>
    var tablinks=document.getElementsByClassName("tab-links");
    var tabcontents=document.getElementsByClassName("tab-contents");

    function opentab(tabname){
        for(tablink of tablinks){
            tablink.classList.remove("active-link");
        }
    }
        function opentab(tabname){
        for(tabcontent of tabcontents){
            tabcontent.classList.remove("active-tab");
        }
        event.currentTarget.classList.add("active-link");
        document.getElementById(tabname).classList.add("active-tab");
    }


</script>
<script>
    var sidemenu=document.getElementsById("sidemenu");
    function openmenu(){
        sidemenu.style.right="0";

    }
    function closemenu(){
        sidemenu.style.right="-200px";
        
    }




</script>
<script>
    form.addEventListener('submit',e=>{
        e.preventDefault()
        fetch(scriptURL,{method:'POST',body:new FormData(form)})
        .then(response=>console.log('Sucess!',response))
        .catch(error=>console.log('Error!',error.message))
    })
</script>
</body>
</html>

<!-----------------------CSS------------------->
*{
    margin:0;
    padding:0;
    font-family:'poppins',sans-serif;
    box-sizing:border-box;
}
html{
    scroll-behavior: smooth;
}
body{
    background:lavender;
    color:black;
}
#header{
    width:100%;
    height:100vh;
    background-image:;
    background-size;cover;
    background-position:centre;
}
.container{
    padding:10px 10%;
}
nav{
    display:flex;
    align-items:center;
    justify-content:space-between;
    flex-wrap:wrap;
}
.logo{
    width:140px;

}
nav ul li{
    display:inline-block;
    list-style:none;
    margin:10px 20px;
    text-shadow:5px 5px 5px #ababab;
}
nav ul li a{
    color:black;
    text-decoration:none;
    font-size:18px;
    font-family:"Lucida Console", monospace;
    position: relative;
}
nav ul li a:hover{
    color:#C54B6C;
}
nav ul li a::after{
    content:'';
    width:0%;
    height:3px;
    background:#C54B6C;
    position:absolute;
    left:0;
    bottom:-6px;
    transition:0.5s;

}
nav ul li a:hover::after{
    width:100%;
}
span{
    color:orange;
}
.header-text{
    margin-top:20%;
    font-size:18px;
    font-family: "Lucida Console", "Courier New", monospace;
}
.header-text h2{
    font-size:40px;
    margin-top:20px;
}
/*----------about--------*/
#about{
    padding:80px 0;
    color:black;
}
.row{
    display:flex;
    justify-content:space-between;
    flex-wrap;wrap
}
.about-col-1{
    flex-basis:35%;

}
.about-col-1{
    width:100%;
    border-radius:100%;
}
.about-col-2{
    flex-basis:100%;
    

}
.sub-title{
    font-size:50px;
    font-weight:100%;
    color:maroon;
}
.para{
    font-size:20px;
    font-weight:600;
}
.tab-titles{
    display:flex;
    margin:20px 0 40px;
}
.tab-links{
    margin-right:50px;
    font-size:18px;
    font-weight:500;
    cursor:pointer;
    position:relative;
}
.tab-links::after{
    content:'';
    widht:0;
    height:3px;
    background:#C54B6C;
    position:absolute;
    left:0;
    bottom:-8px;
    transition:0.5s;
}
.abt{
    font-weight:600;
}
.tab-links.active-link::after{
    width:50%;
}
.tab-contents ul li span{
    color:maroon;
    font-size:18px;
    font-weight:400;
}
.tab-contents ul li{
    list-sytle:none;
    margin:10px 0;
}
.tab-contents{
    display:none;
}
.tab-contents.active-tab{
    display:block;
}
/*-------contact-----------*/
.contact-left{
    flex-basis:35%;
}
.contact-right{
    flex-basis:60%;
}
.contact-left p{

}
.contact-left p i{
    color:black;
    margin-right:15px;
    font-size:25px;
}
.social-icons{
    margin-top:30px;

}
.social-icons a{
    text-decoration:none;
    font-size:30px;
    margin-right:15px;
    color:#ababab;
    display:inline-block;
    transition:transform 0.5s;
}
.social-icons a:hover{
    color:#C54B6C;
    trasform:translateY(-5px);
}
.btn{
    display:block;
    background-color:#C54B6C
    margin:50px auto;
    width:fit-content;
    border:1px solid #C54B6C;
    padding:14px 50px;
    border-radius:6px;
    text-decoration:none;
    transition: 0.5s;

}
.btn:hover{
    background:	#DC143C;
}
.btn.btn2{
    display:inline-block;
    background:#C54B6C;
}
.contact-right form{
    width:100%;

}
form input, form textarea{
    width:100%;
    border: 0;
    outline:none;
    background:#262626;
    padding:15px;
    margin:15px 0;
    color:#fff;
    font-size:18px;
    border-radius:6px;
}
form btn2{
    padding:14px 60px;
    font-size:18px;
    margin-top:20px;
    cursor:pointer;
}
.copyright{
    width:100%;
    text-align:center;
    padding:25px 0;
    background:#E0BFB8;
    font-weight:300;
    margin-top:20px;
}
.education-col-1{
    flex-basis:35%;

}
.education-col-1{
    width:100%;
    border-radius:100%;
}
.education-col-2{
    flex-basis:100%;
    

}
nav .fas{
    display:none;
}
@media only screen and (max-width:600px){
    .header{
        background-image:url();

    }
    .header-text{
        margin-top:100%;
        font-size:16px;
    }
    .header-text h1{
        font-size:30px;
    }
    nav .fas{
        display:block;
        font-size:25px;
    }
    nav ul{
        background:#ff004f;
        position:fixed;
        top:0;
        right:-200px;
        width:200px;
        height:100vh;
        padding-top:50px;
        z-index:2;
        transition:right 0.5s;

    }
    nav ul li{
        display:block;
        margin:25px;

    }
    nav ul .fas{
        position:absolute;
        top:25px;
        left:25px;
        cursor:pointer;
    }
    .subtitle{
        font-size:40px;

    }
    .about-col-1, .about-col-2{
        flex-basis:100%;

    }
    .about-col-1{
        margin-bottom:30px;
    }
    .about-col-2{
        font-size:14px;

    }
    .tab-links{
        font-size:16px;
        margin-right:20px;
    }
    .contact-left, .contact-right{
        flex-basis:100%;

    }
    .copyright{
        font-size:14px;

    }


}

#education{
    padding:80px;
    color:black;

}
.row1{
    display:flex;
    justify-content:space-between;
    flex-wrap:wrap;

}
.edu-col-1{
    flex-basis:45%;

}
.edu-col-1 img{
    width:70%;
    border-radius:45px;

}
.edu-col-2{
    flex-basis:55%;


}
.sub-title1{
    font-size:60px;
    font-weight:600;
    color:#262626;

}
.tab-tiles1{
    display:flex;
    margin:20px 0 40px;
}
.tab-links1{
    margin-right:50px;
    font-size:18px;
    font-weight:500;
    cursor:pointer;
    position:relative;

}
.tab-links1::after{
    content:'';
    width:0;
    height:3px;
    background:black;
    position:absolute;
    left:0;
    bottom:-8px;
    transition:0.5s;
}
.tab-links.active-link1::after{
    width:50%;
}
.tab-contents1 ul li span {
    color:maroon;
}
.tab-contents1 ul li{
    font-size:20px;
}
#msg{
    color:black;
    margin-top:-40px;
    display:block;
}

.tab-links.active-link{
    font-size:20px;
}
.tab-links.active-link:hover{
    color:maroon;
}
.tab-links.active-link::after{
    content:'';
    width:0%;
    height:3px;
    background:#C54B6C;
    position:absolute;
    left:0;
    bottom:-6px;
    transition:0.5s;

}
.tab-links.active-link:hover::after{
    width:100%;
}


