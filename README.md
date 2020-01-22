# HaskellStack
## Modelization of a Stack in Haskell

Stack data structure written in Haskell, using a list. Currently it "works", there's an error while assigning the result of a push or pop to the same variable. Ex: if x is a Stack with stackPile list [5,2,3], y = push x 6 whill correctly make y a Stack with stackPile [6,5,2,3] but doing x = push x 6 will fail.

push -> puts a value on top of the Stack  
top -> returns the Just top value of the Stack, Nothing if its empty  
pop -> removes the top value of the Stack, does nothing if its empty  
size -> returns the number of elements in the stack  
fromJust -> returns the value of a Just a, and an error if its Nothing  
