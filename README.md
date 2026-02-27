# gambit-practice
authot: Changwe Musonda
demo in class
```mermaid
sequenceDiagram
	autonumber
	actor Host as Host / GUI (Arena)
	participant Engine as Engine(Main loop)
	participant Paraer as UCI Parser
	participant Position as Position (Board/FEN)
	participant MoveGen as MoveGenerator (pseudoLegalMoves etc.)
	participant Rule as RuleChecker (isSquareAttacked / inCheck)
	participant MoveObj as Move (Move.fromUci / toUci)


```mermaid
