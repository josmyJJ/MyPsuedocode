# Completion Activity
    
   PRINT "WELCOME"

   PRINT "INSERT THE FIRST CARD NUMBER"
```
     INPUT CARDNUMBER1
        IF CARDNUMBER1="J" OR "K" OR "Q"
          THEN CARDNUMBER1=10
        AND IF CARDNUMBER1="A"
          THEN 
            PRINT "CHOOSE BETWEEN 1 AND 11"
            INPUT A
              IF A=1
                THEN CARDNUMBER1=1
              ELSE
                CARDNUMBER1=11
        ELSE CARDNUMBER1=CARDNUMBER1
        END IF
        
   PRINT "INSERT THE SECOND CARD NUMBER"

      INPUT CARDNUMBER2
        IF CARDNUMBER2="J" OR "K" OR "Q"
          THEN CARDNUMBER2=10
        AND IF CARDNUMBER2="A"
          THEN 
             PRINT "CHOOSE BETWEEN 1 AND 11"
             INPUT A
               IF A=1
                 THEN CARDNUMBER2=1
               ELSE
                 CARDNUMBER2=11
        ELSE CARDNUMBER2=CARDNUMBER2
        END IF

   DO
     SET ADD = CARDNUMBER1 + CARDNUMBER2
     IF ADD=21
       THEN PRINT "*" and ADD
     ELSE 
       PRINT ADD
   
   WHILE
    (BOTH CARDNUMBER1 AND CARDNUMBER2 NOT EQUAL TO ZERO)

   END DOWHILE

   PRINT "GOOD BYE"
``` 
