# environmental-sustai6nability
<!DOCTYPE html>
<html>
<head>
	<title>Environmental Sustainability</title>
	<style>
		body {
			background-color: #bde0c8;
			font-family: Arial, sans-serif;
		}
		#container {
			max-width: 1000px;
			margin: auto;
			overflow: hidden;
		}
		#intro {
			background-image: url("background.jpg");
			background-repeat: no-repeat;
			background-size: cover;
			padding: 100px 0;
			text-align: center;
			color: white;
			position: relative;
		}
		#intro h1 {
			font-size: 48px;
			margin-bottom: 20px;
		}
		#intro p {
			font-size: 24px;
			margin-bottom: 50px;
		}
		#intro .character {
			position: absolute;
			bottom: 0;
			left: 50%;
			transform: translateX(-50%);
			animation: move 3s ease-in-out infinite;
		}
		@keyframes move {
			0% {
				bottom: 0;
				transform: translateX(-50%);
			}
			50% {
				bottom: 50px;
				transform: translateX(-50%) scale(1.1);
			}
			100% {
				bottom: 0;
				transform: translateX(-50%);
			}
		}
		#intro .character img {
			width: 100%;
			height: auto;
		}
		#features {
			padding: 100px 0;
			text-align: center;
			background-color: white;
			color: #333;
		}
		#features h1 {
			font-size: 48px;
			margin-bottom: 50px;
		}
		#features .feature {
			margin: 50px 0;
		}
		#features .feature img {
			width: 500px;
			height: auto;
			margin-right: 50px;
		}
		#features .feature p {
			font-size: 24px;
			margin-bottom: 20px;
		}
	</style>
</head>
<body>
	<div id="container">
		<div id="intro">
			<div class="character">
				<img src="" alt="Character explaining environmental sustainability">
			</div>
```<h1>Welcome to Our Environmental Sustainability Site</h1>
<p>Discover How You Can Make a Difference Today!</p>
	</div>
	<div id="features">
		<h1>Our Environmental Sustainability Programs</h1>
		<div class="feature">
			<img src="https://nevonprojects.com/wp-content/uploads/2017/06/Energy-Meter-Monitoring-Over-Iot.jpg" alt="IoT sensors for monitoring energy consumption">
			<p>
				Our IoT sensors help you monitor your energy consumption in real time, so you can make adjustments to reduce your carbon footprint.
			</p>
		</div>
		<div class="feature">
			<img src="https://waste-management-world.com/imager/media/wasteManagementWorld/4466961/AdobeStock_559024883_2023-09-22-075029_kvdn_b0464c6958b2ce61ced917e5958dc330.jpeg" alt="Waste management system with recycling incentives">
			<p>
				Our waste management system rewards you for recycling, helping you turn your trash into treasure.
			</p>
		</div>
		<div class="feature">
			<img src="https://media.istockphoto.com/id/618973378/photo/bicycle-sharing-system.jpg?s=612x612&w=0&k=20&c=ms8wYi_uOo2YgghfJiXeIq073M15Dyoc7dEau9qDFOE=" alt="Sustainable transportation options such as bike sharing programs">
			<p>
				Our bike sharing program makes it easy to get around town without relying on a car, helping you reduce your carbon emissions.
			</p>
		</div>
		<div class="feature">
			<img src="https://donorbox.org/nonprofit-blog/wp-content/uploads/2020/08/21-3.png" alt="Education campaigns to raise awareness about environmental conservation">
			<p>
				Our education campaigns help you understand the importance of environmental conservation and how you can make a difference.
			</p>
		</div>
	</div>
</div>
