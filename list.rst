list1 = [1,2,3,4.4,[3,3],(34,321,'23'),{1:2}]

print(list1)
#append
list1.append('jeevan')
print('list Append => ',list1)

#extend
lst2 = [0,0,0,0,0]
list1.extend(lst2)

#remove
list1.remove(1)
print(list1)

list1.pop(2)

print(list1)

list1.pop()
print(list1)

# list1.sort()
# print(list1)

print(list1.reverse())

print(list1.index(0))

print(list1.count(0))

lst3 = list1.copy()

print(lst3)

list1.clear()
print(list1)
