# Html-page
A task is to create a home page created using html and css given by o1codingclub.
**link of the project**
http://127.0.0.1:8000/url/task
**code**
<!DOCTYPE html>
{% load static %}
<html lang="en" xmlns="http://www.w3.org/1999/html">

<head>
    <meta charset="UTF-8">
    <title>
        {% block title%}
        {% endblock%}
    </title>
    <link href="{% static 'css/bootstrap.css' %}" rel="stylesheet">
    <link href="{% static 'css/all.css' %}" rel="stylesheet">

    <script src="{% static 'js/bootstrap.js' %}"></script>
    <script src="{% static 'js/bootstrap.bundle.js' %}"></script>
<style>
    img,.me{
    height:70%; width:40%;
    min-height:100px;background-size:cover;
    background-attachment:fixed;
    border:1px solid black; border-radius:10px 0px 10px 0px;
    }
    a{
    text-decoration:none;}
    .icon{
    margin:30%;
    }

    .mid{
    min-height:100px;
    width:1480px;margin-left:-3%;
    background-size:cover;
    background-attachment:fixed;
    border-radius:0px;
    }


</style>
</head>
<body>
<!-- header section-->
<div class="container-fluid row header py-3 bg-success">
    <div class="col-sm-2">
        <b><font color="white"><img class="me" src="{%static 'Images/mypic.jpg' %}"/></font></b>
    </div>

    <div class="col-sm-3  fs-2">
        <b><font face="Arial Black" color="white" ><i>SUMIT YAGIK</i></font></b>
        <font color="white" face="Berlin Sans FB" size="3px"><p>Aspiring Web Developer. <br> Intern at oCodingclub</p></font>
    </div>
    <div class="col-sm-1"></div>
    <div class="col-sm-2"><font color="white" face="Berlin Sans FB"><p>This page is created to do a Task given by <u>o1codingclub</u></p></font></div>
    <div class="col-sm-4">
        <font color="white" class="icon">
        <a  href="https://www.facebook.com/profile.php?id=61552141231299" target="_blank"><b class="text-light fs-4 d"><i class="fa-brands fa-facebook sicon"></i></b></a>&ensp;&ensp;
        <a  href="https://www.instagram.com/yagik_sumit_001/" target="_blank"><b class="text-light fs-4 d"><i class="fa-brands fa-instagram sicon"></i></b></a>&ensp;&ensp;
        <!--<a href="https://www.youtube.com/" target="_blank"><b class="text-light fs-4 d"><i class="fa-brands fa-youtube sicon"></i></b></a>&ensp;-->
        <a  href="https://github.com/Sumityagik" target="_blank"><b class="text-light fs-4 d"><i class="fa-brands fa-github sicon"></i></b></a>&ensp;&ensp;
       </font>
    </div>
</div>
<!-- header ends-->
<!-- title-->
<div class=" container-fluid row header py-2 sticky-top bg-dark">
    <div class="col-sm-4 logo fs-3 py-2 text-center">
        <a href="#" rel="nofollow" ><i class="text-white">MY <b class="text-center">PORTFOLIO</b></i></a>
    </div>
</div>
<!-- title ends-->
<!-- body-->
<div class="container-fluid" >

    <div>
    <img src="{% static 'Images/main.jpg' %}" class="mid"/>
    </div>

</div>
<!-- body ends-->

<!--footer-->
<div class=" container-fluid row ufooter">
    <div class="col-sm-1 ps-2 py-2 bg-dark"></div>
        <div class="col-sm-3 ps-2 py-2 bg-dark">
            <h3><i class="text-white gn fw-bolder">MY<b class="gn text-mycolor fw-bolder"> PORTFOLIO</b></i></h3>
            <h5 class="text-light " style="font-family:calligraphy;">Aspiring Web Developer.<br>Intern at o Codingclub</h5><br>

             <a href="https:\\www.facebook.com/profile.php?id=61552141231299" target="_blank"> <b class="text-light fs-3 d"><i class="fa-brands fa-facebook-f"></i></b></a>
               <a href="https:\\mobile.twitter.com" target="_blank"> <b class="text-light fs-3 d"><i class="fa-brands fa-twitter"></i></b></a>
            <a href="https:\\in.pinterest.com" target="_blank">  <b class="text-light fs-3 d"><i class="fa-brands fa-pinterest"></i></b></a>
               <a href="https:\\www.google.co.in" target="_blank"> <b class="text-light fs-3 d"><i class="fa-brands fa-google-plus-g"></i></b></a>
              <a href="https:\\www.instagram.com/yagik_sumit_001/" target="_blank"><b class="text-light fs-3 d"><i class="fa-brands fa-instagram"></i></b></a>
        </div>
        <div class="col-sm-4 ps-2 py-2 bg-dark">
                <b class="fw-bolder text-light fs-3 text-center">ABOUT ME</b><br>
            <p class="text-light fs-6">My name is Sumit Yagik. I am a quick learner, Hardworking and
believe in team work .</p>
             <a href="user/news.html/" class="text-white" >Qualification</a>
             <ul class="text-white" style="text-decoration:none;">
             <li>Diploma in CSE</li>
             <li>Graduated in BA</li>
             <li>Intermediate</li>
             </ul>
            <a href="user/news.html/" class="text-white" >Training</a>
            <ul class="text-white" style="text-decoration:none;">
             <li>Summer Training in 2020</li>
             <li>DSA Training in 2023</li>
             <li>Data analytics by cisco</li>
            </ul>

        </div>
        <div class="col-sm-4 py-2 bg-dark">
            <b class="fw-bolder text-light fs-3 text-center"></b><br>
            <a href="user/news.html/" class="text-white" >Projects</a>
         <ul class="text-white" style="text-decoration:none;">
             <li>India Times 24/7 (website)</li>
             <li>Quiz game</li>
             <li>Flipkart Sales Dashboard</li>
             <li>Walmart Sales Dashboard</li>
             </ul>
            <a href="user/news.html/" class="text-white" >Interest</a>
               <ul class="text-white" style="text-decoration:none;">
             <li>Web developing </li>
             <li>Data analysis</li>
             <li>Power BI Dashboard</li>

             </ul>
               <a href="user/news.html" class="text-white" ></a>


        </div>
    </div>
    <div class="container-fluid row bfooter bg-success">
        <div class="col-sm-6"><i class="text-white">Developed By :</i> <a href="user/about.html/" class="text-white"><i>SUMIT YAGIK</i></a></div>

        <div class="col-sm-6">
            <i class="text-white">&copy; Copyright : <a href="https://www.o1codingclub.in" target="_blank" class="text-white">oCodingclub</a></i>
        </div>
    </div>

<!--footer ends-->
</body>
</html>
