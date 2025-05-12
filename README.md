# Linked-List-Implementation-
A modular and efficient linked list implementation
Explanation of the Code:
Node Structure:

Each node has two fields: data (stores the value) and next (pointer to the next node).

Functions:

1.createNode: Allocates memory for a new node and initializes it.

2.insertAtBeginning: Adds a node at the beginning of the list.

3.insertAtEnd: Adds a node at the end of the list.

4.deleteNode: Deletes a node with the specified value.

5.traverseList: Prints all the nodes in the list.

6.search: Checks if a node with the specified value exists in the list.

Menu:

The program uses a menu-driven interface to allow the user to interact with the linked list.

🧑‍💻 Sample Output:

Singly Linked List Operations
1. Insert at beginning
2. Insert at end
3. Delete node
4. Traverse list
5. Search for node
6. Exit
Enter your choice: 1
Enter data to insert at the beginning: 10

Singly Linked List Operations
1. Insert at beginning
2. Insert at end
3. Delete node
4. Traverse list
5. Search for node
6. Exit
Enter your choice: 2
Enter data to insert at the end: 20

Singly Linked List Operations
1. Insert at beginning
2. Insert at end
3. Delete node
4. Traverse list
5. Search for node
6. Exit
Enter your choice: 4
10 -> 20 -> NULL

Singly Linked List Operations
1. Insert at beginning
2. Insert at end
3. Delete node
4. Traverse list
5. Search for node
6. Exit
Enter your choice: 3
Enter data to delete: 10
Node with value 10 deleted.

Singly Linked List Operations
1. Insert at beginning
2. Insert at end
3. Delete node
4. Traverse list
5. Search for node
6. Exit
Enter your choice: 4
20 -> NULL

📚 Notes:
1.Dynamic Memory Management: The linked list dynamically allocates memory for nodes using malloc(). Always free allocated memory when done.

2.Edge Cases: The program handles cases such as trying to delete from an empty list or searching for non-existent values.
