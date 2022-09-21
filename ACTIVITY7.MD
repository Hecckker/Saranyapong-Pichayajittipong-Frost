START
my_numb = 3
SEND "please enter your guess" TO DISPLAY
RECIEVE "guess" FROM KEYBOARD
IF guess > 10 THEN
    SEND "Too high! Your guess must be between 1 and 10" TO DISPLAY
  ELIF guess = my_numb THEN
    send "Well done! You guessed correctly" TO DISPLAY
  ELSE THEN
    send "Bad luck! The correct number is + my_numb"
END IF
END IF
END IF
