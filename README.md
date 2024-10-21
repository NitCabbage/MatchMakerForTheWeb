# MatchMakerForTheWeb
BACKGROUND IMAGE CREDIT: https://cliply.co/wp-content/uploads/2020/01/402001120_PAPER_HEARTS_1080.png
CEDIT FOR: "let question1Combatibility = 5 - Math.abs(question1Response - DESIRED_Response[0])
let question2Combatibility = 5 - Math.abs(question2Response - DESIRED_Response[1])
let question3Combatibility = 5 - Math.abs(question3Response - DESIRED_Response[2])
let question4Combatibility = 5 - Math.abs(question4Response - DESIRED_Response[3])
let question5Combatibility = 5 - Math.abs(question5Response - DESIRED_Response[4])

console.log("c1="+question1Combatibility)
console.log("c2="+question2Combatibility)
console.log("c3="+question3Combatibility)
console.log("c4="+question4Combatibility)
console.log("c5="+question5Combatibility)


let totalCombatibility = question1Combatibility + question2Combatibility + question3Combatibility + question4Combatibility + question5Combatibility


totalCombatibility *= 100 / MAX_SCORE 
totalCombatibility = Math.round(totalCombatibility) 
console.log("tc="+ totalCombatibility)

document.getElementById("score").innerHTML = "You're score is... " +totalCombatibility" - Eric Pouge

References- Eric Pogue "Code Together: cpsc-20000 Match Maker Lite Parts 1 & 2

To use anwser each response by using the drop down boxes to respond with how you feel based on the five prompts. Once you are done responding to each box click the "Calculate Score" button on the bottom of the page to view your score.
