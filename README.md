# Tic-Tac-Toe

## A game by using C programming

## WHAT IS TIC TAC TOE?
- Tic-tac-toe  is  not  a  very  challenging  game  for  humanbeings.  If you’re  an  enthusiast, you’ve  probably  movedfrom  the  basic  game  to  some  variant  like  threedimensional  tic-tac-toe on  a larger  grid.  If you sit downright now to play ordinary three-by-three tic-tac-toe witha  friend,  what  will  probably  happen  is  that  every  gamewill  come  out  a  tie.  Both  you  and  your  friend  canprobably  play  perfectly,  never  making  a  mistake  thatwould allow your opponent to win. But can you describehow  you  know  where  to  move  each  turn?  Most  of  thetime, you  probably  aren’t  even  aware  of  alternativepossibilities; you just look at the board and instantly knowwhere you want to move. That kind of instant knowledgeis  great  for  human  beings,  because  it  makes  you  a  fastplayer.  But  it  isn’t  much  help  in  writing  a computerprogram. For that, you have to know very explicitly whatyour strategy is.

## Strategy/Algorithm Used in Coding
- The highest-priority and the lowest-priority rules seemedobvious to me right away.The highest-priority are these:
 1. If I can win on this move,do it.
 2. If the other player can win on the next move,block that winning square.Here  are  the  lowest-priority  rules, used  only  if  there  isnothing suggested more strongly by the board position:n-2. Take the center square if it’s free. n-1. Take a corner square if one is free.n. Take whatever is available. The  highest  priority  rules  are  the  ones  dealing  with  themost urgent situations: either me or my opponent can win onthe next move. The lowest priority ones deal with the leasturgent  situations, in  which  there  is  nothing  special  aboutthe moves already made to guide me. What was harder was to find the rules in between. I knew that the goal of my own tic-tac-toe strategy was to set up a fork, a board position in which I have two winning moves, so my opponent can only block one of them.

- [Code](https://github.com/Yash9460/Tic-Tac-Toe/blob/main/Code.c)
