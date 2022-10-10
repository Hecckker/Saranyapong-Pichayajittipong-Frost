SEND "enter temperature" TO DISPLAY
RECIEVE temperature FROM KEYBOARD
IF temperature < 18 THEN
SEND " Cold , the perfect temperature for sleep is 18-21 degrees." TO DISPLAY
ELSE 
  IF temperature > 21 THEN
    SEND "Perfect" TO DISPLAY
  ELSE 
    SEND "No!, the perfect temperature for sleep is 18-21 degrees." TO DISPLAY
  END IF
END IF
     
