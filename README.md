# Experiment 1
# Introduction to Python Programming


## Alphabet Soup Problem
````
#Define function sorting string alphabetically
def sort_alphabetically(S):
		sorted_STRING = ''.join(sorted(S))
    return sorted_STRING

#User Inputs A String
user_input = input("Please enter a string: ")

#Alphabetically sort the string
result = sort_alphabetically(user_input)

#Display the sorted result
print("Sorted string: ", result)
````

## Emoticon Problem
````
#Define the function that changes specific words of a sentence into an emoticon
def emotify(sentence):
    #Dictionary of words to their corresponding emoticons
    emoticons = { "smile": ":)", "grin": ":D", "sad": ":((", "mad": ">:("}
    
    #Split the sentence into separate words
    words = sentence.split()
    
    #Replace words with their corresponding emoticons
    emotified = [emoticons.get(word, word) for word in words]
    
    #Combine the words back into a single sentence
    new_sentence = ' '.join(emotified)
    
    return new_sentence
    
#Get user input
user_input = input("Please enter a sentence: ")

#Replace words with emoticons
result = emotify(user_input)

#Display the result
print(result)
````

## Unpacking List Problem
````
#Define the list writeyourcode here
writeyourcodehere = [1, 2, 3, 4, 5, 6, 7, 8, 9, 10]

#Unpack the list
first, *middle, last = writeyourcodehere

#Print the variables
print("first:", first, " middle:", middle, " last:", last)
````
