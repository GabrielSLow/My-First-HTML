# My First HTML
<!DOCTYPE html>
<html>
	<head>
		<title>Learning HTML</title>
        <meta charset="UTF-8">
        <meta name="description" content="My first HTML website">
        <link rel="stylesheet" href="index.css">

		<meta name=“viewport” content=“width=device-width, initial scale=1.0”

		<link rel=“stylesheet” href=“index.css”>
		<link rel=“stylesheet” href="https://use.fontawesome.com/releases/v5.0.6/css/all.css">

</head> <body>id="home" class="open-left">
        <section class="center">
            <header>
                <nav>
                    Navigation
		    <ul>
			<li><a href=“#” > Top </a></li>
			<li><a href="#" > Quote </a></li>
                        <li><a href="#" > Contact Us </a></li>
			<li><a href="#"> Next Page </a></li>
                    </ul>
 		</div>
       		<div class="togglebar">
            		<!-- adds the class of hide to .offcanvas.left -->
            	<div class="toggle" onclick="toggleLeft()">
              		<i class="fa fa-bars"></i>
            	</div>
        </div>
	<div class="center">
            <header>
                <nav>
                    <ul>
                        <li><a href=“#top” > Top </a></li>
                        <li><a href=“#quote” > Quote 1 </a></li>
                        <li><a href=“#contact” > Contact Us 1 </a></li>
			<li><a href=“#next.html”> Next Page </a></li>
                    </ul>
                </nav>
            </header>
            <section>
                <main id="top">
                    <article>
                        <figure class=“hero”>
			<img src=“https://picsum.photos/1200/440/?image=201" alt=“a laptop with a mouse on a desk and a pair of glasses.”/>
			<figcaption>
				The figure image caption
			</figcaption>
			
			<video src=“https://www.w3schools.com/html/mov_bbb.mp4” controls autoplay muted loop preload width=“600” height=“350”>
			</figure>
			<div class=“responsive-vid”>
		<figcaption>
			<h1>Learning HTML</h1>
                </figcaption>
                        </figure>
                        <h2 style="font-size: 3em">This is the second most important heading!</h2>
                        <h6>This is the least important heading!</h6>
			<hr>
			 <p>
                            <b>Hypertext Markup Language (HTML)</b> is the standard markup language for creating web pages and web applications. With <i>Cascading Style Sheets (CSS)</i> and <em>JavaScript</em>, it forms a triad of <strong>cornerstone technologies</strong> for the World Wide Web. Web browsers receive <mark>HTML documents</mark> from a web server or from local storage and render them into multimedia web pages. <a href="#">HTML describes</a> the structure of a web page semantically and originally included cues for the appearance of the document.
                        </p>
			<p>
                            Web browsers receive <q>HTML documents</q> from a web server or from local storage and render them into multimedia web pages. <a 				    href="#">HTML describes</a> the structure of a web page semantically and originally included cues for the appearance of the document.
                        </p>
                    <blockquote cite="http://twitter.com" id="quote">
                            "Every great developer you know got there by solving problems they were unqualified to solve until they actually did it." - Patrick McKenzie
                        </blockquote>
<!-- Tables-->
                        <table class="styled">
                            <colgroup>
                                <col style="background-color: blueviolet;">
                            </colgroup>
                            <colgroup>
                                <col style="background-color: #f4e767;" span="2">
                            </colgroup>
                            <thead>
                                <tr>
                                    <th>First Name</th>
                                    <th>Last Name</th>
                                    <th>Email</th>
                                </tr>
                            </thead>
                            <tbody>
                                <tr>
                                    <td>John</td>
                                    <td>Doe</td>
                                    <td>Johnny.doe@gmail.com</td>
                                </tr>
                                <tr>
                                    <td>Jane</td>
                                    <td>Doe</td>
                                    <td>i_heart_johnny@gmail.com</td>
                                </tr>
                            </tbody>
                        </table>  
 				</section>
                    </article>
                </main>
                <footer>
                    <section>
                        <table class="styled">
                            <tr>
                                <th colspan="2">Working Hours</th>
                            </tr>
                            <tr>
                                <td>mon-fri</td>
                                <td>7am-6pm</td>
                            </tr>
                            <tr>
                                <td>sat-sun</td>
                                <td>closed</td>
                            </tr>
                        </table>
                        <table class="styled">
                            <tr>
                                <th colspan="2">Contact Info</th>
                            </tr>
                            <tr>
                                <td>Cell:</td>
                                <td>123.345.6789</td>
                            </tr>
                            <tr>
                                <td>Email:</td>
                                <td>info@learninghtml.com</td>
                            </tr>
                        </table>
                    </section>
		<section>
                        <form action="/action_page.php" id="contact">
                            <legend><b>Contact Us</b></legend>
                            <input type="text" name="fullname" placeholder="Full name">
                            <input type="text" name="email" placeholder="Email">
                            <textarea name="msg" placeholder="Write message here"></textarea>
                            <input type="submit" value="Submit">
                            <!-- https://www.w3schools.com/tags/tag_form.asp -->
                        </form>
                    </section>                  
            </footer>
        </section>
</div>
        <script type="text/javascript" src="index.js"></script>
    </body>

</html>
