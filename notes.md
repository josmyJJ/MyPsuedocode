# This is my file for notes
How to remove a link?
  rmdir /s MyPsuedocode2
git pull origin master=== compares the changes made on the local and compares to the github
To configure a user name
  git config --list
  git config --global user.name "some one else"
  git config --global user.email "rando@email.com"


CONDITIONS

INPUT USERNAME
INPUT PASSWORD
 IF USERNAME=USER NAME IN DB
            AND
    PASSSOWRD=PASSWORDIN DB FOR USERNAME
   THEN LOGIN
 ELSE
   LOGIN FAILED

 IF:
       IF CONDITION
       THEN ACTION
       ELSE 
       ANOTHER ACTION
    END IF

 WHILE:codition comes first 
      WHILE PERSON IN DB
        CHECK AGE
        IF AGE>18
        ALLOW
        ELSE DISALLOW
 DOWHILE:condition comes at the end
         check if the first one is true and dont care the others
      DO 
       CHECK AGE
       IF AGE>18
       ALLOW
       ELSE DISALLOW
      WHILE PERSON IN DB
    
  FOR:first you have to know the number of repetitions
      FOR PERSON IN CHECK DB
       CHECK AGE
       IF AGE>18
       ALLOW
       ELSE DISALLOW
      END FOR
CASE STATEMENT

-CACSE:HRS>40
   PRINT "OVER TIME"
   BREAK
  CASE:HRS<=40
   PRINT "NO OVER TIME"
   BREAK
- IF HRS>40
   THEN
   PRINT "OVER TIME"
  ELSE 
  PRINT "NO OVER TIME"

- FOR I=1 TO 5
   PRINT I
   I=I+2
  END FOR
