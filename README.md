<!DOCTYPE html>
<html lang="en"><head>
<meta http-equiv="content-type" content="text/html; charset=UTF-8">
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Portfolio</title>
	<link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&family=Inter:wght@400;700&family=Open+Sans:wght@400;700&family=Lato:wght@400;700&family=Abel&family=Montserrat:wght@400;700&family=Poppins:wght@400;700&family=Noto+Sans:wght@400;700&family=Raleway:wght@400;700&family=Source+Sans+Pro:wght@400;700&family=Merriweather:wght@400;700&family=Oswald:wght@400;700&family=Barlow:wght@400;700&family=Assistant:wght@400;700&family=Urbanist:wght@400;700&display=swap">	
    <style>
        body {
            background-color: #000;
            color: #fff;
            font-family: Source Sans Pro, sans-serif;
            margin: 0;
            padding: 0;
            box-sizing: border-box;
			text-align:center;
        }
		
		h1 {
			font-family:lato;
			font-size:40px;
			width:100%;
			margin:20px;
			margin-left:0px;
			padding:0;
		}
		
		h2 {
			font-family:roboto;
			font-size:30px;
			opacity:0.7;
			width:100%;
			margin:20px;
			margin-left:0px;
			padding:0;
		}
		
		h3 {
			font-family:abel;
			font-size:26px;
			width:100%;
			margin:0;
			padding:0;
		}
		
        .container {
            display: flex;
            flex-wrap: wrap;
            justify-content: space-around;
            align-items: center;
			font-size:18px;
			max-width:800px;
			height:auto;
        }
		
		header {
			width:100%;
            display: flex;
            align-items: center;
            justify-content: center;
			text-align:left;
		}
		
		header img {
			max-width:250px;
			border:10px solid white;
			border-radius:50%;
		}
		
		section {
			width:100%;
            display: flex;
            align-items: center;
            justify-content: center;
		}
		
		.main-content div {
			width:300px;
			height:auto;
			margin:10px;
			padding:10px;
			
			color:white;
			text-align:center;
			font-family: Arial, sans-serif;
			font-size:30px;
		}
		
		.main-content h3 {
			margin:5px;
		}
		
		.main-content p {
			font-size:18px;
		}
		
		.main-content img {
			width:250px;
			border:10px solid white;
			box-shadow:0 10px 16px 0 rgba(0,0,0,0.5),0 6px 20px 0 rgba(0,0,0,0.5) !important;
		}
		
		.project {
			background-color: #222;
		}
		
		.project img {
			background-color: #252525;
		}
		
		.architecture {
			background-color: #222;
		}
		
		footer {
			background-color: #10121f;
			padding: 20px;
			color: #fff;
			text-align: center;
		}

		.footer-links {
			display: flex;
			flex-wrap: wrap;
			justify-content: space-around;
		}

		.footer-column {
			flex: 1;
			text-align: center;
			margin-bottom: 20px;
		}

		footer a {
			color: #fff;
			text-decoration: none;
			display: block;
			margin-bottom: 8px;
		}

		.social-icons {
			margin-top: 0px;
        }

        .social-icons a {
            display: inline-block;
            margin: 0 10px;
            color: #fff;
            font-size: 24px;
            text-decoration: none;
        }

		.small-logo {
			height:30px;
			margin-top:0px;
		}
		
		@media (min-width: 768px) {
			.footer-links {
				flex-direction: column;
				text-align: center;
			}

			.footer-column {
				flex: 1;
				text-align: center;
				margin-bottom: 20px;
			}
		}
    </style>
</head>
<body>
    

	<header>
		<div class="container">
			<h1>Portfolio</h1>
			<img id="logo" src="pp.png">
			<h2>Rachel (ESFP)</h2>
			<h3>Penang</h3>
			<p>Rachel Lee Ler Xuan is a determined and vibrant individual with a passion for numbers and a flair for sports. Born with a natural knack for organization and detail, Rachel aspires to become an accomplished accountant, where she can utilize her analytical skills to their fullest potential. With a bubbly and outgoing personality, she thrives in social settings, embracing new experiences and challenges with enthusiasm. Rachel's Myers-Briggs Type Indicator (MBTI) profile as an ESFP-T (Extroverted, Sensing, Feeling, Perceiving, Turbulent) reflects her energetic and spontaneous nature, always ready to engage and connect with others. Balancing her love for numbers with an active lifestyle, Rachel finds joy and relaxation in various sports, demonstrating her commitment to both physical and mental well-being. As she embarks on her journey towards her professional goals, Rachel's determination and passion serve as guiding forces, propelling her towards success in both her career and personal endeavors.
			</p>
		</div>
	</header>
	<div class="main-content">
	<h2>My Projects</h2>
	<section>
		<div class="architecture"><h3>My Achitecture Project</h3>
			<img src="./architecture.jpg">
			<p>School Architectural Competition</p>
		</div>
		<div class="project"><h3>.</h3>
			<img src="./project.png">
			<p>.</p>
		</div>
		<div class="project"><h3>.</h3>
			<img src="./project.png">
			<p>.</p>
		</div>
	</section>

	<section>
		<div class="project"><h3>.</h3>
			<img src="./project.png">
			<p>.</p>
		</div>
		<div class="project"><h3>.</h3>
			<img src="./project.png">
			<p>.</p>
		</div>
		<div class="project"><h3>.</h3>
			<img src="./project.png">
			<p>.</p>
		</div>
	</section>
	</div>

	<footer>
		<div class="footer-links">
			<div class="footer-column social-icons">
				<a href="#" target="_blank" title="Facebook"><i class="fab fa-facebook-f"></i></a>
				<a href="#" target="_blank" title="Twitter"><i class="fab fa-twitter"></i></a>
				<a href="#" target="_blank" title="Instagram"><i class="fab fa-instagram"></i></a>
				<a href="#" target="_blank" title="Instagram"><i class="fab fa-whatsapp"></i></a>
			</div>
		</div>
	</footer>

    <!-- Font Awesome icons (you can include this in your project or use a CDN) -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css">
	
</body></html>