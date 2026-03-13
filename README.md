List ADT using Array
class ListArray:
def __init__(self):
self.arr = []
def insert(self, data):
self.arr.append(data)
def delete(self):
if len(self.arr) == 0:
print("List is Empty")
else:
self.arr.pop()
def display(self):
print("List Elements:", self.arr)
# Driver Code
l = ListArray()
l.insert(10)
l.insert(20)
l.insert(30)
l.display()
l.delete(30)
l.display()
OUTPUT:
List Elements: [10, 20, 30]
List Elements: [10, 20]
# Data-structure
