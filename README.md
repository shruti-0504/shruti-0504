import random
print()
print("===============================================")
print("|        Hello, Welcome to GK Quiz!           |")
print("|       Created By Shruti Gupta               |")
print("|      Of Lovely Professional University      |")
print("|     Section: K22FG  Roll No.: RK22FGA57     |")
print("===============================================")
print()
xyz=input("Enter your name: ")
print()
my_dict = {
    'Delhi is the Capital of India': 'TRUE',
    'Netaji Subash Chandra Bose is also known the Father of Nation': 'FALSE',
    'The five rings on the Olympic flag are interlocking?': 'TRUE',
    'Mount Kilimanjaro is the highest mountain in the world?': 'FALSE',
    'Strictly Come Dancing first aired in the UK in 2005?': 'FALSE',
    'A group of swans is known as a bevy?': 'TRUE',
    'Sydney is the capital of Australia?': 'FALSE',
    'The Penny Black is an old-fashioned coin?': 'FALSE',
    'Will.i.am is the only mentor to have appeared on every single series of The Voice UK?' : 'TRUE',
    'A heptagon has eight sides?' : 'FALSE',
    'The star sign Capricorn is represented by a goat?' : 'TRUE',
    'Fish cannot blink?': 'TRUE',
    'Nepal is the only country in the world which does not have a rectangular flag?': 'TRUE',
    'Switzerland shares land borders with four other countries?' : 'FALSE',
    'My Beautiful Dark Twisted Fantasy is a studio album by Kendrick Lamar?':'FALSE'
}
count=0
key = random.sample(list(my_dict.items()),5)
print()
print()
print(key[0][0],end=": ")
a1=input().upper()
if a1==key[0][-1]:
    count=count+1
print("Current Score:",count)
print()
print(key[1][0],end=": ")
a2=input().upper()
if a2==key[1][-1]:
    count=count+1
print("Current Score:",count)
print()
print(key[2][0],end=": ")
a3=input().upper()
if a3==key[2][-1]:
    count=count+1
print("Current Score:",count)
print()
print(key[3][0],end=": ")
a4=input().upper()
if a4==key[3][-1]:
    count=count+1
print("Current Score:",count)
print()
print(key[4][0],end=": ")
a5=input().upper()
if a5==key[4][-1]:
    count=count+1
print("Current Score:",count)
print()
print("Thank you for Participating",xyz,"!")
print("Congratulations you just finished the Quiz! Your Final Score is",count,end="")
if count==5:
    print("! Outstanding")
elif count==4:
    print("! Excellent")
elif count==3:
    print("! Very Good")
elif count==2:
    print("! Good")
elif count==1:
    print("! Improve")
else:
    print("! What did I just witness!!")
print()


