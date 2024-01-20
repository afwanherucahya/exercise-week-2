Css

#paragraph-1{
    color: black;
}

.col{
    width: 700px;
}

* { /*Selector untuk semua*/
    margin: 0;
    padding: 0;    
}

body{
    background-color: gainsboro;
}

.navbar{
    background-color: black;
    color: white;
    display: flex;
    flex-direction: row;
    justify-content: space-between;
    margin-bottom: 64px;
    padding: 12px 128px;
}

.navbar ul{
    display: flex;
    flex-direction: row;
    list-style: none;
    gap: 16px;
}

#post{
    margin: 16px 128px 128px 128px;

}

#post .row{
    display: flex;
    flex-direction: row;
    gap: 32px;
}

#post .row .col{
    width: 100%;
}

#post .row .col h3{
    text-align: left;
    margin: 8px 0;
}

#post .row .col #my-page {
    margin-bottom: 16px; /* Jarak 16px dari my-page ke the-team */
}

#post .row .col #the-team {
    margin-bottom: 64px; /* Jarak 64px dari the-team ke we-offer */
}

#post .row .col article{
    border: 1px solid black;
    background-color: white;
    border-radius: 16px;
    padding: 16px;
    margin: 1px 0;
}

#post .row .col #the-team .image-team {
    text-align: center;
}

#post .row .col #the-team img {
    background-color: black;
    border: 1px solid black;
    width: 100px;
    height: 100px;
    object-fit: cover;
    border-radius: 64px; 
    margin-right: 16px; 
    justify-content: center;
    color: white;
}

#post .row .col article form {
    width: 100%;
}

#post .row .col article label,
#post .row .col article input,
#post .row .col article textarea {
    width: 100%;
    box-sizing: border-box;
    margin-bottom: 16px;
}

#post .prev-next{
    display: flex;
    justify-content: center;
    margin-top: 360px;

}

#post .row .col article textarea {
    height: 64px;
}

#post .prev-next #prev-btn{
    width: 64px;
    height: 32px;
    background-color: black;
    color: white;
}

#post .prev-next #next-btn{
    width: 64px;
    height: 32px;
    background-color: black;
    color: white;
    margin-left: 128px;
}

#post .row .col .submit {
    display: flex;
    justify-content: center;
    margin-top: 16px; 
}

#post .row .col .submit button {
    width: 96px;
    height: 32px;
    background-color: black;
    color: white;
    border: none;
    border-radius: 8px;
}

footer{
    position: fixed;
    bottom: 0;
    width: 100%;
    background-color: black;
    color: white;
    text-align: center;
    padding: 16px 0;    
}

About

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="icon" href="path/to/favicon.ico" type="image/x-icon">
    <link rel="shortcut icon" href="assets/icons/favicon.png" type="image/x-icon">
    <link rel="stylesheet" type="text/css" href="assets/css/style.css">
    <title>About</title>
</head>
<body>
    <nav class="navbar">
        <div class="brand">Blog</div>
        <ul>
            <a href="index.html">Home</a>
            <a href="about.html">About</a>
            <a href="contact.html">Contact</a>
        </ul>
    </nav>

    <section id="post">
        <div class="row"> 
            <div class="col">
                <article id="my-page">
                    <h3>About My Page</h3>
                    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Reiciendis, numquam excepturi pariatur cupiditate quam quas nam recusandae laudantium facere labore natus minus! Veritatis assumenda nihil, incidunt obcaecati illum mollitia eos?    
                    </p>
                </article>
                <article id="the-team">
                    <h3>Meet The Team</h3>
                    <div class="image-team"> 
                        <img src="assets/icons/profile.png" alt="IMG">
                        <img src="https://i.pinimg.com/originals/83/47/c2/8347c25869e30dd3e00e3d0e3b7bac66.png" alt="IMG">
                        <img src="assets/icons/profile3.png" alt="IMG">
                    </div>

                </article>
                <article id="we-offer">
                    <h3>What We Offer</h3>
                    <p> 
                        - Lorem ipsum dolor sit amet consectetur adipisicing elit. 
                    </p>
                    <p> 
                        - Reiciendis, numquam excepturi pariatur      
                    </p>
                    <p> 
                        - Veritatis assumenda nihil    
                    </p>
                    <p> 
                        - Incidunt obcaecati illum mollitia eos?    
                    </p>
                </article>
            </div>
                       
        </div>

    </section>

    <footer>
        <div class="brand">My Blogspot</div>
    </footer>
</body>
</html>

Contact
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="icon" href="path/to/favicon.ico" type="image/x-icon">
    <link rel="shortcut icon" href="assets/icons/favicon.png" type="image/x-icon">
    <link rel="stylesheet" type="text/css" href="assets/css/style.css">
    <title>Contact</title>
</head>
<body>
    <nav class="navbar">
        <div class="brand"></div>
        <ul>
            <a href="index.html">Home</a>
            <a href="about.html">About</a>
            <a href="contact.html">Contact</a>
        </ul>
    </nav>

    <section id="post">
        <h3>Contact Us</h3>
        <div> lorem ipsum 
            <div class="row"> 
                <div class="col">
                    <article>
                        <form action="">
                            <label for="name">Name</label>
                            <input type="text" placeholder="Name" id="name">
                            
                            <label for="email">Email</label>
                            <input type="email" placeholder="Email" id="email">
                            
                            <label for="text">Message</label>
                            <textarea placeholder="your message..." id="text" rows="4"></textarea>
                        </form>
                    </article>
                    <div class="submit">  
                        <button id="submit">Submit</button> 
                    </div>        
            </div>
        </div>
    </section>

    <footer>
        <div class="brand">My Blogspot</div>
    </footer>
</body>
</html>

Home

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="icon" href="path/to/favicon.ico" type="image/x-icon">
    <link rel="shortcut icon" href="assets/icons/favicon.png" type="image/x-icon">
    <link rel="stylesheet" type="text/css" href="assets/css/style.css">
    <title>Home</title>
</head>
<body>
    <nav class="navbar">
        <div class="brand">Blog</div>
        <ul>
            <a href="index.html">Home</a>
            <a href="about.html">About</a>
            <a href="contact.html">Contact</a>
        </ul>
    </nav>

    <section id="post">
        <div class="row"> 
            <div class="col">
                <article>
                    <h3>Blog Title</h3>
                    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Reiciendis, numquam excepturi pariatur cupiditate quam quas nam recusandae laudantium facere labore natus minus! Veritatis assumenda nihil, incidunt obcaecati illum mollitia eos?    
                    </p>
                </article>
            </div>           
        </div>
        <div class="prev-next">
            <button id="prev-btn">Prev</button>
            <button id="next-btn">Next</button>
        </div>
    </section>

    <footer>
        <div class="brand">My Blogspot</div>
    </footer>
</body>
</html>
