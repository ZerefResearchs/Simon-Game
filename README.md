# Simon-Game

ABSTRACT



This JavaScript application is based on the 80’s classic memory game “Simon”. The game has been deliberately styled to replicate the original 80’s game and gives the user a significant feeling of nostalgia. 

To start the game, the user must press any key on their keyboard to start, this will cause the button to indent and the game will create the first colour sequence. The game will go through the process of showing the user coloured lights in a random sequence, the user must then repeat the sequence without making any mistakes. To enter a colour sequence, the user must click on the coloured light buttons shown forth on their desktop/screen. Each time the user correctly repeats the sequence of coloured lights; one more light will be added to the end of the sequence to enable the user to progress through the game. It’s an endless game without any levels restricting your progress.

Features


•	Lights - These were deliberately chosen to replicate the original game and were set out in the same configuration to fully capitalise on the nostalgia that user one would feel when using my application. The brightly coloured lights also make the game visually engaging to children like user two.


•	Level Display - A clear display to show users which level they have reached, the number on the display also corresponds to how many lights will flash at each level. This helps the user track the current level they are on.


•	Start Button - The Start Button is basically you pressing any key on your keyboard. It also provides a clean and intuitive experience which caters for user by making the game easy-to-use and child-friendly.
					
Features to Add


•	I could add an extra element of difficulty to the game calling it “HARD” mode and making the lights flash faster, this would be done within the "intervalID" section, reducing the amount of time between each light.

•	I would also like to add a Colour-Blind friendly mode where orange and purple lights are used instead of red and green, and the user has the option to turn this colour-blind friendly mode on and off.

Technologies Used

•	This project uses a mixture of HTML, CSS and JavaScript technologies.

•	HTML is used to control the placement of page elements and help form the structure of the “Simon”. This uses the “class” and “id” selectors to enable the elements to be effectively styled by the CSS and also enable the JavaScript to add interactivity to the game. The majority of the tags used in this project are semantic “div” elements because this allows for the greatest design flexibility.

•	CSS is used to add styling to the game and to enable the light buttons to replicate the style of the original game. I styled each section using similar logic so that the game was symmetrical and well proportioned. It is also useful to make sure the same styling is used across the application to make sure it is consistent.

•	JavaScript is used to add the dynamic elements to the application, such as the sequencing which is based on picking a number between 0-1 “(Math.random ())”, multiplying that by 4 “(* 4)”, adding one and then rounding the number to the nearest integer ”(Math.round)”. The JavaScript then runs this algorithm to match the level requirements. Each light button has its own colour and number assigned to it so that when the JavaScript produces a number, the user can see the corresponding coloured light, flash. After each level, one more light will be added to the end of the sequence to enable the user to progress to the next level.

Deployment


GitHub Repository: https://github.com/ZerefResearchs/Simon-Game

GitHub Pages: https://zerefresearchs.github.io/Simon-Game/

Using GitHub's provided system, I was able to pick the branch I wanted to show on a webpage, and deploy it very simply to the dedicated web page displayed above. In this case, the branch that was deployed was the master branch.
