# projects
                                                               PROJECT REPORT
General outline:
	We have imported pygame and random modules to use in our project(HAND CRICKET).Here in the game there will be three 3 stages . 1)toss 2)bat or bowl(depending on the toss result,you have to either bat or bowl) 3)end(displaying the result of the game whether you won or lost).To accomplish this,we have defined total four functions . They are toss(),user_bat(),user_bowl(),end().

	At first, we have called the toss function.In it you will be instructed to press the keys "O"(odd) OR "E"(even).Then you will be asked to press any number from 0 to 6 and computer also generates a random number from 0 to 6(used "random" ).If the sum of the 2 numbers is your selected choice(odd or even),you will be asked to press any of "B"(bat) or "F"(field) keys.If the sum is not your selected choice,computer will decide to bat or bowl(used "random").
  
      It goes to user_bat or user_bowl functions according to the result in the toss,in the first innings, the score will be calculated and wickets also will be calculated. After the 5 wickets ,first innings will be completed and it comes out of the function(user_bat or user_bowl) and that function returns the score of the first innings.
  
      Next, it goes into the remaining function in user_bat or bowl. The score of the first innings will be set as a target for the second innings.If the target is crossed (or) the 5 wickets are over before raching the target,it wil come out of the function and this function returns the score of the second innings.

     At last, it will go into the end() function and the returned scores in the both innings will be computed and it displayes the result of the game (whether the match was won or lost or tied).  

