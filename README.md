
# Math Quiz

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

<img width="1094" alt="Screen Shot 2021-08-02 at 9 57 57 PM" src="https://user-images.githubusercontent.com/82775553/128001537-007df442-6cfa-4fbe-80fd-e66061190d60.png">

# # Copyright & licenses 

Shola Onabanjo.
