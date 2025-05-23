-----------------------------File-Driven Management System-------------------------------

->Project Description
This File-Driven Management System is a comprehensive C++ program designed to simulate a real-world file management environment using advanced data structures. The system aims to efficiently handle file operations such as insertion, deletion, searching, and version control, providing a user-friendly and optimized way to manage files programmatically.

->How the System Works
1. File Organization with AVL Trees
To maintain fast and balanced file storage, the system uses AVL trees — a type of self-balancing binary search tree. This ensures that operations like file insertion, deletion, and searching happen in O(log n) time, making the system scalable even as the number of files increases. The AVL tree keeps the file records balanced so that no part of the tree becomes overly deep, which would slow down access.

2. File Deletion and Recycle Bin (Stack)
When files are deleted, they are not immediately lost. Instead, they are pushed onto a stack-based recycle bin, implementing a Last-In-First-Out (LIFO) structure. This allows users to restore the most recently deleted files easily. The stack structure helps in managing deleted files efficiently and provides a safety net against accidental deletions.

3. User Management with Linked Lists
The system manages multiple users through linked lists, enabling dynamic addition, deletion, and traversal of user records. This allows smooth management of user sessions and permissions without the need for fixed-size arrays, thus providing flexibility.

4. File Versioning
One of the advanced features of the system is file version control. Each file can have multiple versions saved using arrays to keep track of different states of the file over time. Users can view or revert to previous versions of any file, which is critical for maintaining historical data and undoing unwanted changes.

5. Practical File Handling Operations
Users can interact with the system via a menu-driven interface to:

------------------Functionalities------------------
->Add new files
->Search for existing files
->Delete files (with option to restore)
->View file versions
->Manage user accounts

The system ensures data consistency and optimal performance by combining these data structures thoughtfully.

-------------Why This System Is Useful---------------
This project demonstrates the power of combining fundamental data structures like AVL trees, stacks, linked lists, and arrays to build an efficient and reliable file management system. It provides hands-on experience with:
->Balancing trees for quick data retrieval
->Using stacks for undo-like features
->Dynamically managing users and data
->Implementing version control

This is a practical example that can be extended to real-world applications such as document management systems, version-controlled repositories, and more.
