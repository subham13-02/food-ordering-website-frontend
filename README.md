/* CSS Reset */

*{
    margin: 0;
    padding: 0;
}


html{
    scroll-behavior: smooth;
}

/* CSS Variables */
:root{
    --navbar-height: 59px;
}

/* Navigation Bar */
#navbar{
    display: flex;
    align-items: center;
    position: sticky;
    top: 0px;
}
#navbar::before{
    content: "";
    background-color: rgb(49, 15, 15);
    position: absolute;
    top:0px;
    left:0px;
    height: 100%;
    width:100%;
    z-index: -1;
    opacity: 0.7;
}


/* Navigation Bar: Logo and Image */

#logo{
    margin: 10px 34px;
}

#logo img{
    height: 47px;
    margin: 3px 6px;
}

/* Navigation Bar: List Styling */

#navbar ul{
    display: flex;
    font-family: 'Baloo Bhai', cursive;
}

#navbar ul li{
    list-style: none;
    font-size: 1.3rem;
}
#navbar ul li a{
    color: white;
    display: block;
    padding: 3px 22px;
    border-radius: 20px;
    text-decoration: none;
}
#navbar ul li a:hover{
    color: black;
    background-color: white;
}

/* Home Section */
#home{
    display: flex;
    flex-direction: column;
    padding:3px 200px;
    height: 550px;
    justify-content: center;
    align-items: center;
}

#home::before{
    content: "";
    position: absolute;
    background: url('../bg1.jpg') no-repeat center center/cover;
    height: 642px;
    top:0px;
    left:0px;
    width: 100%;
    z-index: -1;
    opacity:0.89;
}

#home h1{
    color:white;
    text-align: center;
    font-family: 'Bree Serif', serif;}

#home p{
    color:white;
    text-align: center;
    font-size: 1.5rem;
    font-family: 'Bree Serif', serif;
}

/* Services Section */

#services{
    margin: 34px;
    display: flex;
}

#services .box{
    border: 2px solid brown;
    padding: 34px;
    margin: 2px 55px;
    border-radius: 28px;
    background: #9ee5da;
    margin-bottom: 20px;
}

#services .box img{
   height: 160px;
   margin: auto;
   display: block;
}
#services .box p{
    font-family: 'Bree Serif', serif;
}
 
/* Clients Section */

#client-section{
    z-index: -2;
    position: relative;
}

#client-section::before{
   content: "";
   position: absolute;
   background: url('../bg.jpg');
   width: 100%;
   height: 100%;
   z-index: -5;
   opacity: 0.3;
}

#clients{
    display: flex;
    justify-content: center;
    align-items: center;
}

.client-item{
    padding: 24px;
}
#clients img{
    height: 54px;
}
/* Contact Section */

#contact{
    z-index: -2;
    position: relative;
}

#contact::before{
    content: "";
    position: absolute;
    width: 100%;
    height: 100%;
    z-index: -1;
    opacity: 0.7;
    background: url('../contact.jpg') no-repeat center center/cover;
}

#contact-box{
    display: flex;
    justify-content: center;
    align-items: center;
    padding-bottom: 34px;
}

#contact-box input, 
#contact-box textarea{
    width: 100%;
    padding: 0.rem;
    border-radius: 9px;
    font-size: 1.1rem;
}

#contact-box form{
    width: 40%;
}

#contact-box label{
   font-size: 1.3rem;
   font-family: 'Bree Serif', serif;
}
footer{
    background: black;
    color: white;
    padding: 9px 20px;
}

/* Utility Classes */

.h-primary{
    color:brown;
    font-family: 'Bree Serif', serif;
    font-size: 3.8rem;
    padding: 12px;
}

.h-secondary{
    color:rgb(50, 11, 11);
    font-family: 'Bree Serif', serif;
    font-size: 2.3rem;
    padding: 12px;
}

.btn{
    padding: 6px 20px;
    border: 2px solid white;
    background-color: brown;
    color: white;
    margin: 17px;
    font-size: 1.5rem;
    border-radius: 10px;
    cursor:pointer;
}

.center{
    text-align: center;
}
