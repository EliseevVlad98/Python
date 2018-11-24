empty_list = []
empty_list = list()
none_list = [None] * 10
collections = ['list', 'tuple', 'dict', 'set']
user_data = [
['Elena', 4.4],
['Andrey', 4.2]
]
print(len(collections))
print(collections.__len__())
print(collections[0])
print(collections[-1])
print('tuple' in collections)
print('Vlad' in collections)
range_list = list(range(10))
print(range_list)
range_list[1:3]
range_list[::2]
range_list[::-1]
range_list[5:1:-1]
print(range_list[:] is range_list)

collections.extend(['ponyset', 'unicorndict'])
print(collections)
print(len(collections))

collections += [None]
print(collections)

del collections[4]
print(collections)

numbers = [4, 17, 19, 9, 2, 6, 10, 13]
print(min(numbers))
print(max(numbers))
print(sum(numbers))

tag_list = ['python', 'course', 'coursera']
print(', '.join(tag_list))

import random
numbers = []
for _ in range(10):
    numbers.append(random.randint(1, 20))
print(numbers)
print(sorted(numbers)

blink = ([], [])
blink[0].append(5)
blink[0].append(10)
print(blink)
