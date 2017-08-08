# Rakesh-
import random
input_list = ['R', 'A', 'K', 'H', 'I']

lists = [[], [], []]

random.shuffle(input_list)

while input_list:
    char = input_list.pop()
    lists[random.randint(0,2)].append(char)

print lists
