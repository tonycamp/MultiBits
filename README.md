# MultiBits
its also a recursive attempt by blitzmax basic

 the thing is

 you read 2 bits you nibble them 00=0 01=1 10=2 11=3

 if its 1 or 2 you store in a table just one bit 0 or 1
 if its 0 or 3 you get out of the cicle and have the number of 1 and 2 stored
 you check if it ended 0 or 3
 if ended 0 or 3 and there no 1 or 2 inside you store bits 00=0 or 01=3
 if there are 1 or 2s inside you state 10=0 or 11=3
 and you put a cicle ahead of 0 0 0 depending on the number of 1 and 2 inside
 ending the cicle with 1
 if its just only one 1 or one 2 inside there are no zeros just a ending 1
 to store the final table of 1 and 2 you just store the one bit case its 0 or 1 signifyng the 01 or 11
 and you move on to next ending 00 or 11
 unfortunatly in end of the file after it becomes more the the filesize im not storing the ending block of 00 or 11 but that like only 2 or 3 bytes top not stored yet.
 the reverse engine it will be done
