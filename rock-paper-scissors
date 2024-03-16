const getUserChoice = userInput => {
  userInput = userInput.toLowerCase();
  if(userInput === 'rock' || userInput === 'paper' || userInput === 'scissors'){
    console.log(userInput);
    return userInput;
  } else{
    console.log('Error! Please choose either rock, paper, or scissors.');
  }
}

function getComputerChoice() {
  const randomNumber = Math.floor(Math.random() *3);
  switch (randomNumber) {
    case 0:
      return 'rock';
    case 1:
      return 'paper';
    case 2:
      return 'scissors';
    default:
      return 'Error';
  }
}

function determineWinner(userChoice, computerChoice) {
  if (userChoice === computerChoice) {
    return 'Its a tie';
  } else if (userChoice === 'rock' && computerChoice === 'paper') {
    return 'computer wins';
  } else {
    return 'user wins';
  } else if (userChoice === 'paper' && computerChoice === 'scissors' or 'rock') {
    
  }
}


