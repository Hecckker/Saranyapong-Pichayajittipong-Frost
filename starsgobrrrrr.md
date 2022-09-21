SEND "enter height" TO DISPLAY
RECIEVE "enter height" FROM KEYBOARD
SEND "enter weight" TO DISPLAY
RECIEVE "enter weight" FROM KEYBOARD
SET BMI TO "enter weight" / "enter height ^2"
 IF BMI < 18.5 THEN
 SEND "Underweight" TO DISPLAY
 ELIF BMI <= 24.9 THEN
 SEND "Normal Weight" TO DISPLAY
 ELSE BMI >=25 THEN
 SEND "Overweight" TO DISPLAY
 END IF 
 END IF 
 END IF
