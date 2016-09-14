<!DOCTYPE html>
<html>

<head>
    <style>
        * {
            font-family: sans-serif;
        }
        
        body {
            background-color: #333;
        }
        
        ul {
            list-style-type: none;
            margin: -9px;
            padding: 0;
            overflow: hidden;
            background-color: #333;
        }
        
        li {
            float: left;
        }
        
        #logo {
            text-decoration: none;
            color: whitesmoke;
            font-weight: bold;
            background-color: dodgerblue;
            text-align: center;
            padding: 17px 30px;
        }
        
        li a,
        .dropbtn {
            display: inline-block;
            color: white;
            text-align: center;
            padding: 17px 30px;
            text-decoration: none;
        }
        
        li a:hover,
        .dropdown:hover .dropbtn {
            background-color: black;
        }
        
        li.dropdown {
            display: inline-block;
        }
        
        .dropdown-content {
            display: none;
            position: absolute;
            background-color: #f9f9f9;
            min-width: 160px;
            box-shadow: 0px 8px 16px 0px dimgrey;
        }
        
        .dropdown-content a {
            color: black;
            padding: 12px 16px;
            text-decoration: none;
            display: block;
            text-align: left;
        }
        
        .dropdown-content a:hover {
            background-color: gainsboro;
        }
        
        .dropdown:hover .dropdown-content {
            display: block;
        }
        
        firstimage {
            display: block;
        }
        
        .content {
            float: left;
            display: inline-block;
            background-color: white;
            margin-top: 20px;
            margin-left: 20px;
            padding-left: 10px;
            padding-right: 10px;
            width: 33%;
            border: 3px solid #333;
            border-radius: 25px;
        }
        
        .contentheader {
            border-bottom: 4px solid dodgerblue;
            margin-top: 0px;
            text-align: center;
        }
        
        img {
            margin-top: 9px;
            margin-left: 1px;
            width: 100%;
        }
        
        iframe {
            float: left;
            margin: 10px;
            width: 95%;
        }
    </style>
</head>

<body>

    <ul>
        <li id="logo"> Logo </li>
        <li><a href="#" class="active"> First </a> </li>
        <li><a href="#"> Second  </a> </li>
        <li class="dropdown">
            <a href="#" class="dropbtn">Dropdown</a>
            <div class="dropdown-content">
                <a href="#">Link 1</a>
                <a href="#">Link 2</a>
                <a href="#">Link 3</a>
            </div>
        </li>
    </ul>

    <div>
        <center>
            <img src="nepalschool.png">
        </center>
    </div>

    <center>
        <div class="content">
            <div class="contentheader">
                <h1> Header </h1>
            </div>
            <p>
                Interested in our idea? Sign up here:
                <iframe src="https://docs.google.com/a/tas.tw/forms/d/e/1FAIpQLSfMNYqROBV6IiPSOWLlu_oGeokatY6qvSDHBInov1GhCpKj-Q/viewform?embedded=true" width="760" height="500" frameborder="0" marginheight="0" marginwidth="0">Loading...</iframe>
            </p>
        </div>
        <div class="content">
            <div class="contentheader">
                <h1> Header </h1>
            </div>
            <p>Llamas appear to have originated from the central plains of North America about 40 million years ago. They migrated to South America about three million years ago. By the end of the last ice age (10,000–12,000 years ago), camelids were extinct in North America.[4] As of 2007, there were over seven million llamas and alpacas in South America, and due to importation from South America in the late 20th century, there are now over 158,000 llamas and 100,000 alpacas in the United States and Canada. A cria (from Spanish for "baby") is the name for a baby llama, alpaca, vicuña, or guanaco. Crias are typically born with all the females of the herd gathering around, in an attempt to protect against the male llamas and potential predators. Llamas give birth standing. Birth is usually quick and problem-free, over in less than 30 minutes. Most births take place between 8 am and noon, d</p>
        </div>

    </center>
    </body>
</html>
