
[![Join the chat at https://gitter.im/18dew/Algorythmix](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/18dew/Algorythmix?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

# Proof-of-Compliance

## Brief 

The Current methods of regulation are more driven from command and control approach. and become more like one person / entity making a law and other entities maintaining the law for sustenance of the ecosystem leading to the decentralized problem and solving this problem using centralized approaches leads to enormous cost to participants.

## Objective 

 - To provide a mechanism to ensure consensus that rules laid down by regulator are adhered by participants on collectively.

## Axioms 

 - Relies on underlying structure of blockchains and smart contracts. 

## Algo

1 - Regulator issues maintain the registered user / participants  [ R = regulator , P = Registered Participants ]
2 - Regulator issues random token to these participants and is mappes token to the registered users. Token is known only to Regulator and Participants [T = Token ]
3 - Regulator specifices rule set to follow to ensure compliance in shared manner. [ r = Rules {returns (bool)} ] [ This can be granularised to controls for compliance] 
4 - Register participants does the check for the rule to meet the requirement and registers it as a tx on the blockchain after signing the recursive hash of the Token and timestamp. 

 
