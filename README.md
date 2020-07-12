# PythonFunctions

#Assigning elements to different lists

fruits=["Apple","Mango","Strawberry","Watermelon"]
fruits.append("Kiwi")
print(fruits)


#Accessing elements from a tuple

Languages=("C","C++","Python","Java")
print(Languages[2])                                output=Python
print(Languages[0])                                output=C


#Deleting different dictionay elements

Fruits={"Apple":"Red","Mango":"Yellow","Kiwi":"Green","Watermelon":"Red"}
del Fruits["Apple"]
print(Fruits)

(Or)

Fruits={"Apple":"Red","Mango":"Yellow","Kiwi":"Green","Watermelon":"Red"}
Fruits.pop("Watermelon")
print(Fruits)
