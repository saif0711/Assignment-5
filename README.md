# Assignment-5

#1
dictionary = {'Arpit':85,'Mahesh':95,'Pradeep':87,'Gaurav':96}
user_key = input("Enter the student's name: ",)
if user_key in dictionary:
    marks = dictionary[user_key]
    print(f"{user_key}'s marks: {marks}")
else:
    print('Student not found')

#2
number_list = [1,2,3,4,5,6,7,8,9,10]
print('Original list:',number_list)
extracted_list = number_list[:5]
print('Extracted first five elements:',extracted_list)
extracted_list.reverse()
print('Reverse extracted elements:',extracted_list)

