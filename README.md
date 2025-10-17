# MultiBits
its also a recursive attempt by blitzmax basic

 the thing is

 you read 2 bits you nibble them 00=0 01=1 10=2 11=3

 if its 1 or 2 you store in a table just one bit 0 or 1 and increase the counter num
 if its 0 or 3 you get out of the cicle and have the number of 1 and 2 stored
 you check if it ended 0 or 3
 if ended 0 or 3 and there no 1 or 2 inside you store bits 0=0 or 1=3
 you do the abs of num-nible
 if the nible its 0 obviously you do a cicle of the real value into 000001  (value number of 0) ending 1
 if the nible its 3 obviously you do a cicle of the abs value into 000001  (value number of 0) ending 1 in case the value its less than 4 you need to store a bit on table 0 if num its minor then nible=3 or
 1 if its bigger or EQUAL to nible=3
 in case of equal you can test the reverse engine when gest zero if bit came to 1
 you store the 00001 of the value
 and in the last table you store the previous 0 and 1 of those middle 01 and 10 nibles just stating the last bit
 and you move on to next ending 00 or 11
 unfortunatly in end of the file after it becomes more the the filesize im not storing the ending block of 00 or 11 but that like only 2 or 3 bytes top not stored yet.
 the reverse engine it will be done
