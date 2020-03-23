<!DOCTYPE html>
<html>
    <head>
        <title>DEMEU</title>
        <style>
            *{
    margin:0;
    padding: 0;
    box-sizing: border-box;
}
body {
    background-image: url('bb.jpg');
    background-repeat: no-repeat;
    background-attachment: fixed; 
    background-size: 100% 100%;
  }
.rr{
    color: white;
    background: lightsalmon;
    display: block;
    height: 64px;
    font-family: lato;
    font-weight: bold;
    display: flex;
    align-items: center;
    justify-content: center;
    text-decoration: none;
    transition: background 0.4s;
}
.rr:hover, .aas:hover{
    background:coral;
}
#main-nav ul{
    list-style: none;
    display: flex;
} 
#main-nav li{
    width: 100%;
    text-align: center;
    position: relative;
}
.mainh, .ttr{
    font-family:  cursive;
    text-align: center;
    margin-top: 20px;
    font-size: 75px;
}
.ttrr{
    font-family:  cursive;
    text-align: center;
    margin-top: 20px;
    font-size: 35px;
}
.cit{
    font-family:  cursive;
    text-align: right;
    font-size: 20px;
}
.aq{
    width: 80%;
    margin-left: 10%;
    margin-right: 10%;
    height: 70%;
    margin-top: 15%;
    margin-bottom: 15%;
}
.aa{
    font-family:  cursive;
    text-align: center;
    font-size: 20px;
}
.as{
    display:  grid;
    grid-template-columns: 1fr 2fr 1fr;
}
.ff{
    display:  grid;
    grid-template-columns: 1fr 1fr 1fr ;  
}
.foot{
    display:  grid;
    grid-template-columns: 1fr ;  
    background-image: url(border.png);
    background-repeat: no-repeat;
    background-size: 100% auto;
}
.jpg{
    height: 25px;
    width: 25px;
}
.cntct{
    margin-top: 20px;
    text-align: center;
      font-size: 25px;
     font-family:  cursive; 
}
.aas{
    background: lightsalmon;
    display: flex;
    align-items: center;
    justify-content: center;
    transition: background 0.4s;
    width: 80%;
    height: 30px;
    border-radius: 5px;
    margin-top: 2px;
    margin-left: 10%;
}

 .tt{
     display:grid;
     grid-template-columns: 1fr 1fr 1fr;
 }
 .yyyy{
     width:200px;     
     margin-left: 130px;
     margin-right: 130px;
     background-color: white;
     font-size: 23px;
     font-family: 'Times New Roman', Times, serif;
 }
 .bc{
     color: black;
     background-color: lightsalmon;
 }
 #uuu{
     display: grid;
     grid-template-columns: repeat(2, 1fr);
     margin-left: 20px;
     margin-right: 10px;
 }
 .tttr{
     background-color: lightsalmon;
     font-family:  cursive;
     text-align: center;
     font-size: 20px;
     width: 70%;
     margin-top: 30%;
     margin-right: 15%;
     margin-left: 15%;
     border-radius: 5px;
 }
 .top{
     background-color: lightsalmon;
     width:20px;
     height: 25px;
     margin-left: 250px;
 }
 .topp{
    background-color: lightsalmon;
    width:20px;
    height: 25px;
    margin-left: 90%;
 }
 form{
     display: grid;
     grid-template-columns: 1fr;
     height:60%;
 }
 label{
     font-size: 23px;
     font-family: Verdana, Geneva, Tahoma, sans-serif;
 }
 input{
     padding: 1%;
     border-radius: 15px;
     width:80%;
     margin-left: 10%;
     margin-right: 10%;
 }
 hr {
    height: 2px;
    color:lightsalmon;
    background-color: lightsalmon;
 }
 

@media(max-width:1000px){
    #main-nav ul{
        display: grid;
        grid-template-columns: 1fr;
    }
    .cntct{
        margin-top: 5px;
    }
    .tttr, .ttr{
        font-size: 35px;
    }
    .aa, .cit, .yyyy{
        font-size:15px;
    }
    .tt, .as{
        display: grid;
        grid-template-columns: 1fr;
    }
    video{
        width: 70%;
        margin-left: 15%;
        margin-right: 15%;
    }
    #team{
        margin-left: 30%;
        margin-right: 30%;
        width: 300px;
        height: 300px;
    }
    .yyyy{
        margin-left: 35%;
        margin-right: 40%;
    }
    label{
        font-size: 20px;
    }
    .tttr{
        width: 50%;
        margin-left: 25%;
        margin-right: 30%;
        margin-top: 15%;
    }
    form{
        width: 80%;
        margin-left: 15%;
    }
    .ttrr{
        font-size: 20px;
    }
    
}
@media(max-width:600px){
    label{
        font-size: 20px;
    }
    .cntct{
        font-size: 15px;
        margin-top: 0px;
    }
    .jpg{
        height: 20px;
        width: 20px;
    }
    .aas{
        height: 25px;
    }
    #main-nav ul{
        display: grid;
        grid-template-columns: 1fr;
    }
    .tttr, .ttr{
        font-size: 25px;
    }
    .aa, .cit, .yyyy{
        font-size:15px;
    }
    .tt, .as{
        display: grid;
        grid-template-columns: 1fr;
    }
    video{
        width: 70%;
        margin-left: 15%;
        margin-right: 15%;
    }
    #team{
        margin-left: 30%;
        margin-right: 30%;
        width: 300px;
        height: 300px;
    }
    .yyyy{
        margin-left: 35%;
        margin-right: 40%;
    }
    .tttr{
        width: 50%;
        margin-left: 25%;
        margin-right: 30%;
        margin-top: 15%;
    }
    form{
        width: 80%;
        margin-left: 15%;
    }
    .ttrr{
        font-size: 20px;
    }
}
        </style>
        <script>
            function checkfirstsymbol(letters){
                let numbers=[1,2,3,4,5,6,7,8,9,0];
                for(let l=0;l<numbers.length;l++)    {
                    if (letters[0]==numbers[l])        {
                        return false;
                    }
                    else{
                        return true;
                    }
                }
            }
            function send(){
                let fname = document.getElementById("fname").value;
                let lname = document.getElementById('lname').value;
                let email = document.getElementById('email').value;
                let rfname = document.getElementById('repeatfname').value;
                if (fname.length<1){
                    alert("Please fill First Name");
                    return false;
                }
                else if(checkfirstsymbol(fname)==false){
                    alert("You cannot use symbols!");
                    return false;
                }
                else if (fname.length>32){
                    alert('No more than 32 letters');
                    return false;
                }
                else{
                    if (fname!=rfname){            
                        repeatfname.style.backgroundColor='yellow';
                        return false;
                    }
                    else{   
                        repeatfname.style.backgroundColor='white';
                            if (lname.length<1){
                                alert("Please fill Last Name");
                                return false;
                            }
                            else if (lname.length>32){
                                alert('No more than 32 letters in Last Name');
                                return false;
                            }
                            else{
                                if (email.length<1){
                                    alert("Please fill Email");
                                    return false;
                                }
                                else if (email.length>32){
                                    alert('No more than 32 letters');
                                    return false;
                                }
                                else{
                                    return true;
                                }
                            }                
                    }       
                }    
            }
            </script>
        <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.4.1/css/bootstrap.min.css" integrity="sha384-Vkoo8x4CGsO3+Hhxv8T/Q5PaXtkKtu6ug5TOeNV6gBiFeWPGFN9MuhOf23Q9Ifjh" crossorigin="anonymous">
        <script src="https://code.jquery.com/jquery-3.4.1.slim.min.js" integrity="sha384-J6qa4849blE2+poT4WnyKhv5vZF5SrPo0iEjwBvKU7imGFAV0wwj1yYfoRSJoZ+n" crossorigin="anonymous"></script>
<script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.0/dist/umd/popper.min.js" integrity="sha384-Q6E9RHvbIyZFJoft+2mJbHaEWldlvI9IOYy5n3zV9zzTtmI3UksdQRVvoxMfooAo" crossorigin="anonymous"></script>
<script src="https://stackpath.bootstrapcdn.com/bootstrap/4.4.1/js/bootstrap.min.js" integrity="sha384-wfSDF2E50Y2D1uUdj0O3uMBJnjuUD4Ih7YwaYd1iqfktj0Uod8GCExl3Og8ifwB6" crossorigin="anonymous"></script>
        <script src="Bekzhanthebest.js"></script>
    </head>
    <body>
        <nav id="main-nav">
            <ul>
                <li><a class="rr" href="#bbb">About us</a></li> 
                <li><a class="rr" href="#ttt">Our team</a></li>
                <li><a class="rr" href="#yyy">Activities</a></li>
                <li><a class="rr" href="#uuu">Do you want to join us?</a></li>
            </ul>
        </nav>
            <div class="bb" id="bbb">
                <p class="mainh">Demeu</p>
                <div class="as">
                    <div><video controls>
                        <source src="video1.mp4" type="video/mp4">
                        </video></div>
                    <div class="aq">
                        <p class="aa">We are a club aimed at providing moral support and assistance to our students, because each of us goes through certain difficulties, no matter how trite it sounds. And at this moment, the best thing we can do for each other is to become a support environment that makes us more cohesive and stronger. 
                        Our club would be very pleased to be able to help each of you and be useful :)</p>
                        <p class="cit">Smile for everyone</p><p class="cit" style="font-size: 20px;">Demeu team</p>
                    </div>
                    <div><video controls>
                        <source src="video2.mp4" type="video/mp4">
                        </video></div>
                </div>    
            </div>
        <hr>
        <div class="tt" id="ttt">
            <div><p class="tttr">Our aim</p>
            <p class="yyyy"> Organize events, trainings, meetings to improve the communication skills of students. Create a pleasant atmosphere and support students. </p></div>
            <div id="team">
                    <p class="ttr">Our team</p>
                    <div id="carouselExampleCaptions" class="carousel slide" data-ride="carousel">
                        <ol class="carousel-indicators">
                        </ol>
                        <div class="carousel-inner">
                        <div class="carousel-item active">
                            <img src="me.jpg" class="d-block w-100" alt="...">
                            <div class="carousel-caption d-none d-md-block">
                            <h5 class="bc">Aisha</h5>
                            <p class="bc">President</p>
                            </div>
                        </div>
                        <div class="carousel-item">
                            <img src="lenya.jpg" class="d-block w-100" alt="...">
                            <div class="carousel-caption d-none d-md-block">
                            <h5 class="bc">Aynel</h5>
                            <p class="bc">Vice-president</p>
                            </div>
                        </div>
                        <div class="carousel-item">
                            <img src="kosya.jpg" class="d-block w-100" alt="...">
                            <div class="carousel-caption d-none d-md-block">
                            <h5 class="bc">Aruzhan</h5>
                            <p class="bc">Cool</p>
                            </div>
                        </div>
                        <div class="carousel-item">
                            <img src="das.jpg" class="d-block w-100" alt="...">
                            <div class="carousel-caption d-none d-md-block">
                            <h5 class="bc">Dastan</h5>
                            <p class="bc">Strong</p>
                            </div>
                        </div>
                        <div class="carousel-item">
                            <img src="nur.jpg" class="d-block w-100" alt="...">
                            <div class="carousel-caption d-none d-md-block">
                            <h5 class="bc">NurikJJJan</h5>
                            <p class="bc">Kind</p>
                            </div>
                        </div>
                        <div class="carousel-item">
                            <img src="dau.jpg" class="d-block w-100" alt="...">
                            <div class="carousel-caption d-none d-md-block">
                            <h5 class="bc">Daulet</h5>
                            <p class="bc">Long</p>
                            </div>
                        </div>
                        <div class="carousel-item">
                            <img src="roo.jpg" class="d-block w-100" alt="...">
                            <div class="carousel-caption d-none d-md-block">
                            <h5 class="bc">Aruzhan</h5>
                            <p class="bc">Cute</p>
                            </div>
                        </div>
                        <div class="carousel-item">
                            <img src="naz.jpg" class="d-block w-100" alt="...">
                            <div class="carousel-caption d-none d-md-block">
                            <h5 class="bc">Nazerke</h5>
                            <p class="bc">Shy</p>
                            </div>
                        </div>
                        <div class="carousel-item">
                            <img src="karu.jpg" class="d-block w-100" alt="...">
                            <div class="carousel-caption d-none d-md-block">
                            <h5 class="bc">Karu</h5>
                            <p class="bc">Oruzhiye</p>
                            </div>
                        </div>
                        <div class="carousel-item">
                            <img src="erken.jpg" class="d-block w-100" alt="...">
                            <div class="carousel-caption d-none d-md-block">
                            <h5 class="bc">Erken</h5>
                            <p class="bc">Anime smotrit</p>
                            </div>
                        </div>
                        <div class="carousel-item">
                            <img src="ayzh.jpg" class="d-block w-100" alt="...">
                            <div class="carousel-caption d-none d-md-block">
                            <h5 class="bc">Ayzhamal</h5>
                            <p class="bc">not beautiful (very bautiful)</p>
                            </div>
                        </div>
                        </div>
                        <a class="carousel-control-prev" href="#carouselExampleCaptions" role="button" data-slide="prev">
                        <span class="carousel-control-prev-icon" aria-hidden="true"></span>
                        <span class="sr-only">Previous</span>
                        </a>
                        <a class="carousel-control-next" href="#carouselExampleCaptions" role="button" data-slide="next">
                        <span class="carousel-control-next-icon" aria-hidden="true"></span>
                        <span class="sr-only">Next</span>
                        </a>
                    </div>
            </div>
            <div id="yyy">
                <p class="tttr">Activities</p>
                <div class="yyyy">
                 <div id="carouselExampleCaptions" class="carousel slide" data-ride="carousel">
                            <ol class="carousel-indicators">
                            </ol>
                            <div class="carousel-inner">
                            <div class="carousel-item active">
                                <img src="1.jpg" class="d-block w-100" alt="...">
                                <div class="carousel-caption d-none d-md-block">
                                </div>
                            </div>
                            <div class="carousel-item">
                                <img src="2.jpg" class="d-block w-100" alt="...">
                                <div class="carousel-caption d-none d-md-block">
                                </div>
                            </div>
                            <div class="carousel-item">
                                <img src="3.jpg" class="d-block w-100" alt="...">
                                <div class="carousel-caption d-none d-md-block">
                                </div>
                            </div>
                            <div class="carousel-item">
                                <img src="4.jpg" class="d-block w-100" alt="...">
                                <div class="carousel-caption d-none d-md-block">
                                </div>
                            </div>
                            <div class="carousel-item">
                                <img src="5.jpg" class="d-block w-100" alt="...">
                                <div class="carousel-caption d-none d-md-block">
                                </div>
                            </div>
                            <div class="carousel-item">
                                <img src="6.jpg" class="d-block w-100" alt="...">
                                <div class="carousel-caption d-none d-md-block">
                                </div>
                            </div>
                            <div class="carousel-item">
                                <img src="7.jpg" class="d-block w-100" alt="...">
                                <div class="carousel-caption d-none d-md-block">
                                </div>
                            </div>
                            </div>
                            <a class="carousel-control-prev" href="#carouselExampleCaptions" role="button" data-slide="prev">
                            <span class="carousel-control-prev-icon" aria-hidden="true"></span>
                            <span class="sr-only">Previous</span>
                            </a>
                            <a class="carousel-control-next" href="#carouselExampleCaptions" role="button" data-slide="next">
                            <span class="carousel-control-next-icon" aria-hidden="true"></span>
                            <span class="sr-only">Next</span>
                            </a>
                        </div>
                        <div class="top"><a href="#"><img src="Arrow_top.png" alt="top" style="width:20px; height: 20px;"></a></div>
                        </div>
            </div>
        </div>
        <hr>
        <p class="ttr">Join us</p>
        <div id="uuu">
            <div>
                <form method="POST" onsubmit="return send()">
                        <label for="fname">First Name</label>                                           
                        <input type="text" id="fname" name="fname">
                        <label for="repeatfname">Repeat Name</label>                      
                        <input type="text" id="repeatfname" name="fname">
                        <label for="lname">Last Name</label>                 
                        <input type="text" id="lname" name="lname">
                        <label for="email">E-mail</label>
                        <input type="email" id="email" name="email">
                        <label for="message" name="message">why do you want to join club "Demeu"?</label>                        
                        <input style="padding: 25px;" type="text" name="message" placeholder="Your answer"><br>          
                         <input style="background-color: lightsalmon;" type="submit" name="Submit">
                </form>
            </div>
            <div>
                <div style="margin-top: 10px;"><video width="70%" style=" margin-left: 15%;" controls>
                    <source src="video3.mp4" type="video/mp4">
                    </video></div>
                    <p class="ttrr">Be with us. We are ready to support you and share our energy. We will be glad if you join our family.</p>
            </div>
        </div><br><br><br>
        <div class="topp"><a href="#"><img src="Arrow_top.png" alt="top" style="width:20px; height: 20px;"></a></div>
        <hr>
        <div class="ff" id="fff">
            <div></div>
            <div class="foot">
                <div class="cntct" >Contact us:</div>
                <div class="contact">
                    <div class="contactt">
                        <a class="aas" href="https://www.instagram.com/demeu.aitu/" target="_blank"><img class="jpg" src="inst.png" alt=""></a>
                        <a class="aas" href="https://mail.google.com/mail/u/0/#inbox" target="_blank"><img class="jpg" src="mail.png" alt=""></a>
                    </div>
                </div>
            </div>
            <div></div>
        </div>
        <br><br>
        <div style="text-align: center;">Astana IT University, 2020</div>
    </body>
</html>
