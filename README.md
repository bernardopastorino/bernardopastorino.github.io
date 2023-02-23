<!DOCTYPE html>
<html>
<head>
	<meta name="viewport" content="width=device-width, initial-scale=1.0">
	<title>Hey there! I'm Bernardo Pastorino.</title>
	<style>
		body {
			font-family: sans-serif;
			margin: 0;
			padding: 0;
			display: flex;
			flex-direction: column;
			align-items: center;
			justify-content: center;
			min-height: 100vh;
		}
		header {
			background-color: #333;
			color: white;
			padding: 10px;
			display: flex;
			flex-direction: column;
			align-items: center;
		}
		nav ul {
			list-style: none;
			margin: 0;
			padding: 0;
			display: flex;
			flex-wrap: wrap;
			justify-content: center;
		}
		nav li {
			margin: 0 10px;
		}
		nav a {
			color: white;
			text-decoration: none;
		}
		main {
			padding: 20px;
			max-width: 800px;
			margin: auto;
		}
		ul {
			list-style: none;
			padding: 0;
			margin: 0;
		}
		li {
			margin: 10px 0;
		}
		@media (max-width: 600px) {
			header {
				flex-direction: row;
				justify-content: space-between;
				align-items: center;
			}
			nav {
				order: 2;
			}
			h1 {
				order: 1;
			}
			main {
				padding: 10px;
			}
			nav ul {
				flex-direction: column;
			}
			nav li {
				margin: 5px 0;
			}
		}
	</style>
</head>
<body>
	<header>
		<h1>Hey there! I'm Bernardo Pastorino.</h1>
		<nav>
			<ul>
				<li><a href="https://www.example.com">Example Link 1</a></li>
				<li><a href="https://www.example.com">Example Link 2</a></li>
				<li><a href="https://www.example.com">Example Link 3</a></li>
				<li><a href="https://www.example.com">Example Link 4</a></li>
			</ul>
		</nav>
	</header>

	<main>
		<p>This is a paragraph of text on my website.</p>
		<ul>
			<li>List item 1</li>
			<li>List item 2</li>
			<li>List item 3</li>
		</ul>
		<p>Here are some external links:</p>
		<ul>
			<li><a href="https://www.example.com">Example Link 1</a></li>
			<li><a href="https://www.example.com">Example Link 2</a></li>
			<li><a href="https://www.example.com">Example Link 3</a></li>
			<li><a href="https://www.example.com">Example Link 4</a></li>
		</ul>
	</main>

	<footer>
		<p>&copy; 
