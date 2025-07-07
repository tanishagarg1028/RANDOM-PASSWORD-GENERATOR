#TO GENERATE RANDOM PASSWORD OF:- CHARACTERS(LOWERCASE{a,b,c,d},UPPERCASE{A,B,C,D},NO:{1,2,3,4},PUNCTUATORS{!,@,#,$,%,^,&,*}

import random
import string 

pass_len=8
charvalues= string.asciiletters+string.digits+string.punctuations
passwords="".join[{random.choice(charvalues) for i in range(pass_len)}]
print ("your random password is:",password)
