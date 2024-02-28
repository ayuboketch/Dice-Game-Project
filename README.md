![Screen Shot 2024-02-28 at 16 06 49](https://github.com/ayuboketch/Dice-Game-Project/assets/17433791/d0261e8b-9b99-41b4-9c22-efc9006477d0)

# Dice-Game-Project

# 🎲 Interactive Dice Game Project Showcase 🎲
# Overview:
Embark on an exhilarating journey into the world of probability with this interactive dice game project. Crafted using the trifecta of web development languages - HTML, CSS, and JavaScript, this project showcases both creativity and algorithmic finesse.
Key Features:

# 1. 🚀 Dynamic Dice Rolling:
Experience the thrill of rolling dice dynamically using the Math.random() function. The low-level algorithm ensures randomness, creating an engaging user experience.

# javascript

const rollDice = () => {
  diceValuesArr = [];
  for (let i = 0; i < 5; i++) {
    const randomDice = Math.floor(Math.random() * 6) + 1;
    diceValuesArr.push(randomDice);
  }
  listOfAllDice.forEach((dice, index) => {
    dice.textContent = diceValuesArr[index];
  });
};

# 2. 📈 Algorithmic Decision Making:

Explore intricate algorithms for scoring, including the detection of duplicates, full houses, and straights. The project intelligently calculates the optimal score based on the dice outcome.

javascript

const getHighestDuplicates = (arr) => {
  // Algorithm for detecting duplicates and updating score options
  // ...
};

const detectFullHouse = (arr) => {
  // Algorithm for detecting full houses and updating score options
  // ...
};

const checkForStraights = (arr) => {
  // Algorithm for checking straights and updating score options
  // ...
};

# 3. 🎓 Educational Modal Integration:

Enhance user experience with a dynamic rules modal. The modal, toggled with a rules button, provides an educational overlay, making the project both entertaining and informative.

javascript

rulesBtn.addEventListener("click", () => {
  isModalShowing = !isModalShowing;
  // Toggle modal visibility and update button text
  // ...
});

# 4. 🏆 Scoring and Game Progression:

Witness the seamless scoring system and game progression. The project tracks rounds, rolls, and total scores, providing feedback to the user and ensuring a challenging yet enjoyable gameplay.

javascript

keepScoreBtn.addEventListener("click", () => {
  // Algorithm for updating scores, rounds, and progressing the game
  // ...
});

# Conclusion:

Incorporating innovative algorithms and a sleek user interface, this dice game project showcases not only technical prowess but also a commitment to creating engaging and educational web experiences. Roll the virtual dice, strategize your moves, and embrace the excitement of probability in this dynamic gaming environment! 🎲🌐✨

![Screen Shot 2024-02-28 at 16 10 08](https://github.com/ayuboketch/Dice-Game-Project/assets/17433791/5c0f6cef-13ad-48bc-abd3-5f24fb9c2263)

