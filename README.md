<h1>Catch Game on Pygame</h1>
<p>This is a simple Catch game implemented using Pygame, a popular Python library for game development.</p>

<h3>Features</h3>

<p><b>Player as an Arkanoid-style Bar:</b> The player is represented as a bar that moves along the x-axis. The movement of the bar is controlled using the 'A' and 'D' keys. It possesses acceleration and comes to a halt when it collides with the borders of the game window.</p>

<p><b>Red Falling Object:</b> A red object falls along the y-axis, appearing randomly at any x-axis position. As the game progresses, the falling object accelerates its descent after every three successful catches.</p>

<p><b>Score Tracking:</b> The game keeps track of the player's score, which increases each time a falling object is successfully caught.</p>

<p><b>Lose and Restart System:</b> If the player fails to catch an object, the game ends and displays the final score. The player can restart the game by pressing the 'R' key.</p>

<p><b>Built-in Music Player:</b> An 8-bit version of the popular song 'Dura' by Daddy Yankee plays continuously in the background, adding to the immersive epic gaming experience.</p>

<h3>Changelog</h3>
<p>Added a pip install upgrade pygame command at the beginning of the code to ensure compatibility for users who do not have the Pygame library installed.</p>
<p>Updated the music playback functionality. The pygame.mixer.music.play command now has the loop parameter set to -1, enabling the music to loop continuously throughout the game.</p>
<p>Enhanced the player movement for a more enjoyable gaming experience. The player_acc value has been adjusted to 0.5, providing smoother acceleration for the player-controlled bar. The player_max_vel value has been increased to 10, allowing for faster movement and greater responsiveness. These modifications contribute to improved gameplay dynamics and overall user satisfaction.</p>
