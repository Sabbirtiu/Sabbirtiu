<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Welcome to Our Website</title>
    <link rel="stylesheet" href="styles.css">
    <script src="script.js" defer></script>
</head>
<body>
    <div id="page">
        <span class="extra"></span>
        <div id="header">
            <div id="logo">
                <h1>Our Logo</h1>
            </div>
            <ul id="navigation">
                <li class="selected"><a href="# ">Home</a></li>
                <li><a href="# ">About</a></li>
                <li><a href="# ">Services</a></li>
                <li><a href="# ">Contact</a></li>
            </ul>
        </div>
        <div id="contents">
            <h1>Marriage is compulsory for all</h1>
            <p>Welcome to our website! We are glad to have you here.</p>
            <div id="user-input-section">
                <label for="user-input">Enter your name: </label>
                <input type="text" id="user-input">
                <button onclick="displayGreeting()">Submit</button>
                <p id="greeting-message"></p>
            </div>
            <div class="section">
                <p>Some content here.. . </p>
            </div>
        </div>
        <div id="footer">
            <p>Student ID: 22319038 | Name: Hossain Sabbir</p>
        </div>
    </div>
</body>
</html>
body {
    background: url(../images/bg-body.jpg) repeat left top
}
#page {
    background: url(../images/bg-page.png) no-repeat right top;
    width: 960px;
    margin: 0 auto;
    padding-top: 54px;
    position: relative;
}
img {
    border: 0;
}
#page span.extra {
    background: url(../images/bg-extra.png) repeat-x right top;
    display: block;
    height: 122px;
    width: 100%;
    position: absolute;
    left: -960px;
    top: 54px;
}
/*------------------------------ HEADER ------------------------------*/
#header {
    background: url(../images/bg-header.png) no-repeat right top;
    height: 122px;
    line-height: 122px;
    text-align: right;
}
/** Logo **/
#logo {
    float: left;
    display: inline-block;
    height: 86px;
    width: 300px;
    margin-left: 68px;
    margin-top: 16px;
}
/** Navigation **/
#navigation {
    display: inline-block;
    list-style: none;
    width: 312px;
    margin: 0 10px;
    padding: 0;
}
#navigation li {
    float: left;
    font-size: 14pt;
    padding: 0 30px;
    text-align: center;
}
#navigation li a {
    color: #fff;
    font: 18px/24px Georgia, "Times New Roman", Times, serif;
    text-decoration: none;
    text-shadow: 1px -1px #661021;
}
#navigation li a:hover, #navigation li.selected a {
    background: url(../images/bg-menuhover.gif) repeat-x left bottom;
    color: #ffffff;
    padding-bottom: 5px;
}
/*------------------------------ CONTENTS ------------------------------*/
#contents {
    background: url(../images/bg-content.png) repeat-y right top;
    padding: 30px 38px 0 70px;
}
#contents p {
    color: #616161;
    font-size: 16px;
    line-height: 30px;
    margin: 0;
    padding: 0 0 30px;
    text-align: justify;
}
#contents p a {
    color: #616161;
}
#contents a:hover {
    color: #3c3839;
}
#contents .section {
    float: left;
    min-height: 590px;
    width: 426px;
    margin-bottom: 30px;
}
#contents .section p {
    color: #a51330;
    font-size: 22px;
    line-height: 30px;
    padding: 0 20px;
}
#contents .section b {
    display: block;
    font-weight: normal;
    text-transform: uppercase;
}
#contents .section p span {
    display: block;
    color: #787369;
    font-size: 14px;
    padding-bottom: 6px;
}
#contents .section i {
    color: #a79d88;
}
#contents div.frame {
    width: 410px;
    margin-bottom: 24px;
    -moz-box-shadow: 0 0 5px 5px rgba(200,200,200,0.6);
    -webkit-box-shadow: 0 0 5px 5px rgba(200,200,200,0.6);
    box-shadow: 0 0 5px 5px rgba(200,200,200,0.6);
}
#contents div.frame > div {
    background-color: #fff7e7;
    display: inline-block;
}
#contents div.frame > div.first img {
    margin-bottom: 3px;
}
#contents div.frame > div.first p {
    line-height: 36px;
}
#contents div.frame img {
    border: 2px solid #fff;
}
#contents div.frame > div.noImg {
    padding: 41px 20px 6px;
}
#contents div.frame > div.noImg p {
    font-size: 24px;
    line-height: 38px;
}
#contents div.frame > div.sideImg img {
    float: left;
    margin-bottom: 0;
    margin-right: 20px;
}
#contents div.frame > div.sideImg p {
    padding: 20px 40px 20px 20px;
    text-align: left;
}
#contents .footer {
    background: url(../images/border.gif) repeat-x left bottom;
    clear: both;
    color: #616161;
    padding-bottom: 32px;
}
#contents .footer > div {
    background: url(../images/border-heading.gif) repeat-x left 22px;
    display: inline-block;
    width: 852px;
}
#contents .footer h1 {
    background: url(../images/bg-heading.png) no-repeat center top;
    color: #fff;
    font: bold 28px/50px Georgia, "Times New Roman", Times, serif;
    height: 56px;
    letter-spacing: 1px;
    width: 300px;
    margin: 0 auto;
    text-align: center;
    text-shadow: 1px -1px #661021;
    text-transform: uppercase;
}
#contents .footer h2 {
    text-transform: uppercase;
}
#contents .footer img {
    float: left;
    border: 4px solid #bcbcbc;
    margin-right: 30px;
}
#contents .footer p {
    font-size: 18px;
}
/** connect **/
#connect {
    float: right;
    width: 200px;
    margin-left: 60px;
}
#connect h2 {
    color: #616161;
    font: bold 20px/30px Georgia, "Times New Roman", Times, serif;
    text-transform: uppercase;
}
#connect a {
    background: url(../images/icons.png) no-repeat;
    color: #616161;
    display: block;
    font-size: 20px;
    height: 55px;
    line-height: 55px;
    margin-bottom: 6px;
    padding-left: 70px;
    text-decoration: none;
}
#connect a.facebook {
    background-position: 0 -65px;
}
#connect a.twitter {
    background-position: 0 -195px;
}
#connect a.googleplus {
    background-position: 0 -325px;
}
#connect a.facebook:hover {
    background-position: 0 0;
}
#connect a.twitter:hover {
    background-position: 0 -130px;
}
#connect a.googleplus:hover {
    background-position: 0 -260px;
}
/** Tabs **/
#tab {
    background: url(../images/border.gif) repeat-x left bottom;
    height: 40px;
    margin-bottom: 24px;
}
#tab ul {
    list-style: none;
    margin: 0;
    padding: 0;
}
#tab ul li {
    float: left;
    margin-left: 10px;
}
#tab ul li:first-child {
    margin-left: 0;
}
#tab ul li a {
    background-color: #9d9d9d;
    color: #fff;
    display: inline-block;
    font: 16px/37px Georgia, "Times New Roman", Times, serif;
    border-top: 1px solid #838383;
}
