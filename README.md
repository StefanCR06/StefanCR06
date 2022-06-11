print('Welcome to math quiz!!!')

playing = input('Do you want to play? ')

if playing.lower() != 'yes'  :
    quit()

print("Okay! Let' s play :)")
score = 0

answer = input('10+10= ')
if answer.lower() == "20":
    print ('Correct!')
    score += 1
else:
        print('Inccorect! The correct answe is 20')


answer = input('10*10= ')
if answer.lower() == "100":
    print ('Correct!')
    score += 1
else:
        print('Inccorect! The correct answer is 100')


answer = input('10*10-10= ')
if answer.lower() == "90":
    print ('Correct!')
    score += 1
else:
        print('Inccorect! The correct answer is 90')


answer = input('2*(2+3)+10-5= ')
if answer.lower() == "15":
    print ('Correct!')
    score += 1
else:
        print('Inccorect! The correct answer is 15')

print("You got "  + str(score) +  " questions correct !")
print("You got "  + str((score / 4) * 100) + "%.")


playing = input('Do you want to do something more complicated? ')

if playing.lower() != 'yes':
    quit()

print("Okay! Let's do it :)")

answer = input('8*8/(64/8)+10+2*1= ')
if answer.lower() == "20":
    print ('Correct! You got +2 points')
    score += 2
else:
        print('Inccorect! The correct answer is 20')

playing = input('Now you have ' + str(score) + ' points, you can dublicate or luse all. Do you want to continue ? ')

if playing.lower() != 'yes':
    quit()
print('Find the value of x')
answer = input('2x+18+2(x+3)=0  , x=')
if answer.lower() == "-6":
    print ('Cool now your best score is ' + str(score*2) )
    
else:
        print("It's incorrect you lost all your point :(")
        print("Your best score is '0' ")
