<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Startup Matchmaker</title>

    <style>

        ,::before,*::after {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
        }

        body {
            font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
        }

        a {
            text-decoration: none;
        }

        .container {
            width: 80%;
            margin-left: auto;
            margin-right: auto;
        }

        .yellow {
            color: yellow;
        }

        .text-center {
            text-align: center;
        }

        .line-cut {
            text-decoration: line-through;
        }

        .underline {
            text-decoration: underline;
            text-decoration-color: yellow;
        }


        #main-header > .first-content {
            display: flex;
            justify-content: space-between;
            align-items: center;
            border-bottom: 3px solid yellow;
            background: #000;
            padding: 20px;
        }

        #main-header > .second-content {
            display: flex;
            justify-content: center;
            padding-top: 30px;
            padding-bottom: 30px;
            background: gray;
            color: #000;
            font-size: 24px;
            font-weight: bold;
        }

        #main-header ul {
            display: flex;
            list-style: none;
        }

        #main-header ul li a {
            padding: 12px;
            color: #fff;
        }

        #banner {
            height: 660px;
            background: url("https://previews.123rf.com/images/ferli/ferli1604/ferli160400123/54703699-portrait-of-creative-business-people-teamwork-meeting-at-cafe.jpg");
            background-repeat: no-repeat;
            background-size: cover;
            background-position: center center;
            display: flex;
            justify-content: flex-end;
            align-items: center;
            padding-right: 30px;
            padding-left: 30px;
        }

        #banner > .banner-content {
            background: rgba(255, 255, 255, 0.9);
            width: 380px;
            height: 260px;
            padding: 30px;
            box-shadow: 0px 0px 30px rgba(255, 255, 255, 0.5);
        }

        #banner > .banner-content h4 {
            margin-bottom: 20px;
        }

        #banner > .banner-content p {
            margin-bottom: 20px;
        }

        #banner > .banner-content .btn {
            display: block;
            background: rgb(255, 123, 0);
            color: #000;
            text-transform: uppercase;
            padding: 12px;
            text-align: center;
            font-weight: bold;
        }

        #main > .item {
            justify-content: space-between;
            align-items: center;
            padding-top: 100px;
            padding-bottom: 100px;
        }

    </style>
</head>
<body>
    <header id="main-header">
        <div class="first-content">
            <h2 class="logo yellow">Startup Matchmaker</h2>

            <ul>
                <li><a href="#">Find Developer</a></li>
                <li><a href="#">Find Designer</a></li>
                <li><a href="#">How it Works</a></li>
                <li><a href="#">Our Team</a></li>
                <li><a href="#">Blog</a></li>
            </ul>
        </div>
        <div class="second-content">
            <p>Because two brains <span class="line-cut">taste</span> <span class="underline">are</span> better than one.</p>
        </div>
    </header>
    
    <div id="banner">
        <div class="banner-content">
            <h3>Meet your Match!</h3>
            <p>Hello there..  Have a great idea for a product, but need help making it a reality? We’re here to help.
                Startup Matchmaker is the best place for designers and developers to find each other.
                </p>
            <a href="#" class="btn">Create account</a>
        </div>
    </div>
</body>
<div>
<p></p><br><p></p>
    <div id:"column" >
        <div class="item">
        <img src="img/customer-profile-template.jpg" alt="create-profile" />
        <h4>Create Profile</h4>
        <p>Are you a designer ? developer ?
             put yourself out there so others can find you.
            </p>
            <button>SIGN UP NOW </button>
    </div>
    <p></p><br><p></p>
    <div id:"column" >
        <div class="item">
        <img src="img/developer 1.png" alt="find developer" />
        <h4>Find Developer</h4>
        <p>Looking for a fantastic developer to work with on the next
             big thing ? Look no  further.
            </p>
            <button>START YOUR SEARCH</button>
    </div>
    <p></p><br><p></p>
        <div id:"column" >
        <div class="item">
        <img src="img/designer.webp" width:"50" height:"50" alt="find designer" />
        <h4>Find Designer</h4>
        <p>Need someone who can make a product intuitive and appealing?
            Get ready.
        </p>
        <button>START YOUR SEARCH</button>

    </div>
    </div>
</div>

</html>

