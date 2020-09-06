# Assignment-1-IT-310-Algorithm-in-python
#This is a recap assignment on python just to refresh the memory of students!!

print("///////////////////////////////Problem 1////////////////////////////////////////////")

def main():# this line is defining the main function
    food_list = ['Plantain', 'Rice', 'beans', 'spinach']#creating the list of my favorite foods
    for food in food_list:#looping through the food list
        print(food) #printing each item from the list


main()#end of main method
print("///////////////////////////////Problem 2//////////////////////////////////////////")

first_name = input("What's your first name?")# Prompting the user to enter his/her firstname using input

last_name = input("What's your last name?")# Prompting the user to enter his/her lastname using input

print("Hello, " + first_name  + " " +   last_name )#Displaying the Hello message using concatenation

print("///////////////////////////////Problem 3//////////////////////////////////////////////")


player_name = input("What is the player’s name? ")# Prompting the user to enter his/her name using input

number_of_hits = int(input(" How many hits?"))#Prompting the user to enter the number of hits using input


number_at_bats= int(input(" How many at-bats?"))#Prompting the user to enter the number at bats using input

average = (number_of_hits/number_at_bats)#Formula for the average in order to proceed to the calculation

print(player_name + "'s" + " " +  "batting average is:" + str(average))#Displaying the player batting average using the print function

print("////////////////////////////////////Problem 4//////////////////////////////////////////")

noun = input("Enter a noun:")# Prompting the user to enter a noun using input

verb = input("Enter a verb:")# Prompting the user to enter a verb using input

adjective = input("Enter an adjective:")# Prompting the user to enter an adjective using input

place = input("Enter a place:")# Prompting the user to enter  a place using input

print("Take your "   +  adjective   + " " +   noun    + " and "  +  verb + " at the " +  place  +  "!")

#Displaying the Hello message using concatenation

print("/////////////////////////////////Problem 5/////////////////////////////////////////////")
light_speed= 186000 # Initializing the value of lightspeed to its identifier
distance = 34000000#Initializing the value of distance to its identifier
time= distance/light_speed# Formula for the time

print(str(time) + " seconds ")#Displaying the final result after concatenating the 2 strings


