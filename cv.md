# Mikhail Vavilin

## About Me
My name is Mikhail Vavilin. I am 22 years old. I am a student at Penza State University, studying to be a software engineer. In my spare time I do frontend development. I am interested in cycling.

![Personal photo](https://sun9-54.userapi.com/s/v1/if2/2CbEABvc1Jglt37diXELBS6wdWIaUAy6bF6CjMSfyQKG0gjt5SG9batlCf1SF3uJ7KA6i5UEvFDCqPjlY9eoYFRl.jpg?quality=95&as=32x24,48x36,72x54,108x81,160x120,240x180,360x270,480x360,540x405,640x480,720x540,1080x810,1280x960,1440x1080,2560x1920&from=bu&cs=2560x0)

## Contact Information
* [Telegram](https://t.me/mvavilin)
* [Discord](https://discordapp.com/users/1383722446921666681)
* [GitHub](https://github.com/mvavilin)

## Skills
* HTML
* CSS/SASS
* JS
* Git/GitHub
* Figma
* VS Code
* Tailwind CSS
* shadcn/ui
* TypeScript
* React
* Vite
* Versel
* С

## Code Example
### [tic-tac-toe](https://github.com/mvavilin/tic-tac-toe.git)
```
const message = document.getElementById("message");

let currentPlayer = "X";
let gameActive = true;
let gameState = ["", "", "", "", "", "", "", "", ""];

const winningConditions = [
  [0, 1, 2],
  [3, 4, 5],
  [6, 7, 8],
  [0, 3, 6],
  [1, 4, 7],
  [2, 5, 8],
  [0, 4, 8],
  [2, 4, 6],
];

function checkResult() {
  let roundWon = false;

  for (let i = 0; i < winningConditions.length; i++) {
    const [a, b, c] = winningConditions[i];
    if (gameState[a] === "" || gameState[b] === "" || gameState[c] === "") {
      continue;
    }
    if (gameState[a] === gameState[b] && gameState[a] === gameState[c]) {
      roundWon = true;
      break;
    }
  }

  if (roundWon) {
    message.textContent = `Игрок ${currentPlayer} выиграл!`;
    gameActive = false;
    return;
  }

  if (!gameState.includes("")) {
    message.textContent = "Ничья!";
    gameActive = false;
    return;
  }

  currentPlayer = currentPlayer === "X" ? "O" : "X";
}
```

## Projects
* [tic-tac-toe](https://mvavilin.github.io/tic-tac-toe/) (deploy)
* [basket-shop](https://basket-shop-sepia.vercel.app/) (deploy)
* [linear-binary](https://github.com/mvavilin/linear-binary) (repository)

## Education & English Level
* **2019–2023**  
  Serdobsk Branch of Penza State University  
  *Qualification: Software Technician*  

* **2023**  
  JS/FE PRE-SCHOOL 2022Q4 (JavaScript)  
  *[Certificate](https://app.rs.school/certificate/kdioc79h)*  

* **2024–Present**  
  Penza State University  
  *Qualification: Software Engineer*  

* **2025–Present**  
  Center for Project Creativity, PSU  
  *Project-focused training*  

**A1 (Beginner)**  
Basic reading/writing skills.  
