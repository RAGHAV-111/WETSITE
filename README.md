/* CSS Reset*/
* {
    margin: 0;
    padding: 0;
}

html {
    scroll-behavior: smooth;
}

/* CSS Variables*/
:root {
    --navbar-height: 59px;
}

/*Navigation Bar */
#navbar {
    background-color: black;
    display: flex;
    align-items: center;
    position: sticky;
    top: 0px;
}

#navbar::before {
    content: "";
    background-color: black;
    position: absolute;
    top: 0px;
    left: 0px;
    height: 100%;
    width: 100%;
    z-index: -1;
    opacity: 0.7;
}

/*Navigation Bar: Logo and Image*/
#logo {
    margin: 10px 34px;
}

#logo img {
    height: 60px;
    margin: 3px 6px;
}

/*Navigation Bar:List Styling*/
#navbar ul {
    display: flex;
    font-family: 'Times New Roman', Times, serif;

}

#navbar ul li {
    list-style: none;
    font-size: 1.3rem;
}

#navbar ul li a {
    color: white;
    display: block;
    padding: 3px 22px;
    border-radius: 20px;
    text-decoration: none;
}

#navbar ul li a:hover {
    color:white;
    background-color: rgb(243, 6, 6);
}

/* Home section */
#home {
    background: url('../background1.jpg') no-repeat center center/cover;
    display: flex;
    flex-direction: column;
    padding: 3px 200px;
    height: 550px;
    justify-content: center;
    text-align: center;
    opacity: 1;
}

#home::before {
    content: "";
    position: absolute;
    height: 642;
    top: 0px;
    left: 0px;
    width: 100%;
    z-index: -1;
    opacity: 0.89;
}

#home h1 {
    color: white;
    text-align: center;
    font-family: 'Times New Roman', Times, serif;
}

#home p {
    color: white;
    text-align: center;
    font-size: 1.5rem;
    font-family: 'Times New Roman', Times, serif;
}

/* Service Section*/
#services {
    /*background:url('../background.jpg') no-repeat center center/cover;*/
    background-color: white;
    margin: 0px 0px 0px 0px;
    text-align: center;
    height: 700x;
    display: flex;
}

#service.box {
    border: 0px solid rgb(7, 7, 7);

    text-align: center;
    padding: 0px 0px;
    margin: 2px 0px 0px 0px;
    border-radius: 28px;
    margin-bottom: 20px;
}

#services .box img {
    text-align: center;
    height: 300px;
    width: 403px;
    margin: 12px 7px 13px 8px;
    padding: 10px 12px 4px 4px;
    display: flex;
    align-items: initial;
    flex-wrap: nowrap;
    display: block;

}

#services-container h1 {
    color: cyan;
    background-color: darkgreen;
    text-align: center;
    font-family: 'Times New Roman', Times, serif;
}

#services .box p {
    color: black;
    font-family: 'Times New Roman', Times, serif;
    text-align: center;
    font-size: 1rem;

}

/* Client Section*/
#Achievers-section {
    position: relative;
}

#Achievers-section::before {
    content: "";
    position: absloute;
    background-color: lightblue;
    width: 100%;
    height: 100%;
    z-index: -1;
    opacity: 0.3;
}

#Achievers {
    display: flex;
    justify-content: center;
    align-items: center;
}

.Achivers-item {
    padding: 5px;
    margin: 0px 0px 0px 0xp;
}

#Achivers img {
    height: 100px;
    width: 100px;
}

.achiver1.jpg {
    height: 10px;
    width: 10px;

}

#Achievers-section h1 {
    color: cyan;
    background-color: darkgreen;
    text-align: center;
    font-family: 'Times New Roman', Times, serif;
}

#Achievers-section.achiver1.jpg img {

    height: 100px;
    width: 100px;
    margin: 12px 7px 13px 8px;
    padding: 10px 12px 4px 4px;
    display: flex;
    align-items: initial;
    flex-wrap: nowrap;
    display: block;

}

#Achievers-section.achiver2.jpg img {

    height: 100px;
    width: 100px;
    margin: 0px 0px 0px 0px;
    padding: 0px 0px 0px 0px;
    display: flex;
    align-items: initial;
    flex-wrap: nowrap;
    display: block;

}

#contact-box {
    text-align: center;
    display: flex;
    justify-content: center;
    align-items: center;
    padding-bottom: 34px;
}

#contact-box textarea {
    width: 100%;
    padding: 0.5rem;
    border-radius: 9px;
    font-size: 1.1rem;
}

#contact-box form {
    text-align: center;
    width: 40%;
}

#contact-box label {
    text-align: center;
    font-size: 1.3rem;
    font-family: 'Bree Serif', serif;

}


footer {
    background: black;
    color: white;
    padding: 0px 0px;
}

/* Utility Classes */
.h-primary {
    font-family:'Times New Roman', Times, serif;
    font-size: 1.3rem;
    padding: 0px;
}

.h-secondary {
    font-family: 'Bree Serif', serif;
    font-size: 1.0rem;
    padding: 0px;
}

.btn {
    padding: 0px 0px;
    border: 2px solid white;
    background-color: brown;
    color: white;
    margin: 17px;
    font-size: 1.5rem;
    border-radius: 10px;
    cursor: pointer;
}

.center {
    text-align: center;
}
