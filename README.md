# Create-Simple-Singly-Linked-List-DS
Write a code in the language of your choice to implement a singly linked list. 

class Node:
    def __init__(self, value):
        self.value = value
        self.next = None
        
        
class LinkedList:
    def __init__(self, value):
        new_node = Node(value)
        
        self.head = new_node
        self.tail = new_node
        self.length = 1
        
