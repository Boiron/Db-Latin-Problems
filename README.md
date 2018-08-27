# Db-Latin-Problems

<p>We have an interesting dilemna at Boiron. Our original web developers, for reasons unknown to the universe, encoded most of our databases in Latin-Swedish 1. This leaves behind some really crazy symbols when you upgrade Wordpress or even make minor changes to the websites.</p>

<h4>Luckily, I am a web wizard</h4>

<p>I discovered you could essentially "trick" the databases into being read properly by making a minor alteration to the wp-config.php file</p>

<h4>What to change</h4>

<p>First of all, never begin by encoding in Latin 1 or I will make fun of you forever</p>

<p>Second, change: define('DB_CHARSET', 'utf8'); to define('DB_CHARSET', 'latin1');</p>

Remember to always make fun of people who encode in Latin 1 because they don't know what they're doing. 

