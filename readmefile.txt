<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width initial-scale=1.0">
<title> Awesome Quiz App | Edgar Omondi Muga</title>
<link rel="stylesheet" href="style.css">
<script src="https://kit.fontawesome.com/cdbe8bc2d8.js" crossorigin="anonymous"></script>

<div class="start_btn">
<button>
Start Quiz
</button>
</div>
<div class="info_box">
	<div class="info_title">
	<span>Some Rules of this Quiz</span>
	</div>
	<div class="info_list">
		<div class="info">1. You will have only <span>15 seconds </span> per each question</div>
		<div class="info">2. Once you select your answer, you can't reselect</div>
		<div class="info">3. You cannot select any option once time goes off</div>
		<div class="info">4. You can't exit the app while you're playing </div>
		<div class="info">5. You'll get the points based on the basis of your correct answers.</div>
	</div>
	<div class="buttons">
		<button class="quit">Exit Quiz</button>
		<button class="restart">Continue</button>
	</div>
</div>
<div class="quiz_box">
	<header>
	<div class="title">Awesome Quiz Application</div>
	<div class="timer">
	<div class="time_text">Time Left</div>
	<div class="timer_sec">15</div>
	</header>
	<section>
	<div class="que_text">
		<span>What does HTML stand for?</span>
	</div>
	<div class="option_list">
		<div class="option">
			<span>Hypertext Markup Language</span>
			<div class="icon tick"><i class="fas fa-check"></i></div>
		</div>
		<div class="option">
			<span>Hyper text Preprocessor</span>
			<div class="icon cross"><i class="fas fa-times"></i></div>
		</div>
		<div class="option">
			<span>Hyper text Multiple Language</span>
		</div>
		<div class="option">
			<span>Hyper tool Multi Language</span>
		</div>
	</div>
	</section>
	<footer>
		<div class="total_que">
		<span><p>2</p>of<p>5</p>Questions</span>
		</div>
		<button type="button" class="next_btn">Next Que</button>
	</footer>
	</div>
	
	
	<div class="result_box">
		<div class="icon">
			<i class="fas fa-crown"></i>
		</div>
		<div class="complete_text">You've completed the text</div>
		<div class="score_text">
		<span>and sorry, You got only <p>2</p>out of <p>5</p></span>
		</div>
		<div class="buttons">
			<button class="restart">Replay Quiz</button>
			<button class="quit">Quit quiz</button>
		</div>
	</div>
</div>
</head>
</html>