# Python_notes
notes from python pre course
'''
Booleans and quality operators

Operator     /  meaning                                      / Example      /
    ==      /Equal to                                       / 4==4(True)    /
    !=      / Not equal to                                  / 4!=2(False)   /
    >       / Greater than                                  / 3>4(True)     /
    <       / Less than                                     / 3<4(True)     /
    >=      / Greater than or equal to                      / 5 >=5(True)   /.
    <=      / Less than or equal to                         / 5<=4(False)   /
'''

'''
colon at the end of a line will start an indent and IDE will automatically add an indent. The indent shows where 
a code block starts and ends.
'''

# Indent needs to be cleared otherwise any following code will only execute if the control flow was true.
# Elif is followed by if statement and can have single or multiple conditions it has to meet.
# Else does not need conditions e.g. if nothing else is captured then run my code.

customer_age = 15
if customer_age <= 12 or customer_age < 15:
    print('U, PG and 12 films are available')
elif customer_age <= 15 or customer_age < 18:
    print('U, PG, 12 and 15 films are available')
else:
    print('all films are available')

'''
Chatbot greetings
1. between 5:00-12:00 - Good morning
2. between 12:00-18:00 - Good afternoon 
3. between 18:00-00:00 - Good evening
'''

time_of_day = 15

# two options used in if statement are or & and

if time_of_day > 5 and time_of_day < 12:
    print('Good morning ')
elif time_of_day >12 and time_of_day <18:
    print('Good afternoon')
else:
    print('Good evening')
