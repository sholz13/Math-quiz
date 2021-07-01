# Maths Quiz

code and documents for maths quiz game.

A code quiz for the unit 04 web API.

Instead of right or wrong response when the answers are clicked the screen changes.

# # Link

 https://sholz13.github.io/Maths-quiz/

# # demo code


function startGame() { 
    startButton.classList.add('hide')
    shuffledQuestions = questions.sort(() => Math.random() - .5)
    currentQuestionIndex = 0
    questionContainerElement.classList.remove('hide')
    setNextQuestion()
}

function setNextQuestion() {
    resetState()
    showQuestion(shuffledQuestions[currentQuestionIndex])

} 

# # Copyright & licenses 

Shola Onabanjo.
