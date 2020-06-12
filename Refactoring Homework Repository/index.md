<!DOCTYPE html>
<html lang="en-us">
<head>
    <meta charset="UTF-8" />
    <link rel="stylesheet" href="style.css">
    <title>Horiseon Marketing Solutions</title>
</head>

<body>
    <header>
    <div class="header">
        <h1>Hori<span class="seo">seo</span>n Marketing Solutions</h1>
        <hr/>
        <div>
        <article>
            <nav>
            <ul>
                <li>
                    <a href="#search-engine-optimization">Search Engine Optimization</a>
                </li>
                <li>
                    <a href="#online-reputation-management">Online Reputation Management</a>
                </li>
                <li>
                    <a href="#social-media-marketing">Social Media Marketing</a>
                </li>
            </ul>
            </nav>
        </article>
    </header>    
        </div>
    </div>
    <div class="hero"></div>
    <span class="background image" role="img" aria-label="four people in a meeting"> </span>
    <div class="content">
    </br>
    <section>
        <div id="search-engine-optimization" class="search-engine-optimization">
            <h2>Search Engine Optimization</h2>
            <img src="search-engine-optimization.jpg" class="float-left" alt="search-engine-optimization-criteria">
            <p>
                The dominance of mobile internet use means that users are searching for the right business as they travel, shop, or sit on their couch at home. 
            </br>Search Engine Optimization (SEO) allows you to increase your visibility and find the right customers for your business.
            </p>
        </div>
    </section>
    <section>
        <div id="online-reputation-management" class="online-reputation-management">
            <h2>Online Reputation Management</h2>
            <img src="online-reputation-management.jpg" class="float-left" alt="reputation charts">
            <p>
                The web is full of opinions, and some of these can be negative. 
            </br>Social media allows anyone with an internet connection to say whatever they want about your business. 
            </br>Online Reputation Management gives you the control over what potential customers see when they search for your business.
            </p>
        </div>
    </section>
    <section>
        <div id="social-media-marketing" class="social-media-marketing">
        </br>
            <h2>Social Media Marketing</h2>
            <img src="social-media-marketing.jpg" class="float-left"alt="social media images and terms">
            <p>
                Social media continues to have a sizable influence on buying habits. 
            </br>Social media marketing helps you determine which platforms are suited to your brand, using analytics to find the right markets and increase your lead generation.
            </p>
        </div>
    </section>
    </div>
    <div class="benefits">
        <aside>
        <div class="benefit-lead">
        </br>
            <h2>Lead Generation</h2>
            <img src="lead-generation.png" alt="conversion funnel">
            <p>
                Inbound strategies for lead generation require less work for your business, bringing customers directly to your website.
            </p>
        </div>
        <div class="benefit-brand">
        </br>
            <h2>Brand Awareness</h2>
            <img src="brand-awareness.png" alt="lightbulb with suit">
            <p>
                Users find your business through paid and organic searches, increasing the search ranking and visibility for your business.
            </p>
        </div>
        <div class="benefit-cost">
        </br>
            <h2>Cost Management</h2>
            <img src="cost-management.png" alt= "Three dollar signs under a big cog">
            <p>
                As the search ranking for your business increases, your advertising costs decrease, and you no longer need to advertise your page.
            </p>
        </aside>
        </div>
    </div>
    <footer>
    <div class="footer">
        </br>
        <h4>Made with ❤️️ by Horiseon</h4>
        <p>
            &copy; 2019 Horiseon Social Solution Services, Inc.
    </footer>
        </p>
    </div>
</body>
</html>
* {
    box-sizing: border-box;
    padding: 0;
    margin: 0;
}

body {
    background-color: #d9dcd6;
}

.header {
    padding: 38px;
    font-family: 'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;
    background-color: #2a607c;
    color: #ffffff;
}

.header h1 {
    display: inline-block;
    font-size: 48px;
}

.header h1 .seo {
    color: #d9dcd6;
}

.header div {
    padding-top: 15px;
    margin-right: 20px;
    float: right;
    font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
    font-size: 20px;
}

.header div ul {
    list-style-type: none;
    direction: up;
}

.header div ul li {
    display: inline-block;
    margin-left: 25px;
}

a {
    color: #ffffff;
    text-decoration: none;
}

p {
    font-size: 16px;
}

.hero {
    height: 800px;
    width: 100%;
    margin-bottom: 25px;
    background-image: url("digital-marketing-meeting.jpg");
    
    background-size: cover;
    background-position: center;
}

.float-left {
    float: left;
    margin-right: 25px;
}

.float-right {
    float: right;
    margin-left: 25px;
}

.content {
    width: 75%;
    display: inline-block;
    margin-left: 20px;
}

.benefits {
    margin-right: 20px;
    padding: 20px;
    clear: both;
    float: right;
    width: 20%;
    height: 100%;
    font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
    background-color: #2589bd;
}

.benefit-lead {
    margin-bottom: 32px;
    color: #ffffff;
}

.benefit-brand {
    margin-bottom: 32px;
    color: #ffffff;
}

.benefit-cost {
    margin-bottom: 32px;
    color: #ffffff;
}

.benefit-lead h3 {
    margin-bottom: 10px;
    text-align: center;
}

.benefit-brand h3 {
    margin-bottom: 10px;
    text-align: center;
}

.benefit-cost h3 {
    margin-bottom: 10px;
    text-align: center;
}

.benefit-lead img {
    display: block;
    margin: 10px auto;
    max-width: 150px;
}

.benefit-brand img {
    display: block;
    margin: 10px auto;
    max-width: 150px;
}

.benefit-cost img {
    display: block;
    margin: 10px auto;
    max-width: 150px;
}

.search-engine-optimization {
    margin-bottom: 20px;
    padding: 20px;
    height: 300px;
    font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
    background-color: #0072bb;
    color: #ffffff;
}

.online-reputation-management {
    margin-bottom: 20px;
    padding: 20px;
    height: 300px;
    font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
    background-color: #0072bb;
    color: #ffffff;
}

.social-media-marketing {
    margin-bottom: 20px;
    padding: 20px;
    height: 300px;
    font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
    background-color: #0072bb;
    color: #ffffff;
}

.search-engine-optimization img {
    max-height: 200px;
}

.online-reputation-management img {
    max-height: 200px;
}

.social-media-marketing img {
    max-height: 200px;
}

.search-engine-optimization h2 {
    margin-bottom: 20px;
    font-size: 36px;
}

.online-reputation-management h2 {
    margin-bottom: 20px;
    font-size: 36px;
}

.social-media-marketing h2 {
    margin-bottom: 20px;
    font-size: 36px;
}

.footer {
    padding: 30px;
    clear: both;
    font-family: 'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;
    text-align: center;
}

.footer h2 {
    font-size: 20px;
}
